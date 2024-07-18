# financial-qa-dataset

This dataset consists of Question-Answer_Context Pairs. It also consists of metadata for filtering the records.

## Repo Structure
```
financial-qa-dataset
    ├── financial-qa-dataset.csv
    ├── metadata.csv
    ├── notebooks
    │   |── loading_dataset.ipynb
    │   |── Loading_dataset_huggingface.ipynb
    │   |── basic_rag_langchain_vertexai.ipynb
    │   |── basic_rag_with_evaluation.ipynb
    |
    ├── data
        |── Statements
        |── Reports
```

## Use Cases

This dataset can be used for the following :
1. Benchmarking perfromance of RAG systems
2. Supervised Fine-tuning of Large Language Models
3. RLHF for Large Language Models
4. Financial domain specific question answering systems
5. Financial entity extraction

## Sample Scripts
1. [loading_dataset.ipynb]()
2. [Loading_dataset_huggingface.ipynb]()
3. [basic_rag_langchain_vertexai]()
4. [basic_rag_with_evaluation]()

## CITATION
When using the financial-qa-dataset dataset in a product , service, research or including data in a redistribution, please cite the following :

