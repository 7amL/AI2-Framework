Table 11: Offensive Security Aligned Risks 
Offensive Security Aligned Risks 
 
Note: Risks determined as out of scope for an offensive security function are 
categorized by functional alignment and listed in Appendix II: Out of Scope Risks 
Possible Alignments. 
 
 
34 
 
Social Engineering 
Malicious Code Generation 
Vulnerability Discovery 
Identity Impersonation and Synthetic Identity 
Increased Attack Surface 
Complex Attack Surface 
CBRN content generation 
Information Integrity 
Vector and Embedding Weaknesses 
Insecure Integrated Component 
Rogue Actions 
Output Integrity Attack 
Insecure AI Data or Models 
Insecure Model Output 
Insider Threat/Internal Misuse of AI 
Attribute inference attack 
Data poisoning 
Model poisoning 
Prompt Injection 
Prompt Leaking 
Prompt Priming 
Jailbreak Attacks 
Input manipulation attack 
Extraction attack 
Model inversion attack 
Model exfiltration 
Model reverse engineering 
Model theft 
 
 
Membership inference attack 
Model source tampering 
Model skewing 
Model deployment tampering 
Transfer learning attack 
Off-label Model Use 
Denial‑of‑Service 
AI supply chain attacks 
Confidential data in prompt 
IP information in prompt 
Sensitive data disclosure 
Unauthorized training data 
Processing Special Category Data Without Safeguards 
Retrieval‑Augmented Generation (RAG) Pipeline Poisoning 
Federated‑Learning Vulnerabilities 
Chain‑of‑Thought Injection 
Model Interpretability Evasion 
Ownership Evasion 
Covert Channel Attacks 
Backdoor Attacks 
Evasion Attacks 
Deceptive Behavior 
Excessive Agency 
Confabulation 
Hallucination 
Fabrication 
Inferred sensitive data 
Re-identification (Mosaic Effect) 
 
 
Adversary Imitation Assessment Methodology 
 
As stated in the intentions of this framework, this step does not seek to establish an 
end-to-end assessment workflow but to encapsulate the pre-assessment and 
execution portions of an established assessment workflow with adversary imitation 
assessment-specific requirements.  
 
Numerous frameworks exist establishing a standard ethical hacking workflow. This step 
establishes the specific requirements and considerations for adversary imitation 
assessments. The scheduling, risk reporting, and risk remediation process 
requirements remain intact, but the pre-assessment questionnaire, analysis, threat 
modeling, checks performed, and tools used during the assessment are unique to 
adversary imitation assessments.  
 
To establish a compliant, actionable, risk-informed adversarial imitation assessment 
methodology, the Adversary Imitation Assessment Methodology step performs the 
following: 
● Establishes essential pre-assessment actions 
● Maps risks to tactics to techniques (RTTs) using MITRE ATLAS 
● Defines the assessment target (AI model vs. AI application) 
● Aligns RTTs to assessment target 
● Outlines a threat modeling approach to AI models and applications 
● Lists and aligns automated tooling solutions  
● Differentiates Agentic AI risks vs. GenAI 
● Brings it all together to finalize the methodology 
 
 
Pre-Assessment Action 
 
AI adversarial imitation assessments correlate with other assessment types regarding 
pre-assessment requirements, i.e., application review, access provisioning, scope 
definitions, escalation contacts, etc., however certain pre-assessment actions are 
unique to Adversarial Imitation Assessments and likely more thorough.  
 
These unique actions include obtaining model types, inference pipeline details, 
external tool integration and AI system classification information. All of these aid the 
tester in the execution of the assessment, ensuring a comprehensive assurance 
approach. A checklist of pre-assessment actions, alongside a brief purpose statement 
for clarity, is provided below: 
 
35