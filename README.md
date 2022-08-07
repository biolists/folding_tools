**Table of contents**
* [Predictors](#Predictors)
* [Tools, reimplementations, etc.](#Tools)
* [Databases](#Databases)
* [Webservers](#Webservers)


**Note**: discontinued project are marked with 💀

**Thanks for help to:** [@sokrypton](https://twitter.com/sokrypton)

----

<a name="Predictors"></a>
### Predictors
- **MSA-based** (uses Multiple Sequence Alignment as input)
  - AlphaFold2 (JAX)
    - Manuscript: https://www.nature.com/articles/s41586-021-03819-2
    - Code: https://github.com/deepmind/alphafold
  - RoseTTAFold (PyTorch)
    - Manuscript: https://www.science.org/doi/10.1126/science.abj8754
    - Code: https://github.com/RosettaCommons/RoseTTAFold
  - OpenFold (PyTorch)
    - Manuscript?
    - Code: https://github.com/aqlaboratory/openfold
  - HelixFold (PyTorch)
    - Manuscript: https://arxiv.org/abs/2207.05477
    - Code:  https://github.com/PaddlePaddle/PaddleHelix/tree/dev/apps/protein_folding/helixfold
  - Uni-Fold (PyTorch/JAX)
    - Manuscript: https://doi.org/10.1101/2022.08.04.502811
    - Code (PyTorch): https://github.com/dptech-corp/Uni-Fold
    - Code (JAX): https://github.com/dptech-corp/Uni-Fold-jax
  - MineSpore-Fold
    - Manuscript: https://arxiv.org/abs/2206.12240
    - Code: https://gitee.com/mindspore/mindscience/tree/master/MindSPONGE/applications/MEGAProtein

- **pLM-based** (uses Protein Language Model as input)
  - HelixFold
    - Manuscript: https://arxiv.org/abs/2207.13921
    - Code: https://github.com/PaddlePaddle/PaddleHelix/tree/dev/apps/protein_folding/helixfold-single
    - Resource: https://paddlehelix.baidu.com/app/drug/protein-single/forecast
  - OmegaFold (PyTorch)
    - Manuscript: https://doi.org/10.1101/2022.07.21.500999
    - Code: https://github.com/HeliXonProtein/OmegaFold
    - Other: [[tweet] Martin comparing structures](https://twitter.com/thesteinegger/status/1554881669718573062), [[tweet] Sergey's positional encoding observation](https://twitter.com/sokrypton/status/1555536325176168448), 
  - ESM-Fold (PyTorch)
    - Manuscript: https://doi.org/10.1101/2022.07.20.500902
    - Code: ? (potentially: https://github.com/facebookresearch/esm)
    - Other: [[tweet] Alex's announcement](https://twitter.com/alexrives/status/1550148755206414341), 
  - EMBER3D (PyTorch):
    - Manuscript: ?
    - Code: https://github.com/kWeissenow/EMBER3D

 ----
 
<a name="Tools"></a>
### Variations/Repackaging/Tools
  - ColabFold (AF2|MSAs|JAX)
    - Manuscript: https://www.nature.com/articles/s41592-022-01488-1
    - Code: https://github.com/sokrypton/ColabFold
  - gget (AF2)
    - Manuscript: https://doi.org/10.1101/2022.05.17.492392
    - Code: https://github.com/pachterlab/gget#gget-alphafold-
  - FastFold (AF2|OF)
    - Manuscript: https://arxiv.org/abs/2203.00854
    - Code: https://github.com/hpcaitech/FastFold
  - 💀 Lucidrains AF2 (AF2)
    - Code: https://github.com/lucidrains/alphafold2
  - 💀 Lupoglaz OpenFold2 (AF2)
    - Code: https://github.com/lupoglaz/OpenFold2
  - 💀 Moonbear
    - Resource: https://www.getmoonbear.com/
    - Other: [[tweet] Stephanie's announcement](https://twitter.com/stephanieszhang/status/1427773598199164937)

<a name="Extensions"></a>
### Tools building on Predictors
 - AlphaPulldown - protein-protein interaction screens using AlphaFold-Multimer
   - Manuscript: https://www.biorxiv.org/content/10.1101/2022.08.05.502961v1
   - Code: https://www.embl-hamburg.de/AlphaPulldown/
 - AlphaFill - enriching the AlphaFold models with ligands and co-factors
   - Manuscript: https://www.biorxiv.org/content/10.1101/2021.11.26.470110v1
   - Code: https://alphafill.eu/
   
---- 

<a name="Databases"></a>
### Datasets/Databases
 - AlphaFold Database (UniRef90|AF2)
   - Manuscript: https://doi.org/10.1093/nar/gkab1061
   - Resource: alphafold.ebi.ac.uk
 - Eukaryotic interactormes (Pathawy-involved proteins|RoseTTAFold)
   - Manuscript: https://www.science.org/doi/10.1126/science.abm4805
   - Resource: ?

 ----

<a name="Webservers"></a>
### Webservers
 - Lambda PredictProtein (ColabFold|limit:500AA)
   - Manuscript: https://doi.org/10.1101/2022.08.04.502750
   - Resource: http://embed.predictprotein.org/
