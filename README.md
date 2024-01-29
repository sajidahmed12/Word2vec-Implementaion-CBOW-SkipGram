# Word2vec Implementation: CBOW & SkipGram

This repository contains implementations of Word2vec using PyTorch on the NLTK corpus.

## Overview

Word2vec is a popular technique in natural language processing for generating word embeddings. This project provides implementations of both the Continuous Bag of Words (CBOW) and SkipGram models using PyTorch. The models are trained on the NLTK corpus to learn high-quality word embeddings.

## Getting Started

To test and run the models, refer to the provided Jupyter notebook files. Further details, including trained model weights and the NLTK corpus, will be updated soon.

### Dependencies

- Keras
- PyTorch
- NumPy
- Pandas
- Matplotlib
- NLTK
- Regular Expression

## Results

Below are some sample outputs from the SkipGram model after 30 epochs of training:

```plaintext
Epoch: 30/30 Loss: 0.06470464915037155

Target Word | Predicted Context Words / Similar Words

open | impossible, png, radio, fast, don’t
error | started, was, strict, existing, rather
option | accesskeys, realplayer, which, progress, visible
to | whenever, searching, encryption, brings, secure
should | malformed, responding, profile, 4, logging
firebird | users, column, more, speed, return
javascript | talkback, extension, install, leaving, sends
button | checked, horizontal, child, something, every
hit | protocol, follow, overflow, focus, true
servers | offer, highlighted, sites, responding, way
such | few, weird, changes, instances, fonts
separate | take, renaming, moving, tar, scroll
case | browse, fullscreen, addressbar, creating, dragged
dragged | case, brings, transparent, created, unexpected
handler | compile, closes, skin, having, breaks
example | filename, your, numbers, advanced, macos
```

## t-SNE Visualization

![t-SNE Visualization](docs/viz.png)

## Contributing

Contributions to this project are welcome. If you have ideas for improvements or new features, feel free to open an issue or submit a pull request.

## Acknowledgments

Special thanks to the NLTK contributors for providing the corpus used in this project.
