**Table of contents**
* [Predictors](#Predictors)
* [Tools](#Tools)
* [Databases](#Databases)
* [Webservers](#Webservers)

----

<a name="Predictors"></a>
### Predictors
- AlphaFold 2 (MSAs|JAX)
  - Manuscript: https://www.nature.com/articles/s41586-021-03819-2
  - Code: https://github.com/deepmind/alphafold
- RoseTTAFold (MSAs|PyTorch)
  - Manuscript: https://www.science.org/doi/10.1126/science.abj8754
  - Code: https://github.com/RosettaCommons/RoseTTAFold
- HelixFold (pLMs)
  - Manuscript: https://arxiv.org/abs/2207.13921
  - Code: https://github.com/PaddlePaddle/PaddleHelix
  - Resrouce: https://paddlehelix.baidu.com/app/drug/protein-single/forecast
- OmegaFold (pLMs + MSAs|PyTorch)
  - Manuscript: https://doi.org/10.1101/2022.07.21.500999
  - Code: https://github.com/HeliXonProtein/OmegaFold
  - Resources: [[tweet] Martin comparing structures](https://twitter.com/thesteinegger/status/1554881669718573062), [[tweet] Sergey's positional encoding observation](https://twitter.com/sokrypton/status/1555536325176168448), 
- OpenFold (MSAs|PyTorch)
  - Manuscript?
  - Code: https://github.com/aqlaboratory/openfold
- ESM-Fold (pLMs)
  - Manuscript: https://doi.org/10.1101/2022.07.20.500902
  - Code: ? (potentially: https://github.com/facebookresearch/esm)
  - Resources: [Alex's tweet](https://twitter.com/alexrives/status/1550148755206414341), 
- EMBER3D (pLMs|PyTorch):
  - Manuscript: ?
  - Code: https://github.com/kWeissenow/EMBER3D
- ColabFold (AF2|MSAs|JAX)
  - Manuscript: https://www.nature.com/articles/s41592-022-01488-1
  - Code: https://github.com/sokrypton/ColabFold
- Uni-Fold (MSAs|PyTorch)
  - Manuscript: https://doi.org/10.1101/2022.08.04.502811
  - Code: https://github.com/dptech-corp/Uni-Fold
- MineSpore-Fold
  - Manuscript: https://arxiv.org/abs/2206.12240
  - Code: ?

 ----
 
<a name="Tools"></a>
### Variations/Repackaging/Tools

 - gget (AF2)
   - Manuscript: https://doi.org/10.1101/2022.05.17.492392
   - Code: https://github.com/pachterlab/gget#gget-alphafold-
 - FastFold (AF2|OF)
  - Manuscript: https://arxiv.org/abs/2203.00854
  - Code: https://github.com/hpcaitech/FastFold
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
