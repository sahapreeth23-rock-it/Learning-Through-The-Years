Agents are LLM powered knowledge assistants that range from simple question-answering to being able to sense, decide and take actions in order to complete tasks.

LlamaIndex provides a framework to create such agents including RAG.
Workflows are multi-step processes that combine one or more agents to complete a task

1. They are event-driven software that allows to combine RAG data sources and multiple agents to create a complex application.
2. Upload PDF ↓ Extract text ↓ Split text ↓ Create embeddings ↓ Store vectors ↓ Retrieve relevant text ↓ Generate answer

LLMs offer natural language interface between humans and data, they come pretrained with large amount of data, but they don't understand our data as it might be behind API's or trapped in PDF's.
So, Context Augmentation makes data available to LLM to solve the problem, and LLM's use their tools to go from prototype to production.
Ex of Context Augmentation is Retrieval-Augmented Generation or RAG (Combines context with LLMs at interface time).

LlamaIndex makes the usage of LLM's work easier in making auto-complete,chatbots,agents and more.

1. Data Connnectors ingest our exisiting data from native sources like pdf's
2. Data indexes structure data in simple representations that are easy for LLM's to consume
3. Engines provide natural language access to data
       a) Query engines are powerful interfaces for question answering (eg.work flow)

)Chat engines are conversational interfaces for multi-message with data
LlamaIndex provides tools for beginners, advanced users and everyone in between.

