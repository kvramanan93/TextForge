# TextForge

Current implementation based on few key papers:

[x] Bigram (One Character predicts the next one with a counts lookup table
[X] MLP, [Bengio et al. 2003](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf)
[X] RNN, [Mikololv et al.2010](https://www.fit.vutbr.cz/research/groups/speech/publi/2010/mikolov_interspeech2010_IS100722.pdf)
[X] GRU, [Kyunghyun Cho et al. 2014](https://arxiv.org/abs/1409.1259)
[X] Transformer, [Vaswani et al. 2017](https://arxiv.org/abs/1706.03762)


![{8C6E0AE0-930B-4F43-B22A-2A8A5E8420A5}](https://github.com/user-attachments/assets/3b5bd2dc-1e7f-4e31-94e1-49edb3f6252d)

Activation function used - GeLU(From Google BERT repo) , Reference: Gaussian Error Linear Units (GELU) paper: https://arxiv.org/abs/1606.08415
Function - ![{E912E0D1-4DB8-48C7-A761-F0522C9C0498}](https://github.com/user-attachments/assets/524cbc0e-180f-4f1b-ad62-5611db7b9243)

MLP Language model - Takes the previous block_size tokens, encodes them with a lookup table,
    concatenates the vectors and predicts the next token with an MLP.
Reference:
    Bengio et al. 2003 https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf


