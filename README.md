Macro Behavioral Targeting
==========================

We investigate a class of emerging online marketing challenges in social networks; macro behavioral targeting (MBT) is introduced as non-personalized broadcasting efforts to massive populations. We propose a new probabilistic graphical model for MBT. Further, a linear-time approximation method is proposed to circumvent an intractable parametric representation of user behaviors. We compare the proposed model with the existing state-of-the-art method on real datasets from social networks. Our model outperforms in all categories by comfortable margins.

Citation
==================

If you find the code in this respository useful for your research, please cite our paper:
```
@inproceedings{xie2013graphical,
  title={Graphical modeling of macro behavioral targeting in social networks},
  author={Xie, Yusheng and Chen, Zhengzhang and Zhang, Kunpeng and Patwary, Md Mostofa Ali and Cheng, Yu and Liu, Haotian and Agrawal, Ankit and Choudhary, Alok},
  booktitle={Proceedings of the 2013 SIAM International Conference on Data Mining},
  pages={740--748},
  year={2013},
  organization={SIAM}
}
```

Audience & Problem
==================

* **Target audience:** Brand and social media marketers and researchers
* **Problem:** Marketers spend millions every month to acquire Facebook fans
 * *We spent $30M and acquired 20M FB fans. Now what?* – a major US retailer
* **Research question:** How to optimally engage one’s fans so that they stay active and retain their value to the brand?
* FB user => **Fan => Engaged Fan** => Customer

Methodology
===========

* Facebook Engagement Model
![alt tag](https://raw.github.com/yvesx/MacroBehavioralTargeting/master/imgs/1.png)
![alt tag](https://raw.github.com/yvesx/MacroBehavioralTargeting/master/imgs/2.png)
* Three major components in MBT model
![alt tag](https://raw.github.com/yvesx/MacroBehavioralTargeting/master/imgs/3.png)
* User parametrization
![alt tag](https://raw.github.com/yvesx/MacroBehavioralTargeting/master/imgs/4.png)
* Features
![alt tag](https://raw.github.com/yvesx/MacroBehavioralTargeting/master/imgs/5.png)
![alt tag](https://raw.github.com/yvesx/MacroBehavioralTargeting/master/imgs/6.png)
![alt tag](https://raw.github.com/yvesx/MacroBehavioralTargeting/master/imgs/7.png)
![alt tag](https://raw.github.com/yvesx/MacroBehavioralTargeting/master/imgs/viz.png)

Data & Experiments
==================

![alt tag](https://raw.github.com/yvesx/MacroBehavioralTargeting/master/imgs/10.png)
* Prediction performance
![alt tag](https://raw.github.com/yvesx/MacroBehavioralTargeting/master/imgs/11.png)
* Optimization terms
![alt tag](https://raw.github.com/yvesx/MacroBehavioralTargeting/master/imgs/12.png)
