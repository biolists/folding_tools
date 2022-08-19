
💡 **Notes**
- The following lists are curated by humans, as such may be incomplete
- We only include software targeting the inverse folding problem e.g given a structure predict the sequence that folds into it. This is also referred to as protein sequence design. 
- We do not wish to advertize one tool over any other, but simply list the tools we are aware of in order of publication year of the model, preprint or publication (whichever is first)
- Any suggestions for improvements and additions are welcome as issues or pull requests

⚡️ **Brought to you by:** 
- [@simonduerr](https://twitter.com/simonduerr)
- [@ginaelnesr](https://twitter.com/ginaelnesr)


# Protein Sequence design / Inverse folding models

(sorted by year of release)
| Name      | Release year  |Architecture   | Paper | Code | Notes |Experimental validation |
| :-------- | -------       |--------- | --------- | ------- | --------- |---|
| ABACUS-R| 2022 |Transformer|[Nat Comput Sci](https://www.nature.com/articles/s43588-022-00273-6)|[code](https://doi.org/10.24433/CO.3351944.v1)||✅|
| ProteinMPNN     | 2022      | MPNN |[biorxiv](https://www.biorxiv.org/content/10.1101/2022.06.03.494563v1)|[git](https://github.com/dauparas/proteinMPNN)|[webserver](https://hf.space/simonduerr/ProteinMPNN) |✅|
| ProDESIGN-LE    | 2022      | Transformer |[biorxiv](https://www.biorxiv.org/content/10.1101/2022.06.25.497605v4)|| ||
| RaSP    | 2022      | 3DCNN |[biorxiv](https://www.biorxiv.org/content/10.1101/2022.07.14.500157v2)|[git](https://github.com/KULL-Centre/papers/tree/main/2022/ML-ddG-Blaabjerg-et-al)| [colab](https://colab.research.google.com/github/KULL-Centre/papers/blob/main/2022/ML-ddG-Blaabjerg-et-al/RaSPLab.ipynb) |-|
|MIF|2022| SGNN|[biorxiv](https://www.biorxiv.org/content/10.1101/2022.05.25.493516v1)|[git](https://github.com/microsoft/protein-sequence-models)||-|
| ESM-IF1    | 2022      | Transformer |[biorxiv](https://www.biorxiv.org/content/10.1101/2022.04.10.487779v1)|[git](https://github.com/facebookresearch/esm)| |-|
| Partlon et al.   | 2022      | Transformer |[biorxiv](https://www.biorxiv.org/content/10.1101/2022.04.15.488492v1)|-| |-|
| TIMED-*     | 2022      | 3DCNN |[arxiv](https://arxiv.org/pdf/2109.07925.pdf)|[git](https://github.com/wells-wood-research/timed-design)| |not published yet|
| GCNDesign     | 2021      | GCN |[pdf](https://github.com/ShintaroMinami/GCNdesign/blob/master/documents/Method_Summary.pdf)|[git](https://github.com/ShintaroMinami/GCNdesign)| [colab](https://github.com/naokob/ColabGCNdesign) |-|
| GX     | 2021      | 3DCNN+GNN |[arxiv](https://arxiv.org/pdf/2109.07925.pdf)|[git](https://github.com/wells-wood-research/timed-design)| |not published yet|
| CNN_protein_landscape      | 2021      | 3DCNN |[Journal of Biological Physics](https://link.springer.com/article/10.1007/s10867-021-09593-6#Abs1)|[git](https://github.com/akulikova64/CNN_protein_landscape)|||-|
| Orellana et al.      | 2021      | GVP |[biorxiv](https://www.biorxiv.org/content/10.1101/2021.09.06.459171v3))||||-|
| Jing et al.      | 2020      | GVP |[arxiv](https://arxiv.org/abs/2009.01411)|[git](https://github.com/drorlab/gvp-pytorch)|||-|
| DenseCPD     | 2020      | 3DCNN |[JCIM](https://pubs.acs.org/doi/full/10.1021/acs.jcim.0c00043)||[webserver](http://protein.org.cn/densecpd.html)|-|
| ProDCoNN     | 2020      | 3DCNN |[Proteins](https://onlinelibrary.wiley.com/doi/10.1002/prot.25868)|||-|
| ProteinSolver     | 2020      | GNN |[Cell Systems](https://www.sciencedirect.com/science/article/pii/S2405471220303276)|[gitlab](https://gitlab.com/ostrokach/proteinsolver)|[webserver](http://design.ccbr.proteinsolver.org/)|✅|
| MutCompute      | 2020      | 3DCNN |[ACS SynBio](https://pubs.acs.org/doi/full/10.1021/acssynbio.0c00345)|| [webserver](https://mutcompute.com)|✅|
| Ingraham et al.     | 2019      | Transformer |[NeurIPS Proceedings](https://papers.nips.cc/paper/2019/hash/f3a4ff4839c56a5f460c88cce3666a2b-Abstract.html)|[git](https://github.com/jingraham/neurips19-graph-protein-design)| |-|
| 3DCNN      | 2017      | 3DCNN |[BMC Bioinformatics](https://link.springer.com/article/10.1186/s12859-017-1702-0)|||-|

# Protein Rotamer sequence design / Inverse folding models

(sorted by year of release)
| Name      | Release year  |Architecture   | Paper | Code | Notes |Experimental validation |
| :-------- | -------       |--------- | --------- | ------- | --------- | ---|
| TIMED_Rotamer      | 2022      | 3DCNN |-|[git](https://github.com/wells-wood-research/timed-design)| | not published yet |
| SeqDes      | 2021      | 3DCNN |[Nature Comm](https://www.nature.com/articles/s41467-022-28313-9) - [BioRxiv](https://www.biorxiv.org/content/10.1101/2020.01.06.895466v3)|[git](https://github.com/ProteinDesignLab/protein_seq_des)| |✅|

