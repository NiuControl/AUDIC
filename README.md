#AUDIC - Automated Dynamic Identification and Control

AUDIC is a fully automated adaptive predictive controller based on a reliable process identification technology. Compared to traditional PID controllers, AUDIC eliminates the need for initial parameter selection and on-going parameter re-tuning, while offering the superior control performance of predictive control, making it an ideal replacement for PID algorithms.

1. Applications of AUDIC
   
PID control forms the foundation of most feedback control systems today, ranging from large-scale automation in process industries to household appliances, drones, and autonomous vehicles. While simple and effective, PID struggles with nonlinear, time-varying, or high-latency processes, requiring adequate initial parameter tunings and on-going parameter adjustments to stay effective — a challenging and resource-intensive task.

Model Predictive Control (MPC), an advanced control method, surpasses PID in many respects and is widely used in fields like large-scale industrial processes such as refineries and petrochemicals. However, MPC comes with high implementation barriers, including advanced expertise requirements, special hardware and software demands, and ongoing model maintenance, making it unsuitable for simpler control needs like household heaters, drones, or autonomous vehicles.

AUDIC attempts to bridge the gap between PID and MPC, combining the simplicity and reliability of PID with the advanced predictive capabilities of MPC. With AUDIC, users gain an easy-to-use solution that outperforms PID and avoids the complexity of MPC. In addition, its adaptive and predictive nature allows it to handle dynamic changes in process characteristics and assess data quality intelligently.

2. Key Features of AUDIC

AUDIC offers the following unique advantages:
   
   a. Superior Control Performance.  AUDIC delivers advanced predictive control capability by optimizing multi-step control actions, ensuring consistent and accurate performance even for processes with large time-delays.

   b. Fully Automated and Maintenance-Free.  AUDIC operates without user intervention or prior process knowledge. After a brief self-learning phase (10–30 steps), it transitions seamlessly to normal operation without the need for parameter tuning or adjustments.

   c. Adaptive Functionality. Leveraging reliable real-time system identification, AUDIC dynamically adjusts its internal model and control settings to track changes in process characteristics, maintaining optimal performance in nonlinear and time-varying systems.

   d. Simple Architecture, Low Resource Requirements.  AUDIC’s streamlined structure eliminates the need for complex system modeling or online QP-optimization. The algorithm is light-weight and can even run in a web browser, making it a practical and versatile solution for diverse applications.

   e. High Scalability.  AUDIC easily extends to multi-variable control, including feedforward control, and can achieve true nonlinear predictive control for processes with known nonlinear models.


3. Theoretical Foundation of AUDIC

AUDIC is built on the Augmented UD Identification (AUDI) algorithm, known for its numerical stability and reliability across fields like automatic control, telecommunications and signal processing. 

The AUDI algorithm, developed through decades of research and industrial practice (see references below), forms the backbone of AUDIC by providing reliable and real-time tracking and updating of the process model, both the model structure and model parameters.

The control algorithm utilizes a direct control technique and avoids the computational complexity of traditional MPC (e.g., online quadratic programming), delivering a simpler, faster, and more reliable solution suitable for adaptive control.

4. Demonstration Software
   
A browser-based implementation of the AUDIC algorithm is available on GitHub (https://github.com/NiuControl/AUDIC) or upon request via email (niucontrol@gmail.com).

5. References

Niu S (1994) Augmented UD Identification for Process Control. Ph.D. Thesis, University of Alberta
Niu S, Fisher DG (1995) Simultaneous Estimation of Process Parameters, Noise Variance and Signal-to-Noise Ratio. IEEE Transactions on Signal Processing 43:1725–1728
Niu S, Fisher DG (1997) Detecting Parameter Identifiability Problems In System Identification. International Journal of Adaptive Control and Signal Processing 11:603–619
Niu S, Fisher DG (1996) Recursive Information Forgetting with Augmented UD Identification. International Journal of Control 63:623–637
Niu S, Fisher DG, Ljung L, Shah SL (1994) A Tutorial on Multiple Model Least-Squares and Augmented UD Identification. Department of Electrical Engineering, Linkoping University, Linkoping, S58183, Sweden
Niu S, Fisher DG, Xiao D (1992) An Augmented UD Identification Algorithm. International Journal of Control 56:193–211
Niu S, Ljung L, Bjöck Å (1996) Decomposition Methods for Least-Squares Parameter Estimation. IEEE Transactions on Signal Processing 44:2847–2852
Niu S, Xiao D, Fisher DG (1991) A Recursive Algorithm for Simultaneous Identification of Model Order and Parameters. IEEE Transactions on Acoustics, Speech, and Signal Processing 38:884–886
Niu SS (2024) Process Control for Pumps and Compressors. Springer
Niu SS, Xiao D (2022) Process Control –- Engineering Analyses and Best Practices. Springer

   
