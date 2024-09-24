# TextForge
![{8C6E0AE0-930B-4F43-B22A-2A8A5E8420A5}](https://github.com/user-attachments/assets/3b5bd2dc-1e7f-4e31-94e1-49edb3f6252d)

Activation function used - GeLU(From Google BERT repo) , Reference: Gaussian Error Linear Units (GELU) paper: https://arxiv.org/abs/1606.08415
Function - ![{521E0605-3F7E-4A66-B071-8416C405EE01}](https://github.com/user-attachments/assets/2f2a3b60-8b38-42cd-9ed7-6b5788c60319)

MLP Language model - Takes the previous block_size tokens, encodes them with a lookup table,
    concatenates the vectors and predicts the next token with an MLP.
Reference:
    Bengio et al. 2003 https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf


