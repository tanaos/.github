<p align="center">
    <img src='https://raw.githubusercontent.com/tanaos/.github/master/assets/banner.png' alt='tanaos logo' width='100%' /> 
</p>

<p align="center">
    <strong>
        <a href="https://x.com/TanaosAI">X/Twitter</a> | <a href="https://www.linkedin.com/company/tanaos">LinkedIn</a> | <a href="https://docs.tanaos.com">Docs</a> | <a href="https://tanaos.com">Website</a> | <a href="https://slm.tanaos.com/docs">API</a>
    </strong>
</p>

Here is a list of the task-specific Small Language Models developed by Tanaos for various text processing tasks. 

All models can be used and fine-tuned on CPU via the [Artifex library](https://github.com/tanaos/artifex). Don't want to self-host? You can also access these models through Tanaos' [Small-Language-Model API](https://slm.tanaos.com/docs).

| Model | Description | Artifex | Hugging Face |
|-------|-------------|-------------|---------|
| Text Classification | Performs general-purpose text classification based on the user requirements. | [Artifex](https://docs.tanaos.com/artifex/text-classification/code-examples/) | - |
| Guardrail | Flags unsafe, harmful, or off-topic messages. | [Artifex](https://docs.tanaos.com/artifex/guardrail/code-examples/) | [HuggingFace](https://huggingface.co/tanaos/tanaos-guardrail-v1) |
| Intent Classification | Classifies user messages into predefined intent categories. | [Artifex](https://docs.tanaos.com/artifex/intent-classifier/code-examples/) | [HuggingFace](https://huggingface.co/tanaos/tanaos-intent-classifier-v1) |
| Reranker | Ranks a list of items or search results based on relevance to a query. | [Artifex](https://docs.tanaos.com/artifex/reranker/code-examples/) | [HuggingFace](https://huggingface.co/cross-encoder/mmarco-mMiniLMv2-L12-H384-v1) |
| Sentiment Analysis | Determines the sentiment (positive, negative, neutral) of a given text. | [Artifex](https://docs.tanaos.com/artifex/sentiment-analysis/code-examples/) | [HuggingFace](https://huggingface.co/tanaos/tanaos-sentiment-analysis-v1) |
| Emotion Detection | Identifies the emotion expressed in a given text. | [Artifex](https://docs.tanaos.com/artifex/emotion-detection/code-examples/) | [HuggingFace](https://huggingface.co/tanaos/tanaos-emotion-detection-v1) |
| Named Entity Recognition | Detects and classifies named entities in text. | [Artifex](https://docs.tanaos.com/artifex/named-entity-recognition/code-examples/) | [HuggingFace](https://huggingface.co/tanaos/tanaos-NER-v1) |
| Text Anonymization | Removes personally identifiable information (PII) from text. | [Artifex](https://docs.tanaos.com/artifex/text-anonymization/code-examples/) | [HuggingFace](https://huggingface.co/tanaos/tanaos-text-anonymizer-v1) |
| Spam Detection | Identifies whether a message is spam or not. | [Artifex](https://docs.tanaos.com/artifex/spam-detection/code-examples/) | [HuggingFace](https://huggingface.co/tanaos/tanaos-spam-detection-v1) |
| Topic Classification | Classifies text into predefined topics. | [Artifex](https://docs.tanaos.com/artifex/topic-classification/code-examples/) | [HuggingFace](https://huggingface.co/tanaos/tanaos-topic-classification-v1) |