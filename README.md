# FPGA-Hardware-Accelerated-Gaming

 🎯 Introduction
This project focuses on designing and implementing **strategy-based games** (e.g., *Blokus, Lemmings*) on FPGA hardware (Intel Altera DE10-Lite).  
The goal is to achieve **low latency, high performance, and real-time execution** compared to software-only games by leveraging **Verilog HDL** and hardware acceleration.  

Additionally, **AI algorithms** (Monte Carlo Tree Search, FSM, Greedy + Cascading Ring Oscillator PUF) are integrated to make gameplay adaptive and unpredictable.  
A custom **Cascading Ring Oscillator PUF (C-ROPUF)** is used to introduce randomness, ensuring fairness and unbiased game logic.


 📝 Problem Statement
1. Software-based games face **delays** and **performance bottlenecks**.  
2. Need to introduce **unbiasedness and unpredictability** to enhance user experience.  
3. Conduct performance comparisons:  
   - With vs. without randomization  
   - FPGA-based vs. software-based execution  



 🎯 Objectives
- Design and implement **game logic** in Verilog/VHDL.  
- Deploy and test on FPGA hardware (Intel DE10-Lite).  
- Apply **hardware obfuscation** (FSM obfuscation, dummy logic, locking).  
- Ensure both **security and functionality** of the system.  
- Evaluate trade-offs between **performance vs. hardware resources** (timing, power, area).  



 ⚙️ Methodology
1. Define system goals, I/Os, architecture.  
2. Write Verilog/VHDL for core modules (game logic, AI, PUF).  
3. Simulate using **ModelSim** to debug functionality.  
4. Synthesize and map logic on FPGA (Quartus Prime).  
5. Upload bitstream to FPGA and test real-time performance.  
6. Evaluate and compare with software-based counterparts.  


 📊 Expected Outcome
- A functional **FPGA-based gaming system** with hardware acceleration.  
- Reduced latency & improved frame rates.  
- Modular architecture for **easy updates** (games, AI models).  
- Demonstration of **adaptive AI** and **randomized gameplay**.  
- Secure obfuscated design preventing reverse engineering.  


 🛠 Tools & Requirements
Software:  
- ModelSim, Quartus Prime, VScode, Jupyter Notebook  

Hardware:  
- Intel Altera DE10-Lite FPGA Board  

Algorithms/Designs:  
- Monte Carlo Tree Search  
- FSM & Greedy AI models  
- Custom **C-ROPUF** (Verilog-based)  


📚 References
1. Arjun S. Chauhan et al., *Obfuscation by Cascading FPGA RO-PUFs* (IEEE, 2020)  
2. Yiwen Zhang et al., *Effect of Randomness in Gameplay Satisfaction* (IEEE, 2021)  
3. Sila Temsiririrkkul et al., *Biased Random Sequence Generation in Games* (IEEE, 2014)  
4. Mohammadkazem Taram, Ali Jahanshahi, *Blokus Duo Game on FPGA* (ResearchGate, 2013)  
5. Jiménez-Fernández et al., *Learning VHDL through FPGA Game Design* (TAEE, 2020)

🚧 Phase 2 (Implementation) will include:  
- Verilog/VHDL coding  
- Simulation results (ModelSim/Quartus)  
- FPGA hardware demo  
- Performance comparison with software-based versions
