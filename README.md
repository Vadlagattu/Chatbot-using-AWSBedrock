Architecture:

Front-end: Streamlit (Python library)
Back-end: LangChain and Amazon Bedrock with LLaMA foundation model
Need for LangChain:

Foundation models are stateless, cannot maintain context between prompts
  LangChain Memory (e.g., ConversationBufferMemory) stores conversation history
  LangChain Prompt combines past conversation with new query to maintain context
  LangChain Chains (e.g., ConversationChain) connect foundation model with other components
