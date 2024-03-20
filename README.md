
# EMCG

### [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9276462)

> **Learning Fundamental Visual Concepts Based on Evolved Multi-Edge Concept Graph** <br>
> Hang Wang<sup>1,2</sup> | 
Youtian Du<sup>1</sup> | 
Guangxun Zhang<sup>1</sup> | 
Zhongmin Cai<sup>1</sup> | 
[Chang Su](https://sites.google.com/view/changsu/home)<sup>3</sup>

<sup>1</sup>Xi'an Jiaotong University, <sup>2</sup>The Hong Kong Polytechnic University, <sup>3</sup>Cornell University <br>
> In IEEE Transactions on Multimedia (TMM), 2020.


Paper, codes and pretained models will be released soon. 






### Update
- **2024.03.20**: Repo is released.


### Abstract
In general, visual media comprises a set of elements of basic semantics, named fundamental visual concepts, that may not be semantically decomposed, such as objects, scenes and actions. This paper proposes a dynamic learning framework for fundamental visual concept learning from image-textual description paired data based on an evolved multi-edge concept graph (EMCG). First, we construct a multi-edge concept graph to represent the relationships between visual concept instances, in which we introduce two types of edges named visual edges and semantic edges to describe the connection strength in terms of visual appearance and semantic content. Second, we evolve the graph by updating connection strength based on the predicted results of concept learning. Finally, we present a growth algorithm for the multi-edge concept graph to handle cross-dataset concept learning. Driven by the predictions, the multi-edge concept graph can dynamically evolve over time by adjusting the connection strength to adapt better to the observations. In addition, our approach can be considered a weakly-supervised learning algorithm since no labeled concepts are employed for learning. Experimental results demonstrate that evolution can significantly improve the learning of fundamental visual concepts by 14.2%, 7.9% and 12.7% in terms of F1-score for the MSRC, VOC2012 and MSCOCO datasets, respectively, and that the proposed EMCG approach largely outperforms the compared approaches. Single image super-resolution (SISR) with generative adversarial networks (GAN) has recently attracted increasing attention due to its potentials to generate rich details. However, the training of GAN is unstable, and it often introduces many perceptually unpleasant artifacts along with the generated details. In this paper, we demonstrate that it is possible to train a GAN-based SISR model which can stably generate perceptually realistic details while inhibiting visual artifacts. Based on the observation that the local statistics (e.g., residual variance) of artifact areas are often different from the areas of perceptually friendly details, we develop a framework to discriminate between GAN-generated artifacts and realistic details, and consequently generate an artifact map to regularize and stabilize the model training process. Our proposed locally discriminative learning (LDL) method is simple yet effective, which can be easily plugged in off-the-shelf SISR methods and boost their performance. Experiments demonstrate that LDL outperforms the state-of-the-art GAN based SISR methods, achieving not only higher reconstruction accuracy but also superior perceptual quality on both synthetic and real-world datasets.


### License

This project is released under the MIT license.


### Contact
If you have any questions, please feel free to contact: cshwang@comp.polyu.edu.hk



### Citation
```
@ARTICLE{9276462,
  author={Wang, Hang and Du, Youtian and Zhang, Guangxun and Cai, Zhongmin and Su, Chang},
  journal={IEEE Transactions on Multimedia}, 
  title={Learning Fundamental Visual Concepts Based on Evolved Multi-Edge Concept Graph}, 
  year={2021},
  volume={23},
  number={},
  pages={4400-4413},
  keywords={Visualization;Semantics;Image annotation;Image edge detection;Data models;Adaptation models;Task analysis;Fundamental visual concepts;concept graph;model evolution;cross media},
  doi={10.1109/TMM.2020.3042072}
}
```


