# Machine-translation
Machine translation on the language dataset

## Table of Contents
<!-- ⛔️ MD-MAGIC-EXAMPLE:START (TOC:collapse=true&collapseText=Click to expand) -->
<details>
<summary>Click to expand</summary>

- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Performance graphs](#performance-graphs)

</details>
<!-- ⛔️ MD-MAGIC-EXAMPLE:END -->


### Dataset
The dataset consists of the large number of tab-delimited bilingual sentence pairs in various languages.

- Download the dataset from - http://www.manythings.org/anki/


### Project Structure

- ***data:*** This folder contains the dataset on which the model is trained.
- ***static:*** This folder contains the static content such as images (accuracy and validation graphs) etc.
- ***machine-translation-encoder-decoder-model.ipynb:*** Ipython notebook for machine translation using encoder-decoder sequence to sequence architecture. This model is overfitting the data. Please refer to the corresponding performance graph for reference.

### Performance graphs

1. Performance graph for training a model with encoder-decoder architecture and with pre-trained embeddings of 100 dimenstions. 
   - machine-translation-encoder-decoder-model.ipynb
   - The model is overfitting the data.

![Accuracy](https://github.com/agoel41/machine-translation/blob/master/static/acc_machine_translation_lstm.png) ![Loss](https://github.com/agoel41/machine-translation/blob/master/static/loss_machine_translation_lstm.png)

