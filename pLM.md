# Protein Language Models
(sorted by number of parameters)
| Name | Params | Paper | Code | Model |
| :-------- | -------  | --------- | ------- | --------- |
| ESM2 | 8M - 15B | [Preprint](https://www.biorxiv.org/content/10.1101/2022.07.20.500902v1) | ?? ||
| ProGen2 | 151M - 6.4B | [Preprint](https://arxiv.org/abs/2206.13517) | [Code](https://github.com/salesforce/progen/tree/main/progen2) ||
| ProtTrans | 420M - 3B | [Paper](https://ieeexplore.ieee.org/document/9477085/) | [Code](https://github.com/agemagician/ProtTrans)
| ProteinLM | 200M, 3B | [Preprint](https://arxiv.org/abs/2108.07435) | [Code](https://github.com/THUDM/ProteinLM) ||
| RITA | 85M - 1.2B | [Preprint](https://arxiv.org/abs/2205.05789) | [Code](https://github.com/lightonai/RITA) ||
| ProGen1 | 1.2M | [Preprint](https://www.biorxiv.org/content/10.1101/2020.03.07.982272v2) | [Code](https://github.com/salesforce/progen) ||
| ProtGPT2 | 738M | [Paper](https://www.nature.com/articles/s41467-022-32007-7) | [Code](https://huggingface.co/nferruz/ProtGPT2) ||
| ESM1 | 43M - 670M | [Preprint](https://www.pnas.org/doi/10.1073/pnas.2016239118) | [Code](https://github.com/facebookresearch/esm) ||
| Tranceptron | 700M | [Paper](https://proceedings.mlr.press/v162/notin22a.html) | [Code](https://github.com/OATML-Markslab/Tranception) ||
| DistilProtBert | 230M |[Preprint](https://www.biorxiv.org/content/early/2022/05/10/2022.05.09.491157) | [Code](https://github.com/yarongef/DistilProtBert) ||
| TAPE | 38M | [Preprint](https://arxiv.org/abs/1906.08230) | [Code](https://github.com/songlab-cal/tape) ||
| ProteinBERT | 16M | [Paper](https://doi.org/10.1093/bioinformatics/btac020) | [Code](https://github.com/nadavbra/protein_bert), [PyTorch](https://github.com/lucidrains/protein-bert-pytorch) ||
| AminoBERT | ?? | [Preprint](https://www.biorxiv.org/content/10.1101/2021.08.02.454840v1) |  ?? ||

## Non-transformer-based sequence models
| Name | Params | Paper | Code | Model |
| :-------- | -------  | --------- | ------- | --------- |
| CARP | 640M  | [Preprint](https://www.biorxiv.org/content/10.1101/2022.05.19.492714v2) | [Code](https://github.com/microsoft/protein-sequence-models)| CNN |
| SeqVec | 93M | [Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-3220-8) | [Code](https://github.com/mheinzinger/SeqVec)| LSTM |
| UniRep | 90M | [Paper](https://www.nature.com/articles/s41592-019-0598-1)| [Code](https://github.com/churchlab/UniRep)| mLSTM |
| ProSE | ?? | ?? | [Code](https://github.com/tbepler/prose) | LSTM |

## pLM specific to Antibody sequences
| Name | Params | Paper | Code | Model |
| :-------- | -------  | --------- | ------- | --------- |
| AntiBERTa | 86M | [Paper](https://www.sciencedirect.com/science/article/pii/S2666389922001052) | [Code](https://github.com/alchemab/antiberta) ||
| AntiBERTy | 26M | [Preprint](https://arxiv.org/abs/2112.07782) | [Code](https://pypi.org/project/antiberty) ||
| IgLM |1.5M, 13M| [Preprint](https://www.biorxiv.org/content/10.1101/2021.12.13.472419v1.full) | [Code](https://github.com/Graylab/IgLM) ||
| Sapiens | 0.6M | [Paper](https://www.tandfonline.com/doi/full/10.1080/19420862.2021.2020203) | [Code](https://github.com/Merck/BioPhi) ||
| AbLang | ?? | [Paper](https://academic.oup.com/bioinformaticsadvances/article/2/1/vbac046/6609807) | [Code](https://github.com/oxpig/AbLang) ||

# Building on pLMs
- [protGPT2_gradioFold](https://huggingface.co/spaces/Gradio-Blocks/protGPT2_gradioFold) 
