# Detecting AI-Generated Text Using BERT and Ensemble Learning

The rapid adoption of large language models has made it increasingly difficult to distinguish between human-written and AI-generated content. This project investigates the effectiveness of modern text embedding techniques and machine learning classifiers for identifying AI-generated academic abstracts. Multiple embedding approaches and classification algorithms were evaluated, including transformer-based embeddings and ensemble learning methods. The final model was used to estimate the proportion of AI-generated abstracts in two unseen datasets.

OBJECTIVES -
- Compare embedding-based approaches for text classification.
- Evaluate the performance of multiple machine learning classifiers.
- Investigate the effectiveness of ensemble learning methods.
- Estimate the prevalence of AI-generated content in unseen abstract datasets.
- Analyse the strengths and limitations of automated AI-text detection.

DATASETS - 

The project uses labelled academic abstracts containing both human-written and AI-generated text.

Training Data : `ai_hum_text.csv`

Unlabelled Test Data : `test_Abst_A.csv`, `test_Abst_B.csv`

The training dataset was used to build and evaluate classification models, while the test datasets were used to estimate the proportion of AI-generated abstracts.

TEXT EMBEDDINGS - 

Text must be converted into numerical representations before it can be processed by machine learning algorithms.

The project evaluates modern embedding techniques including:
- Word2Vec / Doc2Vec style embeddings
- BERT-based contextual embeddings

Unlike traditional bag-of-words approaches, embeddings capture semantic relationships between words and phrases, allowing models to learn richer representations of language.

