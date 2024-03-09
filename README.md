# TutorBot: Virtual TA for NLP

## Objective

The goal of TutorBot is to develop an advanced question-answering system specifically tailored for inquiries related to Natural Language Processing (NLP). This system aims to serve as a virtual teaching assistant, providing support and enhancing the learning experience in the field of NLP.

## Datasets

To build and refine our model, we leverage:
- **Open Source NLP Material**: Including datasets such as CommonCrawl and Glue, which provide a rich foundation for training and evaluation.

## Approach

### Data Generation

- We plan to augment our primary datasets with additional data generated from these sources, ensuring a broad and relevant dataset for instruction tuning.

### Model Selection

- Our primary models of interest are the [Mistral 7B](https://mistral.ai/news/announcing-mistral-7b/) and [LLaMA 2 7B](https://llama.meta.com/llama2). However, the final selection may depend on GPU availability, and we are open to adapting our choice based on resource constraints.

### Retrieval Augmented Generation (RAG)

- By implementing a RAG pipeline, we aim to enhance the model's factual grounding and contextual understanding, utilizing a vector database for efficient retrieval.

### Fine Tuning

- Techniques such as [PEFT](https://github.com/huggingface/peft) and [QLoRA](https://github.com/artidoro/qlora) will be employed for fine-tuning, with a focus on Prompt Tuning and Instruction Tuning to optimize the model for responding to academic NLP queries.

### Evaluation

- We aim for low perplexity in our model and will conduct human evaluation to assess clarity, correctness, fluency, and usefulness, providing insights beyond quantitative metrics.

### Demo UI

- A user-friendly interface, possibly built with [Streamlit](https://streamlit.io/), will be integrated, including interpretability features for educators to easily interact with TutorBot.

## Future Scope

- **Universal Platform**: Envisioning TutorBot as a versatile platform where instructors can upload teaching materials in various formats and manage course-related queries.
- **Course General Queries**: Expanding TutorBot's capabilities to address general course inquiries, provided it has access to course schedules and grading schemes.

## License

This project is licensed under the [GNU General Public License v3.0](LICENSE) - see the file for details.
