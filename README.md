# 🤖 Anomaly Management in Multi-Robot Coordination: Detection and Handling Framework for Self-Driving Laboratories
## 🚀 Project Overview
In scientific laboratories, the complexity of experimental processes and high-precision equipment increases the likelihood of anomalies, which can compromise results and pose safety risks. This project addresses these challenges by implementing a Multi-Robot Coordination Framework designed for effective anomaly handling in autonomous laboratory environments.
<img width="475" height="288" alt="framework_high" src="https://github.com/user-attachments/assets/e173a318-d7fc-4f79-97f1-6f86fe57458a" />
### 🔑 Key Contributions
- **Anomaly Detection and Handling Framework**: We developed a framework that facilitates the detection and handling of anomalies, aiming to swiftly restore workflows in the presence of disruptive events.
- **Cross-Behavior Tree Extension Algorithm**: An innovative algorithm that is activated upon detecting anomalies, efficiently managing and localizing issues without extensive re-planning.
- **Spatiotemporal Anomaly Propagation Suppression Strategy**: Introduced to minimize the propagation of anomalies, ensuring dynamic adjustments while preserving task dependencies.
- **Extensive Validation**: Rigorous testing in both simulated and real environments demonstrates the framework's effectiveness in enhancing fault tolerance and flexibility during anomaly management.

### 📊 Anomaly Detection
Our framework leverages a Visual Language Model (VLM) for anomaly detection. This model integrates multimodal information to enhance monitoring capabilities during experimental processes. The detection workflow incorporates a hierarchical prompt mechanism using first-person perspective visual data and structured textual descriptions, allowing the model to generate semantic insights into the laboratory environment.
- **Detection Process**: The VLM performs a Chain-of-Thought (CoT) reasoning strategy to analyze states step by step, determining whether conditions are normal or abnormal. This allows for nuanced classification into three main types of anomalies: Spatial, Temporal, and Hybrid.
<img width="2063" height="1104" alt="Fig Anomalydetection" src="https://github.com/user-attachments/assets/6e0a5043-501c-485c-8304-ae8ed798308c" />

- **Anomaly Detection Dataset**
Validation is conducted using the **Sdls Anomaly Detect** dataset（ https://doi.org/10.6084/m9.figshare.29234663.v1 ）, which includes a variety of scenarios and labeled anomalies typically found in laboratory settings. This dataset is crucial for evaluating the robustness of our anomaly handling framework. For further reading, refer to the following foundational paper:
![0054](https://github.com/user-attachments/assets/4d930181-dfbe-4efc-bdfa-1b31bc45e46b)
![0348](https://github.com/user-attachments/assets/48ce3f1e-adc2-45f5-a77c-e22f9624feee)

S. Lin, C. Wang, X. Ding, Y. Wang, B. Du, L. Song, C. Wang, and H. Liu, "A VLM-based Method for Visual Anomaly Detection in Robotic Scientific Laboratories," arXiv preprint arXiv:2506.05405, 2025.

### 🛠️ Methodology
Our framework leverages **Hierarchical Large Language Models (LLMs)** to facilitate intelligent task planning and actions, executing dynamic adjustments in real time. The **Cross-Behavior Tree Expansion Algorithm** effectively identifies and responds to common laboratory anomalies, thus ensuring smooth operation of multi-robot systems.

<img width="7680" height="4320" alt="Fig Methods" src="https://github.com/user-attachments/assets/d7f725b0-e733-4319-b315-076ba08b1a73" />

### 📹 Case Study Videos
We provide extensive case studies demonstrating our anomaly handling processes through practical scenarios. To view various anomaly situations and the corresponding framework responses, check our YouTube Channel.
Link: https://www.youtube.com/watch?v=OH60_Ew9avQ&list=PLIJnmuEVkn7JcBSICKHqBwTBSFjnzq4pN&pp=gAQB

We have conducted extensive case studies demonstrating the anomaly handling process through practical scenarios. The following videos display various anomaly situations encountered and how the framework responds:
- Video 1: Simulated silica gel 1 material shortage  
- Video 2: Simulated pigment shortages continue to increase
- Video 3: Cleaning robot cleans water stains
- Video 4: Simulated the test tube is missing, re-execute the action of taking the test tube
- Video 5: The test tube of the weighing instrument is missing and then put it back in 
- Video 6-1: Workbench robot0 straightens the mold on the mold plate
- Video 6-2: Workbench robot0 straightens the tray mold
- Video 6-3: Workbench robot0 re-rectifies the mold and puts it back on the tray
- Video 7: Workbench robot0 is interrupted when adding pigment to the test tube. Replace the test tube with a new one and add pigment again. 
### 📈 Conclusion
This research presents a novel framework for managing anomalies in multi-robot systems, paving the way for enhanced automation in scientific laboratories. Feel free to dive in, provide feedback, or contribute to enhancing anomaly handling strategies! 💡
