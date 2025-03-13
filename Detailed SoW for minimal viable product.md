# Statement of Work (SoW) and Proposal: AI-Controlled Drone Swarms for Performance Environments

## Project Title:  
**Minimum Viable Product (MVP) & Proof of Concept (PoC) for AI-Influenced Drone Swarms in Blended Performance Systems**

### Research Lead:  
**Shafique Khan**  

### Domain Areas:  
- Electrical Engineering  
- Software Development  
- Artificial Intelligence  

### Affiliated Research Centers:  
- **C2SMARTER** (Connected Cities with Smart Transportation) - NYU Tandon School of Engineering  
- **AVMI** (Autonomous Vehicle Mobility Institute)  
- **Blended Reality Performance System (BRPS)** – CHI  

---

## 1. Project Overview  
This research aims to develop a **Minimum Viable Product (MVP)** and **Proof of Concept (PoC)** to validate the hypothesis that **AI-controlled drone swarms in performance environments can be both feasible and compelling**. The PoC will focus on creating **a small-scale, real-time AI-driven drone choreography** capable of adjusting movement dynamically based on external cues.

By testing **autonomous control, swarm coordination, and AI adaptability**, this project will provide critical insights into **algorithmic flexibility, AI hallucination management, and human-AI collaboration** in performance settings. The results will inform future development of more complex **swarm behaviors, interactive AI models, and full-scale BRPS integration**.

---

## 2. Project Scope & Methodology  

### **A. Minimum Viable Product (MVP) Definition**  
The MVP will consist of the following:
- **A set of 3–5 small drones** with onboard AI control.
- **Basic AI-driven movement coordination** (e.g., simple flocking behaviors, pre-defined formations, and reactive movement).
- **A lightweight control system** that allows for manual override.
- **A performance simulation** where AI-driven drones move in response to environmental stimuli (e.g., light, sound, or performer motion).
- **Integration with the BRPS system** for potential real-time projection mapping.

### **B. Proof of Concept (PoC) Study**  
The PoC will validate key technical and performance aspects of AI-controlled drone swarms, including:
- **Real-time AI influence on drone behavior** without strict centralized control.
- **The effectiveness of AI in coordinating small drone formations**.
- **The impact of AI hallucinations and how they affect performance scenarios**.
- **The ability to integrate AI-driven drones with live performance elements**.
- **How AI-controlled drones respond to external human or environmental stimuli**.

### **C. AI Models, Training, and Swarm Behavior Implementation**  
- Implement a **simplified version of multi-agent reinforcement learning (MARL)** for drone coordination.
- Utilize **Boids-based flocking models** for simple, physics-driven movement.
- Explore **decentralized AI models**, allowing drones to make independent but cooperative decisions.
- Train AI models using **existing datasets from motion capture, real-world drone telemetry, and past performance data**.
- Investigate the feasibility of **LLM acquisition** and training AI to interpret **real-time performance cues**.
- Capture and analyze **biological swarming behavior** from **birds, fish, and pedestrian movements in crowded environments** as additional datasets.
- Test **real-time adaptation** using external sensor input (e.g., cameras, motion tracking, audio signals).

### **D. Hacking & Control of Small Drones**  
- Investigate **off-the-shelf drones** (e.g., DJI Tello, Parrot Anafi) and explore modifications.
- Research **custom drone firmware** (e.g., ArduPilot, PX4) for AI-based control.
- Implement **remote control overrides** to ensure safe PoC testing.

### **E. Performance Simulation & Testing**  
- Create a **virtual environment** for AI-swarm simulation before physical deployment.
- Conduct **small-scale physical tests** with **limited drone numbers** to refine AI coordination.
- Evaluate **latency, accuracy, and stability** of AI-driven performance.

---

## 3. Expected Deliverables & Milestones  

| **Phase**            | **Deliverables**                                              | **Timeline** |
|----------------------|-------------------------------------------------------------|--------------|
| Literature Review   | Research AI swarming models, drone hacking, and control systems | Month 1      |
| AI Model Selection  | Develop simple AI models for initial movement coordination | Month 1      |
| Dataset Acquisition | Identify and curate motion capture, telemetry, and biological swarm behavior data | Month 2      |
| Hardware Setup      | Select, purchase, and modify test drones | Month 2      |
| PoC Development    | Implement basic AI-driven swarm behaviors in a controlled environment | Month 3      |
| Performance Testing | Conduct live demonstrations of AI-controlled drone movement | Month 4      |
| Final Report       | Document findings, performance evaluations, and recommendations | Month 5      |

---

## 4. Potential Applications  

### **Primary Demonstration:**  
- **Blended Shadow Puppet Performance** – AI-driven swarm interactions with projection-mapped shadow imagery.  
- **Blended Reality Performance System (BRPS)** – AI-assisted drone choreography integrated into mixed-reality performances.  

### **Long-Term Applications:**  
- **Autonomous drone fleets** for **interactive art, theater, and live media installations**.  
- **Swarm-based autonomous systems** for **urban mobility, defense, and disaster response**.  
- **AI-driven coordination of robots and aerial systems** for **smart city infrastructure**.  

---

## 5. Resources & Technical Requirements  

### **Hardware:**  
- 3–5 small drones (e.g., **DJI Tello, Parrot Anafi, Crazyflie**).  
- Motion tracking system (e.g., **Vicon, OptiTrack, or OpenCV-based vision tracking**).  
- Single-board computers for local AI processing (e.g., **Raspberry Pi, Jetson Nano**).  

### **Software & AI Frameworks:**  
- **AI Frameworks:** TensorFlow, PyTorch, OpenCV for computer vision-based tracking.  
- **Simulation & Testing:** Unity ML-Agents, SimScale, AirSim for pre-flight AI validation.  
- **Flight Control APIs:** ArduPilot, PX4, or ROS for integrating AI-based control systems.  
- **Communication Protocols:** MAVLink, ROS 2 for drone-to-drone communication.  

### **Personnel & Expertise:**  
- AI researchers specializing in **multi-agent systems and reinforcement learning**.  
- Electrical engineers for **hardware modification and control system integration**.  
- Performance technologists to explore **real-time integration with BRPS**.  

---

## 6. Risk Assessment & Mitigation Strategies  

### **Technical Risks:**  
- **AI unpredictability**: Mitigated by manual override controls.  
- **Hardware failures**: Backup drones and **pre-flight simulation testing**.  
- **Latency issues**: Optimization of **real-time processing pipelines**.  

### **Safety & Compliance:**  
- **Flight restrictions**: Work within **controlled indoor environments**.  
- **Drone stability & collision avoidance**: Implement fail-safes and altitude restrictions.  
- **AI errors & hallucinations**: Deploy **error-checking mechanisms** in AI decision-making.  

---

## 7. Conclusion & Next Steps  
This MVP and PoC will **validate the feasibility** of AI-influenced drone swarms in performance environments, paving the way for more **advanced, real-time adaptive AI swarms** in the future. The **results of this study will serve as the foundation** for further development, leading to **larger-scale autonomous drone performances and practical applications in various industries**.  


