# Neural-Machine-Translation-with-Cross-Attention

In this assignment, I implement a simplified Transformer-based translation model that translates English sentences into Spanish.

The main objective is to understand how Cross-Attention enables the decoder to access information from the encoder output. The model follows an Encoder–Decoder architecture using:

Multi-Head Self-Attention
Cross-Attention
Masked Self-Attention in the decoder
Greedy decoding for inference
Training is performed using the first 50,000 sentence pairs from the Spanish-English dataset.
