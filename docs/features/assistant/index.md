---
title: Assistant
---

# Brickgraph Assistant

The Brickgraph Assistant can be used to answer questions about your knowledge graph. Ask it about entities or relationships, or even to perform calculations. The Assistant is still in active development and under beta release so results may vary (or it may not be able to answer). It prioritises accuracy and therefore will not return an answer that is not derived from your data directly

### LLM Provider

Currently, the Assistant uses **Anthropic's Claude 3.5** model for generating the code that retrieves answers from your knowledge graph. Specifically, Brickgraph utilises the Enterprise API to keep data from being used by Anthropic in training for future models.

### Security

The Assistant dynamically generates database queries based on your question, rather than send your data to the LLM provider. This is to ensure that your internal data is not shared with Brickgraph does, when necessary, use the LLM provider for summarisation and explanation of the returned results.
