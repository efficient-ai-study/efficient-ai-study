# 2022 경량화 Study
날로 거대해지는 AI 모델로 인한 비용 상승을 막기 위한 모든 기술에 대해 공부를 하는 스터디입니다.

## 운영
 - 권세중 (sejung.kwon@navercorp.com)
 - 김정훈 (jeonghoon.samuel@navercorp.com)
 
## 규칙
 - 2020년 이후의 최신 논문을 다루는 것을 원칙으로 합니다. 이왕이면 최신 논문을 공부한다는 마음으로 도전하시는 것을 권합니다. Neurips 2022에서 경량화를 키워드로 스크리닝한 리스트를 드릴테니 고르실수도 있습니다.
 - 워낙 다루는 기술의 폭이 넓다보니 백그라운드 없이 논문을 이해하기 힘들 수 있습니다. 기술의 의미를 설명하는 것에 20%-50% 이상 할애할 필요가 있습니다.
 - 3번 연속으로 참여가 없으신 멤버는 스터디 활동을 원하지 않으시는 것으로 간주할 수 있습니다.
 - 발표 자료와 녹화본의 공개는 각 발표자의 의사에 따릅니다. (발표자료 공개를 원치 않는 경우, 요약 리뷰글을 공개해주셔야합니다.)

## 일정
현재는 2022년까지 설정하였으나 발표자의 수가 늘어나면서 더 길어질수도 있습니다.
주제가 결정된 발표자는 Issue를 생성하고 아래 표에 Issue 번호와 함께 발표 주제를 적어 넣습니다.
추가 디스커션은 Issue를 통해 이뤄지도록 합니다.

When | Who | What | Links | Issue # | Etc.
---- | ----- | ------------------------------------------------------------ | ----------------------- | --------------------- | ----
10/11 | 권세중 | Introduction to Efficient AI | - | #1 | -
10/18 |
10/25 |
11/1 |
11/8 |
11/15 | 이제민 | PTQ4ViT: Post-Training Quantization for Vision Transformers with Twin Uniform Quantization | arxiv.org/abs/2111.12293 | #3 | -
11/22 |
11/29 |
12/6 |
12/13 |
12/20 | 박상수 | Reconfigurable arary for flexible GEMM accelerator | arxiv.org/abs/2101.04799 | #2 | -
12/27 | 

## 논문 후보 (Neurips 2022)
아직 공개가 되지 않은 논문도 많긴하지만, 차차 공개될 것으로 예상합니다.

Title | Link |	Keyword
----- | ------ | --------
FP8 Quantization: The Power of the Exponent	| https://arxiv.org/abs/2208.09225 |	Quantization
ZeroQuant: Efficient and Affordable Post-Training Quantization for Large-Scale Transformers	| https://arxiv.org/abs/2206.01861	| Quantization
Extreme Compression for Pre-trained Transformers Made Simple and Efficient	| https://arxiv.org/abs/2206.01859	| Quantization
Towards Efficient Post-training Quantization of Pre-trained Language Models	| https://arxiv.org/abs/2206.01859	| Quantization
Leveraging Inter-Layer Dependency for Post-Training Quantization	|	No links | Quantization
Entropy-Driven Mixed-Precision Quantization for Deep Network Design on IoT Devices	| https://neurips.cc/Conferences/2022/ScheduleMultitrack?event=54104 |	Quantization 
Redistribution of Weights and Activations for AdderNet Quantization	| No links | Quantization
Optimal Brain Compression: A Framework for Accurate Post-Training Quantization and Pruning	| https://arxiv.org/abs/2208.11580 |	Quantization
ClimbQ: Class Imbalanced Quantization Enabling Robustness on Efficient Inferences	| https://nips.cc/Conferences/2022/Schedule?showEvent=55162 | Quantization
Q-ViT: Accurate and Fully Quantized Low-bit Vision Transformer	| https://arxiv.org/abs/2201.07703 |	Quantization
Structural Pruning via Latency-Saliency Knapsack	| https://nips.cc/Conferences/2022/Schedule?showEvent=52841 |	Pruning
Advancing Model Pruning via Bi-level Optimization | https://neurips.cc/Conferences/2022/ScheduleMultitrack?event=55360 |		Pruning
Pruning has a disparate impact on model accuracy		| https://arxiv.org/abs/2205.13574 | Pruning
Data-Efficient Structured Pruning via Submodular Optimization |	https://arxiv.org/abs/2203.04940 |	Pruning
SAViT: Structure-Aware Vision Transformer Pruning via Collaborative Optimization	| https://nips.cc/Conferences/2022/Schedule?showEvent=55067 |	Pruning
Recall Distortion in Neural Network Pruning and the Undecayed Pruning Algorithm	| https://arxiv.org/abs/2206.02976 |	Pruning
Pruning Neural Networks via Coresets and Convex Geometry: Towards No Assumptions	| https://arxiv.org/abs/2209.08554 |	Pruning
Robust Binary Models by Pruning Randomly-initialized Networks	| https://arxiv.org/abs/2202.01341 |	Pruning
On Neural Network Pruning's Effect on Generalization	| https://nips.cc/Conferences/2022/Schedule?showEvent=53796 |	Pruning
A Fast Post-Training Pruning Framework for Transformers	| https://arxiv.org/abs/2204.09656 |	Pruning
VTC-LFC: Vision Transformer Compression with Low-Frequency Components	| https://neurips.cc/Conferences/2022/ScheduleMultitrack?event=54752 |	Compression
Lossless Compression of Deep Neural Networks: A High-dimensional Neural Tangent Kernel Approach	| https://nips.cc/Conferences/2022/Schedule?showEvent=55429; https://arxiv.org/abs/2001.00218 |	Compression
Fine-tuning Language Models over Slow Networks using Activation Compression with Guarantees	| https://arxiv.org/abs/2206.01299 |	Compression
Deep Compression of Pre-trained Transformer Models	| https://nips.cc/Conferences/2022/Schedule?showEvent=53013 |	Compression
