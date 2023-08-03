# Forensics-DKL-BEPS
This notebook descrips the Forensics analysis of deep kernel leanring driven automated piezoresponse force microscopy experiments. 

Forensic analysis here is an examination of the ative learning driven autonomous experiment's results and the learning processes. We want to gain a deeper understanding of the process of autonomous experiments and identify potentials for improvement. This will offer signals for human intervention at specific points to influence the AI-driven experiment. Human intervention could involve modifying experiment parameters, adjusting acqusitions or target properties, or addressing unforeseen issues that the autonomous experiments might encounter. The combination of autonomous experiments and human intervention has the potential of leveraging the strengths of both machine learning and human expertise via a more adaptable experimental process.

![image](https://github.com/yongtaoliu/Forensics-DKL-BEPS/assets/43964104/c99eb667-33da-4d98-b739-7555d75a6b12)

Figure. Human vs. AI assisted experiments. (a) In human controlled paradigm, human operator issues control commands in the instrument specific hyper language for certain experiments. (b) In ML driven autonomous experiments, the human operator is substituted by the AI agent. (c) In AI assisted human-in-the-loop paradigm, human operator oversees experiments run by the AI agent. During this, human can directly intervene into experiment or tune (in real time) decision making process of the ML agent, which requires developing the methodology to monitor and intervene in the ML-driven autonomous experiments.

The forsensics analysis includes:
(a) Regret analysis including the acquisition function component analysis and counterfactual decision-making. Regrets analysis compares the knowledge-gain following the experimental traces of the actual AE DKL model and the trained DKL models 
(b) Trajectory analysis and feature discovery. This yields real-time and forensic tool to monitor the progression of the autonomous experiment progress.
(c) Global latent trajectory analysis. This constructs the latent space of the system with rVAE, allowing to visulalize the evolution of latent variables along the experimental path in real-time.


In the forensics analysis notebook, users can adjust analysis parameters such as acquistion function, target property, or kernel for their interest, as shown below. 
(a) change acquistion function. 
![image](https://github.com/yongtaoliu/Forensics-DKL-BEPS/assets/43964104/70e57d42-71d8-4b54-b7bb-dacff5566b8d)

(b) adjust target property.
![image](https://github.com/yongtaoliu/Forensics-DKL-BEPS/assets/43964104/c45f0cd8-1f57-4d64-b6a2-622ff934bd01)

(c) select kernel
![image](https://github.com/yongtaoliu/Forensics-DKL-BEPS/assets/43964104/307fb150-2101-4fb5-a5bc-abe7623b3e75)

Note that this repository includes two notebooks using different kernels, RBF and Matern, respectively.


For any questions, please reach out to liuy3@ornl.gov




