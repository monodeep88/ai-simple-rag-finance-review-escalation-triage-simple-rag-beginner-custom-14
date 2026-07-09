# Generation Notes

Mode: ai

Model: groq / llama-3.1-8b-instant

Fallback reason: OpenAI limit reached. Automatically switched to Groq.

Architecture: Real Estate Policy Assistant

Template path: templates/simple-rag/real-estate-policy-assistant

Short description:

A simple RAG (Red, Amber, Green) project for finance review escalation triage

Architecture notes:

- The system will use a combination of natural language processing (NLP) and machine learning algorithms to categorize tasks into Red, Amber, and Green. The escalation service will be responsible for sending notifications to stakeholders when tasks are escalated.

Project planner agent workflow:

- Architecture Agent: Define app boundaries, data flow, runtime stack, and integration points. Outputs: The system will use a combination of natural language processing (NLP) and machine learning algorithms to categorize tasks into Red, Amber, and Green. The escalation service will be responsible for sending notifications to stakeholders when tasks are escalated.
- Backend Agent: Design FastAPI modules, service contracts, validation, and error handling. Outputs: Task Categorization Service (using NLP and machine learning); Escalation Service (using email and notification APIs); Reporting Service (using data visualization libraries)
- Frontend Agent: Design React screens, state flow, controls, and user feedback states. Outputs: Task submission form; Task categorization dashboard; Escalation notification system
- Database Agent: Design persistence models, sample data, indexes, and audit records. Outputs: Run history; Source document metadata; Generated workflow audit records
- Testing Agent: Define contract tests, smoke tests, and generated project validation. Outputs: Unit testing, integration testing, and end-to-end testing using a testing framework like Pytest.
- DevOps Agent: Define environment variables, Docker workflow, and repository packaging. Outputs: Docker-ready project; Environment sample file; GitHub repository upload
- Reviewer Agent: Review the generated plan for completeness, security, and portfolio quality. Outputs: Task submission; Task categorization; Escalation notification; Reporting
