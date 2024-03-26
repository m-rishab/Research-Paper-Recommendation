# Research Paper Recommendation System

## Objective
This project aims to build a research paper recommendation system. Given a paper title as input, the system provides the top 5 recommended research papers. Additionally, it predicts the subject area of the input paper using Natural Language Processing (NLP) techniques and a Large Language Model (LLM) (Mini LM L6-V2).

## Deep Learning Techniques Used
- Natural Language Processing (NLP)
- Large Language Model (LLM) (Mini LM L6-V2) - [Link](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2).

## Sentence Transformer
Sentence Transformers is a framework that transforms sentences or text snippets into fixed-length vector representations, known as embeddings. These embeddings capture semantic meaning and are generated using pre-trained transformer models fine-tuned on large text corpora. They are useful for tasks like semantic similarity computation, text classification, and information retrieval.
<img src="https://github.com/m-rishab/Research-Paper-Recommendation/assets/113618652/6078f4ab-52f9-4c25-8139-0c605ea85376" width="500" height="500">

This flowchart illustrates the process flow of the research paper recommendation system, including data preprocessing, model training, and recommendation generation.

## Future Improvements
- Incorporating user feedback to enhance recommendation accuracy.
- Expanding the dataset to cover a broader range of research domains.
- Integrating more advanced NLP techniques for better understanding of paper content.

## Dataset Used
The dataset used for training and evaluation is available on Kaggle. You can access it [here](https://www.kaggle.com/datasets/spsayakpaul/arxiv-paper-abstracts/data).

## Demo

https://github.com/m-rishab/Research-Paper-Recommendation/assets/113618652/0f3971b6-ebd0-439a-90b2-a168c99f054b

To run the project, follow the steps below:

### How to Run This Project:
1. Run the notebook to execute all models.
2. After running the notebook, execute the `app.py` file using the following command:
   `python app.py`
