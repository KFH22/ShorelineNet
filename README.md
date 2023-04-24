# ShoreLineNet ConvLSTM implementation

This notebook is a fork of "ShorelineNet" for the purpose of a 3rd year project at University College London. The original code is written for the conference paper "ShorelineNet: An Efficient Deep Learning Approach for Shoreline Semantic Segmentation for Unmanned Surface Vehicles" (Yao et al., 2021). 


To cite their conference paper please use the code below.

```
@inproceedings{yao2021shorelinenet,
  title={ShorelineNet: An Efficient Deep Learning Approach for Shoreline Semantic Segmentation for Unmanned Surface Vehicles},
  author={Yao, Linghong and Kanoulas, Dimitrios and Ji, Ze and Liu, Yuanchang},
  booktitle={Proceedings of the... IEEE/RSJ International Conference on Intelligent Robots and Systems. IEEE/RSJ International Conference on Intelligent Robots and Systems},
  year={2021},
  organization={IEEE}
}

```

## About 

This notebooks trains an image segementation network with modified MobileNetV2  + ConvLSTM UNet structure on the MaSTr1325 or MaSTr1478 dataset. The results are evaluated against the MODS benchmark (Bovcon et al., 2022) separately.

Find evaluation code here:  https://github.com/bborja/mods_evaluation

Find datasets here: https://box.vicos.si/borja/viamaro/index.html

## References

BOVCON, B., MUHOVIČ, J., VRANAC, D., MOZETIČ, D., PERŠ, J. & KRISTAN, M. 2022. MODS—A USV-Oriented Object Detection and Obstacle Segmentation Benchmark. IEEE Transactions on Intelligent Transportation Systems, 23, 13403-13418.

YAO, L., KANOULAS, D., JI, Z. & LIU, Y. ShorelineNet: An Efficient Deep Learning Approach for Shoreline Semantic Segmentation for Unmanned Surface Vehicles.  2021 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 27 Sept.-1 Oct. 2021 2021. 5403-5409.


