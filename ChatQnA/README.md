# ChatQnA Application

Chatbots are the most widely adopted use case for leveraging the powerful chat and reasoning capabilities of large language models (LLM). The retrieval augmented generation (RAG) architecture is quickly becoming the industry standard for developing chatbots because it combines the benefits of a knowledge base (via a vector store) and generative models to reduce hallucinations, maintain up-to-date information, and leverage domain-specific knowledge.

RAG bridges the knowledge gap by dynamically fetching relevant information from external sources, ensuring that responses generated remain factual and current. At the heart of this architecture are vector databases, instrumental in enabling efficient and semantic retrieval of information. These databases store data as vectors, allowing RAG to swiftly access the most pertinent documents or data points based on semantic similarity.

ChatQnA architecture shows below:

![architecture](https://i.imgur.com/lLOnQio.png)

This ChatQnA use case performs RAG using LangChain, Redis vectordb and Text Generation Inference on Intel Gaudi2 or Intel XEON Scalable Processors. The Intel Gaudi2 accelerator supports both training and inference for deep learning models in particular for LLMs. Please visit [Habana AI products](https://habana.ai/products) for more details.

# Deploy ChatQnA Service

The ChatQnA service can be effortlessly deployed on either Intel Gaudi2 or Intel XEON Scalable Processors.

## Deploy ChatQnA on Gaudi

Refer to the [Gaudi Guide](./microservice/gaudi/README.md) for instructions on deploying ChatQnA on Gaudi.

## Deploy ChatQnA on Xeon

Refer to the [Xeon Guide](./microservice/xeon/README.md) for instructions on deploying ChatQnA on Xeon.
