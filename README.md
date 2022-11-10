📖 **Table of contents**
* [Predictors](#Predictors)
* [Tools and Extensions](#Tools)
* [Databases and Datasets](#Databases)
* [Webservers](#Webservers)
* [Discontinued](#Discontinued)


💡 **Notes**
- The following lists are curated by humans, as such may be incomplete
- We only include software targeting the folding problem combining learnings from AlphaFold 2 and protein language models. You may find other ML on protein tools [at Kevin's incredible ML for proteins list](https://github.com/yangkky/Machine-learning-for-proteins).
- We do not wish to advertize one tool over any other, but simply list the tools we are aware of in either random or alphabetical order
- Any suggestions for improvements and additions are welcome as issues or pull requests
- Projects we identify as discontinued are marked with 💀 and in a section at the end

⚡️ **Brought to you by:** 
- [@sacdallago](https://twitter.com/sacdallago)
- [@sokrypton](https://twitter.com/sokrypton)

----

<a name="Predictors"></a>
### Predictors
[_in alphabetical order_]
- **MSA-based** (uses Multiple Sequence Alignments (MSAs) as input)
  - AlphaFold2 
  [![](https://img.shields.io/badge/repo-JAX-blue)](https://github.com/deepmind/alphafold)
  [![](https://img.shields.io/badge/DOI-10.1038%2Fs41586--021--03819--2-lightgrey)](https://www.nature.com/articles/s41586-021-03819-2)
    - The original AlphaFold 2 method
    - Features: monomer, multimer
    - Other: [Colab Notebook](https://colab.research.google.com/github/deepmind/alphafold/blob/main/notebooks/AlphaFold.ipynb)
  - ColabFold
  [![](https://img.shields.io/badge/repo-JAX-blue)](https://github.com/sokrypton/ColabFold)
  [![](https://img.shields.io/badge/DOI-10.1038%2Fs41592--022--01488--1-lightgrey)](https://www.nature.com/articles/s41592-022-01488-1)
    - Faster AF2 compiling and MSA generations
    - Features: monomer, multimer 
    - Other: [localcolabfold](https://github.com/YoshitakaMo/localcolabfold)
  - FastFold
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/hpcaitech/FastFold)
  [![](https://img.shields.io/badge/arxiv-2203.00854-lightgrey)](https://arxiv.org/abs/2203.00854)
    - Runtime improvements to OpenFold (see below)
    - Features: monomer
  - HelixFold 
  [![](https://img.shields.io/badge/repo-PaddlePaddle-pink)](https://github.com/PaddlePaddle/PaddleHelix/tree/dev/apps/protein_folding/helixfold)
  [![](https://img.shields.io/badge/arxiv-2207.05477-lightgrey)](https://arxiv.org/abs/2207.05477)
    - Reimplementation of AF2 in PaddlePaddle
    - Features: monomer 
  - MEGA-Fold 
  [![](https://img.shields.io/badge/repo-mindspore-green)](https://gitee.com/mindspore/mindscience/tree/master/MindSPONGE/applications/MEGAProtein)
  [![](https://img.shields.io/badge/arxiv-2206.12240-lightgrey)](https://arxiv.org/abs/2206.12240)
    - Reimplementation of AF2 in MindSpore; provides training code, training dataset and new model params.
    - Features: monomer
  - OpenFold
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/aqlaboratory/openfold)
    - Reimplementation of AF2 in PyTorch; provides training code, training dataset and new model params.
    - Features: monomer 
    - Other: [Colab Notebook](https://colab.research.google.com/github/aqlaboratory/openfold/blob/main/notebooks/OpenFold.ipynb)
  - RoseTTAFold
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/RosettaCommons/RoseTTAFold)
  [![](https://img.shields.io/badge/DOI-10.1126%2Fscience.abj8754-lightgrey)](https://www.science.org/doi/10.1126/science.abj8754)
    - Reproduced AF2 in PyTorch before details of AF2 were available; new model parameters.
    - Features: monomer
    - Other: [Unofficial Colab Notebook](https://colab.research.google.com/github/sokrypton/ColabFold/blob/main/RoseTTAFold.ipynb)
  - Uni-Fold
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/dptech-corp/Uni-Fold)
  [![](https://img.shields.io/badge/DOI-10.1101%2F2022.08.04.502811-lightgrey)](https://doi.org/10.1101/2022.08.04.502811)
    - Reimplementation of AF2 in PyTorch; provides training code and new (monomer/multimer) model parameters.
    - Features: monomer, multimer 
    - Resources: [Colab Notebook](https://colab.research.google.com/github/dptech-corp/Uni-Fold/blob/main/notebooks/unifold.ipynb)
  - Uni-Fold-jax
  [![](https://img.shields.io/badge/repo-JAX-blue)](https://github.com/dptech-corp/Uni-Fold-jax)
  [![](https://img.shields.io/badge/DOI-10.1101%2F2022.08.04.502811-lightgrey)](https://doi.org/10.1101/2022.08.04.502811)
    - Implementation of AF2's training code.


- **pLM-based** (using embeddings from protein Language Models (pLMs) as input)
  - ESM-Fold
   [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/facebookresearch/esm)
  [![](https://img.shields.io/badge/DOI-10.1101%2F2022.07.20.500902-lightgrey)](https://doi.org/10.1101/2022.07.20.500902)
    - Features: monomer 
    - Other: [Unofficial Colab notebook](https://github.com/sokrypton/ColabFold/blob/main/ESMFold.ipynb),[API](https://esmatlas.com/resources?action=fold)
  - EMBER3D
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/kWeissenow/EMBER3D)
    - Features: monomer 
  - HelixFold-single
    [![](https://img.shields.io/badge/repo-PaddlePaddle-pink)](https://github.com/PaddlePaddle/PaddleHelix/tree/dev/apps/protein_folding/helixfold-single)
    [![](https://img.shields.io/badge/arxiv-2207.13921-lightgrey)](https://arxiv.org/abs/2207.13921)
    - Features: monomer 
    - Resource: https://paddlehelix.baidu.com/app/drug/protein-single/forecast
  - IgFold
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/Graylab/IgFold)
  [![](https://img.shields.io/badge/DOI-10.1101%2F2022.04.20.488972-lightgrey)](https://doi.org/10.1101/2022.04.20.488972)
    - pLM focused on antibody sequences
    - Features: monomer 
    - Other: [Colab Notebook](https://colab.research.google.com/github/Graylab/IgFold/blob/main/IgFold.ipynb)
  - OmegaFold
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/HeliXonProtein/OmegaFold)
 [![](https://img.shields.io/badge/DOI-10.1101%2F2022.07.21.500999-lightgrey)](https://doi.org/10.1101/2022.07.21.500999)
    - Features: monomer
    - Other:
    [Unofficial Colab Notebook](https://colab.research.google.com/github/sokrypton/ColabFold/blob/main/beta/omegafold.ipynb),
    [[tweet] Martin comparing structures](https://twitter.com/thesteinegger/status/1554881669718573062),
    [[tweet] Sergey's positional encoding observation](https://twitter.com/sokrypton/status/1555536325176168448)
    
- **Other**
  - EquiFold
    [![](https://img.shields.io/badge/DOI-10.1101%2F2022.10.07.511322-lightgrey)](https://doi.org/10.1101/2022.10.07.511322)
    - Diffusion model to predict protein structures (specifically antibodies)
    - Features: monomer

<a name="Tools"></a>
### Tools and Extensions
  - gget (AF2)
  [![](https://img.shields.io/badge/-repo-gray)](https://github.com/pachterlab/gget#gget-alphafold- )
  [![](https://img.shields.io/badge/DOI-10.1101%2F2022.05.17.492392-lightgrey)](https://doi.org/10.1101/2022.05.17.492392)
  - alphafold_finetune
  [![](https://img.shields.io/badge/-repo-gray)](https://github.com/phbradley/alphafold_finetune)
  [![](https://img.shields.io/badge/DOI-10.1101%2F2022.07.12.499365-lightgrey)](https://doi.org/10.1101/2022.07.12.499365)
    - finetune AlphaFold for Protein-Peptide prediction
    - Other: [[tweet] Amir's announcement](https://twitter.com/AMotmaen/status/1547435940011945984)
  - AlphaPulldown
  [![](https://img.shields.io/badge/-repo-gray)](https://www.embl-hamburg.de/AlphaPulldown/)
  [![](https://img.shields.io/badge/DOI-10.1101%2F2022.08.05.502961-lightgrey)](https://doi.org/10.1101/2022.08.05.502961)
    - protein-protein interaction screens using AlphaFold-Multimer
  - ColabDesign
    [![](https://img.shields.io/badge/-repo-gray)](https://github.com/sokrypton/ColabDesign)
    - Backprop through AlphaFold for protein design
  - AF2Rank
  [![](https://img.shields.io/badge/-repo-gray)](https://github.com/jproney/AF2Rank)
  [![](https://img.shields.io/badge/DOI-10.1101%2F2022.03.11.484043-lightgrey)](https://doi.org/10.1101/2022.03.11.484043)
    - Rank Decoy Structures/Sequences using AlphaFold
    - Resource: [Colab Notebook](https://colab.research.google.com/github/sokrypton/ColabDesign/blob/main/af/examples/AF2Rank.ipynb)
  - protein_structure_module_of_AF2 
  [![](https://img.shields.io/badge/-repo-gray)](https://github.com/pengzhangzhi/protein_structure_module_of_AF2)
    - IPA implementation in pytorch
   
---- 
<a name="Databases"></a>
### Databases of predictions
  - AlphaFold Database
  [![](https://img.shields.io/badge/DOI-10.1093%2Fnar%2Fgkab1061-lightgrey)](https://doi.org/10.1093/nar/gkab1061)
    - All sequences in UniRef90 - viral sequences; Based on AlphaFold 2
    - Resource: https://alphafold.ebi.ac.uk
  - Eukaryotic interactormes
    [![](https://img.shields.io/badge/DOI-10.1126%2Fscience.abm4805-lightgrey)](https://www.science.org/doi/10.1126/science.abm4805)
    - Protein-Protein interactions; Based on RoseTTAFold and AlphaFold 2
    - Resource: https://www.ebi.ac.uk/pdbe/news/predicted-complexes-modelarchive-now-pdbe-kb-pages
  - Structures of human-transcriptome isoforms
    [![](https://img.shields.io/badge/DOI-10.1101%2F2022.06.08.495354-lightgrey)](https://doi.org/10.1101/2022.06.08.495354)
    - Based on ColabFold (AlphaFold 2)
    - Resource: https://www.isoform.io
  - AlphaFill
    [![](https://img.shields.io/badge/DOI-10.1101%2F2021.11.26.470110-lightgrey)](https://doi.org/10.1101/2021.11.26.470110)
    - Enriching the AlphaFold models with ligands and co-factors (AlphaFold 2)
    - Resource: https://alphafill.eu/
  - IgFold Database
   [![](https://img.shields.io/badge/DOI-10.1101%2F2022.04.20.488972-lightgrey)](https://doi.org/10.1101/2022.04.20.488972)
    - Predictions specific to antibody sequences; based on OAS dataset and IgFold
    - Resource: https://data.graylab.jhu.edu/igfold_oas_paired95.tar.gz
    

### Datasets for training
  - OpenFold
    - MSAs for 132K PDBs + 270K UniClust30 predictions for distilation
    - Resource: https://registry.opendata.aws/openfold/
  - MindSpore
    - MSAs for 570K PDBs + 745K Distillation
    - Manuscript: https://arxiv.org/abs/2206.12240
    - Resource: http://ftp.cbi.pku.edu.cn/psp/

----

<a name="Webservers"></a>
### Webservers
  - Lambda PredictProtein
[![](https://img.shields.io/badge/DOI-10.1101%2F2022.08.04.502750-lightgrey)](https://doi.org/10.1101/2022.08.04.502750)
    - Based on ColabFold; Limited to sequences up to 500AAs
    - Resource: http://embed.predictprotein.org/
  - Robetta
    - Based on RoseTTAFold
    - Resource: https://robetta.bakerlab.org/ 

----

<a name="Discontinued"></a>
### Discontinued

  - 💀 Moonbear
    - Resource: https://www.getmoonbear.com/
    - Other: [[tweet] Stephanie's announcement](https://twitter.com/stephanieszhang/status/1427773598199164937)
  - 💀 Lucidrains' AlphaFold2
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/lucidrains/alphafold2)
    - AF2 reproduction attempt
    - Features: monomer
  - 💀 Lupoglaz's OpenFold2
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/lupoglaz/OpenFold2)
    - AF2 reproduction attempt
    - Features: monomer
