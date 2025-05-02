Identify High-Risk AI 
High-risk AI solutions carry the greatest potential for harmful impact and regulatory 
non-compliance, particularly due to legislative mandates that require continuous 
assurance and robust risk mitigation controls. Consequently, these systems demand 
the broadest scope of safeguards, thereby serving as a benchmark that can be tailored 
to lower-risk AI use cases. The AI2 Framework utilizes two examples of high-risk AI as 
described below. 
 
Referencing Table 1c: Layer Attack Surface Impact, the capability and operational 
technique layers present the most significant or numerous AI risks. A common AI 
capability in high demand today is generative AI, and given the unique and distinct 
risks of agentic AI, its frequent alignment with both the capability and operational 
technique layers, and its growing popularity, agentic AI are both considered high-risk 
AI.  
 
High-Risk AI includes: 
● Generative AI 
● Agentic AI 
● AI solutions meeting the criteria established by the EU AI Act, including 
Safety-Critical AI (autonomous vehicles), Healthcare AI (diagnostic imaging), 
Financial AI (algorithmic trading), and Cyber Security AI (automated incident 
response playbooks) 
 
Exploring a practical basis for establishing generative and agentic AI as high-risk: 
●  Generative AI (GenAI or GAI):  
Creates new content based on learned patterns → unpredictable 
Key risks: 
● Harmful Content Generation 
● Hallucinations & Fabrications 
● Agentic AI (AI agents or agents) 
Autonomously execute actions toward goals → unpredictable 
Key risks: 
● Emergent Goals & Autonomy (Goal Drift) 
● Deceptive Behaviors 
 
Harmful content is a serious risk, and emergent goals are almost eerie to learn about; 
however, it is the unpredictable nature of generative and agentic AI that drives their 
high-risk designation, where the consequence of this is both generative and agentic AI 
require layered protection, continuous monitoring, and routine adversarial testing.  
 
14 
 
AI Risk Profile 
 ΔRisksAI + RisksResponsible AI + RisksDocumented = RiskAI Profile 
∑
 
    Table 2: AI Risk Types 
AI Risk Type 
Description 
New 
Risks introduced by the AI solution. 
Responsible AI 
Generation of or failure to prevent harms.  
Documented 
Risks documented in internal policies and standards and public frameworks and 
regulations. 
Emerging Risks 
Emerging AI risks fed into the workflow as part of maintenance. 
 
New (ΔRisksAI) 
 
New risks capture the novel threat vectors created by the rapidly evolving and complex 
nature of AI technology—from unexpected emergent behaviors to novel adversarial 
tactics. These risks can be articulated in the sense they have been here, i.e., emergent 
behavior, however it is difficult to plan a mitigation strategy for a risk that has not been 
discovered yet.  
 
This speaks to 1) the criticality of a layered defense but 2) an OECD reference to the 
importance of a red team function for identifying unknown risks:  
 
“Both known and unknown AI risks should be anticipated to prevent harm. 
Unknown risks might include risks to robustness (i.e. breakdown); security (i.e. hacks); 
secondary uses or misuses of a system, including use of pre-packaged coding for 
malicious purposes; psychological and social impact; and reputational risks. Risk and 
impact assessments can be conducted to identify risks and design mitigation strategies 
before, during, and after deployment. One approach to identifying unknown risks is 
known as “red teaming”, which refers to systematic and controlled attempts to probe 
and expose flaws and weaknesses in a system, process, or organisation to identify and 
mitigate unknown risks.” 
 -from OECD: Advancing Accountability in AI 
 
 
 
15 
 
Considering this, the current AI Risk Profile is: 
 
Table 3: New Risks 
Reference 
Risk 
Center for AI Safety (CAIS) 
Emergent Goals/Behavior 
OECD: Advancing Accountability 
in AI 
Unknown AI Risks 
 
Responsible AI (Harms) 
 
