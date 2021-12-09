# Word2vec-Implementation-CBOW-SkipGram

This is a repository contains word2vec Implementation using PyTorch on NLTK corpus  


#### To test and run the models look into the Jupyter notebook files.
#### Furthur details will be updated with trained model weights and corpus


### Dependencies(Python Libraries) 
- Keras
- PyTorch
- Numpy
- Pandas 
- Matplotlib
- NLTK
- Regular Expression


### Results 

##### Some outputs from skip-gram.

```Epoch: 30/30 Loss: 0.06470464915037155    <= Last Training epoch

Target Word | predicted context words / Similar words

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
### t-SNE Visualization

![](docs/viz.png)