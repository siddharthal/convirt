## ConVIRT - Contrastive Learning Representations of Images and Text pairs

### Pytorch implementation of the architecture descibed in the [ConVIRT paper](https://arxiv.org/pdf/2010.00747.pdf): Contrastive Learning of Medical Visual Representations from Paired Images and Text
Yuhao Zhang, Hang Jiang, Yasuhide Miura, Christopher D. Manning, Curtis P. Langlotz

### DL4H Project - Team 56
Authors: Chufan Gao, Siddhartha Laghuvarapu. 

### Requirements
- Pytorch
- Numpy
- Huggingface
- tqdm

### Code instruction
- To train the model from scratch, the dataset should be downloaded locally, and the paths in the file `CXR\_paths\_for\_images\_and\_text.csv` should be pointed to the data sources.  
- Use the file `run.py` to train.
- Use this [link](https://physionet.org/content/mimic-cxr/2.0.0/) to request for data. 

### Pretrained weights
 You may download pretrained weights from [here](https://uillinoisedu-my.sharepoint.com/:f:/g/personal/chufan2_illinois_edu/El6DqeqGvz1OoUyl5SuM0tkBA_ndFGL1O5534otk4uODBQ?e=hzwkK2)

## References: 
- Yuhao Zhang et al. Contrastive Learning of Medical Visual Representations from Paired Images and Text. https://arxiv.org/pdf/2010.00747.pdf
- Ting Chen et al. A Simple Framework for Contrastive Learning of Visual Representations. https://arxiv.org/abs/2002.05709
- https://github.com/edreisMD/ConVIRT-pytorch
- https://github.com/sthalles/SimCLR
- https://github.com/google-research/simclr
- https://github.com/google-research/bert
- https://github.com/hanxiao/bert-as-service#q-what-are-the-available-pooling-strategies
