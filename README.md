# AI-for-crystal-materials： models and benchmarks
Here we have collected papers with the theme of "AI for crystalline materials" that have appeared at top machine learning conferences and journals (ICML, ICLR, NeurIPS, AAAI, NPJ, NC, etc.) in recent years. See https://arxiv.org/abs/2408.08044 for details.

## Crystalline Material Physicochemical Property Prediction

|Method         |           Paper            |
|----------------|-------------------------------|
|SchNet|    Schnet: A continuous-filter convolutional neural network for modeling quantum interactions (NeurIPS2017) [[**Paper**](https://proceedings.neurips.cc/paper/2017/hash/303ed4c69846ab36c2904d3ba8573050-Abstract.html)][[**Code**](https://github.com/atomistic-machine-learning/schnetpack)]       |         
|CGCNN          |    Crystal graph convolutional neural networks for an accurate and interpretable prediction of material properties (Physical Review Letters, 2018) [[**Paper**](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.120.145301)][[**Code**](https://github.com/txie-93/cgcnn)]        |     
|MEGNET          | Graph networks as a universal machine learning framework for molecules and crystals (Chemistry of Materials, 2019) [[**Paper**](https://pubs.acs.org/doi/10.1021/acs.chemmater.9b01294)][[**Code**](https://github.com/materialsvirtuallab/megnet)]     | 
|GATGNN          | Graph convolutional neural networks with global attention for improved materials property prediction (Physical Chemistry Chemical Physics, 2020) [[**Paper**](https://pubs.rsc.org/en/content/articlelanding/2020/cp/d0cp01474e/unauth)][[**Code**](https://github.com/superlouis/GATGNN)]     | 
|ALIGNN          | Atomistic line graph neural network for improved materials property predictions (npj Computational Materials, 2021) [[**Paper**](https://www.nature.com/articles/s41524-021-00650-1)][[**Code**](https://github.com/usnistgov/alignn)]     | 
|ECN          | Equivariant networks for crystal structures (NeurIPS2022) [[**Paper**](https://proceedings.neurips.cc/paper_files/paper/2022/hash/1abed6ee581b9ceb4e2ddf37822c7fcb-Abstract-Conference.html)][[**Code**](https://github.com/oumarkaba/equivariant_crystal_networks)]     | 
|PotNet          | Efficient Approximations of Complete Interatomic Potentials for Crystal Property Prediction (ICML2023) [[**Paper**](https://proceedings.mlr.press/v202/lin23m.html)][[**Code**](https://github.com/divelab/AIRS/tree/main/OpenMat/PotNet)]     | 
|CrysGNN          | Crysgnn: Distilling pre-trained knowledge to enhance property prediction for crystalline materials (AAAI2023) [[**Paper**](https://ojs.aaai.org/index.php/AAAI/article/view/25892)][[**Code**](https://github.com/kdmsit/crysgnn)]     | 
|ETGNN          | A general tensor prediction framework based on graph neural networks (The Journal of Physical Chemistry Letters, 2023) [[**Paper**](https://pubs.acs.org/doi/abs/10.1021/acs.jpclett.3c01200)]     | 
|GMTNet          |  A Space Group Symmetry Informed Network for O(3) Equivariant Crystal Tensor Prediction (ICML2024) [[**Paper**](https://openreview.net/forum?id=BOFjRnJ9mX)][[**Code**](https://github.com/divelab/AIRS/tree/main/OpenMat/GMTNet)]     | 
|CEGANN          | CEGANN: Crystal Edge Graph Attention Neural Network for multiscale classification of materials environment (npj Computational Materials, 2023) [[**Paper**](https://www.nature.com/articles/s41524-023-00975-z)][[**Code**](https://github.com/sbanik2/CEGANN)]     | 
|ComFormer          | Complete and Efficient Graph Transformers for Crystal Material Property Prediction (ICLR2024) [[**Paper**](https://openreview.net/forum?id=BnQY9XiRAS)][[**Code**](https://github.com/divelab/AIRS/tree/main/OpenMat/ComFormer)]     | 
|Crystalformer          |Crystalformer: infinitely connected attention for periodic structure encoding (ICLR2024) [[**Paper**](https://openreview.net/pdf?id=BnQY9XiRAS)][[**Code**](https://github.com/omron-sinicx/crystalformer)]     | 
|Crystalformer          | Conformal Crystal Graph Transformer with Robust Encoding of Periodic Invariance (AAAI2024) [[**Paper**](https://ojs.aaai.org/index.php/AAAI/article/view/27781)]   | 
|E(3)NN          | Direct prediction of phonon density of states with Euclidean neural networks (Advanced Science, 2021) [[**Paper**](https://onlinelibrary.wiley.com/doi/full/10.1002/advs.202004214)][[**Code**](https://github.com/zhantaochen/phonondos_e3nn)]     | 
|DOSTransformer          | Density of States Prediction of Crystalline Materials via Prompt-guided Multi-Modal Transformer (NeurIPS2023) [[**Paper**](https://proceedings.neurips.cc/paper_files/paper/2023/hash/c23fdcb9f8e28af705a87de1375a705c-Abstract-Conference.html)][[**Code**](https://github.com/HeewoongNoh/DOSTransformer)]     | 
|Matformer          | Periodic Graph Transformers for Crystal Material Property Prediction (NeurIPS2022) [[**Paper**](https://proceedings.neurips.cc/paper_files/paper/2022/hash/6145c70a4a4bf353a31ac5496a72a72d-Abstract-Conference.html)][[**Code**](https://github.com/YKQ98/Matformer)]     | 
|CrysDiff          | A Diffusion-Based Pre-training Framework for Crystal Property Prediction (AAAI2024) [[**Paper**](https://ojs.aaai.org/index.php/AAAI/article/view/28748)]     | 
|MOFTransformer        | A multi-modal pre-training transformer for universal transfer learning in metal-organic frameworks (Nature Machine Intelligence, 2023) [[**Paper**](https://www.nature.com/articles/s42256-023-00628-2)][[**Code**](https://github.com/hspark1212/MOFTransformer)]     | 
|Uni-MOF          | A comprehensive transformer-based approach for high-accuracy gas adsorption predictions in metal-organic frameworks (Nature Communications, 2024) [[**Paper**](https://www.nature.com/articles/s41467-024-46276-x)][[**Code**](https://github.com/dptech-corp/Uni-MOF)]     | 



## Crystalline Material Synthesis

|Method         |           Paper            |
|----------------|-------------------------------|
|G-SchNet         | Symmetry-adapted generation of 3d point sets for the targeted discovery of molecules (NeurIPS2019) [[**Paper**](https://proceedings.neurips.cc/paper/2019/hash/a4d8e2a7e0d0c102339f97716d2fdfb6-Abstract.html)][[**Code**](https://github.com/atomistic-machine-learning/G-SchNet)]     | 
|CDVAE          | Crystal Diffusion Variational Autoencoder for Periodic Material Generation (ICLR2022) [[**Paper**](https://openreview.net/forum?id=03RLpj-tc_)][[**Code**](https://github.com/txie-93/cdvae)]     | 
|Con-CDVAE          | Con-CDVAE: A method for the conditional generation of crystal structures (Computational Materials Today, 2024) [[**Paper**](https://www.sciencedirect.com/science/article/pii/S2950463524000036)][[**Code**](https://github.com/cyye001/Con-CDVAE)]     | 
|Cond-CDVAE         | Deep learning generative model for crystal structure prediction (Arxiv, 2024) [[**Paper**](https://arxiv.org/abs/2403.10846)][[**Code**](https://github.com/ixsluo/cond-cdvae)]     | 
|LCOMs          | Latent Conservative Objective Models for Data-Driven Crystal Structure Prediction (NeurIPS2023 Workshop) [[**Paper**](https://openreview.net/forum?id=BTeWafMOyt)]     | 
|DiffCSP          | Crystal structure prediction by joint equivariant diffusion on lattices and fractional coordinates (NeurIPS2023) [[**Paper**](https://proceedings.neurips.cc/paper_files/paper/2023/hash/38b787fc530d0b31825827e2cc306656-Abstract-Conference.html)][[**Code**](https://github.com/jiaor17/DiffCSP)]     | 
|EquiCSP         | Equivariant Diffusion for Crystal Structure Prediction (ICML2024) [[**Paper**](https://openreview.net/forum?id=VRv8KjJNuj)][[**Code**](https://github.com/EmperorJia/EquiCSP)]     | 
|GemsDiff         | Vector Field Oriented Diffusion Model for Crystal Material Generation (AAAI2024) [[**Paper**](https://ojs.aaai.org/index.php/AAAI/article/view/30224)][[**Code**](https://github.com/aklipf/gemsdiff)]     | 
|SyMat          | Towards symmetry-aware generation of periodic materials (NeurIPS2023) [[**Paper**](https://proceedings.neurips.cc/paper_files/paper/2023/hash/a73474c359ed523e6cd3174ed29a4d56-Abstract-Conference.html)][[**Code**](https://github.com/divelab/AIRS/tree/main/OpenMat/SyMat)]     | 
|EMPNN         | Equivariant Message Passing Neural Network for Crystal Material Discovery (AAAI2023) [[**Paper**](https://ojs.aaai.org/index.php/AAAI/article/view/26673)][[**Code**](https://github.com/aklipf/pegnn)]     | 
|UniMat         | Scalable Diffusion for Materials Generation (ICLR2024) [[**Paper**](https://openreview.net/forum?id=wm4WlHoXpC)][[**Code**](https://unified-materials.github.io/unimat/)]  | 
|MatterGen         | Mattergen: a generative model for inorganic materials design (Arxiv, 2023) [[**Paper**](https://arxiv.org/abs/2312.03687)]   | 
|PGCGM          | Physics guided deep learning for generative design of crystal materials with symmetry constraints (npj Computational Materials, 2023) [[**Paper**](https://www.nature.com/articles/s41524-023-00987-9)][[**Code**](https://github.com/MilesZhao/PGCGM)]     | 
|CubicGAN         | High-throughput discovery of novel cubic crystal materials using deep generative neural networks (Advanced Science, 2021) [[**Paper**](https://onlinelibrary.wiley.com/doi/full/10.1002/advs.202100566)][[**Code**](https://github.com/MilesZhao/CubicGAN)]     | 
|PCVAE          | PCVAE: A Physics-informed Neural Network for Determining the Symmetry and Geometry of Crystals (IJCNN2023) [[**Paper**](https://ieeexplore.ieee.org/abstract/document/10191051)][[**Code**](https://github.com/zjuKeLiu/PCVAE)]     | 
|DiffCSP++          | Space Group Constrained Crystal Generation (ICLR2024) [[**Paper**](https://openreview.net/forum?id=jkvZ7v4OmP)][[**Code**](https://github.com/jiaor17/DiffCSP-PP)]     | 
|FlowMM         | FlowMM: Generating Materials with Riemannian Flow Matching (ICML2024) [[**Paper**](https://openreview.net/forum?id=W4pB7VbzZI)][[**Code**](https://github.com/facebookresearch/flowmm)]     | 
|Govindarajan         | Behavioral Cloning for Crystal Design (ICLR2023 Workshop) [[**Paper**](https://openreview.net/forum?id=qxuIaeDlemv)][[**Code**]()]     | 
|CHGFlowNet         | Hierarchical GFlownet for Crystal Structure Generation (NeurIPS2023 Workshop) [[**Paper**](https://openreview.net/forum?id=dJuDv4MKLE)]    | 
|LM-CM,LM-AC          | Language models can generate molecules, materials, and protein binding sites directly in three dimensions as xyz, cif, and pdb files (Arxiv, 2023) [[**Paper**](https://arxiv.org/abs/2305.05708)][[**Code**](https://github.com/danielflamshep/xyztransformer)]     | 
|CrystaLLM          | Crystal structure generation with autoregressive large language modeling (Arxiv, 2023) [[**Paper**](https://arxiv.org/abs/2307.04340)][[**Code**](https://github.com/lantunes/CrystaLLM)]     | 
|CrystalFormer          | Space Group Informed Transformer for Crystalline Materials Generation (Arxiv, 2024) [[**Paper**](https://arxiv.org/abs/2403.15734)][[**Code**](https://github.com/deepmodeling/CrystalFormer)]     | 
|SLI2Cry         | An invertible, invariant crystal representation for inverse design of solid-state materials using generative deep learning (Nature Communications, 2023) [[**Paper**](https://www.nature.com/articles/s41467-023-42870-7)][[**Code**](https://github.com/xiaohang007/SLICES/tree/main)]     | 
|Gruver         | Fine-Tuned Language Models Generate Stable Inorganic Materials as Text (ICLR2024) [[**Paper**](https://openreview.net/forum?id=vN9fpfqoP1)][[**Code**](https://github.com/facebookresearch/crystal-text-llm)]     | 
|FlowLLM         | FlowLLM: Flow Matching for Material Generation with Large Language Models as Base Distributions (NeurIPS2024) [[**Paper**](https://openreview.net/forum?id=0bFXbEMz8e)][[**Code**](https://github.com/facebookresearch/flowmm)]     | 
|Mat2Seq         | Invariant Tokenization of Crystalline Materials for Language Model Enabled Generation (NeurIPS2024) [[**Paper**](https://openreview.net/forum?id=18FGRNd0wZ&noteId=Tmq6A9Gswe)]   | 


## Aiding Characterization
|Method         |           Paper            |
|----------------|-------------------------------|
|    -      | Insightful classification of crystal structures using deep learning  (Nature Communications, 2018) [[**Paper**](https://www.nature.com/articles/s41467-018-05169-6)]     | 
|-          | Advanced steel microstructural classification by deep learning methods  (Scientific Reports, 2018) [[**Paper**](https://www.nature.com/articles/s41598-018-20037-5)]    | 
|    -      | Neural network for nanoscience scanning electron microscope image recognition (Scientific Reports, 2017) [[**Paper**](https://www.nature.com/articles/s41598-017-13565-z)]     | 
|-         | Deep Learning-Assisted Quantification of Atomic Dopants and Defects in 2D Materials (Advanced Science, 2021) [[**Paper**](https://onlinelibrary.wiley.com/doi/full/10.1002/advs.202101099)]   | 
|-        | Classification of crystal structure using a convolutional neural network  (IUCrJ,2017) [[**Paper**](https://journals.iucr.org/m/issues/2017/04/00/fc5018/index.html)]    | 
|-          | Synthesis, optical imaging, and absorption spectroscopy data for 179072 metal oxides  (Scientific Data, 2019) [[**Paper**](https://www.nature.com/articles/s41597-019-0019-4)]    | 




## Accelerating Theoretical Computation
|Method         |           Paper            |
|----------------|-------------------------------|
|BPNN         | Generalized neural-network representation of high-dimensional potential-energy surfaces  (Physical Review Letters, 2007) [[**Paper**](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.98.146401)]    | 
|-          | Gaussian approximation potentials: The accuracy of quantum mechanics, without the electrons  (Physical Review Letters, 2010) [[**Paper**](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.104.136403)]    | 
|NequIP           | E (3)-equivariant graph neural networks for data-efficient and accurate interatomic potentials  (Nature Communications, 2022) [[**Paper**](https://www.nature.com/articles/s41467-022-29939-5)][[**Code**](https://github.com/mir-group/nequip)]     | 
|CHGNet          | CHGNet as a pretrained universal neural network potential for charge-informed atomistic modelling  (Nature Machine Intelligence, 2023) [[**Paper**](https://www.nature.com/articles/s42256-023-00716-3)][[**Code**](https://github.com/CederGroupHub/chgnet)]     | 
|Cormorant          | Cormorant: Covariant molecular neural networks  (NeurIPS2019) [[**Paper**](https://proceedings.neurips.cc/paper/2019/hash/03573b32b2746e6e8ca98b9123f2249b-Abstract.html)][[**Code**](https://github.com/risilab/cormorant)]     | 
|MACE         | MACE: Higher order equivariant message passing neural networks for fast and accurate force fields  (NeurIPS2022) [[**Paper**](https://proceedings.neurips.cc/paper_files/paper/2022/hash/4a36c3c51af11ed9f34615b81edb5bbc-Abstract-Conference.html)][[**Code**](https://github.com/ACEsuit/mace)]     | 
|DimeNet          | Directional Message Passing for Molecular Graphs  (ICLR2020) [[**Paper**](https://openreview.net/forum?id=B1eWbxStPH)][[**Code**](https://github.com/gasteigerjo/dimenet)]     | 
|M3GNet        | A universal graph deep learning interatomic potential for the periodic table  (Nature Computational Science, 2022) [[**Paper**](https://www.nature.com/articles/s43588-022-00349-3)][[**Code**](https://github.com/materialsvirtuallab/m3gnet)]     | 
|-          | Injecting domain knowledge from empirical interatomic potentials to neural networks for predicting material properties  (NeurIPS2022) [[**Paper**](https://proceedings.neurips.cc/paper_files/paper/2022/hash/5ef1df239d6640a27dd6ed9a59f518c9-Abstract-Conference.html)][[**Code**](https://github.com/shuix007/EIP4NNPotentials)]     | 
|CHGNet        | CHGNet as a pretrained universal neural network potential for charge-informed atomistic modelling  (Nature Machine Intelligence, 2023) [[**Paper**](https://www.nature.com/articles/s42256-023-00716-3)][[**Code**](https://github.com/CederGroupHub/chgnet)]     | 
|-          | Forces are not Enough: Benchmark and Critical Evaluation for Machine Learning Force Fields with Molecular Simulations  (Transactions on Machine Learning Research, 2023) [[**Paper**](https://openreview.net/forum?id=A8pqQipwkt)]     | 

