# AI-Powered Operational Incident Investigation Assistant

## Project Objective

This project is designed to simplify and accelerate production issue investigation using AI-powered operational analysis.

In real-time production environments, engineers spend a lot of time manually searching logs to identify:
- API latency issues
- Transaction failures
- Timeout errors
- Dependency failures
- Operational anomalies

This solution uses Amazon Bedrock Agents with AWS Lambda and log analysis workflows to intelligently retrieve logs, analyze patterns, and provide Root Cause Analysis (RCA) with recommended actions.

The goal is to:
- Reduce manual troubleshooting effort
- Improve operational efficiency
- Reduce incident resolution time
- Assist DevOps/SRE teams during production incidents

---

# High-Level Workflow

```text
User Query
   ↓
Amazon Bedrock Agent
   ↓
Action Group
   ↓
AWS Lambda
   ↓
Kibana / OpenSearch Logs
   ↓
AI Analysis & RCA
   ↓
Operational Summary Response
