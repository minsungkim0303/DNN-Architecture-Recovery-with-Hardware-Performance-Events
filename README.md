# DNN-Architecture-Recovery-with-Hardware-Performance-Events
Deep neural networks (DNNs) have achieved excellent performance in many challenging tasks, such as computer vision and speech recognition, and are widely applied in many industrial sectors. However, DNNs are still vulnerable to various malicious cyberattacks, including side-channel attacks. In this project, we investigated the extent to which an attacker can infer DNN structure through side-channel attacks using hardware performance monitoring counters(PMCs). We built five machine learning classifiers based on the model selection pipeline to predict DNN architecture. The best models, Random Forest classifiers, achieved 98.3% and 100% accuracy for two different prediction tasks. Furthermore, we identified the most predictive PMC features, such as the number of retired instructions during the execution, for the two tasks.

- Collecting data: Fangzhou Li 
- Building ML based classifier: MinSung Kim 
