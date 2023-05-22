# 2023 Efficient AI Study
날로 거대해지는 AI 모델로 인한 비용 상승을 막기 위한 모든 기술에 대해 공부를 하는 스터디입니다.

## 운영
 - 김태수 (taesu.kim@squeezebits.com)
 - 김정훈 (jeonghoon.samuel@navercorp.com)
 - 김민수 (minsoo2333@hanyang.ac.kr)
 
## 규칙
 - 2021년 이후의 최신 논문을 다루는 것을 원칙으로 합니다. 이왕이면 최신 연구내용/기술을 공부한다는 마음으로 도전하시는 것을 권합니다.
 - 워낙 다루는 기술의 폭이 넓다보니 백그라운드 없이 논문을 이해하기 힘들 수 있습니다. 기술의 의미를 설명하는 것에 20%-50% 이상 할애할 필요가 있습니다.
 - 발표가 끝나면 설문을 통해 피드백과 질문을 수집합니다. 발표자는 질문에 대한 대답을 Discussions를 통해 이어나가야하며, 설문 제출은 출석으로 간주됩니다.
 - 4회 이상 출석 체크가 없으신 멤버는 스터디 활동을 원하지 않으시는 것으로 간주하여 강퇴될 수 있습니다.
 - 줌 링크와 발표 자료 링크 등은 Slack 공지방을 통해 공개됩니다.
 - 발표는 녹화하여 내부적으로 1주일간 공유합니다.
 - 발표 자료의 공개는 각 발표자의 의사에 따릅니다. (발표자료 공개를 원치 않는 경우, 최소한 요약 리뷰글을 공개해주셔야합니다.)

## 일정
2023년 5월 10일부터 2023년 7월 26일까지 12주간 진행합니다.
주제가 결정된 발표자는 Issue를 생성하고 아래 표에 Issue 번호와 함께 발표 주제를 적어 넣습니다.
추가 디스커션은 Issue를 통해 이뤄지도록 합니다.

When | Who | What | Links | Issue # | Etc.
---- | -------- | ----------------------------------------- | ----------------------- | --------------------- | ----
5/3 | 김태수 | Introduction to Efficient AI Study | - | #1 | -
5/10 | 권세중 | Challenges on Optimization of LLM Inference | - | #2 | -
5/17 | 김형준 | How to Improve Sampling Speed of Diffusion Models | - | #3 | -
5/24 | TBD | - | - | - | -
5/31 | 박상수 | DFX: A Low-latency Multi-FPGA Appliance for Accelerating Transformer-based Text Generation | https://arxiv.org/pdf/2209.10797.pdf | #5 | -
6/7 | 전은주 | LoRA: Low-Rank Adaptation of Large Language Models | https://openreview.net/forum?id=nZeVKeeFYf9 | #6 | -
6/14 | 강병하 | - | - | #7 | -
6/21 | 김도형 | NoisyQuant: Noisy Bias-Enhanced Post-Training Activation Quantization for Vision Transformers (CVPR-2023) | https://arxiv.org/abs/2211.16056 | #8 | -
6/28 |  김정훈 | FlexRound: Learnable Rounding based on Element-wise Division for Post-Training Quantization | N/A yet | - | -
7/5 | 박다훈 | Reparameterized Technique | https://arxiv.org/abs/2101.03697 , https://arxiv.org/pdf/2212.01593.pdf | #10 | -
7/12 | 이승현 | - | - | - | -
7/19 | TBD | - | - | - | -
7/26 | TBD | - | - | - | -

## 논문 후보 (Neurips 2022 & ICLR 2023) - 추가 예정
아직 공개가 되지 않은 논문도 많긴하지만, 차차 공개될 것으로 예상합니다.

Title | Link |	Keyword
----- | ------ | --------
FP8 Quantization: The Power of the Exponent	| https://arxiv.org/abs/2208.09225 |	Quantization
ZeroQuant: Efficient and Affordable Post-Training Quantization for Large-Scale Transformers	| https://arxiv.org/abs/2206.01861	| Quantization
Extreme Compression for Pre-trained Transformers Made Simple and Efficient	| https://arxiv.org/abs/2206.01859	| Quantization
Towards Efficient Post-training Quantization of Pre-trained Language Models	| https://arxiv.org/abs/2206.01859	| Quantization
Leveraging Inter-Layer Dependency for Post-Training Quantization	|	https://nips.cc/Conferences/2022/Schedule?showEvent=54389 | Quantization
Entropy-Driven Mixed-Precision Quantization for Deep Network Design on IoT Devices	| https://neurips.cc/Conferences/2022/ScheduleMultitrack?event=54104 |	Quantization 
Redistribution of Weights and Activations for AdderNet Quantization	| https://nips.cc/Conferences/2022/Schedule?showEvent=54812 | Quantization
Optimal Brain Compression: A Framework for Accurate Post-Training Quantization and Pruning	| https://arxiv.org/abs/2208.11580 |	Quantization
ClimbQ: Class Imbalanced Quantization Enabling Robustness on Efficient Inferences	| https://nips.cc/Conferences/2022/Schedule?showEvent=55162 | Quantization
Q-ViT: Accurate and Fully Quantized Low-bit Vision Transformer	| https://arxiv.org/abs/2210.06707 |	Quantization
Structural Pruning via Latency-Saliency Knapsack	| https://nips.cc/Conferences/2022/Schedule?showEvent=52841 |	Pruning
Advancing Model Pruning via Bi-level Optimization | https://neurips.cc/Conferences/2022/ScheduleMultitrack?event=55360 |		Pruning
Pruning has a disparate impact on model accuracy		| https://arxiv.org/abs/2205.13574 | Pruning
Data-Efficient Structured Pruning via Submodular Optimization |	https://arxiv.org/abs/2203.04940 |	Pruning
SAViT: Structure-Aware Vision Transformer Pruning via Collaborative Optimization	| https://nips.cc/Conferences/2022/Schedule?showEvent=55067 |	Pruning
Recall Distortion in Neural Network Pruning and the Undecayed Pruning Algorithm	| https://arxiv.org/abs/2206.02976 |	Pruning
Pruning Neural Networks via Coresets and Convex Geometry: Towards No Assumptions	| https://arxiv.org/abs/2209.08554 |	Pruning
Robust Binary Models by Pruning Randomly-initialized Networks	| https://arxiv.org/abs/2202.01341 |	Pruning
On Neural Network Pruning's Effect on Generalization	| https://nips.cc/Conferences/2022/Schedule?showEvent=54812 |	Pruning
A Fast Post-Training Pruning Framework for Transformers	| https://arxiv.org/abs/2204.09656 |	Pruning
VTC-LFC: Vision Transformer Compression with Low-Frequency Components	| https://neurips.cc/Conferences/2022/ScheduleMultitrack?event=54752 |	Compression
Lossless Compression of Deep Neural Networks: A High-dimensional Neural Tangent Kernel Approach	| https://nips.cc/Conferences/2022/Schedule?showEvent=55429; https://arxiv.org/abs/2001.00218 |	Compression
Fine-tuning Language Models over Slow Networks using Activation Compression with Guarantees	| https://arxiv.org/abs/2206.01299 |	Compression
Deep Compression of Pre-trained Transformer Models	| https://nips.cc/Conferences/2022/Schedule?showEvent=53013 |	Compression
GPTQ: Accurate Quantization for Generative Pre-trained Transformers|https://openreview.net/forum?id=tcbBPnfwxS | Quantization 
