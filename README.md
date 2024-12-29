# AUDIC

AUDIC - Automated Dynamic Identification and Control

AUDIC is a fully automated adaptive predictive controller based on dynamic process identification technology. Offering superior control performance compared to traditional PID controllers, AUDIC eliminates the need for initial parameter selection and on-going parameter re-tuning, making it an ideal replacement for PID algorithms.

1. Applications of AUDIC
   
PID control forms the foundation of most feedback control systems today, ranging from large-scale automation in process industries to household appliances, drones, and autonomous vehicles. While simple and effective, PID struggles with nonlinear, time-varying, or high-latency processes, requiring frequent parameter adjustments for optimal performance — a challenging and resource-intensive task.

Model Predictive Control (MPC), an advanced control method, surpasses PID in many respects and is widely used in fields like refineries and petrochemicals. However, MPC comes with high implementation barriers, including expertise requirements, hardware and software demands, and ongoing model maintenance, making it unsuitable for simpler control needs like household heaters, drones, or autonomous vehicles.

AUDIC bridges the gap between PID and MPC, combining the simplicity and reliability of PID with the advanced predictive capabilities of MPC. Its adaptive nature allows it to handle dynamic changes in process characteristics and assess data quality intelligently. With AUDIC, users gain an easy-to-use solution that outperforms PID and avoids the complexity of MPC.

2. Key Features of AUDIC

AUDIC offers the following unique advantages:
   
   a. Superior Control Performance.  AUDIC delivers advanced predictive control by optimizing multi-step control actions, ensuring consistent and accurate performance even for processes with large time-delays.

   b. Fully Automated and Maintenance-Free.  AUDIC operates without user intervention or prior process knowledge. After a brief self-learning phase (10–30 steps), it transitions seamlessly to normal operation without the need for parameter tuning or adjustments.

   c. Adaptive Functionality. Leveraging real-time identification, AUDIC dynamically adjusts its internal model and control settings to track changes in process characteristics, maintaining optimal performance in nonlinear and time-varying systems.

   d. Simple Architecture, Low Resource Requirements.  AUDIC’s streamlined structure eliminates the need for complex system modeling or online optimization. The algorithm is light-weight and can even run in a web browser, making it a practical and versatile solution for diverse applications.

   e. High Scalability.  AUDIC easily extends to multi-variable control, including feedforward control, and can achieve true nonlinear predictive control for processes with known nonlinear models.


3. Theoretical Foundation of AUDIC

AUDIC is built on the Augmented UD Identification (AUDI) algorithm, known for its numerical stability and reliability across fields like automatic control, telecommunications and signal processing. The AUDI algorithm, developed through decades of research and industrial practice, forms the backbone of AUDIC by providing real-time, accurate dynamic process identification.

The algorithm avoids the computational complexity of traditional MPC (e.g., online quadratic programming), delivering a simpler, faster, and more reliable solution for adaptive control.

4. Demonstration Software
   
A browser-based implementation of the AUDIC algorithm is available on GitHub (https://github/NiuControl.com/AUDIC) or via email (niucontrol@gmail.com).
