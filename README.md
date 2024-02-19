<p align="center">
    <img src="./figs/fig_emergence.jpg" width="69%"/> <br />
    <em>
    </em>
</p>

# <p align=center>`Awesome object-centric learning (OCL)`

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/licenses/MIT) 
[![Forks](https://img.shields.io/github/forks/Jun-Pu/Awesome-object-centric-learning.svg?style=for-the-badge)](https://github.com/Jun-Pu/Awesome-object-centric-learning/network/members)
[![Stargazers](https://img.shields.io/github/stars/Jun-Pu/Awesome-object-centric-learning.svg?style=for-the-badge)](https://github.com/Jun-Pu/Awesome-object-centric-learning/stargazers)
[![Issues](https://img.shields.io/github/issues/Jun-Pu/Awesome-object-centric-learning.svg?style=for-the-badge)](https://github.com/Jun-Pu/Awesome-object-centric-learning/issues)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555)](https://www.linkedin.com/in/Jun-Pu/)
   

<p align="center">
The list will be continually updated. Stay tuned!
    
    OCL models decompose and reconstruct the synthetic/real-world scenes via learning multiple disentangled abstract representations, which interpret multiple levels of object-centric concepts, in a fully unsupervised manner.

< **Last updated: Aug/07/2023** >
        

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#Datasets and Benchmarks">Datasets and Benchmarks</a>
      <ul>
        <li><a href="#Synthetic Data">Synthetic Data</a></li>
         <li><a href="#Real-World Data">Real-World Data</a></li>
      </ul>
    </li>
    <li>
      <a href="#Methodologies">Methodologies</a>
      <ul>
        <li><a href="#Year 2023">Year 2023</a></li>
        <li><a href="#Year 2022">Year 2022</a></li>
        <li><a href="#Year 2021">Year 2021</a></li>
        <li><a href="#Year 2020">Year 2020</a></li>
      </ul>
    </li>
    <li><a href="#Contact">Contact</a></li>
  </ol>
</details>


## Datasets \& Benchmarks

### Synthetic Data
    
**Name** | **Source** 
:-: | :-: 
 **Multi-Object Datasets** | [Link](https://github.com/deepmind/multi_object_datasets)
    
### Real-World Data
    
 **Name** | **Source** 
:-: | :-: 
**PASCAL VOC, COCO** | [Link](https://github.com/amazon-science/object-centric-learning-framework)
**CUB200 Birds, Stanford Dogs, Stanford Cars, and Caltech Flowers** | [Link](https://github.com/YuLiu-LY/BO-QSA)
**YCB,ScanNet and COCO** | [Link](https://github.com/vLAR-group/UnsupObjSeg)

## Methodologies

### Year 2023
    
**Year** | **Publication** | **Title** | **Source** | **Forum** |  **Real-World?**  | **Using VLMs?**
:-: | :-:| :- | :-: | :-: | :-: |  :-:
**2023** | **ICCV** | [Unsupervised Compositional Concepts Discovery with Text-to-Image Generative Models](https://arxiv.org/pdf/2306.05357.pdf) <br><sub> **UCCD:** Discovering a set of compositional concepts given a dataset of unlabeled images. </sub> | [Code](https://energy-based-model.github.io/unsupervised-concept-discovery/) | |  :white_check_mark: |  :white_check_mark:
**2023** | **ICML** | [Composer: Creative and Controllable Image Synthesis with Composable Conditions](https://arxiv.org/pdf/2302.09778.pdf) <br><sub> **Composer:** Learning multiple concepts of the given real-world image and synthesize a new one by altering and compose them.  </sub> | | [PMLR](https://proceedings.mlr.press/v202/huang23b.html) | :white_check_mark:  | :white_check_mark: 
**2023** | **ICML** | [Provably Learning Object-Centric Representations](https://proceedings.mlr.press/v202/brady23a/brady23a.pdf) <br><sub> **ProvablyOCL:** Analyzing when object-centric representations can be learned without supervision and introducing two assumptions, compositionality and irreducibility, to prove that ground-truth object representations can be identified. </sub> | [Code](https://brendel-group.github.io/objects-identifiability/) | [PMLR](https://proceedings.mlr.press/v202/brady23a.html)
**2023** | **ICML** | [Unlocking Slot Attention by Changing Optimal Transport Costs](https://arxiv.org/pdf/2301.13197.pdf) <br><sub> **MESH:** A cross-attention module that combines the tiebreaking properties of unregularized optimal transport with the speed of regularized optimal transport.  </sub> | | [PMLR](https://proceedings.mlr.press/v202/zhang23ba.html)
**2023** | **ICML** | [Slot-VAE: Object-Centric Scene Generation with Slot Attention](https://arxiv.org/pdf/2306.06997.pdf) <br><sub> **SlotVAE:** A generative model that integrates slot attention with the hierarchical VAE framework for object-centric structured scene generation. </sub> | | [PMLR](https://proceedings.mlr.press/v202/wang23r.html)
**2023** | **ICML** | [Invariant Slot Attention: Object Discovery with Slot-Centric Reference Frames](https://arxiv.org/pdf/2302.04973.pdf) <br><sub> **InvSlotAttns:** Incorporating equivariance to per-object pose transformations into the attention and generation mechanism of Slot Attention by translating, scaling, and rotating position encodings.  </sub> | [Code](https://github.com/google-research/google-research/tree/master/invariant_slot_attention) | [PMLR](https://proceedings.mlr.press/v202/biza23a.html) | :white_check_mark:
**2023** | **ICML** | [An Investigation into Pre-Training Object-Centric Representations for Reinforcement Learning](https://arxiv.org/pdf/2302.04419.pdf) <br><sub> **OCRL:** Examining critical aspects of incorporating object-centric representation pre-training in reinforcement learning, such as performance in visually complex environments and the selection of an appropriate pooling layer for aggregating object representations. </sub> | [Code](https://sites.google.com/view/ocrl/home) | [PMLR](https://proceedings.mlr.press/v202/yoon23c.html)
**2023** | **ICML** | [Discovering Object-Centric Generalized Value Functions From Pixels](https://arxiv.org/pdf/2304.13892.pdf) <br><sub> **OCGVFs:** Introducing a method that tries to discover meaningful features from objects, translating them to temporally coherent ‘question’ functions and leveraging the subsequent learned general value functions for control. </sub> | | [PMLR](https://proceedings.mlr.press/v202/nath23a.html)
**2023** | **UAI** | [Time-Conditioned Generative Modeling of Object-Centric Representations for Video Decomposition and Prediction](https://arxiv.org/pdf/2301.08951.pdf) <br><sub> **TCGM-OCL:** Introducing a time-conditioned generative model for videos.  </sub> | | [PMLR](https://proceedings.mlr.press/v216/gao23a.html)
**2023** | **CVPR** | [Intrinsic Physical Concepts Discovery with Object-Centric Predictive Models](https://arxiv.org/pdf/2303.01869.pdf) <br><sub> **PHYCINE:** A system that infers physical concepts in different abstract levels without supervision. </sub> | | [CVF Proceedings](https://openaccess.thecvf.com/content/CVPR2023/html/Tang_Intrinsic_Physical_Concepts_Discovery_With_Object-Centric_Predictive_Models_CVPR_2023_paper.html) | 
**2023** | **CVPR** | [Object Discovery from Motion-Guided Tokens](https://arxiv.org/pdf/2303.15555.pdf) <br><sub> **MoTok:** Enabling the emergence of interpretable object-specific mid-level features, demonstrating the benefits of motion-guidance (no labeling) and quantization (interpretability, memory efficiency). </sub> | [Code](https://github.com/zpbao/MoTok) | [CVF Proceedings](https://openaccess.thecvf.com/content/CVPR2023/html/Bao_Object_Discovery_From_Motion-Guided_Tokens_CVPR_2023_paper.html) |  :white_check_mark:
**2023** | **CVPR** | [Shepherding Slots to Objects: Towards Stable and Robust Object-Centric Learning](https://arxiv.org/pdf/2303.17842.pdf) <br><sub> **SLASH:** Consisting of two simple-yet-effective modules on top of Slot Attention.  </sub> | [Code](https://github.com/object-understanding/SLASH) |  [CVF Proceedings](https://openaccess.thecvf.com/content/CVPR2023/html/Kim_Shepherding_Slots_to_Objects_Towards_Stable_and_Robust_Object-Centric_Learning_CVPR_2023_paper.html)
**2023** | **CVPR** | [Multi-Object Manipulation via Object-Centric Neural Scattering Functions](https://arxiv.org/pdf/2306.08748.pdf) <br><sub> **OSFs-MOM:** Combining object-centric neural scattering functions with inverse parameter estimation, and graph-based neural dynamics models.  </sub> | [Code](https://s-tian.github.io/projects/actionosf/) | [CVF Proceedings](https://openaccess.thecvf.com/content/CVPR2023/html/Tian_Multi-Object_Manipulation_via_Object-Centric_Neural_Scattering_Functions_CVPR_2023_paper.html) | :white_check_mark:
**2023** | **ICLR** | [Bridging the Gap to Real-World Object-Centric Learning](https://openreview.net/pdf?id=b9tUk-f_aG) <br><sub> **DINOSAUR:** Using slot attention with self-supervised DINO features to discover objects on real-world data. </sub> | [Code](https://github.com/amazon-science/object-centric-learning-framework) | [OpenReview](https://openreview.net/forum?id=b9tUk-f_aG) | :white_check_mark:
**2023** | **ICLR** | [Improving Object-centric Learning with Query Optimization](https://openreview.net/pdf?id=_-FN9mJsgg) <br><sub> **BO-QSA:** Extending slot attention, outperforming previous baselines on both synthetic and real images. </sub> | [Code](https://github.com/YuLiu-LY/BO-QSA) | [OpenReview](https://openreview.net/forum?id=_-FN9mJsgg) | :white_check_mark:
**2023** | **ICLR** | [Learning to Reason over Visual Objects](https://openreview.net/pdf?id=uR6x8Be7o_M) <br><sub> **STSN:** Combining slot attention, an objectcentric encoding method, and a transformer reasoning module. </sub> | | [OpenReview](https://openreview.net/forum?id=uR6x8Be7o_M) |
**2023** | **ICLR** | [Learning What and Where: Disentangling Location and Identity Tracking Without Supervision](https://openreview.net/pdf?id=NeDc-Ak-H_) <br><sub> **Loci:** An unsupervised disentangled location and identity tracking system, which excels on the CATER and related object tracking challenges featuring emergent object permanence and stable entity disentanglement via fully unsupervised learning. </sub> | [Code](https://github.com/CognitiveModeling/Loci) | [OpenReview](https://openreview.net/forum?id=NeDc-Ak-H_) | :white_check_mark:
**2023** | **ICLR** | [Neural Constraint Satisfaction: Hierarchical Abstraction for Combinatorial Generalization in Object Rearrangement](https://arxiv.org/pdf/2303.11373.pdf) <br><sub> **NCS:** Demonstrating how to generalize over a combinatorially large space of rearrangement tasks from only pixel observations by constructing from video demonstrations a factorized transition graph over entity state transitions that we use for control. </sub> | [Code](https://sites.google.com/view/neural-constraint-satisfaction/home) | [OpenReview](https://openreview.net/forum?id=fGG6vHp3W9W) | 
**2023** | **ICLR** | [Robust and Controllable Object-Centric Learning through Energy-based Models](https://openreview.net/pdf?id=wcNtbEtcGIC) <br><sub> **EGO:** A conceptually simple and general approach to learning object-centric representation through energy-based model. </sub> | | [OpenReview](https://openreview.net/forum?id=wcNtbEtcGIC) | 
**2023** | **ICLR** | [Neural Groundplans: Persistent Neural Scene Representations from a Single Image](https://arxiv.org/pdf/2207.11232.pdf) <br><sub> **GroundPlans:** Training a self-supervised model that learns to map a single image to a 3D representation of the scene, with separate components for the immovable and movable 3D regions. </sub> | [Code](https://prafullsharma.net/neural_groundplans/) | [OpenReview](https://openreview.net/forum?id=Pza24zf9FpS) | 
**2023** | **ICLR** | [Neural Systematic Binder](https://arxiv.org/pdf/2211.01177.pdf) <br><sub> **NSB:** Proposing a novel object-centric representation called block-slots, which unlike the conventional slots, provides within-slot disentanglement via vector-formed factor representations.  </sub> | [Code](https://github.com/singhgautam/sysbinder) | [OpenReview](https://openreview.net/forum?id=ZPHE4fht19t) | 
**2023** | **ICLR** | [SlotFormer: Unsupervised Visual Dynamics Simulation with Object-Centric Models](https://arxiv.org/pdf/2210.05861.pdf) <br><sub> **SlotFormer:** Proposing a general Transformer-based dynamic model to enable consistent future prediction in object-centric models. </sub> | [Code](https://github.com/pairlab/SlotFormer) | [OpenReview](https://openreview.net/forum?id=TFbwV6I0VLg) | 
**2023** | **CLeaR** | [Causal Triplet: An Open Challenge for Intervention-centric Causal Representation Learning](https://openreview.net/pdf?id=HAYU8TRYTCb) <br><sub> **CausalTriplet:** Presenting a causal representation learning benchmark that is close to realistic settings and empirically demonstrate the strengths and weaknesses of recent hypotheses and methods. </sub>   | [Code](https://github.com/CausalTriplet/causaltriplet) | [OpenReview](https://openreview.net/forum?id=HAYU8TRYTCb) | :white_check_mark:
**2023** | **NeurIPS** | [SlotDiffusion: Object-Centric Generative Modeling with Diffusion Models](https://arxiv.org/pdf/2305.11281.pdf) <br><sub> **SlotDiff:** An object-centric latent diffusion model designed for both synthetic/real-world image and video data.  </sub> | [Code](https://slotdiffusion.github.io/) | |  :white_check_mark:
**2023** | **arXiv** | [Object-Centric Slot Diffusion](https://arxiv.org/pdf/2303.10834.pdf) <br><sub> **LSD:** Replacing the conventional slot decoders with a latent diffusion model conditioned on the object slots. </sub> | [Code](https://latentslotdiffusion.github.io/) | | :white_check_mark:
**2023** | **arXiv** | [Sensitivity of Slot-Based Object-Centric Models to their Number of Slots](https://arxiv.org/pdf/2305.18890.pdf) <br><sub> **NumSlots:** Proposing to use analogs to precision and recall based on the Adjusted Rand Index to accurately quantify model behavior over a large range of slots. </sub> 
**2023** | **arXiv** | [Spotlight Attention: Robust Object-Centric Learning With a Spatial Locality Prior](https://arxiv.org/pdf/2305.19550.pdf) <br><sub> **LSP:** Incorporating a spatial-locality prior into state-of-the-art object-centric vision models, and obtaining significant improvements in segmenting objects in both synthetic and real-world datasets. </sub> | | | :white_check_mark:
**2023** | **arXiv** | [Unsupervised Open-Vocabulary Object Localization in Videos](https://arxiv.org/pdf/2309.09858v1.pdf) <br><sub> **RWV-OCL:** Proposing an unsupervised approach to localize and name objects in real-world videos. </sub> | | | :white_check_mark: | :white_check_mark:


### Year 2022
    
**Year** | **Publication** | **Title** | **Source** | **Forum** |  **Real-World?** | **Using VLMs?**
:-: | :-:| :- | :-: | :-: | :-:|  :-:
**2022** | **TMLR** | [Complex-Valued Autoencoders for Object Discovery](https://arxiv.org/pdf/2204.02075.pdf) <br><sub> **CAE:** Introducing complex-valued activations into a convolutional autoencoder, it learns to encode feature information in the activations’ magnitudes and object affiliation in their phase values. </sub> | [Code](https://github.com/loeweX/ComplexAutoEncoder) | | 
**2022** | **NeurIPSw** | [Object-Centric Causal Representation Learning](https://openreview.net/pdf?id=RaIy9t062cD) <br><sub> **CausalOCL:** Advancing causal representation learning by developing an object-centric architecture that leverages weak supervision from sparse perturbations to disentangle each object's properties. </sub> | | [OpenReview](https://openreview.net/forum?id=RaIy9t062cD)
**2022** | **NeurIPSw** | [Unlocking Slot Attention by Changing Optimal Transport Costs](https://arxiv.org/pdf/2301.13197.pdf) <br><sub> **SA-MESH:** Slot attention can do tiebreaking by changing the costs for optimal transport to minimize entropy, which improves results significantly on object detection. </sub> | [Code](https://github.com/davzha/MESH) | [OpenReview](https://openreview.net/forum?id=27L6M45WI9) | 
**2022** | **NeurIPS** | [Visual Concepts Tokenization](https://arxiv.org/pdf/2205.10093.pdf) <br><sub> **VCT:** Proposing an unsupervised transformer-based Visual Concepts Tokenization framework, to perceive an image into a set of disentangled visual concept tokens, with each concept token responding to one type of independent visual concept. </sub> | [Code](https://github.com/thomasmry/VCT) | [OpenReview](https://openreview.net/forum?id=rWgfLdqVVl_&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DNeurIPS.cc%2F2022%2FConference%2FAuthors%23your-submissions)) | :white_check_mark:
**2022** | **NeurIPS** | [Unsupervised Multi-object Segmentation by Predicting Probable Motion Patterns](https://arxiv.org/pdf/2210.12148.pdf) <br><sub> **PPMP:** Segmenting independent objects in still images by predicting regions that contain motion patterns likely to arise from such objects. </sub> | [Code](https://www.robots.ox.ac.uk/~vgg/research/ppmp/) | [OpenReview](https://openreview.net/forum?id=_w2-1nXNjvv) | :white_check_mark:
**2022** | **NeurIPS** | [Unsupervised Causal Generative Understanding of Images](https://openreview.net/pdf?id=VvOcK2DGM7G) <br><sub> **UCGU:** A framework for unsupervised object-centric 3D scene understanding that generalizes robustly to out-of-distribution images. </sub> | | [OpenReview](https://openreview.net/forum?id=VvOcK2DGM7G) | 
**2022** | **NeurIPS** | [SAVi++: Towards End-to-End Object-Centric Learning from Real-World Videos](https://arxiv.org/pdf/2206.07764.pdf) <br><sub> **SAVi++:** An object-centric video model which is trained to predict depth signals from a slot-based video representation. SAVi++ is able to learn emergent object segmentation and tracking from videos in the real-world Waymo Open dataset. </sub> | [Code](https://github.com/google-research/slot-attention-video/) | [OpenReview](https://openreview.net/forum?id=fT9W53lLxNS) | :white_check_mark:
**2022** | **NeurIPS** | [Promising or Elusive? Unsupervised Object Segmentation from Real-world Single Images](https://arxiv.org/pdf/2210.02324.pdf) <br><sub> **UnsupObjSeg:** Training more than 200 models to demonstrate that current unsupervised methods cannot segment generic objects from real-world single images, unless the complex objectness biases are removed. </sub> | [Code](https://github.com/vLAR-group/UnsupObjSeg) | [OpenReview](https://openreview.net/forum?id=DzPWTwfby5d) | :white_check_mark:
**2022** | **NeurIPS** | [Object Scene Representation Transformer](https://arxiv.org/pdf/2206.06922.pdf) <br><sub> **OSRT:** Proposing Object Scene Representation Transformer, a highly efficient 3D-centric model in which individual object representations naturally emerge through novel view synthesis. </sub> | [Code](https://osrt-paper.github.io/#code) | [OpenReview](https://openreview.net/forum?id=znNmsN_O7Sh) | 
**2022** | **NeurIPS** | [Object Representations as Fixed Points: Training Iterative Refinement Algorithms with Implicit Differentiation](https://arxiv.org/pdf/2207.00787.pdf) <br><sub> **iSlotAttns:** Improving the training of object-centric learning methods by applying implicit differentiation to slot attention. </sub> | [Code](https://sites.google.com/view/implicit-slot-attention) | [OpenReview](https://openreview.net/forum?id=-5rFUTO2NWe) |
**2022** | **NeurIPS** | [Simple Unsupervised Object-Centric Learning for Complex and Naturalistic Videos](https://arxiv.org/pdf/2205.14065.pdf) <br><sub> **STEVE:** A simple fully unsupervised model for object-centric learning in complex and naturalistic videos. </sub> | [Code](https://sites.google.com/view/slot-transformer-for-videos) | [OpenReview](https://openreview.net/forum?id=eYfIM88MTUE) | :white_check_mark:
**2022** | **ICML** | [Unsupervised Image Representation Learning with Deep Latent Particles](https://arxiv.org/pdf/2205.15821.pdf) <br><sub> **DLP:** Decomposing the visual input into low-dimensional latent particles, where each particle is described by its spatial location and features of its surrounding region. </sub> | [Code](https://taldatech.github.io/deep-latent-particles-web/) | [PMLR](https://proceedings.mlr.press/v162/daniel22a.html) | :white_check_mark:
**2022** | **ICML** | [Toward Compositional Generalization in Object-Oriented World Modeling](https://arxiv.org/pdf/2204.13661.pdf) <br><sub> **HOWM:** Formalizing the compositional generalization problem with an algebraic approach and studying how a world model can achieve that.  </sub> | [Code](https://lfzhao.com/publication/2022-oowm/) | [PMLR](https://proceedings.mlr.press/v162/zhao22b.html)
**2022** | **ICML** | [COAT: Measuring Object Compositionality in Emergent Representations](https://proceedings.mlr.press/v162/xie22b/xie22b.pdf) <br><sub> **COAT:** Directly measuring compositionality in the representation space as a form of objections, making such evaluations tractable for a wider class of models. </sub> | | [PMLR](https://proceedings.mlr.press/v162/xie22b.html)
**2022** | **ICML** | [Generalization and Robustness Implications in Object-Centric Learning](https://proceedings.mlr.press/v162/dittadi22a/dittadi22a.pdf) <br><sub> **OCLLib:** when the distribution shift affects the input in a less structured manner, robustness in terms of segmentation and downstream task performance may vary significantly across models and distribution shifts. </sub> | [Code](https://github.com/addtt/object-centric-library) | [PMLR](https://proceedings.mlr.press/v162/dittadi22a.html)
**2022** | **CVPR** | [HP-Capsule: Unsupervised Face Part Discovery by Hierarchical Parsing Capsule Network](https://arxiv.org/pdf/2203.10699.pdf) <br><sub> **HPCapsule:** Extending the application of capsule networks from digits to human faces and takes a step forward to show how the neural networks understand homologous objects without human intervention. </sub> |  | [CVF Proceedings](https://openaccess.thecvf.com/content/CVPR2022/html/Yu_HP-Capsule_Unsupervised_Face_Part_Discovery_by_Hierarchical_Parsing_Capsule_Network_CVPR_2022_paper.html) | :white_check_mark:
**2022** | **CVPR** | [Discovering Objects that Can Move](https://arxiv.org/pdf/2203.10159.pdf) <br><sub> **ObjMove:** Simplifying auto-encoders' architecture, and augmenting the resulting model with a weak learning signal from general motion segmentation algorithms. </sub> | [Code](https://github.com/zpbao/Discovery_Obj_Move/) | [CVF Proceedings](https://openaccess.thecvf.com/content/CVPR2022/html/Bao_Discovering_Objects_That_Can_Move_CVPR_2022_paper.html) | :white_check_mark:
**2022** | **ICLRw** | [Towards Self-Supervised Learning of Global and Object-Centric Representations](https://arxiv.org/pdf/2203.05997.pdf) <br><sub> **SSL-OCL:** Discussing the interplay of attention, global and per-object contrastive losses, and data augmentation for learning object representations through self-supervision. </sub> | [Code](https://github.com/baldassarreFe/iclr-osc-22) | [OpenReview](https://openreview.net/forum?id=SRfVvBuI9xq)
**2022** | **ICLR** | [Illiterate DALL-E Learns to Compose](https://arxiv.org/pdf/2110.11405.pdf) <br><sub> **SLATE:** To learn compositional slot-based representation of an image and perform slot composition for zero-shot novel image generation. </sub> | [Code](https://sites.google.com/view/slate-autoencoder) | [OpenReview](https://openreview.net/forum?id=h0OYV0We3oh) |  :white_check_mark: |  :white_check_mark:
**2022** | **ICLR** | [Conditional Object-Centric Learning from Video](https://arxiv.org/pdf/2111.12594.pdf) <br><sub> **SAVi:** A sequential extension to Slot Attention.  </sub> | [Code](https://github.com/google-research/slot-attention-video/) | [OpenReview](https://openreview.net/forum?id=aD7uesX1GF_) 
**2022** | **ICLR** | [Unsupervised Discovery of Object Radiance Fields](https://arxiv.org/pdf/2107.07905.pdf) <br><sub> **uORF:** Inferring object-centric factorized 3D scene representations from a single image, learned without 3D geometry or segmentation supervision. </sub> | [Code](https://github.com/KovenYu/uORF) | [OpenReview](https://openreview.net/forum?id=rwE8SshAlxw) | :white_check_mark:
**2022** | **ICLR** | [Evaluating Disentanglement of Structured Representations](https://arxiv.org/pdf/2101.04041.pdf) <br><sub> **SLR-Metric:** Introducing the first metric for evaluating disentanglement at individual hierarchy levels of a structured latent representation, and applying it to object-centric generative models. </sub> | | [OpenReview](https://openreview.net/forum?id=SLz5sZjacp)
**2022** | **CLeaR** | [VIM: Variational Independent Modules for Video Prediction](https://openreview.net/pdf?id=bDOU-vlPM8n) <br><sub> **VIM:** Defining an object-centric video prediction model that learns modular object dynamics and displays good compositional generalization skills. </sub> | | [OpenReview](https://openreview.net/forum?id=bDOU-vlPM8n)
**2022** | **SIGGRAPH** | [Sprite-from-Sprite: Cartoon Animation Decomposition with Self-supervised Sprite Estimation](https://lllyasviel.github.io/GitPageToonDecompose/toondecompose.pdf) <br><sub> **ToonDecompose:** Decomposing a cartoon animation into several components (_a.k.a._, "Sprites" in terminology), where the optical flow is the only external prior used for model training.  </sub> | [Code](https://github.com/lllyasviel/ToonDecompose) | | :white_check_mark: 

### Year 2021
    
**Year** | **Publication** | **Title** | **Source** | **Forum** |  **Real-World?** | **Using VLMs?** 
:-: | :-:| :- | :-: | :-: | :-:|  :-:
**2021** | **NeurIPS** | [Unsupervised Foreground Extraction via Deep Region Competition](https://arxiv.org/pdf/2110.15497.pdf) <br><sub> **DRC:** An unsupervised foreground extraction algorithm to unseen objects, in both synthetic and low-resolution real-world scenes. </sub> | [Code](https://github.com/yuPeiyu98/DRC) | [OpenReview](https://openreview.net/forum?id=tu5Wg41hWl_) | :white_check_mark:
**2021** | **NeurIPS** | [SIMONe: View-Invariant, Temporally-Abstracted Object Representations via Unsupervised Video Decomposition](https://arxiv.org/pdf/2106.03849.pdf) <br><sub> **SIMONe:** A video scene model which separates the time-invariant, object-level contents of the scene from global time-varying elements such as viewpoint. </sub> | [Code](https://sites.google.com/view/simone-scene-understanding/) | [OpenReview](https://openreview.net/forum?id=YSzTMntO1KY)
**2021** | **NeurIPS** | [Object-Centric Representation Learning with Generative Spatial-Temporal Factorization](https://arxiv.org/pdf/2111.05393.pdf) <br><sub> **DyMON:** Extending unsupervised object-centric representation learning to multi-view-dynamic-scene settings. </sub> |  | [OpenReview](https://openreview.net/forum?id=cA8Yp87yTiR) | :white_check_mark:
**2021** | **NeurIPS** | [Neural Production Systems](https://arxiv.org/pdf/2103.01937.pdf) <br><sub> **NPS:** Modelling sparse interactions among seperate entities using dynamically selected rules. </sub> | | [OpenReview](https://openreview.net/forum?id=xQGYquca0gB)
**2021** | **NeurIPS** | [MarioNette: Self-Supervised Sprite Learning](https://arxiv.org/pdf/2104.14553.pdf) <br><sub> **MarioNette:** Jointly learning a dictionary of texture patches and training a network that places them onto a canvas, effectively deconstructing sprite-based content video content. </sub> | [Code](https://github.com/dmsm/MarioNette) | [OpenReview](https://openreview.net/forum?id=3zP6RrQtNa) | :white_check_mark:
**2021** | **NeurIPS** | [GENESIS-V2: Inferring Unordered Object Representations without Iterative Refinement](https://arxiv.org/pdf/2104.09958v2.pdf) <br><sub> **GENESISv2:** Presenting an improved object-centric generative model of visual scenes that uses a stochastic clustering algorithm for inferring object representations without imposing a fixed ordering on objects or using iterative refinement. </sub> | [Code](https://github.com/applied-ai-lab/genesis) | [OpenReview](https://openreview.net/forum?id=nRBZWEUhIhW) | :white_check_mark:
**2021** | **NeurIPS** | [Dynamic Visual Reasoning by Learning Differentiable Physics Models from Video and Language](https://arxiv.org/pdf/2110.15358.pdf) <br><sub> **VRDP:** A unified framework to learn visual concepts and infer physics models of objects and their interactions jointly from videos and language. </sub> | [Code](http://vrdp.csail.mit.edu/) | [OpenReview](https://openreview.net/forum?id=lk1ORT35tbi) | :white_check_mark: | :white_check_mark:
**2021** | **NeurIPS** | [Attention over Learned Object Embeddings Enables Complex Visual Reasoning](https://arxiv.org/pdf/2012.08508.pdf) <br><sub> **ALOE:** A general framework of attention over learned object embeddings outperforms task-specific models on complex visual reasoning tasks thought to be too challenging for general models. </sub> | [Code](https://github.com/deepmind/deepmind-research/tree/master/object_attention_for_reasoning) | [OpenReview](https://openreview.net/forum?id=lHmhW2zmVN)
**2021** | **ICML** | [Efficient Iterative Amortized Inference for Learning Symmetric and Disentangled Multi-Object Representations](https://arxiv.org/pdf/2106.03630.pdf) <br><sub> **EfficientMORL:** A framework for efficient multi-object representation learning consisting of a hierarchical VAE and a lightweight network for iterative refinement. </sub> | [Code](https://github.com/pemami4911/EfficientMORL) | [PMLR](https://proceedings.mlr.press/v139/emami21a.html)
**2021** | **ICCV** | [PARTS: Unsupervised segmentation with slots, attention and independence maximization](https://openaccess.thecvf.com/content/ICCV2021/papers/Zoran_PARTS_Unsupervised_Segmentation_With_Slots_Attention_and_Independence_Maximization_ICCV_2021_paper.pdf) <br><sub> **PARTS:** Introducing a recurrent slot-attention like encoder which allows for top-down influence during inference, to both 3D synthetic and real-world robotics' scenes. </sub> | | [CVF Proceedings](https://openaccess.thecvf.com/content/ICCV2021/html/Zoran_PARTS_Unsupervised_Segmentation_With_Slots_Attention_and_Independence_Maximization_ICCV_2021_paper.html) | :white_check_mark:
**2021** | **ICLR** | [Self-supervised Visual Reinforcement Learning with Object-centric Representations](https://openreview.net/pdf?id=xppLmXCbOw1) <br><sub> **SMORL:** The combination of object-centric representations and goal-conditioned attention policies helps autonomous agents to learn useful multi-task policies in visual multi-object environments. </sub> | [Code](https://github.com/martius-lab/SMORL) | [OpenReview](https://openreview.net/forum?id=xppLmXCbOw1)

### Year 2020
    
**Year** | **Publication** | **Title** | **Source** | **Forum** |  **Real-World?**  | **Using VLMs?**
:-: | :-:| :- | :-: | :-: | :-:|  :-:
**2020** | **NeurIPS** | [Learning Object-Centric Representations of Multi-Object Scenes from Multiple Views](https://arxiv.org/pdf/2111.07117.pdf) <br><sub> **MulMON:** Extending IODINE with Generative Query Network (GQN)-based module, for unsupervised object segmentation in 2D multi-view synthetic data. </sub> | [Code](https://github.com/NanboLi/MulMON) | [NeurIPS Proceedings](https://proceedings.neurips.cc/paper_files/paper/2020/hash/3d9dabe52805a1ea21864b09f3397593-Abstract.html)
**2020** | **NeurIPS** | [Object-Centric Learning with Slot Attention](https://arxiv.org/pdf/2006.15055.pdf) <br><sub> **SLotAttns:** Learning abstract representations of Convolutional Neural Networks (CNNs) for unsupervised object segmentation in 2D synthetic data. </sub> | [Code](https://github.com/google-research/google-research/tree/master/slot_attention) | [NeurIPS Proceedings](https://proceedings.neurips.cc/paper_files/paper/2020/hash/8511df98c02ab60aea1b2356c013bc0f-Abstract.html)
**2020** | **NeurIPS** | [Unsupervised object-centric video generation and decomposition in 3D](https://arxiv.org/pdf/2007.06705.pdf) <br><sub> **O3V:** Generation and decomposition of 3D synthetic scenes with 2D synthetic videos. </sub> | [Code](https://www.pmh47.net/o3v/) | [NeurIPS Proceedings](https://proceedings.neurips.cc/paper_files/paper/2020/hash/20125fd9b2d43e340a35fb0278da235d-Abstract.html)
**2020** | **NeurIPS** | [BlockGAN: Learning 3D Object-aware Scene Representations from Unlabelled Images](https://arxiv.org/pdf/2002.08988.pdf) <br><sub> **BlockGAN:** Representing 3D synthetic objects using GANs based on 2D synthetic data. </sub> | [Code](https://www.monkeyoverflow.com/#/blockgan/) | [NeurIPS Proceedings](https://proceedings.neurips.cc/paper_files/paper/2020/hash/4b29fa4efe4fb7bc667c7b301b74d52d-Abstract.html) | :white_check_mark:
**2020** | **ICLR** | [GENESIS: Generative Scene Inference and Sampling with Object-Centric Latent Representations](https://openreview.net/pdf?id=BkxfaTVFwH) <br><sub> **GENESIS:** Modeling relationship of scene components for decomposition and generation of 3D synthetic scenes. </sub> | [Code](https://github.com/applied-ai-lab/genesis) | [OpenReview](https://openreview.net/forum?id=BkxfaTVFwH) | 
**2020** | **ICLR** | [Structured Object-Aware Physics Prediction for Video Modeling and Planning](https://openreview.net/pdf?id=B1e-kxSKDH) <br><sub> **STOVE:** Proposing a structured object-aware video prediction model, which explicitly reasons about objects and demonstrate that it provides high-quality long term video predictions for planning. </sub> | [Code](https://github.com/jlko/STOVE) | [OpenReview](https://openreview.net/forum?id=B1e-kxSKDH)
**2020** | **ICLR** | [SCALOR: Generative World Models with Scalable Object Representations](https://openreview.net/pdf?id=SJxrKgStDH) <br><sub> **SCALOR:** Generation of  both synthetic and  low-resolution real-world scenes where a large number of objects exist. </sub> | [Code](https://github.com/JindongJiang/SCALOR) | [OpenReview](https://openreview.net/forum?id=SJxrKgStDH) | :white_check_mark:
**2020** | **ICML** | [Improving Generative Imagination in Object-Centric World Models](https://arxiv.org/pdf/2010.02054.pdf) <br><sub> **G-SWM:** Modeling multi-modal uncertainty and situation-awareness for 3D synthetic scene generation. </sub> | [Code](https://github.com/zhixuan-lin/G-SWM) | [PMLR](https://proceedings.mlr.press/v119/lin20f.html)

### Year 2019
    
**Year** | **Publication** | **Title** | **Source** | **Forum** |  **Real-World?**  | **Using VLMs?**
:-: | :-:| :- | :-: | :-: | :-:|  :-:
**2019** | **ICML** | [Multi-Object Representation Learning with Iterative Variational Inference](https://arxiv.org/pdf/1903.00450.pdf) <br><sub> **IODINE:** Learning multi-object disentangled representations for unsupervised object segmentation in 2D synthetic data. </sub> | [Code](https://github.com/deepmind/deepmind-research/tree/master/iodine) | [PMLR](https://proceedings.mlr.press/v97/greff19a.html) | :white_check_mark:
**2019** | **arXiv** | [MONet: Unsupervised Scene Decomposition and Representation](https://arxiv.org/pdf/1901.11390.pdf)  <br><sub> **MoNet:** Training a Variational Autoencoder (VAE) and a recurrent attention network to decompose and represent 3D synthetic scenes. </sub> | [Code](https://github.com/baudm/MONet-pytorch)

## Contact
    
Feel free to drop an e-mail to yi23zhang.2022@gmail.com
