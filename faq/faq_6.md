---
title: "NPU와 GPU의 차이점은?"
slug: "npu-gpu-difference"
author: "Jiwon"
createdDate: "2025-03-04"            
category: "NPU"                    
tags: ["npu", "gpu"]         
---
NPU(Neural Processing Unit)와 GPU(Graphics Processing Unit)는 모두 병렬 연산을 수행하지만, 최적화된 연산 방식과 사용 목적이 다릅니다.

GPU는 원래 그래픽 렌더링을 위해 설계되었지만, 대규모 병렬 연산이 가능해 AI 학습(training)과 고성능 컴퓨팅(HPC)에 활용됩니다. 일반적으로 FP32/FP16 연산을 사용하며, CUDA 코어 및 Tensor 코어를 포함하여 다양한 연산을 지원합니다.
NPU는 AI/딥러닝 추론(inference)에 특화된 프로세서로, 저전력에서 효율적인 연산을 수행하도록 설계되었습니다. INT8, FP16과 같은 저비트 연산을 최적화하며, 신경망 연산을 가속하는 전용 하드웨어 구조를 가집니다.