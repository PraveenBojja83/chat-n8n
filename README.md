Project Title
n8n Chatbot Orchestrator with AI Agent, Context Memory, and Dynamic Intent Logic

Description
This project is a real-time guest chat automation system designed in n8n, orchestrating multiple workflow nodes such as chat ingestion, file-based context enrichment, programmable logic, AI-driven understanding, memory augmentation, and SQL logging.

Core Workflow:

Chat Message Node: Captures incoming guest or user messages as the workflow entry point, supporting web, WhatsApp, or other chat frontends.

Edit Fields/Read File Node: Dynamically loads or edits context, brand intents, or configuration from a local or remote CSV/JSON file, allowing property-specific rules and real-time updates.

JavaScript Function Nodes: Applies advanced, programmable logic for intent matching, custom transformations, and multi-step handling of guest requests.

Merge Node: Integrates structured data from multiple nodes, enabling contextual enrichment, session-scoped variables, and modular conversation logic.

AI Agent Node: Connects to generative AI models (e.g., Gemini/GPT) for fallback replies, complex request understanding, and enhanced guest satisfaction.

Gemini Chat Model Node: Delivers intelligent natural language responses, supplementing rule-based logic and boosting accuracy for open-ended or ambiguous queries.

Simple Memory Node: Maintains user/session state, enabling personalized, context-aware replies and tracking ongoing requests for seamless multi-turn dialogues.

SQL Logging Node: Inserts all chat transactions—complete with guest, intent, response, department, and AI/memory context—into a structured database for analytics, escalation, and reporting.

Capabilities:

Modular node-based architecture enabling rapid addition of new hotels, departments, and AI models.

Layered context and memory logic ensures both rule-based and AI-driven responses depending on query complexity.

End-to-end traceability of each guest interaction from ingestion through AI handling, memory usage, and persistent database entry.

Use Cases:

Providing instant answers to guest questions about policies (e.g., smoking, pool, meals) with instant, accurate automation.

Handling both simple rule-based requests and complex conversational queries using a blend of logic and AI.

Logging all conversations for service improvement and regulatory compliance.
