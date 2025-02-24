# neural_spelling_correction

In this project, I implement a context-sensitive spelling correction system using a fine-tuned sequence-to-sequence model (Flan-T5) with LoRA (Low-Rank Adaptation) for efficient adaptation. The model is trained on noisy text data generated from the WikiText dataset, where I introduce controlled spelling errors. During inference, the model corrects input sentences by leveraging contextual information. I compare my approach against Norvig’s spell checker, evaluating both on a test set using Levenshtein distance as a metric.
