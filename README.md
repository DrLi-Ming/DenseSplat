<p align="center">
  <h1 align="center"> DenseSplat: Densifying Gaussian Splatting SLAM with Neural Radiance Prior </h1>
  <h3 align="center">TVCG 2025</h3>
    <p align="center">Mingrui Li*, Shuhong Liu*, Tianchen Deng, Hongyu Wang†</p>
    <p align="center">(*equal contribution)</p>
</p>

## Abstract
[DenseSplat](https://doi.ieeecomputersociety.org/10.1109/TVCG.2025.3617961) is the first SLAM system that effectively combines the advantages of NeRF and 3DGS. It utilizes sparse keyframes and NeRF priors for initializing primitives that densely populate maps and seamlessly fill gaps. It also implements geometry-aware primitive sampling and pruning strategies to manage granularity and enhance rendering efficiency. Moreover, DenseSplat integrates loop closure and bundle adjustment, significantly enhancing frame-to-frame tracking accuracy.  
We have performed an extensive experimental validation of our system in the large robot sequence of [NewCollege](https://ori-drs.github.io/newer-college-dataset/), evaluating the general performance of the system, in 16 handheld indoor sequences of the [TUM RGB-D benchmark](http://vision.in.tum.de/data/datasets/rgbd-dataset), evaluating the localization accuracy, relocalization and lifelong capabilities, and in 10 car outdoor sequences from the [KITTI dataset](http://www.cvlibs.net/datasets/kitti/eval_odometry.php), evaluating real-time large scale operation, localization accuracy and efficiency of the pose graph optimization.

<video src="https://github.com/user-attachments/assets/70300e61-c012-4de4-8d6e-a960c84e45c2" width="100%" controls > </video>

## Usage

_**Source code will be released soon.**_

<!-- ## Acknowledgement -->

## License
DenseSplat is released under the [GNU General Public License v3.0](LICENSE).

## Citation

If you find our work useful, please kindly cite us:

```bibtex
@ARTICLE{11193868,
  author={Li, Mingrui and Liu, Shuhong and Deng, Tianchen and Wang, Hongyu},
  journal={ IEEE Transactions on Visualization \& Computer Graphics },
  title={{ DenseSplat: Densifying Gaussian Splatting SLAM with Neural Radiance Prior }},
  year={5555},
  volume={},
  number={01},
  ISSN={1941-0506},
  pages={1-14},
  abstract={ Gaussian SLAM systems excel in real-time rendering and fine-grained reconstruction compared to NeRF-based systems. However, their reliance on extensive keyframes is impractical for deployment in real-world robotic systems, which typically operate under sparse-view conditions that can result in substantial holes in the map. To address these challenges, we introduce DenseSplat, the first SLAM system that effectively combines the advantages of NeRF and 3DGS. DenseSplat utilizes sparse keyframes and NeRF priors for initializing primitives that densely populate maps and seamlessly fill gaps. It also implements geometry-aware primitive sampling and pruning strategies to manage granularity and enhance rendering efficiency. Moreover, DenseSplat integrates loop closure and bundle adjustment, significantly enhancing frame-to-frame tracking accuracy. Extensive experiments on multiple large-scale datasets demonstrate that DenseSplat achieves superior performance in tracking and mapping compared to current state-of-the-art methods. },
  keywords={Simultaneous localization and mapping;Neural radiance field;Real-time systems;Rendering (computer graphics);Geometry;Cameras;Tracking loops;Optimization;Interpolation;Point cloud compression},
  doi={10.1109/TVCG.2025.3617961},
  url = {https://doi.ieeecomputersociety.org/10.1109/TVCG.2025.3617961},
  publisher={IEEE Computer Society},
  address={Los Alamitos, CA, USA},
  month=oct}
```
 
