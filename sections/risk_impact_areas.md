24 
Chain‑of‑Thought Injection 
Manipulating AI reasoning steps to alter outcomes. 
Model Interpretability Evasion 
Techniques that obscure how models make decisions. 
Ownership Evasion 
Concealing the true origin or owner of AI models. 
Covert Channel Attacks 
Using AI systems to stealthily exfiltrate data. 
 
Risk Impact Areas 
 
 
 
Based on Microsoft’s AI risk categorization design, the AI2 Framework designated three 
distinct risk impact areas as defined in the table below: 
 
 
              
 
 
               
 
           Table 7: Risk Impact Areas 
Impact Area 
Focus 
Concerns 
 AI Application 
Security 
The security of the AI system 
itself as an application 
● 
Exploits in AI logic (i.e., adversarial 
examples, model inversion, prompt 
injection) 
● 
Tampering with model outputs or behavior 
● 
Attacks on model APIs (i.e., abuse of 
inference endpoints) 
● 
Unauthorized access to proprietary models 
AI Usage Safety and 
Security 
The safe and secure use of 
AI by people 
● 
Harmful content generation (i.e., 
hallucinated medical advice) 
● 
Bias and fairness risks 
● 
Decision-making based on faulty or 
opaque outputs 
● 
Social engineering or manipulation through 
AI interactions (i.e., chatbots) 
AI Platform Security 
The infrastructure and 
environment where AI runs 
● 
Securing cloud-hosted AI services and 
compute environments 
● 
Protecting model training environments 
and data storage 
● 
Supply chain integrity (i.e., compromised 
libraries or pre-trained weights) 
● 
Isolation of AI workloads in multi-tenant 
environments 
 
Categorizing risk impact areas is an important step in AI risk management because it: 
 
● aligns with established risk management frameworks (aligns with NIST, 
ISO/IEC, and Microsoft’s Red Teaming approach → AI2 Framework is auditable) 
● establishes ownership of risks (domain alignment → control alignment→ owner 
alignment) 
● aids in the selection of controls and risk mitigations through the categorical 
alignment of risks most commonly affecting a given impact area 
 
For example, without having performed any part of any adversarial engagement, 
one could rightfully predict that the listed controls and mitigations would have a 
significant positive impact in deterring the materialization of risks if implemented: 
 
 
25 
 
 
 Table 8: Risk Impact Areas Controls and Mitigations 
Impact Area 
Controls and Mitigations 
AI Application Security 
Input sanitization, adversarial robustness, prompt filtering 
AI Usage Safety & Security 
Output moderation, bias audits, consent user experience (UX) 
AI Platform Security 
Container hardening, IaC validation, data pipeline security 
 
To know which controls and mitigations to implement in a given impact area, the 
risks commonly affecting that impact area must be known. With this in mind, the 
next step is to align each risk with a specific risk impact area. The use-cases for 
this alignment are to modularly execute assurance functions for specific 
domains and demonstrate coverage of risks in those domains. 
 
Each risk identified in the AI Risk Profile list has been mapped to a 
corresponding Risk Impact Area, which initiates the risk management framework 
step. 
 
     Table 9: Risk Mapping to Impact Areas 
AI Platform Security 
AI Usage Safety and Security 
 AI Application Security 
Emergent Goals/Behavior 
Physical Harm 
Social Engineering 
Unknown AI Risks 
Psychological Harm 
Malicious Code Generation 
Statistical uncertainty in 
pre‑trained models 
Financial Harm 
Vulnerability Discovery 
Side‑effects not visible in 
statistical measures 
Economic Harm 
Identity Impersonation and Synthetic 
Identity 
Complex Systems 
Informational Harm 
Increased Attack Surface 
Third‑party data or 
component trustworthiness 
Reputational Harm 
Complex Attack Surface 
Unbounded Consumption 
(Sponge Examples) 
Discrimination & Inequity 
CBRN content generation 
Excessive Data Handling 
Autonomy and Agency Harm 
Information Integrity 
Controllability and Autonomy 
Risks 
Social & Democratic Harm 
Lower Offensive Cyber Barriers 
Reliability and Robustness 
Risks 
Environmental Harm 
Vector and Embedding Weaknesses 
 
26