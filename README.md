# TextForge

Current implementation based on few key papers:
- [x] **Bigram**: One character predicts the next using a counts lookup table.
- [x] **MLP**: Based on Bengio et al. (2003).
- [x] **RNN**: Based on Mikolov et al. (2010).
- [x] **GRU**: Based on Kyunghyun Cho et al. (2014).
- [x] **Transformer**: Based on Vaswani et al. (2017).


![{8C6E0AE0-930B-4F43-B22A-2A8A5E8420A5}](https://github.com/user-attachments/assets/3b5bd2dc-1e7f-4e31-94e1-49edb3f6252d)

Activation function used - GeLU(From Google BERT repo) , Reference: Gaussian Error Linear Units (GELU) paper: https://arxiv.org/abs/1606.08415
Function - ![{E912E0D1-4DB8-48C7-A761-F0522C9C0498}](https://github.com/user-attachments/assets/524cbc0e-180f-4f1b-ad62-5611db7b9243)

MLP Language model - Takes the previous block_size tokens, encodes them with a lookup table,
    concatenates the vectors and predicts the next token with an MLP.
Reference:
    Bengio et al. 2003 https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf


