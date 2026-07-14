# Sentinel Edge

Sentinel Edge is an AI-powered threat intelligence platform that correlates cybersecurity telemetry with banking transaction behavior to proactively detect cyber threats, financial fraud, and emerging quantum-related risks. By combining multiple sources of security and transactional data, the platform provides contextual risk assessment and explainable insights to support faster and more accurate decision-making.

## Problem Statement

Banks generate large volumes of cybersecurity and transactional data, but these data sources are often analyzed independently. This separation makes it difficult to detect sophisticated attacks, identify fraud patterns, and recognize emerging threats such as Harvest Now, Decrypt Later (HNDL) attacks.

Sentinel Edge addresses this challenge by correlating cybersecurity events with transactional behavior to provide a unified and explainable threat intelligence platform.

## Key Features

- Correlates cybersecurity telemetry with transaction data
- Detects anomalous user and transaction behavior
- Identifies potential fraud patterns
- Monitors indicators of quantum-related security risks
- Generates explainable AI-based risk assessments
- Reduces false positives through contextual analysis
- Provides a unified security and fraud intelligence dashboard

## Technology Stack

### Backend
- Python
- FastAPI

### AI & Machine Learning
- XGBoost
- Isolation Forest
- Transformer
- SHAP

### Data Processing
- Pandas
- NumPy
- Scikit-learn

### Database
- PostgreSQL

### Frontend
- React.js

## System Workflow

1. Collect cybersecurity telemetry.
2. Collect banking transaction data.
3. Enrich events using customer profile and threat intelligence.
4. Correlate events across multiple data sources.
5. Analyze behavior using AI/ML models.
6. Generate contextual risk scores.
7. Explain the reasoning behind each alert.
8. Present actionable insights through the dashboard.

## AI Components

| Component | Purpose |
|----------|---------|
| Isolation Forest | Detects anomalous user and system behavior |
| XGBoost | Predicts fraudulent transactions |
| Transformer | Learns suspicious event sequences |
| SHAP | Explains AI predictions for analyst transparency |

## Project Structure

```
Sentinel-Edge/
├── backend/
├── frontend/
├── models/
├── data/
├── api/
├── utils/
├── docs/
├── requirements.txt
└── README.md
```

## Future Enhancements

- Temporal Graph Network (TGN) for relationship-based threat detection
- Real-time event streaming with Apache Kafka
- Live Threat Intelligence integration
- Quantum readiness assessment
- SIEM integration

## License

This project is developed for educational and hackathon purposes.
