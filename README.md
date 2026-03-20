# flowise-chatbot-ku
🤖 Chatbot LLM Chain (Flowise / LangChain)
File konfigurasi ini mendefinisikan sebuah chatbot berbasis LLM (Large Language Model) menggunakan konsep LangChain dengan pendekatan modular (node-based flow).

🧠 Arsitektur Utama
Chatbot ini dibangun menggunakan 4 komponen utama:
1. Chat Model (LLM) → Groq
2. Memory → Buffer Window Memory
3. Prompt → Chat Prompt Template
4. Chain → Conversation Chain
Semua komponen ini dihubungkan menjadi satu alur (flow) menggunakan konsep LangChain Chains.

```
User Input
   ↓
Conversation Chain
   ├── Chat Model (Groq)
   ├── Memory (Buffer Window)
   └── Prompt Template
   ↓
Response ke User


