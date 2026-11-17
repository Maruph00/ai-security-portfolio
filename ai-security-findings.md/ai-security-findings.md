AI Security Findings and Recommendations

Introduction

This document summarises key security risks associated with large language models and provides recommendations for improving AI security.

Key Security Findings

1. Direct Prompt Injection

Malicious user instructions can attempt to override an AI system's intended behaviour.

Recommendation: Maintain clear instruction hierarchies and validate user requests.

2. Indirect Prompt Injection

External content can contain malicious instructions that influence AI responses.

Recommendation: Treat retrieved documents, websites and emails as untrusted input.

3. System Prompt Extraction

Users may attempt to expose hidden system instructions.

Recommendation: Avoid placing passwords, API keys or sensitive information in system prompts.

4. Information Disclosure

Poorly designed AI applications may expose information that should remain private.

Recommendation: Apply access controls and protect sensitive information.

5. Unreliable AI Responses

AI models can produce inaccurate or unsupported information.

Recommendation: Introduce response validation and human review where necessary.

General Security Recommendations

- Conduct regular security assessments.
- Test against prompt injection attempts.
- Protect sensitive information.
- Monitor unusual model behaviour.
- Apply appropriate access controls.
- Document and review security findings.

Conclusion

AI security requires continuous testing, monitoring and improvement. Understanding common vulnerabilities is an important step towards building safer and more reliable AI systems.

Research Status

Educational security research and recommendations. Further practical testing is required to validate these findings.
