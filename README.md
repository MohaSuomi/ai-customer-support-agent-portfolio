# AI Customer Support Agent | RAG & Automation
![AI Customer Support Agent](AI%20Customer%20Support%20Agent.png)
### Intelligent Customer Support Built with n8n

## Project Overview
An AI-powered customer support automation system built with n8n, combining Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), and business application integrations.

The system answers customer questions using company knowledge, creates support tickets when human assistance is required, and sends email notifications to support staff.

Built and tested using a fictional Finnish skincare retailer.

## Key Features
- **AI-Powered Conversations:** Understands and responds to customer questions.
- **RAG Knowledge Base:** Retrieves relevant information from company PDF documents using vector embeddings.
- **Multilingual Support:** Tested with English and Finnish customer inquiries.
- **FAQ Integration:** Retrieves company information from Google Sheets.
- **Support Ticket Creation:** Records unresolved requests in Google Sheets.
- **Human Handoff:** Sends Gmail notifications for customer issues requiring human support.
- **Duplicate Detection:** Checks existing tickets before creating new ones.
- **Conversation Memory:** Maintains context during conversations.

## Technologies & Skills
- n8n — Workflow Automation
- OpenAI API — Language Models and Embeddings
- RAG — Retrieval-Augmented Generation
- Vector Search — Semantic Document Retrieval
- Google Drive — PDF Document Integration
- Google Sheets API — FAQ and Ticket Management
- Gmail API — Support Notifications
- AI Agent Tools — External System Integration

## How It Works
1. A customer sends a message through the chat interface.
2. The AI Agent identifies the customer's request.
3. For company-related questions, it retrieves relevant information from Google Sheets or the RAG knowledge base.
4. The agent generates a response using available company information.
5. If human assistance is required, it checks existing support tickets.
6. If no matching open ticket is found, it can create a new ticket.
7. The system sends an email notification after successful ticket creation.

## Testing & Results
Successfully demonstrated:

- Customer FAQ responses
- Semantic retrieval from PDF documents
- Multilingual responses in English and Finnish
- Support ticket creation
- Gmail notifications
- Duplicate ticket avoidance in tested scenarios
- Accurate handling of unsupported actions

## Business Value
This solution demonstrates how businesses can automate repetitive support questions, organize customer requests, and reduce manual administrative work while keeping human support available for complex issues.

## Project Status

**Functional portfolio prototype — not a production deployment.**
The project currently uses an in-memory vector store and model-guided duplicate detection. Additional reliability, persistence, security, and concurrency controls would be required for production use.

## Implementation & Demonstration
The complete n8n implementation is maintained privately.

This public repository documents the architecture, capabilities, and results without distributing the complete workflow.

Live demonstration available upon request.
