# AI Security Checklist

Use this for AI security content, future tooling, and production-agent architecture reviews.

- Identify what data the AI system can read.
- Identify what actions the AI system can take.
- Define identity, role, tenant, and permission boundaries.
- Require audit logs for tool calls and state-changing actions.
- Define approval gates for sensitive actions.
- Include prompt-injection and data-exfiltration risks.
- Prefer least-privilege tool scopes over broad access.
- Include rollback or recovery guidance for failed actions.
- Define evals and incident review for security-relevant failures.
- State what must be reviewed by humans before production.
