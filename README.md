# mllm_challenge
## Task description
This challenge is conducted on a dataset that is manually curated based on criteria of helpfulness, honesty, and harmlessness for Multimodal Large Language Models (MLLMs). The primary goal is to execute a successful attack on Llava-1.5. Participants must alter either the input image or text  or both to significantly impair the model's accuracy in helpfulness and honesty, and safety rate in harmfulness. The core challenge involves ingeniously designing inputs that prompt the MLLM to generate incorrect or harmful outputs, thereby evaluating the model's robustness against attacks.

Generally, for each given input pair (I, T), we aim to design specific MLLM attack methods to automatically construct image adversarial perturbation ΔI or a textual prompt ΔT, such that the target MLLM may generate inaccurate or unsafe outputs (i.e., choosing the wrong choice for multiple-choice questions or generating harmful sentences for harmlessness evaluation) with prompted inputs (i.e., (I+ΔI, T) / (I, T+ΔT) / (I+ΔI, T) / (I+ΔI,T+ΔT)). The lower accuracy or more unsafe responses indicates the better attack methods. 

## [Challenge](https://icml-tifa.github.io/challenges/track1/)
