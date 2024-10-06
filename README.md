Project Description: E-commerce Review Chatbot - end to end implementation

The E-commerce Review Chatbot is an AI-powered chatbot designed to provide personalized product recommendations and insights based purely  on customer reviews and their sentiments.

It leverages Natural Language Processing (NLP) via GEMINI 1.5 PRO and state-of-the-art Astra db embeddings to analyze and respond to user queries. 

Trained on product reviews from e-commerce dataset of headphones the chatbot enables users to gain insights about products directly from real customer feedback.

The project is built with Langchain for document processing and embeddings, integrated with AstraDB Vector Store to store and search vectors efficiently. 

Google Generative AI Embeddings are used to represent product reviews as vectors, allowing for effective similarity search and query matching. The system seamlessly retrieves relevant reviews and metadata, thanks to a well-structured pipeline involving pre-processing of data and embedding into a vector database.

The chatbot is deployed using Streamlit, offering an intuitive user interface where users can ask product-related queries and receive responses in real-time. The system is designed for scalability, and with its flexible architecture

it can be extended to support additional brands or languages in the future.

Future work -- Flask API + AWS deployment.
