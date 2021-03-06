# awesome-vehicle-re-identification
collection of dataset&amp;paper&amp;code on Vehicle Re-Identification

## dataset
* VeRi-776 [[Project]](https://github.com/VehicleReId/VeRidataset) [[paper]](https://link.springer.com/chapter/10.1007/978-3-319-46475-6_53)
* PKU-VehicleID [[Project]](http://pkuml.org/resources/pku-vehicleid.html) [[pdf]](http://openaccess.thecvf.com/content_cvpr_2016/papers/Liu_Deep_Relative_Distance_CVPR_2016_paper.pdf)
* PKU-VD [[Project]](http://pkuml.org/resources/pku-vds.html) [[pdf]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Yan_Exploiting_Multi-Grain_Ranking_ICCV_2017_paper.pdf)
* VehicleReId [[Project]](https://medusa.fit.vutbr.cz/traffic/datasets/) [[pdf]](http://openaccess.thecvf.com/content_cvpr_2016_workshops/w25/papers/Zapletal_Vehicle_Re-Identification_for_CVPR_2016_paper.pdf)
* PKU-Vehicle[[Project]](http://59.110.216.11/html/) [[pdf]](https://ieeexplore.ieee.org/abstract/document/8265213/)
* CompCars[[Project]](http://mmlab.ie.cuhk.edu.hk/datasets/comp_cars/index.html) [[pdf]](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Yang_A_Large-Scale_Car_2015_CVPR_paper.pdf)

## paper
### 2017 & before
1. Orientation Invariant Feature Embedding and Spatial Temporal Regularization for Vehicle Re-Identification
    * Wang Z, Tang L, Liu X, et al. Orientation Invariant Feature Embedding and Spatial Temporal Regularization for Vehicle Re-identification[C]//Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2017: 379-387.
[[pdf]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Wang_Orientation_Invariant_Feature_ICCV_2017_paper.pdf)

2. Learning Deep Neural Networks for Vehicle Re-ID With Visual-Spatio-Temporal Path Proposals
    * Shen Y, Xiao T, Li H, et al. Learning Deep Neural Networks for Vehicle Re-ID With Visual-Spatio-Temporal Path Proposals[C]//Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2017: 1900-1909.[[pdf]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Shen_Learning_Deep_Neural_ICCV_2017_paper.pdf) VeRi: mAP 58.27, top1: 83.49, top5: 90.04; siamese net, tripple loss, chain MRF. Useful!!! 

3. Vehicle Re-Identification for Automatic Video Traffic Surveillance
    * Zapletal D, Herout A. Vehicle re-identification for automatic video traffic surveillance[C]//Computer Vision and Pattern Recognition Workshops (CVPRW), 2016 IEEE Conference on. IEEE, 2016: 1568-1574.[[pdf]](http://openaccess.thecvf.com/content_cvpr_2016_workshops/w25/papers/Zapletal_Vehicle_Re-Identification_for_CVPR_2016_paper.pdf)

4. Exploiting Multi-Grain Ranking Constraints for Precisely Searching Visually-similar Vehicles
    * Yan K, Tian Y, Wang Y, et al. Exploiting Multi-Grain Ranking Constraints for Precisely Searching Visually-similar Vehicles[C]//Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2017: 562-570.[[pdf]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Yan_Exploiting_Multi-Grain_Ranking_ICCV_2017_paper.pdf)

5. Deep Relative Distance Learning- Tell the Difference Between Similar Vehicles
    * Liu H, Tian Y, Yang Y, et al. Deep relative distance learning: Tell the difference between similar vehicles[C]//Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2016: 2167-2175.[[pdf]](http://openaccess.thecvf.com/content_cvpr_2016/papers/Liu_Deep_Relative_Distance_CVPR_2016_paper.pdf)

6. A Deep Learning-Based Approach to Progressive Vehicle Re-identification for Urban Surveillance
    * Liu X, Liu W, Mei T, et al. A deep learning-based approach to progressive vehicle re-identification for urban surveillance[C]//European Conference on Computer Vision. Springer, Cham, 2016: 869-884.[[paper]](https://link.springer.com/chapter/10.1007/978-3-319-46475-6_53)

7. Large-Scale Vehicle Re-Identification in Urban Surveillance Videos
    * Liu X, Liu W, Ma H, et al. Large-scale vehicle re-identification in urban surveillance videos[C]//Multimedia and Expo (ICME), 2016 IEEE International Conference on. IEEE, 2016: 1-6.[[paper]](https://ieeexplore.ieee.org/document/7553002/)

### 2018
8. PROVID- Progressive and Multimodal Vehicle Reidentification for Large-Scale Urban Surveillance
    * Liu X, Liu W, Mei T, et al. PROVID: Progressive and Multimodal Vehicle Reidentification for Large-Scale Urban Surveillance[J]. IEEE Transactions on Multimedia, 2018, 20(3): 645-658.[[paper]](https://ieeexplore.ieee.org/abstract/document/8036238/)

9. Group Sensitive Triplet Embedding for Vehicle Re-identification
    * Bai Y, Lou Y, Gao F, et al. Group Sensitive Triplet Embedding for Vehicle Re-identification[J]. IEEE Transactions on Multimedia, 2018.[[paper]](https://ieeexplore.ieee.org/abstract/document/8265213/) VERI766: MAP 59.47 HIT1: 96.24 HIT5: 98.97; COMPCARS: MAP: =0.402 1: 0.769; VEHICLEID: small: 0.754, medium: 0.743, large: 0.724. Group with K-Means to handle intra-class variance. Useful!!!

10. Improving triplet-wise training of convolutional neural network for vehicle re-identification
    * Zhang Y, Liu D, Zha Z J. Improving triplet-wise training of convolutional neural network for vehicle re-identification[C]//Multimedia and Expo (ICME), 2017 IEEE International Conference on. IEEE, 2017: 1386-1391.[[paper]](https://ieeexplore.ieee.org/abstract/document/8019491/)

11. Multi-modal metric learning for vehicle re-identification in traffic surveillance environment
    * Tang Y, Wu D, Jin Z, et al. Multi-modal metric learning for vehicle re-identification in traffic surveillance environment[C]//Image Processing (ICIP), 2017 IEEE International Conference on. IEEE, 2017: 2254-2258.[[paper]](https://ieeexplore.ieee.org/abstract/document/8296683/)

12. Vehicle re-identification by fusing multiple deep neural networks
    * Cui C, Sang N, Gao C, et al. Vehicle re-identification by fusing multiple deep neural networks[C]//Image Processing Theory, Tools and Applications (IPTA), 2017 Seventh International Conference on. IEEE, 2017: 1-6.[[paper]](https://ieeexplore.ieee.org/abstract/document/8310090/)

13. Deep hashing with multi-task learning for large-scale instance-level vehicle search
    * Liang D, Yan K, Wang Y, et al. Deep hashing with multi-task learning for large-scale instance-level vehicle search[C]//Multimedia & Expo Workshops (ICMEW), 2017 IEEE International Conference on. IEEE, 2017: 192-197.[[paper]](https://ieeexplore.ieee.org/abstract/document/8026274/)

14. Unsupervised Vehicle Re-Identification using Triplet Networks
    * Antonio Marin-Reyes P, Palazzi A, Bergamini L, et al. Unsupervised Vehicle Re-Identification Using Triplet Networks[C]//Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops. 2018: 166-171. [[paper]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w3/Marin-Reyes_Unsupervised_Vehicle_Re-Identification_CVPR_2018_paper.pdf)
    
15. Vehicle Re-Identification with the Space-Time Prior
    * Wu C W, Liu C T, Chiang C E, et al. Vehicle re-identification with the space-time prior[C]//CVPR Workshop (CVPRW) on the AI City Challenge. 2018. [[paper]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w3/Wu_Vehicle_Re-Identification_With_CVPR_2018_paper.pdf)[[code]](https://github.com/cw1204,772/AIC2018_iamai)mAP: 
    53.35; R1: 82.06%.
16. Viewpoint-aware Attentive Multi-view Inference for Vehicle Re-identification
    * Zhou, Y., & Shao, L. (2018). Aware Attentive Multi-View Inference for Vehicle Re-Identification. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (pp. 6489-6498).[[paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhou_Viewpoint-Aware_Attentive_Multi-View_CVPR_2018_paper.pdf)
    
17. Coarse-to-fine: A RNN-based hierarchical attention model for vehicle re-identification. 
    * [[paper]](https://arxiv.org/abs/1812.04239)[[code]](https://github.com/tzzcl/RNN-HA)VeRi: mAP:56.80; R1: 74.79%; VehicleID: test800: R1: 83.8%.(ACCV2018)

18. RAM: A Region-Aware Deep Model for Vehicle Re-Identification
    * [[paper]](https://arxiv.org/pdf/1806.09283.pdf) [[code]](https://github.com/liu-xb/RAM) (ICME2018)VeRi: mAP: 0.615, R1: 0.886; VehicleID: testsmall: 0.752.
    
### 2019
19. Attributes Guided Feature Learning for Vehicle Re-identification
    * [[paper]](https://arxiv.org/pdf/1905.08997.pdf) [[code]](https://github.com/xmlin1995/CVTC) GAN for data genneration. Ensemble of color, class, direction. No use.
20. A unified neural network for object detection, multiple object tracking and vehicle re-identification
    * [[paper]](https://arxiv.org/pdf/1907.03465.pdf) Concat two neighbor frame or camera. Use tripple loss to find similar vihecles in this concated image. However, it is no use for continuous frames.
21. A survey of advances in vision-based vehicle re-identification
    * [[paper]](https://arxiv.org/pdf/1905.13258.pdf) Gste > vstm = nufact = oim 
22. A Dual-Path Model With Adaptive Attention For Vehicle Re-Identification
    * [[paper]](https://arxiv.org/pdf/1905.03397.pdf) [[code]](https://github.com/Pirazh/Vehicle_Key_Point_Orientation_Estimation) Use key point to help Re-id. This code only has key point part. VeRi-776: mAP: 66.35, t1: 90.17, t5: 94.34; VehicleID: small: t1: 74.69, t2: 93.82, medium t1: 68.62, t2: 89.95; large: t1: 63.54, t5: 85.64;
23. Variational Representation Learning for Vehicle Re-Identification
    * [[paper]](https://arxiv.org/pdf/1905.02343.pdf) No code. Result is not good. Veri: mAP: 59.18, t1: 88.08, t5 94.63; VehicleID: small: t1: 73.37, t5: 85.52.
[[Website contains many new Re-Id papers]](https://amds123.github.io/rid/)
