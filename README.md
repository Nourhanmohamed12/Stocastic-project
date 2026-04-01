<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=60A5FA&center=true&vCenter=true&lines=Hidden+Markov+Model+Trainer;Forward-Backward+%26+Baum-Welch;Probabilistic+Modeling+📊" />
  <br><br>
  <img src="https://img.shields.io/badge/💻-Python%20Project-1E40AF?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/📊-Machine%20Learning-3B82F6?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/🧠-HMM-60A5FA?style=for-the-badge" />
</div>

---

## <div align="center"><b style="color:#1E40AF">📊 Project Overview</b></div>

This project implements a **Hidden Markov Model (HMM)** from scratch using **Python and NumPy**, including:

- 🔁 Forward Algorithm  
- 🔁 Backward Algorithm  
- 🤖 Baum-Welch Training (Expectation-Maximization)  

It allows users to **train an HMM model** based on an observation sequence and estimate:

- Transition probabilities  
- Emission probabilities  
- Initial state distribution  

<div align="center">
  <img src="https://img.shields.io/badge/🔁-Forward%20Backward-60A5FA?style=for-the-badge" />
  <img src="https://img.shields.io/badge/🤖-EM%20Algorithm-3B82F6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/📊-Probabilities-1E40AF?style=for-the-badge" />
</div>

---

## ✨ **Key Features**

| Feature | Description |
|--------|------------|
| 🔁 Forward Algorithm | Computes probability of observation sequence |
| 🔁 Backward Algorithm | Computes backward probabilities |
| 🤖 Baum-Welch | Learns model parameters automatically |
| 📊 Probability Matrices | Transition, Emission, Initial |
| ⚡ Iterative Training | Converges over iterations |
| 🧪 Custom Input | User-defined probabilities |

---

## 🖥️ **System Flow**

```mermaid
graph TD
    A[📥 Input Observation Sequence] --> B[⚙️ Initialize Parameters]
    B --> C[🔁 Forward Algorithm]
    B --> D[🔁 Backward Algorithm]
    C --> E[📊 Compute Alpha]
    D --> F[📊 Compute Beta]
    E --> G[🤖 Baum-Welch Update]
    F --> G
    G --> H[🔄 Iterate Until Convergence]
    H --> I[📈 Updated Model Parameters]
