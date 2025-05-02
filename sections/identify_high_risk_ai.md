Agentic AI Solution Layers Considerations 
 
The peculiarities of Agentic AI are covered in depth in a later section (see Agentic AI 
Nuances), but a brief introduction is necessary here due to their relevance to the 
previous analysis. Wherever possible, Agentic AI solutions should be broken down 
using the same AI Solution Layering approach applied to traditional systems. 
 
However, Agentic AI does not fit neatly within this model. While it may use familiar 
capabilities (i.e., LLMs, retrieval techniques (RAG), or generative outputs), Agentic AI 
introduces a distinct operational paradigm - one based on autonomous action, goal 
pursuit, and decision-making. These systems often orchestrate multiple layers 
simultaneously, integrating modalities and techniques in ways that blur traditional layer 
boundaries. 
 
As a result, Agentic AI must be assessed across the full span of AI Solution Layers. 
Each layer should still be classified and tested individually, but to achieve sufficient 
assurance, Agentic AI must also be tested holistically, with all applicable risks 
considered—especially those tied to autonomy, orchestration, and emergent behaviors. 
 
Remember, Agentic AI introduces a new class of cybersecurity risk - not only does it 
carry the same risks as traditional AI Solutions, its autonomous nature means it must 
be considered an independent threat actor. 
 
  
 
 
 
 
 
 
 
 
 
 
 
13 
 
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