“Responsible AI aims to prioritize people in our design process, considering both the 
benefits and potential harms that AI systems may have on society.”  This is a quote 
from Microsoft, a company who has built a comprehensive approach to managing the 
risks of harm in their AI solutions. In this regard, harm reflects concerns over whether 
an AI solution is used in ways that uphold fairness, protect privacy, and maintain 
transparency and accountability. 
 
Defined by the Center for Security and Emerging Technology (CSET) as “when an 
entity experiences harm (or potential for harm) that is directly linked to the behavior of 
an AI system,” harm focuses on the potential ethical, societal, and safety-related 
impacts from deploying AI systems. Harm can be tangible and intangible, examples of 
both follow below: 
 
Tangible Harm: 
● Autonomous vehicle crashes into another vehicle 
● AI trading algorithm executes unauthorized trades resulting in grave financial 
loss 
● An LLM outputs medical data, resulting in a HIPAA violation 
 
Intangible Harm: 
● AI-generated toxic or biased outputs lead to emotional trauma 
 
● AI system is publicly criticized for reinforcing gender bias 
● Facial recognition AI disproportionately misidentifies people of color 
 
Mitigations should be in place to prevent the materialization of harms from any AI 
system, especially generative AI systems with new content that could bypass a filtering 
system. Red teams can simulate or reveal vulnerabilities that lead to physical, financial, 
or data harms, but other controls should be in place to further reduce the risk of harm. 
 
 
 
16 
 
 
The AI2 Framework lists the categories of harm with relevant examples in Table 4: 
Harm Categories. Some prominent organizations rank the severity level of a harmful 
output, mostly to determine the applicable follow up actions and consequences. If this 
is of interest, the Microsoft harm rating system is a good place to start. 
 
          Table 4: Harm Categories  
                               
Harm Category 
Example 
Physical Harm 
Injury from autonomous system 
Psychological Harm 
Toxic chatbot causing trauma 
Financial/Economic Harm 
Biased loan denial, unauthorized trading 
Informational Harm 
Privacy breach, IP leakage, prompt inversion 
Reputational Harm 
False claims generated by AI 
Discrimination & Inequity 
Biased hiring algorithm 
Autonomy and Agency Harm 
Covert manipulation or deceptive agents 
Social & Democratic Harm 
AI-generated propaganda, loss of civic trust 
Environmental Harm 
High carbon footprint of AI models 
Legal/Regulatory Harm 
GDPR noncompliance, unauthorized surveillance 
Operational Harm 
Service outage due to adversarial inputs 
Ethical/Value-Based Harm 
Violating ethical norms 
 
Consolidating the two tables produced so far, the AI Risk Profile is: 
 
   Table 5: AI Risk Profile Considering Responsible AI (Harms) 
Risk 
Description 
Emergent Goals/Behavior 
Unintended objectives or behaviors that arise from the AI’s 
training data or optimization functions. 
Unknown AI Risks 
Unanticipated vulnerabilities or consequences not yet 
identified due to the novelty or complexity of the AI. 
Physical Harm 
AI-driven actions that could cause bodily injury or damage 
(i.e., in robotics, autonomous vehicles). 
Psychological Harm 
Negative mental or emotional effects caused by interactions 
 
17 
 
with AI (i.e., manipulative or toxic content). 
Financial/Economic Harm 
Monetary losses from incorrect predictions, fraud 
enablement, or disruption of markets or business models. 
Informational Harm 
Misinformation, disinformation, or degradation of information 
quality caused or amplified by AI systems. 
Reputational Harm 
Damage to an individual’s or organization’s public image due 
to AI errors, misuse, or controversial outputs. 
Discrimination & Inequity 
Biased outcomes from AI that disproportionately harm 
protected or vulnerable groups. 
Autonomy and Agency Harm 
Erosion of human control or decision-making ability due to 
overreliance or deceptive AI behavior. 
Social & Democratic Harm 
Undermining trust in institutions, election integrity, or public 
discourse through AI-enabled manipulation. 
Environmental Harm 
Resource-intensive AI processes (i.e., training large models) 
that contribute to environmental degradation. 
Legal/Regulatory Harm 
Violations of laws, data regulations (i.e., GDPR), or resulting 
fines and litigation stemming from AI use. 
Operational Harm 
Business disruption or process failure caused by AI errors, 
outages, or integration issues. 
Ethical/Value-Based Harm 
Breaches of societal or organizational values, even if legally 
permissible, due to AI decisions or outputs. 
 
