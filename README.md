# Email_classifier_Ai_agent
An automated workflow, built in n8n, that watches a Gmail inbox, uses AI to understand incoming emails, and automatically labels and replies to them — essentially a mini AI receptionist for a business

I built an AI-powered email triage system using n8n. It monitors a Gmail inbox, uses GPT-4o-mini to extract the sender's name and classify each email into categories like course requests, consultations, and payments, then automatically labels the email and sends a personalized reply. It cuts out manual sorting and gives every sender an instant response."
What it does: Watches a Gmail inbox, uses AI (GPT-4o-mini) to extract the sender's name and classify each email into Course Requests, Consultation Requests, Payments, or Miscellaneous, then automatically labels the email and sends a personalized reply.

Flow: Gmail Trigger → Extract Name (LLM) → If/Set/Merge (handle missing names) → Classify Email (LLM) → Label + Auto-Reply via Gmail.

Tools: n8n, Gmail API, OpenAI API, LangChain nodes (Information Extractor, Text Classifier), If / Set / Merge nodes.

Skills: No-code automation, prompt engineering, API integration (OAuth2), conditional logic, LLM-based classification.

Benefit: Saves time, organizes the inbox, and gives every sender an instant response.
Tech stack
n8n (workflow engine)
Gmail API (trigger, labels, replies)
OpenAI GPT-4o-mini (2x, for extraction + classification)
LangChain nodes (Information Extractor, Text Classifier)
Logic nodes: If, Set, Merge
Skills demonstrated
No-code automation design
LLM prompt engineering (structured extraction & classification)
API integration (Gmail OAuth2, OpenAI API)
Conditional logic / branching workflows
Practical "agentic" email-handling system design
