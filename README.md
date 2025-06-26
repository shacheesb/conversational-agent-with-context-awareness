# 🤖 LLM Conversational Agent with Context Awareness

This project demonstrates how to build a conversational agent using LangChain and OpenAI's language models, enhanced with memory to maintain context over a multi-turn conversation. It uses LangChain’s `RunnableWithMessageHistory` to enable session-specific dialogue continuity.

---

## 🧠 Key Features

- **LLM Integration**: Uses `gpt-4o-mini` from OpenAI via LangChain’s `ChatOpenAI`.
- **Session Memory**: Retains conversation history using `ChatMessageHistory` per user session.
- **Contextual Responses**: Each response includes knowledge of prior interactions in the same session.
- **Dynamic Prompting**: Utilizes `ChatPromptTemplate` and `MessagesPlaceholder` to include history in prompts.



