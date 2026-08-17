**Database**

* **User** ID, name, subscribed?
* **Groups**
* **Chat**
id
title,
user
generated
...

* **Training sessions**
modelo, configuracion del modelo



 X and Y data points
* **Inference time**
query
configuracion
time

* **Paradigm:**
Quantum
photonic
thermic
Biological neurons
Biological DNA
Trits

[Dataset]
- id
- name
- Source



* **Time for each component:**
part,paradigm, time, model 

[HardwareProfile]
- id
- paradigm (Classical, Quantum, Photonic, Thermodynamic, Biological, Trits)
- device_name (e.g., "PennyLane-StateVector", "Boreal Light-1", "Extropic-Thermodynamic-V1", "NVIDIA H100")
- is_simulator (Boolean)
- theoretical_clock_speed_hz


[ExecutionEnvironment]
- id
- host_cpu / host_gpu
- simulation_framework (e.g., JAX, PennyLane, Qiskit, PyTorch, Custom)
- framework_version


[ComponentBenchmark]
- id
- training_session_id / inference_session_id
- component_type (e.g., "Multi-Head Attention - QKV Projection", "Gibbs Sampling Update", "LayerNorm")
- paradigm (Quantum, Photonic, Thermodynamic, Classical)
- input_shape (e.g., [batch_size, seq_len, d_model])
- parameter_count
- wall_clock_time_ms           -- Time spent executing on the simulator host
- estimated_hardware_time_ms   -- Calculated time on target physical substrate
- energy_consumed_joules       -- Estimated/Measured energy cost
- simulation_fidelity          -- Precision loss or noise ratio (e.g., quantum shot noise, photonic optical loss)
- fallback_occurred            -- Boolean (did it fall back to CPU/GPU due to convergence issues?)

* **MetricPoint for build this graph 6 graphs:**
loss 
Perplexity 
Learning rate 
Gradient norm 
Parameter norm 
Tokens processed 

[MetricPoint]
- id
- training_session_id
- step_number
- epoch
- tokens_processed
- loss
- perplexity
- learning_rate
- gradient_norm
- parameter_norm
- hardware_energy_joules_per_token

[ModelConfiguration]
- id
- name (e.g., "nanoGPT-Hybrid-Q1T1")
- total_parameters
- context_window
- vocabulary_size

[LayerParadigmMapping]
- id
- model_configuration_id
- component (e.g., "Attention_Head_0_4", "MLP_Layer_3")
- assigned_paradigm (Quantum, Photonic, Thermodynamic, Classical)
- simulation_params_json (e.g., {"num_qubits": 8, "photonic_modes": 16, "thermic_temp": 0.3})

Components

Tokenizer 
 Input Embeddings 
 Positional Encoding / Positional Embeddings 
 Matrix multiplication
 Transformer Blocks 
 Multi-Head Self-Attention 
 Feed-Forward Network (MLP) 
 Layer Normalization 
 Residual Connections 
 Output / Language Modeling Head 
 Softmax / Probability Distribution 
 Sampling / Decoding 
 KV Cache (during inference) 
 Context Window 
 Parameters / Weights 
 Biases 
 Attention Masks 
 Training Pipeline 
 Dataset 
 Loss Function 
 Optimizer 
 Backpropagation 
 Gradient Updates /Gibs sampling
 Inference Pipeline 
 Prompt Processing 
 Prefill 
 Autoregressive Decoding 
 Token Generation