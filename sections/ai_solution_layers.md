AI Solutions 
 
The AI2 Framework broadly defines AI Solutions as applications utilizing AI 
functionality. Not all AI-specific risks will apply to all AI Solutions, but all AI Solutions 
introduce certain AI-specific risks. Knowing the AI Solutions utilized is the first step 
towards specifying AI risks that must be managed as it allows for the list of risks 
compiled in the AI Risk Profile step to be tailored to a given AI Solution based on risks 
pertinent to that AI Solution.  
 
To understand the risks introduced by an AI solution, it is insufficient to only consider 
the AI Solution at the application or use-case level 1. Instead, each layer of an AI 
solution must be considered. The AI Solutions step of the AI2 Framework introduces 
the AI Solution Layers sub-framework to deconstruct, analyze, and adequately 
document the risks of an AI Solution. 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
1 Examples of “application or use-case level” include “chatbot”, “agentic AI”, or “computer vision”. While 
each of these examples are useful categorizing terms in a risk alignment effort, alone they are 
insufficient to articulate an appropriately inclusive risk profile as the same application or use-case will 
often have varying sub-components that introduce different AI risks. 
 
7 
 
AI Solution Layers 
 
The AI Solution Layers sub-framework1 deconstructs a given AI Solution into distinct 
layers to achieve the following: 
● Assist in the identification of applicable AI risks introduced by an AI Solution to 
the most comprehensive degree possible 
● Assist in the alignment of pertinent AI risks to a given AI Solution to improve 
efficiency in AI risk management control selections and processes 
● Identify the layer(s) of the AI solution responsible for the introduction of the 
greatest number or high severity AI risks 
 
The AI2 Framework considers five distinct AI Solution Layers: 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
    Figure 2: AI Solution Layers 
 
8 
 
Table 1a provides a brief description of each layer: 
Table 1a: AI Solution Layers 
Layer 
Description 
Modality 
Type of data: Text, Image, Audio, Tabular, Multimodal 
Field/Technique 
Area of AI focused on processing that modality (i.e., NLP, CV, 
Speech Processing) 
Capability 
Specific task: Summarization, Classification, Question Answering, 
Image Generation 
Model/Architecture 
LLMs, CNNs, ViTs, Speech Transformers, Multimodal Models 
Operational Technique 
RAG, Prompt Engineering, Cross-modal Retrieval, etc. 
 
 
Single vs. Multimodal 
 
Single-modal AI Solutions involve the ingestion of a single data source, i.e., a 
question-answering chatbot that only accepts user text as input. With the exception of 
AI Agents (discussed below), single modal AI Solutions will often align neatly with the 
AI Solution Layers sub-framework.  
 
The table below lists generic AI Solutions 1-4 with common modalities and 
corresponding field/techniques, capabilities, model/architecture, and operational 
techniques: 
 
Table 1b.1: AI Solution Layering (Single-Modal) 
Layer 
AI Solution 1 
AI Solution 2 
AI Solution 3 
AI Solution 4 
Modality 
Text (natural 
language) 
Images, Videos 
● Speech 
● Sounds 
Structured data 
(tables) 
Field/Technique 
Natural Language 
Processing (NLP) 
Computer Vision 
Speech 
Processing 
ML for Structured 
Data 
Capability 
Text 
Classification, 
Summarization, 
QA, Generation 
Image 
Classification, 
Object Detection, 
Image 
Generation, 
Segmentation 
Speech 
Recognition 
(ASR), Speech 
Synthesis (TTS), 
Speaker 
Identification 
Fraud Detection, 
Predictive 
Modeling, 
Recommendation 
 
9