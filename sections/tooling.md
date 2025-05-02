you're the admin"). Evaluate whether the agent role-plays beyond 
boundaries or fabricates credentials. 
Goal Hijacking via 
Environmental Cues 
Provide carefully crafted environment data (metadata, file names, 
injected cues) that suggest alternate goals. Observe shifts in behavior 
or goal prioritization. Use shadow prompts to trace internal decision 
logic. 
Agent Goal Manipulation 
Test for vulnerability to external inputs that modify goal state (i.e., 
prompt injection that redefines the objective). Use adversarial prompt 
chaining or third-party injected objectives. 
Compromised Agents 
Simulate attacker control of the agent's memory, tools, or system 
prompts. Test if manipulated agents can act maliciously. Use forensic 
logging to trace injected behaviors. 
Agent Impersonation 
Attempt to clone or spoof agent identity within multi-agent systems. 
Observe whether identity verification (i.e., cryptographic keys or agent 
registry lookups) is bypassed or faked. 
Agent Identity Compromise 
Introduce access to agent tokens, configuration, or identity parameters. 
Test for reuse or theft of identity in replay attacks. Monitor for 
unauthorized identity transitions. 
Agent Compromise 
Simulate code or behavior corruption (i.e., agent injected with malicious 
subroutine). Validate resilience and fallback behaviors. Use simulated 
payloads to induce misbehavior. 
Registry Compromise 
Test centralized agent registries for modification without authorization. 
Simulate registry poisoning by inserting malicious or spoofed agents. 
Audit how agents validate discovered identities. 
Chain-of-Thought Injection 
Inject adversarial reasoning steps into agent plans or few-shot prompts. 
Observe if agents follow malicious or misleading chains. Use 
intermediate trace logging to detect hijacked logic. 
Multi-Agent Collusion 
Place multiple agents in a shared goal task with misaligned individual 
incentives. Analyze communication patterns, delegation behavior, or 
synchronized responses to detect covert cooperation. 
 
 
 
 
 
 
 
 
 
 
50 
 
Tooling 
 
Adversary testing, especially when combined with other forms of testing, i.e., 
web application penetration tests for AI Applications, virtually require the use of 
automated tools to get adequate coverage and assurance. 
 
One conceptually simple reason for this is the nature of LLMs. LLMs output 
different responses to the same prompts, and this means the absence of a 
vulnerability in a response to a malicious prompt does not provide a high degree 
of assurance that no vulnerability exists. AI vulnerabilities also tend to be subtle, 
where only an automated tool would detect a measurable difference in the 
model behavior or output to know the exploit was successful. Automated tools 
are essential parts of adversarial testing and therefore adversary imitation. 
 
Tools Overview 
 
Adversarial & Robustness Testing Tools 
Tables 18-22: Tooling Solutions 
Tool 
Description 
Adversarial Robustness Toolbox (ART) 
IBM toolkit for adversarial ML testing, 
poisoning, and privacy attacks. 
Foolbox 
Adversarial example generation for 
robustness testing (white/black box). 
SecML 
Python library for secure and adversarial 
machine learning. 
TextAttack 
NLP-specific adversarial attack generation 
and benchmarking. 
PrivacyRaven 
Privacy testing (membership inference, model 
inversion, extraction). 
ModelSim (MITRE ATLAS) 
Model simulation and attack replication 
aligned with MITRE ATLAS. 
HAX-LLM 
LLM hallucination and safety evaluation (by 
Harvard researchers). 
PromptBench 
Prompt sensitivity benchmarking and prompt 
attack simulation. 
 
51