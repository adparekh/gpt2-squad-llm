Large pre-trained language models such as GPT can be useful for many natural language tasks other than text generation. In this project, I am taking a look at one such task: question-answering (QA).

In a typical QA task, the model is given some **context** text and a **question** related to the context. The model is tasked to generate the correct answer based on the context and question. For example, a context could be "Joe enjoys pizza but prefers pasta over anything else", and given a question "What's Joe's favorite food", the model should output "pasta".

Here, I am extending and fine-tuning a pre-trained large language model (GPT2) to perform question-answering task.
