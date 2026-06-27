Abhilasha — Agentic AI Healthcare Assistant

Selected for Round 2 of the Ulster University Agentic AI Hackathon (UK).

WHAT IT ACTUALLY DOES ?
Multi-agent AI health assistant with intent classification, medical RAG retrieval,
triage, and specialist-referral agents — each with bounded tool-use scope to prevent
hallucination cascade.

Stack Used - 
LangChain · Anthropic SDK · RAG · Mistral-7B (QLoRA fine-tuned) · PEFT · Hugging Face Hub

Fine tuning 
Mistral-7B-Instruct fine-tuned on MedAlpaca using QLoRA (4-bit NF4, LoRA r=16).
Adapter weights published on Hugging Face Hub.

