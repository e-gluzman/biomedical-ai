# biomedical-ai
Machine learning for application in biology and medicine. 

## medical_question_llm.ipynb

See this notebook for a showcase of how to finetune a state of the art open source Large Language Model (Mistral) to solve Medical Questions using 'MedMCQA : A Large-scale Multi-Subject Multi-Choice Dataset for Medical domain Question Answering'.

I load the Mistral LLM from Hugging Face, create prompts from training data, fine-tune the model on the medical question dataset and then apply it to question answering.

The model achieved 37% accuracy on medical entrance exam questions intended for professional doctors.
