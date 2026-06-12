# Tarjama-
Human-in-the-Loop Arabic Machine Translation


Built a human-in-the-loop (HITL) translation environment for English–Arabic and French–Arabic. Curated a large-scale multi-domain
parallel corpus, benchmarked state-of-the-art multilingual models, and designed an agentic pipeline for continuous learning from human
feedback.
n NLLB-3.3B achieved best performance after fine-tuning: BLEU 48.81, METEOR 73.24, TER 30.52
n QLoRA fine-tuning pipeline with 6-agent orchestration (Preprocessor, Validator, Deduplicator, Executor, Monitor, Orchestrator)
n FAISS-based deduplication & automatic fine-tuning triggers at 10k corrections or 7-day intervals
