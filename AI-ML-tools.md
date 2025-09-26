
# AI-ML Tools

- NumPy provides the foundational n-dimensional array object for efficient numerical computations, serving as the core data structure that nearly all other data science libraries in Python are built upon. 

- Pandas is used for data manipulation and analysis, providing easy-to-use data structures (DataFrames) for working with structured, tabular data like spreadsheets or database tables. 

- TensorFlow and PyTorch are both open-source machine learning frameworks used for building and training complex models, especially deep neural networks, with PyTorch being favoured for research and prototyping due to its flexibility, while TensorFlow is often preferred for large-scale production deployment.
- LLM Framework:

  - OpenAI API (GPT-4) or Llama 3 (self-hosted via Hugging Face)

  - LangChain (orchestration) for workflow automation (e.g., connecting to Supabase/Sensors).

  - Embedding Models: OpenAI’s text-embedding-3-small or BAAI/bge-small-en-v1.5 (for semantic search).
 
- Vector Database:
  - Supabase Vector (PostgreSQL PGVector extension) or Pinecone (for scalable storage of embeddings).

  - Data Pipeline:

      - AWS Lambda (triggered by sensor data updates) to preprocess and feed data to the LLM.

      - Supabase Webhooks (to detect new meter readings/events).

      - For Enhanced Digital Twin Features:

  - Real-time Analytics:

    - TimescaleDB (time-series extension for Supabase) to optimize sensor data storage.

- Predictive AI:

    - PyTorch/TensorFlow (custom models for anomaly detection) + LangChain Agents (for action recommendations).


