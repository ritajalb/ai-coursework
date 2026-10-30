# AI & Data Science Coursework

Selected labs and assignments I completed during the Tuwaiq Academy AI & Data Science Diploma (2026), plus one university project. Several of these start from instructor-provided lab templates; the runs, changes and outputs are mine.

My standalone projects live in their own repositories (see my profile).

## NLP

| Notebook | What it does |
|---|---|
| [`imdb_embeddings_keras_vs_word2vec.ipynb`](nlp/imdb_embeddings_keras_vs_word2vec.ipynb) | Trains a Keras sentiment classifier on IMDB that learns its own word embeddings (**89.2% test accuracy**), then compares those task-specific embeddings with pretrained Google News Word2Vec using cosine similarity, 2-D projections and nearest neighbours |
| [`arabic_toxicity_detection.ipynb`](nlp/arabic_toxicity_detection.ipynb) | Arabic toxicity classification on the `textdetox/multilingual_toxicity_dataset` Arabic split: EDA, Arabic text cleaning, Word2Vec embeddings, embedding matrix and padding for a neural classifier |
| [`annotated_transformer_en_ar.ipynb`](nlp/annotated_transformer_en_ar.ipynb) | Based on *The Annotated Transformer*: the full encoder–decoder implementation adapted to **English → Arabic** translation with byte-level BPE, trained on up to 100k sentence pairs, with attention visualisations |

## Computer Vision

| Notebook | What it does |
|---|---|
| [`vehicle_recognition_cnn.ipynb`](computer-vision/vehicle_recognition_cnn.ipynb) | Builds two CNNs from scratch, compares two ImageNet-pretrained architectures before and after adaptation, analyses errors, and ends with a sequence-learning RNN |
| [`yolo11_vs_yolo26_finetuning.ipynb`](computer-vision/yolo11_vs_yolo26_finetuning.ipynb) | Compares how many objects YOLO11 and YOLO26 recognise out of the box, then fine-tunes a YOLO detector on annotated examples of a new class |

## Machine Learning

| Notebook | What it does |
|---|---|
| [`nyc_taxi_trip_duration.ipynb`](machine-learning/nyc_taxi_trip_duration.ipynb) | Predicts New York taxi trip duration: EDA and outlier handling on ~974K trips, automated feature engineering with Featuretools (Deep Feature Synthesis), and Linear Regression, Decision Tree and Random Forest models compared as features are added. King Abdulaziz University project with Mariam Alotaibi (2024) |

**Tech:** Python · TensorFlow / Keras · PyTorch · Gensim · Ultralytics YOLO · scikit-learn · Featuretools · pandas

**Author:** Ritaj Albogami
