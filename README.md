# Apple_silicon_benchmark
Apple silicon benchmark
Nvidia A6000 vs M2 Max 38gpu core 64GB

Model:opt-125m(huggingface pytorch) LORA finetune with PEFT FP32
Batchsize = 16 (input sequences less than 30 token)
Memory: 7820M vs 32GB
GPU-Util: 73% vs 92%
Speed: 21it/s vs 7it/s

