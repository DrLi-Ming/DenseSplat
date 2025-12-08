<h1 align="center"> DenseSplat: Densifying Gaussian Splatting SLAM with Neural Radiance Prior </h1>

<video width="100%">
  <source src="https://raw.githubusercontent.com/DrLi-Ming/DenseSplat/refs/heads/main/intro.mp4" type="video/mp4">
</video>

# Related Publications
\[1\] M. Li, S. Liu, T. Deng and H. Wang, **"DenseSplat: Densifying Gaussian Splatting SLAM with Neural Radiance Prior"** in IEEE Transactions on Visualization & Computer Graphics, vol. , no. 01, pp. 1-14, PrePrints 5555, doi: 10.1109/TVCG.2025.3617961.

 # Introduction
 
 The paper is available in [10.1109/TVCG.2025.3617961](https://doi.ieeecomputersociety.org/10.1109/TVCG.2025.3617961)
 <!-- - [Video](https://www.youtube.com/watch?v=XVrVLun0ckk&ab_channel=%E9%8D%BE%E8%B5%B7%E9%B3%B4) 
 
 More details can be found in my master thesis (Main content is written in English).
 - [offical link (require registration to download)](https://etds.ncl.edu.tw/cgi-bin/gs32/gsweb.cgi/ccd=ldn10D/record?r1=1&h1=0)
 - [pdf](https://drive.google.com/file/d/1WYjB8JAu0lATqvtImMTieT8PcewzS5CM/view)
 -->
 
# 
**Source code will be released soon.**
 
# License
DenseSplat is released under the [GNU General Public License v3.0](LICENSE).

If you use DenseSplat in an academic work, please cite:
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
 
