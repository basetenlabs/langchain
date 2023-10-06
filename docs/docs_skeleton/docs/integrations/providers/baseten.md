# Baseten

[Baseten](https://baseten.co) provides all the infrastructure you need to deploy and serve ML models performantly, scalably, and cost-efficiently. With Baseten, you can:

- Deploy open-source models in two clicks from the [model library](https://app.baseten.co/explore).
- Package and deploy your own models with [Truss](https://truss.baseten.co).
- Set up autoscaling and observability for your models.

This doc provides an overview of Baseten as a LangChain provider and introduces the LLM, Chat model, and text embedding model components for Baseten.
## Installation and Setup

- Create a [Baseten](https://baseten.co) account.
- Make an [API key](https://docs.baseten.co/settings/api-keys) and save it as an environment variable named `BASETEN_API_KEY`.
- Deploy [an open-source model](https://app.baseten.co/explore) or [your own model](https://truss.baseten.co) and copy the model ID.

## LLM

See a [usage example](/docs/integrations/llms/baseten).

```python
from langchain.llms import Baseten
```


## Chat model

See a [usage example](/docs/integrations/chat/baseten).

```python
from langchain.chat_models import ChatBaseten
```

## Text Embedding Model

See a [usage example](/docs/integrations/text_embedding/baseten)

```python
from langchain.embeddings import BasetenEmbeddings
```
