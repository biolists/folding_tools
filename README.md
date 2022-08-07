📖 **Table of contents**
* [Predictors](#Predictors)
* [Tools](#Tools)
* [Extensions](#Extensions)
* [Databases](#Databases)
* [Webservers](#Webservers)


💡 **Notes**
- The following lists are curated by humans, as such may be incomplete
- We only include software targeting the folding problem combining learnings from AlphaFold 2 and protein language models. You may find other ML on protein tools [at Kevin's incredible ML for proteins list](https://github.com/yangkky/Machine-learning-for-proteins).
- We do not wish to advertize any tool over any other, but simply list the tools we are aware of in either random or alphabetical order
- Any suggestions for improvements and additions are welcome as issues or pull requests
- Projects we identify as discontinued are marked with 💀

⚡️ **Brought to you by:** 
- [@sacdallago](https://twitter.com/sacdallago)
- [@sokrypton](https://twitter.com/sokrypton)

----

<a name="Predictors"></a>
### Predictors
[_in alphabetical order_]
- **MSA-based** (uses Multiple Sequence Alignment as input)
  - AlphaFold2 (JAX)
    - Manuscript: https://www.nature.com/articles/s41586-021-03819-2
    - Code: https://github.com/deepmind/alphafold
  - ColabFold (JAX - faster AF2 compiling and MSA generations)
    - Manuscript: https://www.nature.com/articles/s41592-022-01488-1
    - Code: https://github.com/sokrypton/ColabFold
    - Code: https://github.com/YoshitakaMo/localcolabfold
  - FastFold (Pytorch)
    - Manuscript: https://arxiv.org/abs/2203.00854
    - Code: https://github.com/hpcaitech/FastFold
  - HelixFold (PaddlePaddle)
    - Manuscript: https://arxiv.org/abs/2207.05477
    - Code:  https://github.com/PaddlePaddle/PaddleHelix/tree/dev/apps/protein_folding/helixfold
  - MineSpore-Fold (mindspore)
    - Manuscript: https://arxiv.org/abs/2206.12240
    - Code: https://gitee.com/mindspore/mindscience/tree/master/MindSPONGE/applications/MEGAProtein
  - OpenFold (PyTorch)
    - Manuscript?
    - Code: https://github.com/aqlaboratory/openfold
  - RoseTTAFold (PyTorch)
    - Manuscript: https://www.science.org/doi/10.1126/science.abj8754
    - Code: https://github.com/RosettaCommons/RoseTTAFold
  - Uni-Fold (PyTorch/JAX)
    - Manuscript: https://doi.org/10.1101/2022.08.04.502811
    - Code (PyTorch): https://github.com/dptech-corp/Uni-Fold
    - Code (JAX): https://github.com/dptech-corp/Uni-Fold-jax

- **pLM-based** (uses Protein Language Model as input)
  - ESM-Fold (PyTorch)
    - Manuscript: https://doi.org/10.1101/2022.07.20.500902
    - Code: ? (potentially: https://github.com/facebookresearch/esm)
    - Other: [[tweet] Alex's announcement](https://twitter.com/alexrives/status/1550148755206414341), 
  - EMBER3D (PyTorch):
    - Manuscript: ?
    - Code: https://github.com/kWeissenow/EMBER3D
  - HelixFold-single (PaddlePaddle)
    - Manuscript: https://arxiv.org/abs/2207.13921
    - Code: https://github.com/PaddlePaddle/PaddleHelix/tree/dev/apps/protein_folding/helixfold-single
    - Resource: https://paddlehelix.baidu.com/app/drug/protein-single/forecast
  - OmegaFold (PyTorch)
    - Manuscript: https://doi.org/10.1101/2022.07.21.500999
    - Code: https://github.com/HeliXonProtein/OmegaFold
    - Other: [[tweet] Martin comparing structures](https://twitter.com/thesteinegger/status/1554881669718573062), [[tweet] Sergey's positional encoding observation](https://twitter.com/sokrypton/status/1555536325176168448), 

 ----
 
<a name="Tools"></a>
### Tools
  - gget (AF2)
    - Manuscript: https://doi.org/10.1101/2022.05.17.492392
    - Code: https://github.com/pachterlab/gget#gget-alphafold-
  - 💀 Lucidrains AF2 (AF2)
    - Code: https://github.com/lucidrains/alphafold2
  - 💀 Lupoglaz OpenFold2 (AF2)
    - Code: https://github.com/lupoglaz/OpenFold2


 ----
 
<a name="Extensions"></a>
### Extensions
  - AlphaPulldown - protein-protein interaction screens using AlphaFold-Multimer
    - Manuscript: https://www.biorxiv.org/content/10.1101/2022.08.05.502961v1
    - Code: https://www.embl-hamburg.de/AlphaPulldown/
  - AlphaFill - enriching the AlphaFold models with ligands and co-factors
    - Manuscript: https://www.biorxiv.org/content/10.1101/2021.11.26.470110v1
    - Code: https://alphafill.eu/
  - ColabDesign - Backprop through AlphaFold for protein design
    - Code: https://github.com/sokrypton/ColabDesign
  - AF2Rank - Rank Decoy using AlphaFold
    - Manuscript: https://www.biorxiv.org/content/10.1101/2022.03.11.484043v3
    - Code: https://github.com/jproney/AF2Rank
    - Resource: [Colab Notebook](https://colab.research.google.com/github/sokrypton/ColabDesign/blob/main/af/examples/AF2Rank.ipynb)
  - alphafold_finetune - finetune AlphaFold for Protein-Peptide prediction
    - Manuscript: https://www.biorxiv.org/content/10.1101/2022.07.12.499365v1
    - Code: https://github.com/phbradley/alphafold_finetune
    - Other: [[tweet] Amir's announcement](https://twitter.com/AMotmaen/status/1547435940011945984)
   
---- 

<a name="Databases"></a>
### Datasets/Databases
 - AlphaFold Database (UniRef90|AF2)
   - Manuscript: https://doi.org/10.1093/nar/gkab1061
   - Resource: https://alphafold.ebi.ac.uk
 - Eukaryotic interactormes (Pathawy-involved proteins|RoseTTAFold)
   - Manuscript: https://www.science.org/doi/10.1126/science.abm4805
   - Resource: https://www.ebi.ac.uk/pdbe/news/predicted-complexes-modelarchive-now-pdbe-kb-pages
 - Structures of human-transcriptome isoforms (ColabFold)
   - Manuscript: https://doi.org/10.1101/2022.06.08.495354
   - Resource: https://www.isoform.io

 ----

<a name="Webservers"></a>
### Webservers
 - Lambda PredictProtein (ColabFold|limit:500AA)
   - Manuscript: https://doi.org/10.1101/2022.08.04.502750
   - Resource: http://embed.predictprotein.org/
- 💀 Moonbear
   - Resource: https://www.getmoonbear.com/
   - Other: [[tweet] Stephanie's announcement](https://twitter.com/stephanieszhang/status/1427773598199164937)
