<h1 align="center">Gustavo Gimenez</h1>
<h3 align="center">Embedded Software Engineer · C/C++ · Safety-Critical Systems</h3>

<p align="center">
  Building software where reliability is non-negotiable.<br/>
  Focus: embedded systems, firmware, and applied cryptography.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/SBRC-2026-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/B.Sc.-Computer%20Science-informational?style=flat-square" />
  <img src="https://img.shields.io/badge/Technical-Electronics-informational?style=flat-square" />
</p>

---

### 🔬 Published Research

**[Post-Quantum Cryptography for IoT: Evaluation of Algorithms on Embedded Devices](https://sol.sbc.org.br/index.php/sbrc/article/view/42308)**  
*SBRC 2026 · Simpósio Brasileiro de Redes de Computadores*

Evaluated ML-KEM, FIPS 203, the post-quantum key exchange standard finalized by NIST in 2024, on ESP32 devices, using the official standard, not preliminary versions evaluated by prior work. Compared ML-KEM against RSA and ECDH across execution time, energy consumption, and memory usage at equivalent security levels (128/192/256-bit). Results show ML-KEM is ~36× faster than ECDH and up to ~768× faster than RSA, with proportionally lower energy cost, at the tradeoff of ~4× higher stack usage (~13 kB minimum for ML-KEM-512). Also proposed and validated a complete quantum-safe communication architecture (ML-KEM + AES-128-CTR + HMAC-SHA-256) on a real two-device ESP32 IoT setup, achieving full message exchange in ~181 ms with ~16 kB of stack.

The work contributes a joint evaluation of performance, energy, and memory in a controlled embedded environment, and a practical architecture for quantum-safe IoT communication, addressing gaps in prior literature that evaluated metrics in isolation or used pre-standardization algorithm versions.

I'm actively pursuing further research in this space: optimizing PQC implementations for memory-constrained devices, integrating post-quantum signature schemes (ML-DSA), and extending the evaluation to other embedded platforms

🔗 **[Source code & benchmarks](https://github.com/ggtxz/MLKEM-on-ESP32)**

---

### 💼 Experience

**Embedded Software Developer Intern, Embraer** *(2024–2025)*  
- Cryptographic libraries in C (SHA-2, SHA-3, AES) for a safety-critical software loading system  
- DO-178C compliance, MISRA C and CERT C conformance, 100% reduction in static analysis findings  
- ARINC protocol communication implementation  
- Python tool for Model-Based Design test automation: 3× speedup  
- Cybersecurity requirements elicitation for avionics systems

**Junior Software Developer** *(2026–present)*  
C/C++ backend development on a Linux environment for a distributed simulation system.

---

### 🎓 Education

**B.Sc. Computer Science**, UNIFEI *(2021–2025)*  
Thesis: *Post-Quantum Cryptography for IoT: Implementation and Evaluation of Algorithms on Embedded Devices* · Published at SBRC 2026

**Technical Degree in Electronics**, UNESP *(2017–2019)*  
Thesis: *Bluetooth-Controlled Waste Collection and Sorting Robot*

---

### 🧭 Currently

- 🔭 Working on C/C++ backend for distributed simulation systems
- 📖 Deepening Modern C++ (C++17/20), smart pointers, RAII, STL, move semantics
- 🔐 Pursuing further research in post-quantum cryptography for constrained embedded devices
- 🎯 Interested in: bare-metal firmware, RTOS, safety-critical software, PQC for IoT

---

### 🛠️ Stack

**Languages**

![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Assembly](https://img.shields.io/badge/assembly-%23525252.svg?style=for-the-badge&logo=assemblyscript&logoColor=white)

**Embedded & Tools**

![Linux](https://img.shields.io/badge/linux-%23FCC624.svg?style=for-the-badge&logo=linux&logoColor=black)
![RTOS](https://img.shields.io/badge/RTOS-%23003366.svg?style=for-the-badge&logoColor=white)
![ESP-IDF](https://img.shields.io/badge/ESP--IDF-%23E7352C.svg?style=for-the-badge&logo=espressif&logoColor=white)
![CMake](https://img.shields.io/badge/cmake-%23008FBA.svg?style=for-the-badge&logo=cmake&logoColor=white)
![GDB](https://img.shields.io/badge/GDB-debug-%23A42E2B?style=for-the-badge)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

**Testing & Quality**

![GTest](https://img.shields.io/badge/gtest-%234285F4.svg?style=for-the-badge&logo=google&logoColor=white)
![LDRA](https://img.shields.io/badge/LDRA-static%20analysis-orange?style=for-the-badge)

---

### 📊 Stats

<p align="center">
  <img src="https://github-readme-stats-alpha-six-91.vercel.app/api?username=ggtxz&theme=vue-dark&show_icons=true&hide_border=true&count_private=true" height="150" />
  <img src="./streak-stats.svg" height="150" />
  <img src="https://github-readme-stats-alpha-six-91.vercel.app/api/top-langs/?username=ggtxz&theme=vue-dark&show_icons=true&hide_border=true&layout=compact" height="150" />
</p>

---

### 🔗 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ggtxz/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ggtxz)
[![Gmail](https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red)](mailto:ggimenezt@gmail.com)
