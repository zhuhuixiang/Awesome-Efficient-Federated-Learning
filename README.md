# Awesome-Efficient-Federated-Learning
A curated list of **Efficient Federated Learning** and **Personalized Federated Learning** publications in Top-tier Conference, included **ICML, NeurIPS, AAAI, Infocom, etc.**
## Contributing
If your publication is not included here, please feel free to send me pull requests or email (zhuhuixiang@hust.edu.cn) to add links.
## Change Log
- Dec.1st.2021 The first version released.
- **Updating**
## Table of Contents

## publications in Top-tier Conference
   - **Survey**
   - **2021**
     - **ICML 2021**
     - **NeurIPS 2021**
## 2021
### ICML 2021
| Title  | Authors |  Targeting Problem | Method | Code/Dataset |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| [Hermes: An Efficient Federated Learning Framework for Heterogeneous Mobile Clients](https://dl.acm.org/doi/abs/10.1145/3447993.3483278)  | Duke，Alibaba | Communication &  Inference Efficiency | Personalized and structured sparse network | 

### NeurIPS 2021 
| Title  | Authors |  Targeting Problem | Method | Code/Dataset | 
| ------------- | ------------- | ------------- | ------------- | ------------- |
| [QuPeD: Quantized Personalization via Distillation with Applications to Federated Learning](https://openreview.net/forum?id=P_egPJZKro)  | UCLA | Non-I.I.D, Resource Heterogeneity | Knowledge Distillation | 
| [DeepReduce: A Sparse-tensor Communication Framework for Federated Deep Learning](https://openreview.net/forum?id=OAy508Q3T8)  | KAUST | Communication Efficiency | Tensors Compression| [Code](https://github.com/hangxu0304/DeepReduce)|
| [Parameterized Knowledge Transfer for Personalized Federated Learning](https://openreview.net/forum?id=_89s8ViNwwj)  | POLYU, HUST| Strongly-convex / Non-convex Optimization | Knowledge Transfer|
| [Fast Federated Learning in the Presence of Arbitrary Device Unavailability](https://openreview.net/forum?id=1_gaHBaRYt)  | Tsinghua, Princeton, MIT| Non-I.I.D, Latency | Novel asynchronous algorithm| [Code](https://github.com/hmgxr128/MIFA_code/)|
| [Few-Round Learning for Federated Learning](https://openreview.net/forum?id=ZgUZmeV1Mtut)  | KAIST | Communication Efficiency | Meta Learning |
| [Personalized Federated Learning With Gaussian Processes](https://openreview.net/forum?id=byCQ9Uu4PD)  | BIU, NVIDIA | Non-I.I.D, Communication Efficiency | Gaussian processes with deep kernel learning | [Code](https://github.com/IdanAchituve/pFedGP)|
| [Linear Convergence in Federated Learning: Tackling Client Heterogeneity and Sparse Gradients ](https://openreview.net/forum?id=h7FqQ6hCK18)  | UPENN | Strongly-convex / Convex / Non-convex Optimization | 
| [On Large-Cohort Training for Federated Learning ](https://openreview.net/forum?id=Kb26p7chwhf)  | Google, CMU | Optimal number of clients sampled | | [Code](https://github.com/google-research/federated/tree/f4e26c1b9b47ac320e520a8b9943ea2c5324b8c2/large_cohort)|
| [Federated Multi-Task Learning under a Mixture of Distributions](https://openreview.net/forum?id=YCqx6zhEzRp)  | INRIA | Non-I.I.D | Surrogate Optimization Algorithms |[Code](https://github.com/omarfoq/FedEM)|
| [Federated-EM with heterogeneity mitigation and variance reduction](https://openreview.net/forum?id=KSLNajziJeA)  | Polytechnique | Non-I.I.D, Communication Efficiency  |  Compression |[Code](https://github.com/omarfoq/FedEM)|
| [Breaking the centralized barrier for cross-device federated learning](https://openreview.net/forum?id=FMPuzXV1fR)  | EPFL, Google | Non-I.I.D, Communication Efficiency  |  |[Code](https://github.com/google/fedjax) [Document](https://fedjax.readthedocs.io/en/latest/fedjax.algorithms.html#)|
| [FedDR – Randomized Douglas-Rachford Splitting Algorithms for Nonconvex Federated Composite Optimization ](https://openreview.net/forum?id=SkDYNXUM4xZ)  | UNC | Non-I.I.D, Communication Efficiency  | A combination between a nonconvex Douglas-Rachford splitting method, randomized block-coordinate strategies, and asynchronous implementation |
| [STEM: A Stochastic Two-Sided Momentum Algorithm Achieving Near-Optimal Sample and Communication Complexities for Federated Learning](https://openreview.net/forum?id=J28lNO4p3ki)  | UMN, CMU | Parameters Optimization  |
