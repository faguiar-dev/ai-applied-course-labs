# LLM Architecture Notes

## High-Level Architecture

Input → Tokenization → Embeddings → Transformer Layers → Output Tokens

### Important Observations

- LLMs are probabilistic systems
- Outputs are non-deterministic
- Token context size directly impacts cost
- Latency increases with model size

### Backend Implications

- Need for logging token usage
- Retry strategies
- Guardrails for hallucination
- Validation pipelines
