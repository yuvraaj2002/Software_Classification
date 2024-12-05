# Software_Classification

### Model considerations
Stage 1: Binary Classification (Functional vs. Non-Functional)

- RoBERTa or BERT: These models are robust for binary classification. RoBERTa generally has higher performance, but BERT is easier to fine-tune and more lightweight in comparison.
- DistilBERT: If speed and resource efficiency are crucial, choose this for faster training with minimal performance trade-offs.

Stage 2: Multi-Class Classification (Non-Functional Subcategories)

- RoBERTa: Best for nuanced distinctions between non-functional subcategories (e.g., security, scalability).
- ALBERT: If memory efficiency is a concern but you still want high accuracy.
- XLNet: Choose if your requirements text involves long sequences with complex dependencies.