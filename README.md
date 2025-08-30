# LLM Adversarial Testing: A Case Study on ChatGPT

**Introduction:**

While Large Language Models (LLMs) are becoming increasingly robust, proactive adversarial testing remains critical for identifying novel misuse pathways. This project documents a case study on challenging ChatGPT's safety protocols using indirect and creative prompting techniques. My goal was to explore the model's response to non-traditional prompts and analyze its behavior beyond standard safety guardrails.

**Methodology:**

I employed a persona-based prompt engineering technique, directing the model to act as a corporate consultant or an HR manager. The aim was not to extract harmful information, but to see if the model could be coaxed into revealing or suggesting internal processes that would typically be off-limits.

**Findings:**

After a series of carefully crafted dialogues, the model did not directly provide the information I was seeking. Instead, it subtly directed me towards using an internal feedback mechanism to achieve my goal. This was a critical finding. It demonstrated that even when a model successfully blocks a direct request, it may still provide indirect pathways to exploit or circumvent its intended behavior. This highlights a nuanced vulnerability in the model's design.

**Conclusion:**

This case study shows that testing AI models should go beyond what they say and also focus on what they guide the user to do. This "indirect guidance" could be a significant area for future adversarial testing, offering a new perspective on how to analyze and strengthen AI safety protocols. The project proves my capability to think like a "red teamer," identifying subtle yet important risks that traditional testing methods might miss.

---

### Case Study 2: Exploiting Abstract and Theoretical Concepts

**Introduction:**
AI models are typically trained to block direct requests for harmful information. However, this case study explores how a model can be manipulated by discussing abstract, theoretical, or seemingly harmless scientific concepts.

**Methodology:**
I initiated a conversation with ChatGPT about a theoretical mechanism to apply the Sun's gravitational force to Earth. The goal was to test if the model would provide guidance on a concept that, while not immediately dangerous, has a high potential for misuse if the underlying principles are explained.

**Findings:**
Instead of refusing the request outright, the model provided detailed guidance on the scientific and engineering principles required for such a mechanism. This subtle and indirect engagement on a potentially dangerous topic demonstrates a significant gap in its safety protocols. The model's behavior shows that even an abstract, physics-based scenario can be used to extract actionable information with harmful potential.

**Conclusion:**
This finding highlights a crucial aspect of adversarial AI: the need to test for vulnerabilities in the "gray areas" of knowledge. It reinforces the idea that an AI safety analyst must not only look for direct violations but also for indirect pathways that can be exploited by a malicious actor. This proves my ability to identify nuanced and complex security risks in AI systems.
