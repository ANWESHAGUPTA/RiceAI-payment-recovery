# Prompt V1 — Basic Classification

```
Analyze this Stripe payment failure and respond in JSON only with keys: risk_score (1-10), failure_type, recovery_strategy, urgency, email_subject, email_body. Event: {event_data}
```

## Results
- Basic classification works
- Risk scores inconsistent across similar failure types
- Email tone too generic
- No differentiation between temporary vs permanent failures
