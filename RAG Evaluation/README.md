1. Install dependencies:

2. Configure Environment Variables:
-  Create a .env file and add your API keys: ( GROQ/OPEN AI, LANGSMITH )

3. 🧪 Running the Evaluation
The core logic is contained in RAG_evaluation.ipynb. The workflow follows these steps:

- Dataset Creation: Loading a set of domain-specific questions and ground-truth answers.

- Target Function: Defining the RAG chain that processes inputs.

- Evaluators: Implementing "LLM-as-a-judge" functions to grade the outputs.

- Experimentation: Running client.evaluate() to generate a performance report in LangSmith.

📈 Conclusion
This project establishes a repeatable infrastructure for maintaining high precision in production-ready AI applications. By systematically identifying hallucinations and optimizing retrieval quality, the framework ensures that the RAG system remains reliable and factually anchored as it scales.
