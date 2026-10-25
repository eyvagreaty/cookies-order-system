## Key Concepts of Agentic AI
1.	Autonomy 
-	Agentic AI are designed to operate with a degree of independence and executing actions that align with predefined objectives. For instance, Agent AI can perform tasks, such as checking cookie availability without requiring the user to guide every step.

2.	Goal-oriented Behaviour
-	Agentic AI is trained to pursue specific ends and breaking down complex goals into sub-tasks using hierarchical planning. For example, helping a customer find suitable cookies and preparing their order.

3.	Adaptability
-	Agentic AI must handle uncertainty such as environmental conditions or incomplete information. For example, it adjusts its recommendation when a selected cookie is unavailable or the customer’s budget changes. 

 
## LangGraph
LangGraph is a framework for building AI agents with multi-step workflows. It allows developers to control the sequence of actions, maintain information between steps and include human approval. 
Application: In COS, LangGraph could coordinate the process of checking cookie availability, calculating the order total, suggesting alternatives for unavailable cookies and asking the customer to confirm the order.

## CrewAI
CrewAI enables developers to create teams of AI agents with different roles, goals and tools. Its Crews feature supports collaboration between agents while its Flows feature manages the workflow and decision paths.
Application: A cookie recommendation agent could identify suitable flavours as an inventory agent could check stock and an order assistant could prepare the order summary. 

## Semantic Kernel
Semantic Kernel is an open-source SDK from Microsoft that integrates AI models with existing applications, functions, plugins and external services. It supports languages including C, Python and Java although available agent capabilities vary by language. 
Application: It could connect an AI cookie-ordering assistant to existing system functions, such as retrieving cookie prices, checking stock, calculating totals and preparing an order.

## MetaGPT
MetaGPT is a multi-agent framework that assigns different roles to AI agents and organizes their collaboration through structured procedures. It is particularly associated with software development tasks such as producing requirements and designing systems.
Application: For COS, MetaGPT could help AI agents develop or improve the system. For example, a product manager agent could define ordering requirements and an engineer agent could generate implementation code.
 
## Fit to Problem

Agentic AI can improve the Cookies Order System by acting as an AI-powered ordering assistant. It can understand customer preferences, check cookie prices and stock through database tools, recommend suitable products and prepare an order summary. For instance, if matcha cookies are unavailable, it can suggest an alternative flavour within the customer’s budget and must be confirmed by the customer before it is saved.

Benefits: Agentic AI provides personalized recommendations, reduces manual effort, improves ordering efficiency and adapts suggestions when products are unavailable.

Limitations and Risks: AI may generate incorrect recommendations or misunderstand customer requests. Other than that, customer information must be protected to maintain privacy and security. In addition, implementation may require additional development time and API costs.

Comparison and Choice: Agentic AI offers more flexible customer interactions compared to a traditional rule-based systems which following fixed instructions. I would choice Agentic AI because it can understand different customer preferences, recommend suitable cookies and adapts when the cookie is unavailable. Thus, this makes the Cookies Order System more convenient and user-friendly. 

