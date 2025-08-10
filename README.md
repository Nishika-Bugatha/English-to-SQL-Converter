# Natural Language to SQL with T5 and Spider Dataset

## Project Overview
This project converts **natural language queries** into **SQL queries** using the **T5 (Text-To-Text Transfer Transformer)** model. T5 is a versatile transformer-based model that handles a variety of text-to-text tasks, including translating natural language into SQL.

## Objectives
- **Natural Language to SQL Translation**: Train T5 to generate SQL queries from natural language questions.
- **Utilize Spider Dataset**: Use the Spider dataset, a benchmark with complex SQL queries across multiple database schemas, to ensure robustness and generalization.

## Dataset
We use the **Spider dataset**, known for its complexity and cross-domain nature:
- **Natural Language Questions** – English phrases describing database queries.
- **SQL Queries** – Structured queries corresponding to the natural language questions.
- **Database Schemas** – Tables, columns, and relationships from multiple databases.

**Spider Paper:** [https://yale-lily.github.io/spider](https://yale-lily.github.io/spider)

## Model
**T5 (Text-To-Text Transfer Transformer)** treats every NLP task as text-to-text, enabling it to be trained on various problems, including NL-to-SQL translation.

**T5 Paper:** [https://arxiv.org/abs/1910.10683](https://arxiv.org/abs/1910.10683)

## Training & Evaluation
- **Training**: Fine-tune T5 on the Spider dataset to learn NL → SQL mapping.
- **Evaluation**: Assess using metrics like query accuracy, execution accuracy, and generalization to complex queries.

## Use Cases
- **Database Query Generation** – Auto-generate SQL queries from user-friendly input.
- **Query Understanding** – Make database interaction more intuitive.

## Expected Outcomes
- **Enhanced User Interaction** – Simplified database access via natural language.
- **Robust Model** – Trained on diverse schemas and queries.

## Acknowledgements
- **T5 Model** – Developed by Google Research ([Paper](https://arxiv.org/abs/1910.10683)).
- **Spider Dataset** – Created by Yale University & University of Hong Kong ([Paper](https://yale-lily.github.io/spider)).

## License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
