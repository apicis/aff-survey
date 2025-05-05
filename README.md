# Visual Affordances: Enabling robots to understand object functionality

[[arXiv](...)]
[[webpage](https://apicis.github.io/aff-survey/)]

## Table of Contents
1. [Related works](#related-works)
    1. [Surveys](#surveys)
    2. [Task-driven object detection and segmentation](#task-driven-detection)
    3. [Affordance classification](#affordance-classification)
    4. [Affordance detection and segmentation](#affordance-detection)
    5. [Affordance grounding](#affordance-grounding)
    6. [Grasping detection](#grasping-detection)
    7. [End-effector pose estimation and synthesis](#end-effector-pose)
2. [Contributing](#contributing)
3. [Credits](#credits)
4. [Enquiries, Question and Comments](#enquiries-question-and-comments)
5. [License](#license)

## Related works <a name="related-works"></a>

<details>
<summary>  Surveys <a name="surveys"></a></summary>

- [Visual affordance and function understanding](https://dl.acm.org/doi/10.1145/3446370)
- [A survey of visual affordance recognition based on deep learning](https://ieeexplore.ieee.org/document/10171410)
- [Affordances in Robotic Tasks -- A Survey](https://arxiv.org/abs/2004.07400)

</details>

<details>
<summary> Task-driven object detection and segmentation <a name="task-driven-detection"></a></summary>

- [What object should i use? - Task driven object detection](https://arxiv.org/abs/1904.03000)
- [TaskCLIP: Extend Large Vision-Language Model for Task Oriented Object Detection](https://arxiv.org/abs/2403.08108)
- [VLTP: Vision-Language Guided Token Pruning for Task-Oriented Segmentation](https://arxiv.org/abs/2409.08464)
- [TOIST: Task oriented instance segmentation transformer with noun-pronoun distillation](https://arxiv.org/abs/2210.10775)
- [CoTDet: Affordance Knowledge Prompting for Task Driven Object Detection](https://arxiv.org/abs/2309.01093)

</details>

<details>
<summary> Affordance classification <a name="affordance-classification"></a></summary>

- [Visual object-action recognition: Inferring object affordances from human demonstration](https://www.sciencedirect.com/science/article/pii/S107731421000175X) 
- [Learning visual object categories for robot affordance prediction](https://journals.sagepub.com/doi/abs/10.1177/0278364909356602)
- [High-level object affordance recognition](https://ieeexplore.ieee.org/document/8812515)
- [Functional object descriptors for human activity modeling](https://ieeexplore.ieee.org/document/6630736)

</details>

<details>
<summary> Affordance detection and segmentation <a name="affordance-detection"></a></summary>

- [AffordanceNet: An end-to-end deep learning approach for object affordance detection](https://arxiv.org/pdf/1709.07326)
- [Bayesian deep learning for affordance segmentation in images](https://arxiv.org/abs/2303.00871)
- [Learning affordance segmentation: An investigative study](https://ieeexplore.ieee.org/document/9363390)
- [Are standard object segmentation models sufficient for learning affordance segmentation?](https://arxiv.org/pdf/2107.02095)
- [Object affordance detection with boundary-preserving network for robotic manipulation task](https://link.springer.com/article/10.1007/s00521-022-07446-4)
- [A new semantic edge aware network for object affordance detection](https://link.springer.com/article/10.1007/s10846-021-01525-9)
- [Object-based affordances detection with convolutional neural networks and dense conditional random fields](https://ieeexplore.ieee.org/document/8206484/)
- [Weakly supervised affordance detection](https://openaccess.thecvf.com/content_cvpr_2017/html/Sawatzky_Weakly_Supervised_Affordance_CVPR_2017_paper.html)
- [Adosmnet: a novel visual affordance detection network with object shape mask guided feature encoders](https://www.researchgate.net/publication/374003529_ADOSMNet_a_novel_visual_affordance_detection_network_with_object_shape_mask_guided_feature_encoders)
- [Detecting object affordances with convolutional neural networks](https://ieeexplore.ieee.org/document/7759429)
- [FPHA-Afford: A domain-specific benchmark dataset for occluded object affordance estimation in human-object-robot interaction](https://www.researchgate.net/publication/341616812_FPHA-Afford_A_Domain-Specific_Benchmark_Dataset_for_Occluded_Object_Affordance_Estimation_in_Human-Object-Robot_Interaction)
- [Affordance segmentation of hand-occluded containers from exocentric images](https://arxiv.org/pdf/2308.11233)
- [Visual affordance detection using an efficient attention convolutional neural network](https://www.sciencedirect.com/science/article/pii/S0925231221000278?casa_token=aVmHyZiJ7yIAAAAA:9DJyfZW_scvf76oX-b-0I5PGU_QmZ9dWfGsFsymZT99H7xlWl313ZbogB1uHwj7XybCp6f1N)
- [Multi-scale fusion and global semantic encoding for affordance detection](https://ieeexplore.ieee.org/document/9892363)
- [Object affordance detection with relationship-aware network](https://link.springer.com/article/10.1007/s00521-019-04336-0)
- [Strap: Structured object affordance segmentation with point supervision](https://arxiv.org/pdf/2304.08492)
- [Segmenting object affordances: Reproducibility and sensitivity to scale](https://arxiv.org/abs/2409.01814)

</details>

<details>
<summary> Affordance grounding <a name="affordance-grounding"></a></summary>

- [Understanding 3d object interaction from a single image](https://arxiv.org/abs/2305.09664)
- [Locate: Localize and transfer object parts for weakly supervised affordance grounding](https://arxiv.org/abs/2303.09665)
- [One-shot transfer of affordance regions? affcorrs!](https://arxiv.org/abs/2311.17776)
- [Demo2vec: Reasoning object affordances from online video](https://openaccess.thecvf.com/content_cvpr_2018/html/Fang_Demo2Vec_Reasoning_Object_CVPR_2018_paper.html)
- [Grounded human-object interaction hotspots from video](https://arxiv.org/abs/1812.04558)
- [Oval-prompt: Open-vocabulary affordance localization for robot manipulation through LLM affordance-grounding](https://arxiv.org/abs/2404.11000)
- [What does clip know about peeling a banana?](https://arxiv.org/abs/2404.12015)
- [One-shot open affordance learning with foundation model](https://arxiv.org/abs/2209.07147)
- [Learning affordance grounding from exocentric image](https://arxiv.org/abs/2203.09905)
- [Affordancellm: Grounding affordance from vision language model](https://arxiv.org/abs/2401.06341)

</details>

<details>

<summary> Grasping detection <a name="grasping-detection"></a></summary>

- [Deep Learning for Detecting Robotic Grasps](https://arxiv.org/abs/1301.3592)
- [Real-Time Grasp Detection Using Convolutional Neural Networks](https://arxiv.org/abs/1412.3128)
- [Robotic Grasp Detection using Deep Convolutional Neural Networks](https://arxiv.org/abs/1611.08036)
- [GraspNet: An Efficient Convolutional Neural Network for Real-time Grasp Detection for Low-powered Devices](https://www.ijcai.org/proceedings/2018/0677.pdf)
- [Real-world Multi-object, Multi-grasp Detection](https://arxiv.org/abs/1802.00520)
- [ROI-based Robotic Grasp Detection for Object Overlapping Scenes](https://arxiv.org/abs/1808.10313)
- [End-to-end Trainable Deep Neural Network for Robotic Grasp Detection and Semantic Segmentation from RGB](https://arxiv.org/abs/2107.05287)
- [Jacquard: A Large Scale Dataset for Robotic Grasp Detection](https://arxiv.org/abs/1803.11469)

</details>

<details>

<summary> End-effector pose estimation and synthesis <a name="end-effector-pose"></a></summary>

- [Ganhand: Predicting human grasp affordances in multi-object scenes](https://openaccess.thecvf.com/content_CVPR_2020/html/Corona_GanHand_Predicting_Human_Grasp_Affordances_in_Multi-Object_Scenes_CVPR_2020_paper.html)
- [Multi-FinGAN: Generative Coarse-To-Fine Sampling of Multi-Finger Grasps](https://arxiv.org/abs/2012.09696)
- [Affordance diffusion: Synthesizing hand-object interaction](https://arxiv.org/abs/2303.12538)

</details>

## Contributing <a name="contributing"></a>

If you find an error, if you want to suggest a new feature or a change, you can use the issues tab to raise an issue with the appropriate label. 

Complete and full updates can be found in [CHANGELOG.md](CHANGELOG.md). The file follows the guidelines of [https://keepachangelog.com/en/1.1.0/](https://keepachangelog.com/en/1.1.0/).


## Credits <a name="credits"></a>


```
```


## Enquiries, Question and Comments <a name="enquiries-question-and-comments"></a>

If you have any further enquiries, question, or comments, or you would like to file a bug report or a feature request, please use the Github issue tracker. 


## Licence <a name="license"></a>
This work is licensed under the MIT License.  To view a copy of this license, see [LICENSE](LICENSE).
