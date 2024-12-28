# AUDIC

Automated Dynamic Identification and Control

AUDIC is a fully automated adaptive predictive controller based on dynamic process identification technology. Offering superior control performance compared to traditional PID controllers, AUDIC eliminates the need for initial parameter selection and parameter re-tuning during operation, making it an ideal replacement for PID algorithms.

1. Applications of AUDIC
   
Current Landscape

PID control forms the foundation of most feedback control systems today, ranging from large-scale automation in process industries to household appliances, drones, and autonomous vehicles. While simple and effective, PID struggles with nonlinear, time-varying, or high-latency processes, requiring frequent parameter adjustments for optimal performance—a challenging and resource-intensive task.

Limitations of Existing Advanced Controllers

Model Predictive Control (MPC), an advanced control method, surpasses PID in many respects and is widely used in fields like petrochemicals. However, MPC comes with high implementation barriers, including expertise requirements, hardware and software demands, and ongoing model maintenance, making it unsuitable for simpler control needs like household heaters, drones, or autonomous vehicles.

The Role of AUDIC

AUDIC bridges the gap between PID and MPC, combining the simplicity and reliability of PID with the advanced predictive capabilities of MPC. Its adaptive nature allows it to handle dynamic changes in process characteristics and assess data quality intelligently. With AUDIC, users gain an easy-to-use solution that outperforms PID and avoids the complexity of MPC.

2. Key Features of AUDIC
   
Superior Control Performance

AUDIC delivers advanced predictive control by optimizing multi-step control actions for high-latency processes, ensuring consistent and accurate performance.

Fully Automated and Maintenance-Free

AUDIC operates without user intervention or prior process knowledge. After a brief self-learning phase (10–30 steps), it transitions seamlessly to normal operation without the need for parameter tuning or adjustments.

Adaptive Functionality

Leveraging real-time identification, AUDIC dynamically adjusts its internal model and control settings to track changes in process characteristics, maintaining optimal performance in nonlinear and time-varying systems.

Simple Architecture, Low Resource Requirements

AUDIC’s streamlined structure eliminates the need for complex system modeling or online optimization. The algorithm is lightweight and can even run in a web browser, making it a practical and versatile solution for diverse applications.

High Scalability

AUDIC easily extends to multi-variable control, including feedforward strategies, and can incorporate nonlinear predictive control for processes with known nonlinear models.

3. Theoretical Foundation of AUDIC

AUDIC is built on the Augmented UD Identification (AUDI) algorithm, known for its numerical stability and reliability across fields like control, telecommunications and signal processing. The AUDI algorithm, developed through decades of research and industrial practice, forms the backbone of AUDIC by providing real-time, accurate dynamic process identification.

The algorithm avoids the computational complexity of traditional MPC (e.g., online quadratic programming), delivering a simpler, faster, and more reliable solution for adaptive control.

4. Demonstration Software
   
A browser-based implementation of the AUDIC algorithm is available on GitHub or via email (niucontrol@gmail.com). The demonstration includes:

Process Simulation

Simulates processes with transfer functions, allowing users to adjust parameters such as gain, delay, and noise for realistic scenarios.

Controller Algorithm

Compares manual control, PID control, and AUDIC. AUDIC requires no user intervention, unlike PID, which depends on parameter tuning.

Visualization

Real-time displays of input-output dynamics, controller actions, and predictive diagnostics provide users with valuable insights into system behavior.

5. References

A comprehensive list of references is provided, including seminal works on the AUDI algorithm and its applications in process control, signal processing, and adaptive control systems.

Niu S (1994) Augmented UD Identification for Process Control. University of Alberta
Niu S, Fisher DG (1995) Simultaneous estimation of process parameters, noise variance and signal-to-noise ratio. IEEE Transactions on Signal Processing 43:1725–1728
Niu S, Fisher DG (1997) Deteting parameter identifiability problems in system identification. International Journal of Adaptive Control and Signal Processing 11:603–619
Niu S, Fisher DG (1996) Recursive information forgetting with augmented UD identification. International Journal of Control 63:623–637
Niu S, Fisher DG, Ljung L, Shah SL (1994) A tutorial on multiple model least-squares and augmented UD identification. Department of Electrical Engineering, Linkoping University, Linkoping, S58183, Sweden
Niu S, Fisher DG, Xiao D (1992) An augmented UD identification algorithm. International Journal of Control 56:193–211
Niu S, Ljung L, Bjöck Å (1996) Decomposition methods for least-squares parameter estimation. IEEE Transactions on Signal Processing 44:2847–2852
Niu SS, Xiao D (2022) Process Control –- Engineering Analyses and Best Practices. Springer
Niu S, Xiao D, Fisher DG (1991) A recursive algorithm for simultaneous identification of model order and parameters. IEEE Transactions on Acoustics, Speech, and Signal Processing 38:884–886
For further details, contact: niucontrol@gmail.com
