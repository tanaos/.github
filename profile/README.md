<p align="center">
    <img src='https://raw.githubusercontent.com/tanaos/.github/master/assets/banner.png' alt='tanaos logo' width='100%' /> 
</p>

<p align="center">
    <strong>
        <a href="https://x.com/TanaosAI">X/Twitter</a> | <a href="https://www.linkedin.com/company/tanaos">LinkedIn</a> | <a href="https://docs.tanaos.com">Docs</a> | <a href="https://tanaos.com">Website</a>
    </strong>
</p>

Here is a list of the task-specific Small Language Models developed by Tanaos for various text processing tasks. Below are the details of each model along with links to their Hugging Face repositories and code examples for easy integration.

**Every model can be used and fine-tuned on CPU**, making them accessible for a wide range of applications.

| Model | Size | Description | Links |
|-------|------|-------------|------------|
| Text Classification | 0.1B params, 470MB | Performs general-purpose text classification based on the user requirements. | [Code Examples](https://docs.tanaos.com/artifex/text-classification/code-examples/)
| Guardrail | 0.1B params, 500MB | Flags unsafe, harmful, or off-topic messages. | [HF](https://huggingface.co/tanaos/tanaos-guardrail-v1) • [Code Examples](https://docs.tanaos.com/artifex/guardrail/code_examples/)
| Intent Classification | 0.1B params, 500MB | Classifies user messages into predefined intent categories. | [HF](https://huggingface.co/tanaos/tanaos-intent-classifier-v1) • [Code Examples](https://docs.tanaos.com/artifex/intent-classifier/code_examples/)
| Reranker | 0.1B params, 470MB | Ranks a list of items or search results based on relevance to a query. | [HF](https://huggingface.co/cross-encoder/mmarco-mMiniLMv2-L12-H384-v1) • [Code Examples](https://docs.tanaos.com/artifex/reranker/code_examples/)
| Sentiment Analysis | 0.1B params, 470MB | Determines the sentiment (positive, negative, neutral) of a given text. | [HF](https://huggingface.co/tanaos/tanaos-sentiment-analysis-v1) • [Code Examples](https://docs.tanaos.com/artifex/sentiment-analysis/code_examples/)
| Emotion Detection | 0.1B params, 470MB | Identifies the emotion expressed in a given text. | [HF](https://huggingface.co/tanaos/tanaos-emotion-detection-v1) • [Code Examples](https://docs.tanaos.com/artifex/emotion-detection/code_examples/)
| Named Entity Recognition (NER) | 0.1B params, 500MB | Detects and classifies named entities in text. | [HF](https://huggingface.co/tanaos/tanaos-NER-v1) • [Code Examples](https://docs.tanaos.com/artifex/named-entity-recognition/code_examples/)
| Text Anonymization | 0.1B params, 500MB | Removes personally identifiable information (PII) from text. | [HF](https://huggingface.co/tanaos/tanaos-text-anonymizer-v1) • [Code Examples](https://docs.tanaos.com/artifex/text-anonymization/code_examples/)
| Spam Detection | 0.1B params, 500MB | Identifies whether a message is spam or not. | [HF](https://huggingface.co/tanaos/tanaos-spam-detection-v1) • [Code Examples](https://docs.tanaos.com/artifex/spam-detection/code_examples/)
| Topic Classification | 0.1B params, 500Mb | Classifies text into predefined topics. | [HF](https://huggingface.co/tanaos/tanaos-topic-classification-v1) • [Code Examples](https://docs.tanaos.com/artifex/topic-classification/code_examples/)
