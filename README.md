# fixeval a cancelled trial stops during its backoff

None

### Sample
```json
[
  {
    "id": "trial_T001_event_01",
    "timestamp": "2023-10-26T09:00:00Z",
    "metric": "trial_initialization",
    "region": "us-east-1",
    "risk_score": 15
  },
  {
    "id": "trial_T001_event_02",
    "timestamp": "2023-10-26T09:15:00Z",
    "metric": "trial_running",
    "region": "us-east-1",
    "risk_score": 20
  }
]
```

[Full Download](https://t.me/Datawonder_bot?start=payload)