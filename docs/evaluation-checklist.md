# LLM Evaluation Checklist

## 1. Response Quality

Evaluate generated responses for:

- Factual accuracy
- Relevance
- Completeness
- Groundedness
- Hallucination risk

## 2. RAG Evaluation

Measure:

- Retrieval precision
- Context relevance
- Answer faithfulness
- Retrieval latency

## 3. Agent Observability

Track:

- Tool execution traces
- Failed API calls
- Token consumption
- Model response time
- Retry attempts

## 4. Production Monitoring

Recommended practices:

- Use OpenTelemetry for distributed tracing.
- Track model and prompt versions.
- Define measurable quality thresholds.
- Run regression evaluations before deployment.
- Monitor latency and inference costs.
