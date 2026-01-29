<p align="center">
    <img src='https://raw.githubusercontent.com/tanaos/.github/master/assets/banner.png' alt='tanaos logo' width='100%' /> 
</p>

<p align="center">
    <strong>
        <a href="https://x.com/TanaosAI">X/Twitter</a> | <a href="https://www.linkedin.com/company/tanaos">LinkedIn</a> | <a href="https://docs.tanaos.com">Docs</a> | <a href="https://tanaos.com">Website</a> | <a href="https://colab.research.google.com/github/tanaos/tanaos-docs/blob/master/blueprints/tanaos-api/tanaos-api-tutorial.ipynb">API</a>
    </strong>
</p>

At Tanaos we develop **task-specific Small Language Models** for various text processing tasks. The table below lists the available models along with links to several ways to use them.

For ease of use and maximum performance, **we recommend using them through the [Tanaos API](https://colab.research.google.com/github/tanaos/tanaos-docs/blob/master/blueprints/tanaos-api/tanaos-api-tutorial.ipynb)**. With 100ms end-to-end latency, our API is perfect for real-time applications. Get a free API key by signing up on [our platform](https://platform.tanaos.com).

If you'd rather use the models on your own metal, or if you want to fine-tune them on your specific tasks without training data, use our open-source [Artifex library](https://github.com/tanaos/artifex). 

Additionally, all models are available for download from our [Hugging Face page](https://huggingface.co/tanaos).

| Model | Description | API | Artifex | HuggingFace |
|-------|-------------|-----|---------|-------------|
| Text Classification | Performs general-purpose text classification based on the user requirements. | - | [Artifex](https://docs.tanaos.com/artifex/text-classification/code-examples/) | - |
| Guardrail | Flags unsafe, harmful, or off-topic messages. | [API](https://colab.research.google.com/github/tanaos/tanaos-docs/blob/master/blueprints/tanaos-api/tanaos-api-tutorial.ipynb#scrollTo=ptAF6Efb3-6-) | [Artifex](https://docs.tanaos.com/artifex/guardrail/code-examples/) | [HuggingFace](https://huggingface.co/tanaos/tanaos-guardrail-v1) |
| Intent Classification | Classifies user messages into predefined intent categories. | [API](https://colab.research.google.com/github/tanaos/tanaos-docs/blob/master/blueprints/tanaos-api/tanaos-api-tutorial.ipynb#scrollTo=jytV4CBv4nT7) | [Artifex](https://docs.tanaos.com/artifex/intent-classifier/code-examples/) | [HuggingFace](https://huggingface.co/tanaos/tanaos-intent-classifier-v1) |
| Reranker | Ranks a list of items or search results based on relevance to a query. | - | [Artifex](https://docs.tanaos.com/artifex/reranker/code-examples/) | - |
| Sentiment Analysis | Determines the sentiment (positive, negative, neutral) of a given text. | [API](https://colab.research.google.com/github/tanaos/tanaos-docs/blob/master/blueprints/tanaos-api/tanaos-api-tutorial.ipynb#scrollTo=nOvE4a5H5QUX) | [Artifex](https://docs.tanaos.com/artifex/sentiment-analysis/code-examples/) | [HuggingFace](https://huggingface.co/tanaos/tanaos-sentiment-analysis-v1) |
| Emotion Detection | Identifies the emotion expressed in a given text. | [API](https://colab.research.google.com/github/tanaos/tanaos-docs/blob/master/blueprints/tanaos-api/tanaos-api-tutorial.ipynb#scrollTo=gdcmvZlR55K2) | [Artifex](https://docs.tanaos.com/artifex/emotion-detection/code-examples/) | [HuggingFace](https://huggingface.co/tanaos/tanaos-emotion-detection-v1) |
| Named Entity Recognition | Detects and classifies named entities in text. | [API](https://colab.research.google.com/github/tanaos/tanaos-docs/blob/master/blueprints/tanaos-api/tanaos-api-tutorial.ipynb#scrollTo=cEnZ2iu64IqM) | [Artifex](https://docs.tanaos.com/artifex/named-entity-recognition/code-examples/) | [HuggingFace](https://huggingface.co/tanaos/tanaos-NER-v1) |
| Text Anonymization | Removes personally identifiable information (PII) from text. | [API](https://colab.research.google.com/github/tanaos/tanaos-docs/blob/master/blueprints/tanaos-api/tanaos-api-tutorial.ipynb#scrollTo=ZDbuM6Xk4atr) | [Artifex](https://docs.tanaos.com/artifex/text-anonymization/code-examples/) | [HuggingFace](https://huggingface.co/tanaos/tanaos-text-anonymizer-v1) |
| Spam Detection | Identifies whether a message is spam or not. | [API](https://colab.research.google.com/github/tanaos/tanaos-docs/blob/master/blueprints/tanaos-api/tanaos-api-tutorial.ipynb#scrollTo=3418gc_N4-fF) | [Artifex](https://docs.tanaos.com/artifex/spam-detection/code-examples/) | [HuggingFace](https://huggingface.co/tanaos/tanaos-spam-detection-v1) |
| Topic Classification | Classifies text into predefined topics. | [API](https://colab.research.google.com/github/tanaos/tanaos-docs/blob/master/blueprints/tanaos-api/tanaos-api-tutorial.ipynb#scrollTo=2hb4qVeQ6JQH) | [Artifex](https://docs.tanaos.com/artifex/topic-classification/code-examples/) | [HuggingFace](https://huggingface.co/tanaos/tanaos-topic-classification-v1) |