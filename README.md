# CENG463-Assignment2

This project is part of the Middle East Technical University CENG 463 - Introduction to NLP course. The assignment focuses on analyzing parliamentary speeches to identify the speaker's political ideology and party position (government or opposition).

## **About the Project**
In this project:
- **Task 1 (Ideology Task)**: Determine whether the speaker’s party leans left or right.
- **Task 2 (Power Task)**: Identify whether the speaker’s party is in government or opposition.

The dataset is sourced from the ParlaMint project, which includes parliamentary speeches from 29 European countries.

## **Technologies and Models**
- **Python**: Used for data processing and model training.
- **Hugging Face Transformers**: Fine-tuned `bert-base-multilingual-cased` and `xlm-roberta-base` pre-trained models.
- **Scikit-learn**: For data splitting and metric evaluation.
- **Google Colab**: GPU-enabled environment for training models.

## **Setup**
### Requirements:
- Python 3.8+
- Required libraries: `transformers`, `datasets`, `torch`, `evaluate`, `scikit-learn`

Install the dependencies using:
```bash
pip install transformers datasets torch evaluate scikit-learn
```

### Dataset Download:
Download the dataset here and place it in the appropriate directory.
I chose the Latvian dataset, which can be downloaded from the same repository. For convenience, I stored the dataset in a Google Drive directory. This approach proved to be one of the fastest methods to work with the dataset in Google Colab.

## **Usage**
1. **Model Training and Evaluation**:
   - Run `task1.py` and `task2.py` to train models for both tasks.

Detailed results and analysis are included in the report.

## **File Structure**
- `task1.py`: Model training for the Ideology Task.
- `task2.py`: Model training for the Power Task.
  
