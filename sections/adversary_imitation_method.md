Membership inference 
attack 
Collection 
AML.TA0011 Membership Inference AML.T0024.000 
Model source tampering 
Impact 
AML.TA0014 Model Tampering 
AML.T0048.000 
Model skewing 
Impact 
AML.TA0014 Model Skewing 
AML.T0048.001 
Model deployment 
tampering 
Impact 
AML.TA0014 Deployment 
Tampering 
AML.T0048.002 
Transfer learning attack 
Impact 
AML.TA0014 Transfer Learning 
Manipulation 
AML.T0048.003 
Off-label Model Use 
Execution 
AML.TA0002 Misuse of AI 
Capabilities 
AML.T0012 
Denial‑of‑Service 
Impact 
AML.TA0014 Denial of Service 
AML.T0048.004 
AI supply chain attacks 
Initial Access 
AML.TA0001 Supply Chain 
Compromise 
AML.T0010 
Confidential data in prompt 
Collection 
AML.TA0011 Prompt Injection 
AML.T0051.000 
IP information in prompt 
Collection 
AML.TA0011 Prompt Injection 
AML.T0051.000 
Sensitive data disclosure 
Exfiltration 
AML.TA0013 Data Leakage via 
Model Outputs 
AML.T0025 
Unauthorized training data 
Resource 
Development 
AML.TA0005 Use of Unauthorized 
Data Sources 
AML.T0016.000 
Processing Special 
Category Data Without 
Safeguards 
Impact 
AML.TA0014 Abuse of Data 
Processing 
AML.T0048.005 
Retrieval‑Augmented 
Generation (RAG) Pipeline 
Poisoning 
Impact 
AML.TA0014 Training Data 
Poisoning 
AML.T0018 
Federated‑Learning 
Vulnerabilities 
Impact 
AML.TA0014 Federated Learning 
Poisoning 
AML.T0019.000 
Chain‑of‑Thought Injection 
Execution 
AML.TA0002 Prompt Injection 
AML.T0051.000 
Model Interpretability 
Evasion 
Defense Evasion AML.TA0010 Adversarial Example 
Generation 
AML.T0015 
Ownership Evasion 
Defense Evasion AML.TA0010 Model Evasion 
Techniques 
AML.T0054 
 
39 
 
Covert Channel Attacks 
Exfiltration 
AML.TA0013 Covert Data 
Exfiltration 
AML.T0025.001 
Backdoor Attacks 
Persistence 
AML.TA0007 Model Backdooring 
AML.T0018.000 
Evasion Attacks 
Defense Evasion AML.TA0010 Adversarial Example 
Generation 
AML.T0015 
Deceptive Behavior 
Impact 
AML.TA0014 Manipulation of Model 
Outputs 
AML.T0048.006 
Excessive Agency 
Impact 
AML.TA0014 Abuse of AI Autonomy AML.T0054 
Confabulation 
Impact 
AML.TA0014 Model Hallucination 
AML.T0048.007 
Hallucination 
Impact 
AML.TA0014 Model Hallucination 
AML.T0048.007 
Fabrication 
Impact 
AML.TA0014 Model Hallucination 
AML.T0048.007 
Inferred sensitive data 
Collection 
AML.TA0011 Attribute Inference 
AML.T0024.000 
Re-identification (Mosaic 
Effect) 
Collection 
AML.TA0011 Model Inversion 
AML.T0024.001 
 
 
 
Adversary Imitation Assessment Target 
 
Assessment requirements will differ dramatically depending on whether the target of 
the assessment is the AI model or AI application. It is vital to determine this during 
the pre-assessment phase because it will impact the entire scope and requirements of 
the adversarial test. 
 
Break down of AI Model versus AI Application: 
      
 
   Table 13: AI Model vs. AI Application 
Assessment Target 
Overview 
AI Model 
Assessment involves attacks on training, 
inference, weights, architecture, or data 
representations of the model.  
AI Application 
Assessment involves misuse, manipulation, or 
compromise of the AI system at the application 
layer, including prompts, access, or integration. 
Overlap 
Risk should be tested for in AI Model- and AI 
Assessment-targeted assessments. 
 
 
 
40