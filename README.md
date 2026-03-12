# SchemaGuard
Schema-based AI Data Poisoning Detection for LLM/RAG Pipelines

When an AI system reads external webpages, the Schema.org/JSON-LD structured data, visible text, and even inconsistencies between the two can become entry points for data poisoning or indirect prompt injection.

Therefore, we're not building a typical chatbot, but rather an AI data security auditing tool for engineers and platform administrators.

Usage Flow:

User enters a URL

→ System retrieves page content

→ Extracts schema / JSON-LD / visible text

→ Analyzes for potential malware infection risks

→ Generates a risk report


