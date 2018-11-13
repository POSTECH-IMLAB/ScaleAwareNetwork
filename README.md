## Scale Aware Network
Created by [Yonghyun Kim](http://imlab.postech.ac.kr/members.htm) and [Daijin Kim](http://imlab.postech.ac.kr/members_d.htm) at [POSTECH IM Lab](http://imlab.postech.ac.kr)

### Overview

Most of the recent successful methods in accurate object detection build on the convolutional neural networks (CNN).
However, due to the lack of scale normalization in CNN-based detection methods, the activated channels in the feature space can be completely different according to a scale and this difference makes it hard for the classifier to learn samples.
We propose a Scale Aware Network (SAN) that maps the convolutional features from the different scales onto a scale-invariant subspace to make CNN-based detection methods more robust to the scale variation, and also construct a unique learning method which considers purely the relationship between channels without the spatial information for the effcient learning of SAN.
To show the validity of our method, we visualize how convolutional features change according to the scale through a channel activation matrix and experimentally show that SAN reduces the feature differences in the scale space.
We evaluate our method on VOC PASCAL and MS COCO dataset. We demonstrate SAN by conducting several experiments on structures and parameters.
The proposed SAN can be generally applied to many CNN-based detection methods to enhance the detection accuracy with a slight increase in the computing time.

## Citation

If you're using this code in a publication, please cite our papers.

```
  @inproceedings{kim2018san,
    title={SAN: Learning Relationship between Convolutional Features for Multi-Scale Object Detection},
    author={Kim, Yonghyun and Kang, Bong-Nam and Kim, Daijin},
    booktitle={Proceedings of the European Conference on Computer Vision (ECCV)},
    pages={316--331},
    year={2018}
  }
```

### Overall

We propose a Scale Aware Network (SAN) that maps the convolutional features from the different scales onto a scale-invariant subspace to make CNN-based detection methods more robust to the scale variation, and also construct a unique learning method which considers purely the relationship between channels without the spatial information for the efficient learning of SAN.
To show the validity of our method, we visualize how convolutional features change according to the scale through a channel activation matrix and experimentally show that SAN reduces the feature differences in the scale space.

### Related Papers

Yonghyun Kim, Bong-Nam Kang, Daijin Kim, "SAN: Learning Relationship between Convolutional Features for Multi-Scale Object Detection," European Conference on Computer Vision (ECCV), 2018.

### Acknowledgements

This work was supported by IITP grant funded by the Korea government (MSIT) (IITP-2014-3-00059, Development of Predictive Visual Intelligence Technology, IITP-2017-0-00897, SW Starlab support program, and IITP-2018-0-01290, Development of Open Informal Dataset and Dynamic Object Recognition Technology Affecting Autonomous Driving)
