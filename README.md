### Hi, I'm Boktiar Hossain

I'm a Ph.D. Candidate in Computer Science at **Oklahoma State University** (Stillwater, Oklahoma), working in [Dr. Jahan's Lab](https://cas.okstate.edu/computer_science/about_us/dr_jahan_lab). My doctoral research focuses on cloud-native cybersecurity, service-mesh defense, and self-adaptive systems: building decentralized machine-learning defenders for service-level DDoS detection and conflict-free policy reconciliation in **Kubernetes** and **Istio**, and automating **Goal Structuring Notation (GSN)** Security Assurance Case (SAC) instantiation and **MAPE-K** runtime failover under **NIST SP 800-53**.

Alongside my systems security research, I build machine learning and deep learning pipelines for network intrusion detection, microservice telemetry anomaly classification, medical diagnostics, computer vision, and antenna/RF propagation modeling.

I hold an M.S. in Electrical Engineering (2025) and am pursuing my Ph.D. in Computer Science at **Oklahoma State University** (2025–Present).

I worked at **Huawei Technologies** as a **Product Solution Architect** for approximately **eight years** and at **Ericsson** as a **Radio and Transmission Engineer** for approximately **two years**.

#### Research code
Every research repository includes end-to-end reproducible scripts, documented architecture configurations, and experimental evaluation artifacts.

| Repository | What it does | Status |
|---|---|---|
| [Autonomic DDoS Defense in Kubernetes Service Meshes: A Decentralized ML and Optimistic Concurrency Control Approach](https://github.com/mdboktiarhossain/Autonomic-DDoS-Defense-Kubernetes-OCC) | Two-dimensional multi-process & thread-pool ML defense (`4×1 vCPU` pods, 24 workers), hybrid 3-path attribution (EWMA rate, 7-feature RF/HGB on corrected CIC-IDS2017/DistriNet, Stage 3B gateway provenance), isolated `v4` decoy quarantine, and Lease/OCC atomic routing recovery (`56/56` conflict-free OCC commits, `99.98%` benign success) | *Springer Nature*, Dec. 2026 · [Code](https://github.com/mdboktiarhossain/Autonomic-DDoS-Defense-Kubernetes-OCC) · [Dataset Archive](https://ostatemailokstate-my.sharepoint.com/my?id=%2Fpersonal%2Fmd%5Fboktiar%5Fhossain%5Fokstate%5Fedu%2FDocuments%2FOther%20Data) |
| [A Decentralized ML-Based Framework for Service-Level DDoS Detection and Mitigation in Service Mesh Infrastructures](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=LF46WHgAAAAJ&citation_for_view=LF46WHgAAAAJ:9ZlFYXVOiuMC) | Decentralized autonomic ML defender for service-level DDoS detection and traffic rerouting in Kubernetes & Istio service meshes across 4 Bookinfo microservices (`productpage`, `details`, `reviews`, `ratings`). Achieves 98.9% F1-score, <2.1 s detection-to-mitigation latency, and 25% fault blast-radius isolation | Accepted, *ICOIN 2027* ([Google Scholar](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=LF46WHgAAAAJ&citation_for_view=LF46WHgAAAAJ:9ZlFYXVOiuMC)) · [Code](https://github.com/mdboktiarhossain/DDoS--Decentralized-Detection-Mitigation) |
| [Compliance-Guard--Automated-SAC-Instantiation](https://github.com/mdboktiarhossain/Compliance-Guard--Automated-SAC-Instantiation) | Automated LLM policy extraction of 38 atomic NIST SP 800-53 rules, 117-node Labeled Property Graph (LPG) cloud architecture model, 7-level GSN assurance tree constructor, weighted satisficing completeness scorer, and MAPE-K runtime failover (+4.9% compliance gain on failover) | In preparation |
| [AI-Driven-Anomaly-Detector-as-a-Service](https://github.com/mdboktiarhossain/AI-Driven-Anomaly-Detector-as-a-Service) | Containerized ML anomaly detection microservice for real-time telemetry classification in cloud-native service mesh environments | Active prototype |
| [istio-1.24.2](https://github.com/mdboktiarhossain/istio-1.24.2) | Istio 1.24.2 service mesh testbed integration with microservice telemetry monitoring and anomaly detection | Active testbed |

#### Selected publications
- M. B. Hossain and S. Jahan, "Autonomic DDoS Defense in Kubernetes Service Meshes: A Decentralized ML and Optimistic Concurrency Control Approach," *Springer Nature*, Dec. 2026. [[Google Scholar](https://scholar.google.com/citations?user=LF46WHgAAAAJ&hl=en)] · [[Code](https://github.com/mdboktiarhossain/Autonomic-DDoS-Defense-Kubernetes-OCC)]
- M. B. Hossain and S. Jahan, "A Decentralized ML-Based Framework for Service-Level DDoS Detection and Mitigation in Service Mesh Infrastructures," *The 41st International Conference on Information Networking (ICOIN 2027)*, IEEE, 2026. [[Google Scholar](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=LF46WHgAAAAJ&citation_for_view=LF46WHgAAAAJ:9ZlFYXVOiuMC)] · [[Code](https://github.com/mdboktiarhossain/DDoS--Decentralized-Detection-Mitigation)]
- M. B. Hossain, K. Hoque, S. Abdi, E. Bazgir, and M. A. Rahman, "Design and Simulation of a 1×2 Rectangular Microstrip Patch Antenna Array with Feeding Network," *Fifth International Conference on Advances in Electrical, Computing, Communication and Sustainable Technologies (ICAECT)*, IEEE, 2025. [[Google Scholar](https://scholar.google.com/citations?user=LF46WHgAAAAJ&hl=en)]
- K. Hoque, M. B. Hossain, A. B. Siddik, M. M. Billah, D. L. Michael, and M. A. Rahman, "Performance Analysis of Yagi and Helix Antennas at 7.2 GHz with Far-Field Propagation Evaluation," *8th International Conference on Trends in Electronics and Informatics (ICOEI)*, IEEE, 2025. [[IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/11013571)]
- M. B. Hossain, K. Hoque, M. A. Rahman, P. Podder, and D. Gupta, "Hepatitis C Prediction Applying Different ML Classification Algorithm," *International Conference on Computing and Communication Networks (ICCCN)*, Springer LNNS, 2025. [[doi:10.1007/978-981-96-3250-3_32](https://doi.org/10.1007/978-981-96-3250-3_32)]
- M. S. Rahman, K. Hoque, M. B. Hossain, D. Das, and T. Wu, "Detection of Coal Miner with a Comprehensive Dataset Using Transfer Learning Techniques," *International Conference on Computing and Communication Networks (ICCCN)*, Springer Nature Singapore, 2024. [[ResearchGate](https://www.researchgate.net/publication/392945281_Detection_of_Coal_Miner_with_Comprehensive_Dataset_Using_Transfer_Learning_Techniques)]
- K. Hoque, M. B. Hossain, D. Das, and P. P. Roy, "Integration of IoT in Energy Sector," *International Journal of Computer Applications (IJCA)*, 186(36), 2024. [[doi:10.5120/ijca2024923981](https://doi.org/10.5120/ijca2024923981)] · [[link](https://www.ijcaonline.org/archives/volume186/number36/integration-of-iot-in-energy-sector/)]
- K. Hoque, M. B. Hossain, A. Sami, D. Das, A. Kadir, and M. A. Rahman, "Technological Trends in 5G Networks for IoT-Enabled Smart Healthcare: A Review," *International Journal of Science and Research Archive (IJSRA)*, 12(2), 2024. [[doi:10.30574/ijsra.2024.12.2.1381](https://doi.org/10.30574/ijsra.2024.12.2.1381)]
- M. B. Hossain and K. Hoque, "Machine Learning Approaches in IDS," *International Journal of Science and Research Archive (IJSRA)*, 7(2), 2022. [[doi:10.30574/ijsra.2022.7.2.0303](https://doi.org/10.30574/ijsra.2022.7.2.0303)]
- M. B. Hossain, R. Rahman, and K. Hoque, "Feature-Driven Supervised Learning for Detecting DDoS Attack," *International Journal of Science and Research Archive (IJSRA)*, 4(1), 2021. [[doi:10.30574/ijsra.2021.4.1.0204](https://doi.org/10.30574/ijsra.2021.4.1.0204)]

Full list on [Google Scholar](https://scholar.google.com/citations?user=LF46WHgAAAAJ&hl=en).

#### Earlier projects
- [AI-Based-Traffic-Management-System](https://github.com/mdboktiarhossain/AI-Based-Traffic-Management-System): YOLOv8 vehicle detection for adaptive traffic signal timing (MSEE capstone, 2024)
- [ML-Breast-Cancer](https://github.com/mdboktiarhossain/ML-Breast-Cancer): Supervised machine learning pipeline for breast cancer diagnostic classification
- [Machine-Learning-and-Deep-Learning](https://github.com/mdboktiarhossain/Machine-Learning-and-Deep-Learning): Machine learning and deep learning models, architectures, and experimental notebooks

#### Skills
- **Cloud & Network Security:** Kubernetes, Istio Service Mesh, Envoy Proxy, Prometheus, Docker, DDoS Detection & Mitigation, NIST SP 800-53, Goal Structuring Notation (GSN), MAPE-K Self-Adaptive Systems
- **ML and data:** Python, NumPy, pandas, scikit-learn, RandomForest, HistGradientBoosting, PyTorch, Keras, YOLOv8, Matplotlib
- **Engineering:** Antenna & RF Simulation (HFSS / CST), MATLAB/Simulink, SystemVerilog/Verilog, C/C++, Raspberry Pi, Linux

#### Contact
[Google Scholar](https://scholar.google.com/citations?user=LF46WHgAAAAJ&hl=en) · [Academic Website](https://mdboktiarhossain.github.io/) · md_boktiar.hossain@okstate.edu
