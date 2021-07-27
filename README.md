# AttentionSeq2Seq-Torch
### Sequence to Sequence Model + Attention Using PyTorch

Yet another sequence to sequence model with multiple attention mechanisms in Pytorch. This code is heavily inspired by the [official torch tutorial](https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html), with some differences, most importantly the batched training and inference functionality.

To use the code you need ```python > 3.5```. Then install the required packages using pip: 
``` 
pip install -r requirements.txt
```

For training, we use ```train.py``` file which can be invoked with additional flags e.g.:
```
python3 train.py -lr 0.01 -h 256 -d 'cuda' -e 150
```