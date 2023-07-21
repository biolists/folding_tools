# Protein Language Models
(sorted by number of parameters)
| Name | Params | Paper | Code | Notes |
| :-------- | -------  | --------- | ------- | --------- |
| xTrimoPGLM | 100B | [bioRxiv](https://doi.org/10.1101/2023.07.05.547496) | Not available ||
| ESM2 | 8M - 15B | [bioRxiv](https://www.biorxiv.org/content/10.1101/2022.07.20.500902v1)| [Code](https://github.com/facebookresearch/esm) ||
| ProGen2 | 151M - 6.4B | [arXiv](https://arxiv.org/abs/2206.13517) | [Code](https://github.com/salesforce/progen/tree/main/progen2) ||
| ProtTrans | 420M - 3B | [Paper](https://ieeexplore.ieee.org/document/9477085/) | [Code](https://github.com/agemagician/ProtTrans) |BFD+UniRef50|
| ProteinLM | 200M, 3B | [arXiv](https://arxiv.org/abs/2108.07435) | [Code](https://github.com/THUDM/ProteinLM) ||
| RITA | 85M - 1.2B | [arXiv](https://arxiv.org/abs/2205.05789) | [Code](https://github.com/lightonai/RITA) ||
| ProGen1 | 1.2M | [bioRxiv](https://www.biorxiv.org/content/10.1101/2020.03.07.982272v2) | [Code](https://github.com/salesforce/progen) ||
| Ankh | 450M, 1.15B | [arXiv](https://arxiv.org/abs/2301.06568) | [Code](https://github.com/agemagician/Ankh) ||
| ProtGPT2 | 738M | [Paper](https://www.nature.com/articles/s41467-022-32007-7) | [Code](https://huggingface.co/nferruz/ProtGPT2) ||
| Tranception | 700M | [Paper](https://proceedings.mlr.press/v162/notin22a.html) | [Code](https://github.com/OATML-Markslab/Tranception) ||
| ESM1 | 43M - 670M | [Paper](https://www.pnas.org/doi/10.1073/pnas.2016239118) | [Code](https://github.com/facebookresearch/esm) ||
| PoET | 57M - 604M | [arXiv](https://arxiv.org/abs/2306.06156) | Not available | Only available through OpenProtein.AI web app |
| DistilProtBert | 230M |[bioRxiv](https://www.biorxiv.org/content/early/2022/05/10/2022.05.09.491157) | [Code](https://github.com/yarongef/DistilProtBert) ||
| DARK | 128M | [bioRxiv](https://www.biorxiv.org/content/10.1101/2022.01.27.478087v1)|||
| PRoBERTa | 44M | [Paper](https://doi.org/10.1145/3388440.3412467) | [Code](https://github.com/annambiar/PRoBERTa) ||
| TAPE | 38M | [arXiv](https://arxiv.org/abs/1906.08230) | [Code](https://github.com/songlab-cal/tape) ||
| ProteinBERT | 16M | [Paper](https://doi.org/10.1093/bioinformatics/btac020) | [Code](https://github.com/nadavbra/protein_bert), [PyTorch](https://github.com/lucidrains/protein-bert-pytorch) |~106M proteins from UniRef90; 28 days over ~670M records (i.e. ~6.4 iterations)|
| AminoBERT || [bioRxiv](https://www.biorxiv.org/content/10.1101/2021.08.02.454840v1) |[Code](https://github.com/aqlaboratory/rgn2)||

## Special purpose pLM
| Name | Params | Paper | Code | Notes | 
| :-------- | -------  | --------- | ------- | --------- |
| PeTriBERT | 40M | [bioRxiv](https://www.biorxiv.org/content/10.1101/2022.08.10.503344v1) | N/A | Optimized for protein design |

## Non-transformer-based sequence models
| Name | Params | Paper | Code | Notes |
| :-------- | -------  | --------- | ------- | --------- |
| CARP | 600K - 640M  | [bioRxiv](https://www.biorxiv.org/content/10.1101/2022.05.19.492714v2) | [Code](https://github.com/microsoft/protein-sequence-models)| CNN |
| SeqVec | 93M | [Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-3220-8) | [Code](https://github.com/mheinzinger/SeqVec)| bidirectional LSTM; UniRef50 |
| UniRep | 90M | [Paper](https://www.nature.com/articles/s41592-019-0598-1)| [Code](https://github.com/churchlab/UniRep)| mLSTM |
| ProSE | 24M | [Paper](https://www.sciencedirect.com/science/article/pii/S2405471221002039) | [Code](https://github.com/tbepler/prose) | LSTM |

## pLM specific to Antibody sequences
| Name | Params | Paper | Code | Notes |
| :-------- | -------  | --------- | ------- | --------- |
| TCR-BERT | 100M | [bioRxiv](https://www.biorxiv.org/content/10.1101/2021.11.18.469186v1) |[Code](https://github.com/wukevin/tcr-bert)||
| AntiBERTa | 86M | [Paper](https://www.sciencedirect.com/science/article/pii/S2666389922001052) | [Code](https://github.com/alchemab/antiberta) ||
| AntiBERTy | 26M | [arXiv](https://arxiv.org/abs/2112.07782) | [Code](https://pypi.org/project/antiberty) ||
| IgLM |1.5M, 13M| [bioRxiv](https://www.biorxiv.org/content/10.1101/2021.12.13.472419v1.full) | [Code](https://github.com/Graylab/IgLM) ||
| Sapiens | 0.6M | [Paper](https://www.tandfonline.com/doi/full/10.1080/19420862.2021.2020203) | [Code](https://github.com/Merck/BioPhi) ||
| AbLang || [Paper](https://academic.oup.com/bioinformaticsadvances/article/2/1/vbac046/6609807) | [Code](https://github.com/oxpig/AbLang) ||

## DNA language models
| Name | Params | Paper | Code | Notes |
| :-------- | -------  | --------- | ------- | --------- |
| GenSLM  | 25M - 25B | [bioRxiv](https://doi.org/10.1101/2022.10.10.511571)| [Code](https://github.com/ramanathanlab/genslm) ||
| Nucleotide Transformer | 500M - 2.5B | [bioRxiv](https://www.biorxiv.org/content/10.1101/2023.01.11.523679v2) | [Code](https://github.com/instadeepai/nucleotide-transformer) ||
| GENA-LM | 110M - 336M | [bioRxiv](https://doi.org/10.1101/2023.06.12.544594)| [Code](https://github.com/AIRI-Institute/GENA_LM) | Inputs up to 36,000 base pairs |

# Building on pLMs
- [protGPT2_gradioFold](https://huggingface.co/spaces/Gradio-Blocks/protGPT2_gradioFold) 
