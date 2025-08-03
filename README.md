# FairMatter 📰  
*An AI-powered RAG system designed to combat media bias by automatically generating a neutral, fact-based summary of any news article.*

---

## 🚀 How It Works

The system takes a URL to a news article and orchestrates a multi-step retrieval and generation process:

1. **Neutral Query Generation**  
   An LLM analyzes the article's title and description to extract core keywords and form a bias-free search query.

2. **Multi-Source Retrieval**  
   The agent uses this query to retrieve comprehensive context from three distinct sources:
   - **AskNews API**: Gathers different perspectives from a variety of mainstream news outlets.
   - **Reddit**: Collects public opinion, discussions, and alternative viewpoints on the topic.
   - **Original Article RAG**: Retrieves specific facts and details from the source text itself.

3. **Synthesis and Neutralization**  
   All gathered information is fed into a final LLM, which synthesizes the diverse perspectives and facts into a single, cohesive, and unbiased news article.  
   It retains key details while stripping away any biased language or framing.

---

## ✨ Key Features

- **Agentic Framework**  
  Built on LangChain, the agent intelligently plans and executes a multi-step workflow.

- **Comprehensive Context**  
  Gathers information from mainstream media, public forums, and the original source for a holistic view.

- **Bias Removal**  
  Specifically engineered to identify and neutralize politically or emotionally charged language.

- **Extensible Architecture**  
  The modular design allows for easy integration of new data sources (e.g., academic journals, government reports).
