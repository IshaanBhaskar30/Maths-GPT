🧮 Text-to-Math Problem Solver & Wikipedia-Powered Assistant (Gemma 2)
This project is an intelligent Streamlit chatbot application designed to solve math problems, answer reasoning-based questions, and search for general knowledge using Wikipedia—all powered by Gemma 2 (9B) via Groq’s blazing-fast LLM infrastructure and the LangChain framework. Users can input natural language questions involving basic or moderately complex math operations, logical reasoning, or general knowledge, and the assistant provides point-by-point solutions or relevant information accordingly.

The assistant works by combining several tools:

->A math calculator that uses LangChain’s LLMMathChain for solving arithmetic and numeric expressions.

->A Wikipedia search utility that pulls reliable and concise summaries from Wikipedia articles.

->A custom reasoning tool that interprets and solves contextual problems, especially ones involving steps and logic (e.g., word problems with quantities or sequential decisions).

All these tools are orchestrated using a zero-shot reactive agent from LangChain, allowing the app to decide dynamically which tool to use based on the user's input.

This makes the app perfect for:

->Students who need help breaking down and understanding math word problems.

->Educators looking for a teaching aid that explains solutions step-by-step.

->Anyone looking to mix factual lookups with logical, math-based computation in one place.
