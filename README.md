# HelpTech.ai
The HelpTech.ai is a Customer Support Chatbot Assistant that leverages LLM technologies to enhance information retrieval and answer generation. The workflow involves scraping content from online articles, segmenting them into smaller chunks, computing embeddings, and storing them in Deep Lake.

Workflow Steps:

1. Content Scraping and Embedding:
   Utilizing web scraping techniques, the system extracts valuable information from online articles. The content is then segmented into smaller, digestible chunks. The embeddings of these chunks are computed to capture the semantic relationships within the text, ensuring a rich representation of the information.

2. Deep Lake Storage:
   The computed embeddings are stored in Deep Lake, forming a structured knowledge base. This allows for efficient retrieval of relevant information during user queries. Deep Lake serves as a reservoir of contextualized content, enabling the system to provide precise and informative responses.

3. User Query Processing:
   When a user submits a query, the system retrieves the most relevant chunks from Deep Lake based on the computed embeddings. These chunks are then compiled into a prompt, serving as input to a Language Model (LLM).

4. Answer Generation with LLM:
   The LLM, powered by GPT-3, processes the prompt and generates a final answer. While acknowledging the risk of hallucinations or misinformation, the system is designed to assist human operators rather than directly responding to users. Operators can review, validate, and potentially modify the answers before sending them to users.
