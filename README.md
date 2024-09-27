# TextForge

### Current Implementation Based on Key Papers:

- [x] **Bigram**: One character predicts the next using a counts lookup table.
- [x] **MLP**: [Bengio et al. 2003](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf)
- [x] **RNN**: [Mikolov et al. 2010](https://www.fit.vutbr.cz/research/groups/speech/publi/2010/mikolov_interspeech2010_IS100722.pdf)
- [x] **GRU**: [Kyunghyun Cho et al. 2014](https://arxiv.org/abs/1409.1259)
- [x] **Transformer**: [Vaswani et al. 2017](https://arxiv.org/abs/1706.03762)

### Activation Function:
- **GeLU (Gaussian Error Linear Units)**: Used in models like Google BERT.  
  Reference: [GELU Paper](https://arxiv.org/abs/1606.08415)

  ![GeLU Function](https://github.com/user-attachments/assets/524cbc0e-180f-4f1b-ad62-5611db7b9243)

### MLP Language Model:
- **Overview**: The model takes the previous `block_size` tokens, encodes them using a lookup table, concatenates the vectors, and predicts the next token using an MLP.
- **Reference**:  
  [Bengio et al. 2003](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf)

---

![Model Architecture](https://github.com/user-attachments/assets/3b5bd2dc-1e7f-4e31-94e1-49edb3f6252d)