Documented Risks 
 
Documented risks are known AI risks accounted for in enterprise policies and 
standards as well as public frameworks, legislation, regulations, and 
publications. Having compiled AI-specific risks from over two dozen sources, the 
number of documented AI risks is extensive, as shown below in the most current 
AI Risk Profile: 
   Table 6: AI Risk Profile After Considering Documented Risks 
 
18 
AI Risk Profile 
 
New Risks 
Description 
Emergent Goals/Behavior 
AI systems developing unintended objectives or behaviors that 
diverge from their original design. 
Unknown AI Risks 
Hazards not yet identified due to the evolving and opaque nature 
of AI technologies. 
 
 
19 
Responsible AI (Harm) 
Description 
Physical Harm 
Bodily injury or death caused by AI‑controlled machinery or 
systems. 
Psychological Harm 
Emotional distress or mental health impacts from AI interactions 
or outputs. 
Financial Harm 
Monetary losses resulting from AI errors or fraudulent AI‑driven 
schemes. 
Economic Harm 
Broad market disruptions or job displacement driven by AI 
adoption. 
Informational Harm 
Damage from misinformation, data breaches, or compromised 
data integrity. 
Reputational Harm 
Loss of trust or credibility for individuals or organizations due to AI 
actions. 
Discrimination & Inequity 
Unfair treatment of people or groups because of biased AI 
decisions. 
Autonomy and Agency Harm 
Erosion of individuals’ ability to make free, informed choices 
under AI influence. 
Social & Democratic Harm 
Undermining of social cohesion or democratic processes via 
AI‑driven manipulation. 
Environmental Harm 
Ecological damage from AI’s energy use or environmentally 
harmful automated actions. 
Legal Harm 
Regulatory penalties or lawsuits triggered by AI non‑compliance 
or harmful outcomes. 
Operational Harm 
Disruption to critical business or infrastructure operations due to 
AI failures. 
Ethical/Value-Based Harm 
Violations of moral or societal norms by AI, such as privacy 
intrusions. 
Regulatory Harm 
Sanctions or restrictions imposed when AI systems breach legal 
requirements. 
Documented Risks 
Description 
Social Engineering 
AI‑generated phishing or deceptive content that tricks users into 
revealing secrets. 
Malicious Code Generation 
AI producing harmful scripts or malware code. 
Vulnerability Discovery 
AI tools automating the finding of security flaws. 
Identity Impersonation and Synthetic 
Identity 
Creation or misuse of fake identities via AI. 
 
 
20 
Biased Data 
Training datasets reflecting prejudices, leading to unfair model 
outputs. 
Statistical uncertainty in pre‑trained 
models 
Inherent unpredictability in model predictions from limited data. 
Privacy risk due to enhanced 
data‑aggregation capability for AI 
systems 
Combining datasets to reveal sensitive information. 
Side‑effects not visible in statistical 
measures 
Unintended behaviors that standard metrics miss. 
Increased Attack Surface 
New vulnerabilities introduced by adding AI components. 
Complex Attack Surface 
Interconnected AI pipelines creating intricate security gaps. 
Complex Systems 
High system complexity leading to unexpected failure modes. 
CBRN content generation 
AI generating chemical, biological, radiological, or nuclear threat 
content. 
Human‑AI Interaction Risks 
Miscommunications or errors at the human–AI interface. 
Information Integrity 
Ensuring AI outputs remain accurate and untampered. 
Lower Offensive Cyber Barriers 
AI reducing skill requirements for sophisticated attacks. 
Third‑party data or component 
trustworthiness 
Risks from unvetted external AI services or datasets. 
Vector and Embedding Weaknesses Exploitable flaws in model feature representations. 
Unbounded Consumption (Sponge 
Examples) 
AI consuming excessive resources or data beyond intended 
limits. 
Excessive Data Handling 
Overcollection or misuse of data raising privacy and compliance 
concerns. 
Insecure Integrated Component 
Vulnerabilities from poorly secured AI modules within larger 
systems. 
Rogue Actions 
AI taking unauthorized or harmful actions outside its intended 
scope. 
Output Integrity Attack 
Tampering with AI responses to mislead downstream systems. 
Controllability and Autonomy Risks 
Difficulty maintaining human oversight over autonomous AI. 
Reliability and Robustness Risks 
AI failures under adversarial or unexpected inputs. 
Bias and Fairness Risks 
Unfair treatment resulting from skewed model behavior. 
Safety and Resilience Risks 
Weaknesses affecting AI’s safe operation and recovery. 
Data Quality and Integrity Risks 
Poor or corrupted data undermining AI performance. 
 
 
21 
Automated Decision‑Making without 
Safeguards 
AI making unchecked decisions without human review. 
Inadequate Data Subject Rights 
Implementation 
Failure to honor user rights like deletion or portability. 
Insecure AI Data or Models 
Insufficient protection of training data or model artifacts. 
Insecure Model Output 
Lack of validation and protection for AI‑generated outputs. 
Insider Threat/Internal Misuse of AI 
Authorized users abusing AI capabilities maliciously. 
Lack of Incident Reporting 
Mechanisms 
No processes to detect or report AI‑related incidents. 
Lack of Risk Management System 
Absence of a formal framework for AI risk identification and 
mitigation. 
Use of Prohibited AI Applications 
Deploying AI in contexts banned by policy or regulation. 
Data usage restrictions 
Policies limiting permissible uses of data in AI workflows. 
Data acquisition restrictions 
Controls on sourcing data to ensure legality and ethics. 
Data transfer restrictions 
Limits on moving data across jurisdictions or networks. 
Confidential information in data 
Sensitive details embedded in datasets requiring protection. 
Personal information in data 
Inclusion of PII that mandates privacy safeguards. 
IP information in prompt 
Proprietary content embedded in AI inputs risking leakage. 
Attribute inference attack 
Deriving private attributes from model outputs. 
Misclassification of AI risk tier 
Incorrectly prioritizing AI risks, leading to misallocation of 
resources. 
Data poisoning 
Inserting malicious samples into training data to corrupt models. 
Model poisoning 
Direct tampering with model parameters or weights. 
Prompt Injection 
Crafting inputs that hijack AI behavior. 
Prompt Leaking 
Exposing sensitive system prompts through user interactions. 
Prompt Priming 
Biasing AI outputs by preloading specific context. 
Jailbreak Attacks 
Bypassing safety filters to elicit restricted content. 
Confabulation 
AI producing plausible but fabricated statements. 
Hallucination 
AI generating factually incorrect or nonsensical outputs. 
Fabrication 
Deliberate creation of false content by AI. 
Input manipulation attack 
Altering inputs to induce mispredictions. 
Extraction attack 
Retrieving proprietary model details via queries. 
 
 
22 
Model inversion attack 
Reconstructing training data from model outputs. 
Model exfiltration 
Stealing full model artifacts. 
Model reverse engineering 
Inferring model architecture or logic. 
Model theft 
Unauthorized replication of a model. 
Membership inference attack 
Determining if specific data points were in the training set. 
Model source tampering 
Modifying model code or files to introduce vulnerabilities. 
Model skewing 
Shifting performance to favor certain classes or outcomes. 
Model deployment tampering 
Altering deployment pipelines to compromise model integrity. 
Transfer learning attack 
Exploiting pre‑trained models for malicious adaptations. 
Off-label Model Use 
Using models in contexts beyond their intended scope. 
Denial‑of‑Service 
Overwhelming AI services to disrupt availability. 
AI supply chain attacks 
Compromising third‑party AI components or datasets. 
Sensitive data disclosure 
Unintended exposure of private information via AI outputs. 
Inferred sensitive data 
AI deducing confidential details not explicitly provided. 
Unauthorized training data 
Using data without proper rights or consent. 
Confidential data in prompt 
Embedding sensitive data in AI queries risking leakage. 
Re‑identification (Mosaic Effect) 
Combining datasets to re‑identify anonymized individuals. 
Poor model accuracy 
Low predictive performance leading to incorrect decisions. 
Training‑time perturbations 
Changes during training that degrade model behavior. 
Model drift 
Performance degradation over time as data distributions shift. 
Stale or context‑detached datasets 
Using outdated or irrelevant data for inference. 
Improper output handling 
Failure to validate or sanitize AI outputs before use. 
Improper usage 
Deploying AI without necessary context or controls. 
Over‑reliance 
Excessive trust in AI decisions without human oversight. 
Disinformation / Misinformation / 
Toxic / Harmful Content 
AI generating misleading or damaging material. 
Non‑consensual use 
AI using personal data or likeness without permission. 
Intellectual property leakage 
AI revealing proprietary or confidential information. 
Intellectual property mimicry 
AI replicating protected content too closely. 
Copyright infringement 
AI outputs violating copyright law. 
 
 
23 
Generated content intellectual 
property 
Uncertainties around ownership of AI‑created works. 
Data transparency 
Lack of clarity on how data is collected, used, and processed. 
Data provenance 
Inability to trace data origins and transformation history. 
Improper Data Curation 
Poor dataset selection or labeling affecting model quality. 
Data retraining issues 
Risks during model updates, such as regressions or untested 
changes. 
Testing coverage gaps 
Inadequate testing across AI components and scenarios. 
Transparency Gaps 
Insufficient visibility into AI decision‑making processes. 
Explainability Gaps 
Lack of interpretable explanations for AI outputs. 
Accountability Gaps 
Unclear assignment of responsibility for AI decisions. 
Logging Gaps 
Missing or incomplete logs of AI activities and errors. 
Traceability Gaps 
Inability to track data and decision flows through AI pipelines. 
Regulatory & Compliance Risks 
General risks of non‑compliance with AI regulations and 
standards. 
Data privacy rights 
Violations of legal rights (i.e., GDPR data subject entitlements). 
Undisclosed AI Usage 
Failing to inform stakeholders that AI is in use. 
Use of prohibited AI applications 
Deploying AI in contexts banned by law or policy. 
Maintenance Requirements 
Neglecting ongoing monitoring and updates mandated by 
regulations. 
Semantic drift 
Gradual shift in model meaning leading to unintended behaviors. 
Multi-agent collusion 
Multiple AI agents coordinating maliciously. 
Deceptive Behavior 
AI intentionally misleading users or other systems. 
Backdoor Attacks 
Hidden triggers embedded in models causing malicious outputs. 
Excessive Agency 
Vulnerability that enables damaging actions to be performed in 
response to unexpected, ambiguous or manipulated outputs from 
an LLM 
Evasion Attacks 
Crafting inputs that bypass detection or classification. 
Processing Special Category Data 
Without Safeguards 
Handling sensitive data (i.e., health, biometric, location) without 
proper controls. 
Retrieval‑Augmented Generation 
(RAG) Pipeline Poisoning 
Injecting malicious data into external knowledge sources. 
Federated‑Learning Vulnerabilities 
Exploiting weaknesses in distributed training setups. 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
24 
Chain‑of‑Thought Injection 
Manipulating AI reasoning steps to alter outcomes. 
Model Interpretability Evasion 
Techniques that obscure how models make decisions. 
Ownership Evasion 
Concealing the true origin or owner of AI models. 
Covert Channel Attacks 
Using AI systems to stealthily exfiltrate data.