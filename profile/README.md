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

| Model | Description | HuggingFace | Artifex | SLM API |
|-------|-------------|-------------|---------|---------|
| Text Classification | Performs general-purpose text classification based on the user requirements. | - | [Artifex](https://docs.tanaos.com/artifex/text-classification/code-examples/) | - |
| Guardrail | Flags unsafe, harmful, or off-topic messages. | [HuggingFace](https://huggingface.co/tanaos/tanaos-guardrail-v1) | [Artifex](https://docs.tanaos.com/artifex/guardrail/code-examples/) | [SLM API](https://slm.tanaos.com/docs#/Models%20endpoints/guardrail_inference_models_guardrail_post) |
| Intent Classification | Classifies user messages into predefined intent categories. | [HuggingFace](https://huggingface.co/tanaos/tanaos-intent-classifier-v1) | [Artifex](https://docs.tanaos.com/artifex/intent-classifier/code-examples/) | [SLM API](https://slm.tanaos.com/docs#/Models%20endpoints/intent_classification_inference_models_intent_classification_post)
| Reranker | Ranks a list of items or search results based on relevance to a query. | [HuggingFace](https://huggingface.co/cross-encoder/mmarco-mMiniLMv2-L12-H384-v1) | [Artifex](https://docs.tanaos.com/artifex/reranker/code-examples/) | [SLM API](https://slm.tanaos.com/docs#/Models%20endpoints/reranker_inference_models_reranker_post)
| Sentiment Analysis | Determines the sentiment (positive, negative, neutral) of a given text. | [HuggingFace](https://huggingface.co/tanaos/tanaos-sentiment-analysis-v1) | [Artifex](https://docs.tanaos.com/artifex/sentiment-analysis/code-examples/) | [SLM API](https://slm.tanaos.com/docs#/Models%20endpoints/sentiment_analysis_inference_models_sentiment_analysis_post)
| Emotion Detection | Identifies the emotion expressed in a given text. | [HuggingFace](https://huggingface.co/tanaos/tanaos-emotion-detection-v1) | [Artifex](https://docs.tanaos.com/artifex/emotion-detection/code-examples/) | [SLM API](https://slm.tanaos.com/docs#/Models%20endpoints/emotion_detection_inference_models_emotion_detection_post)
| Named Entity Recognition | Detects and classifies named entities in text. | [HuggingFace](https://huggingface.co/tanaos/tanaos-NER-v1) | [Artifex](https://docs.tanaos.com/artifex/named-entity-recognition/code-examples/) | [SLM API](https://slm.tanaos.com/docs#/Models%20endpoints/named_entity_recognition_inference_models_named_entity_recognition_post)
| Text Anonymization | Removes personally identifiable information (PII) from text. | [HuggingFace](https://huggingface.co/tanaos/tanaos-text-anonymizer-v1) | [Artifex](https://docs.tanaos.com/artifex/text-anonymization/code-examples/) | [SLM API](https://slm.tanaos.com/docs#/Models%20endpoints/text_anonymization_inference_models_text_anonymization_post)
| Spam Detection | Identifies whether a message is spam or not. | [HuggingFace](https://huggingface.co/tanaos/tanaos-spam-detection-v1) | [Artifex](https://docs.tanaos.com/artifex/spam-detection/code-examples/) | [SLM API](https://slm.tanaos.com/docs#/Models%20endpoints/spam_detection_inference_models_spam_detection_post)
| Topic Classification | Classifies text into predefined topics. | [HuggingFace](https://huggingface.co/tanaos/tanaos-topic-classification-v1) | [Artifex](https://docs.tanaos.com/artifex/topic-classification/code-examples/) | [SLM API](https://slm.tanaos.com/docs#/Models%20endpoints/topic_classification_inference_models_topic_classification_post)
