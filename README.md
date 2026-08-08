# Rahul Kumar

```console
$ vllm serve Rahulroy5/rahul-kumar --dtype human
  ✓ base_model .......... IIT Bombay  [B.Tech + M.Tech]
  ✓ attention heads ..... agents · RAG · fine-tuning · inference
  ✓ safety alignment .... no hacky solutions
  → server ready — accepting offers  [AI Engineer · ML Engineer · Data Scientist]
```

I build AI systems from first principles — agent loops without LangChain, tool calling
without function-calling APIs, a GPT from bare PyTorch — because knowing what the
abstraction hides is what lets you debug it at 2am. Shipped in industry at
**Hashtee Lab** (vLLM on RunPod GPUs, document intelligence) and **Akai Space**
(CV video pipelines, GPT-4 Vision).

**[Portfolio ↗](https://rahulroy5.github.io)** · [LinkedIn](https://linkedin.com/in/rahul-kumar-25a9b2252) · [Hugging Face](https://huggingface.co/Rahul3736) · [rroy3736@gmail.com](mailto:rroy3736@gmail.com)

---

## Shipped artifacts

Every project ships with one number I can defend.

| Project | The number | How |
|---|---|---|
| [ocr-finetune-eval](https://github.com/Rahulroy5/ocr-finetune-eval) | **~7× drug-name accuracy** vs base (2.1% → 14.9%) | DeepSeek-OCR 3B + LoRA on medical prescriptions; field-level eval on safety-critical fields, not just CER — [model on HF](https://huggingface.co/Rahul3736/deepseek-ocr-medical-prescription) |
| [mini-agent-orchestrator-2.0](https://github.com/Rahulroy5/mini-agent-orchestrator-2.0) | **0 agent frameworks** | Reactive agent loop from scratch — observes tool results, adapts; never emails a confirmation for a failed cancellation |
| [tool-calling-from-scratch](https://github.com/Rahulroy5/tool-calling-from-scratch) | **token-by-token** | Incremental parser catches tool-call XML mid-stream, executes, re-injects — no function-calling API, no hidden modes |
| [rag-assistant](https://github.com/Rahulroy5/rag-assistant) | **0 cloud calls** | Fully local PDF Q&A: semantic chunking, hybrid retrieval + reranking, ChromaDB, Ollama — documents never leave the machine |
| [nano-GPT](https://github.com/Rahulroy5/nano-GPT) | **1.82 cross-entropy** | GPT transformer written from bare PyTorch, trained on Shakespeare |
| [nifty-signal-pod](https://github.com/Rahulroy5/nifty-signal-pod) | **evals before training** | Fine-tuned SLM for NIFTY 50 signals inside a safety orchestrator with 3 hard suppression rules |

Currently researching: [encrypted-traffic-classifier](https://github.com/Rahulroy5/encrypted-traffic-classifier) —
classifying Tor/VPN/HTTPS traffic from flow metadata alone, without decrypting a byte.

---

## Stack

`Python` `PyTorch` `vLLM` `LoRA/Unsloth` `FastAPI` `Ollama` `ChromaDB` `Hugging Face`
`TensorFlow` `scikit-learn` `XGBoost` `Docker` `RunPod` `Databricks` `SQL` `OpenCV` `FFmpeg`

---

## Beyond the terminal

Gold — National Science Olympiad · Bronze — International Mathematics Olympiad ·
345kg powerlifting total @ 60kg bodyweight · 70+ students mentored at IIT Bombay

*The fastest way to reach me is [email](mailto:rroy3736@gmail.com). The most fun way is the
[terminal on my portfolio](https://rahulroy5.github.io/#playground) — try `sudo hire`.*
