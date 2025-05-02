Pre-Assessment Checklist for Adversarial Testing of AI Systems 
 
Pre-Assessment Inputs: AI Model Target 
Item 
Purpose 
Model Type & Architecture 
Determine attack surface (i.e., transformer, CNN, 
ensemble). 
Model Documentation 
Understand model behavior, safety limits, and usage 
guidance. 
Training Data Characteristics 
Identify poisoning, bias, and leakage risks. 
Input/Output Data Schema 
Plan data-specific adversarial strategies. 
Inference Pipeline Details 
Uncover pre/post-processing vulnerabilities. 
Model Access Type 
Scope white-box, black-box, or API-based attacks. 
Fine-Tuning / Transfer Learning History 
Identify inherited vulnerabilities or custom risks. 
Explainability Mechanisms 
Enable interpretability testing and feature sensitivity 
analysis. 
 
 
 
 
Pre-assessment Inputs: AI Application Target 
Item 
Purpose 
Prompt Engineering / Interface Logic 
Understand prompt structuring and sanitization. 
API Access Design 
Assess data flow and interface controls. 
Downstream Dependencies 
Identify impact of model output on other systems. 
Output Moderation Systems 
Plan bypass tests for content filters. 
Authentication & Role-Based Access 
Explore privilege escalation and misuse paths. 
Agentic Behavior Scope 
Test autonomous behavior boundaries. 
External Tool Integration 
Assess attack surface from RAG or orchestration 
layers. 
 
36 
 
 
 
 
Governance and Risk Context 
Item 
Purpose 
AI System Classification / Registry 
Understand model risk tier and governance level. 
Impact Assessment (DPIA, PIA) 
Align test rigor with potential risk or harm. 
Business Use Case Clarity 
Define what constitutes misuse or unsafe outputs. 
Ethical / Safety Requirements 
Guide scope and red team rules of engagement. 
Adversarial Testing Policy 
Understand baseline controls and test expectations. 
Incident Handling Procedures 
Ensure response plan exists for unintended harm. 
 
 
 
 
Mapping Risks to Tactics, Tactics to Techniques (RTTs) 
 
Risk enumeration is critical to better formulate an attack surface, but it is also important 
to convert risks into actionable items. To accomplish this, the AI2 Framework leverages 
MITRE ATLAS to map each red-team aligned risk to an ATLAS Tactic and Technique: 
     Table 12: Risks → Tactics → Techniques (MITRE ATLAS) 
Risk 
Tactic 
Tactic ID 
Technique 
Technique ID 
Social Engineering 
Initial Access 
AML.TA0001 Phishing 
AML.T0052 
Malicious Code Generation 
Execution 
AML.TA0002 Malicious Code 
Generation 
AML.T0011 
Vulnerability Discovery 
Reconnaissance AML.TA0003 
Search for Publicly 
Available Adversarial 
Vulnerability Analysis 
AML.T0001 
Identity Impersonation and 
Synthetic Identity 
Credential 
Access 
AML.TA0004 Credential Stuffing 
AML.T0055 
Increased Attack Surface 
Reconnaissance AML.TA0003 Attack Surface 
Mapping 
AML.T0003 
Complex Attack Surface 
Reconnaissance AML.TA0003 Complex Attack 
Surface Analysis 
AML.T0006 
 
37 
 
CBRN Content Generation 
Impact 
AML.TA0014 Malicious Content 
Generation 
AML.T0048 
Information Integrity 
Impact 
AML.TA0014 Data Manipulation 
AML.T0048.000 
Lower Offensive Cyber 
Barriers 
Resource 
Development 
AML.TA0005 Tool Development 
AML.T0016.001 
Vector and Embedding 
Weaknesses 
Exploitation 
AML.TA0006 Adversarial Example 
Generation 
AML.T0015 
Insecure Integrated 
Component 
Initial Access 
AML.TA0001 Supply Chain 
Compromise 
AML.T0010 
Rogue Actions 
Execution 
AML.TA0002 Unauthorized 
Command Execution 
AML.T0012 
Output Integrity Attack 
Impact 
AML.TA0014 Output Manipulation 
AML.T0048.001 
Insecure AI Data or Models 
Initial Access 
AML.TA0001 Model Theft 
AML.T0024 
Insecure Model Output 
Impact 
AML.TA0014 Output Manipulation 
AML.T0048.001 
Insider Threat/Internal 
Misuse of AI 
Insider Threat 
AML.TA0012 Abuse of Access 
AML.T0053 
Attribute inference attack 
Collection 
AML.TA0011 Attribute Inference 
AML.T0024.000 
Data poisoning 
Impact 
AML.TA0014 Training Data 
Poisoning 
AML.T0018 
Model poisoning 
Impact 
AML.TA0014 Model Poisoning 
AML.T0019 
Prompt Injection 
Execution 
AML.TA0002 Prompt Injection 
AML.T0051.000 
Prompt Leaking 
Collection 
AML.TA0011 Prompt Leakage 
AML.T0051.001 
Prompt Priming 
Execution 
AML.TA0002 Prompt Manipulation 
AML.T0051.002 
Jailbreak Attacks 
Defense Evasion AML.TA0010 Jailbreak 
AML.T0054 
Input manipulation attack 
Execution 
AML.TA0002 Adversarial Input 
AML.T0015 
Extraction attack 
Collection 
AML.TA0011 Model Extraction 
AML.T0025 
Model inversion attack 
Collection 
AML.TA0011 Model Inversion 
AML.T0024.001 
Model exfiltration 
Exfiltration 
AML.TA0013 Model Exfiltration 
AML.T0024.002 
Model reverse engineering 
Reconnaissance AML.TA0003 Model Reverse 
Engineering 
AML.T0014 
Model theft 
Exfiltration 
AML.TA0013 Model Theft 
AML.T0024 
 
38