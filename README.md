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
