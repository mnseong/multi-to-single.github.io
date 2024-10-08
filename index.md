---
layout: project_page
permalink: /

title: "Multi-to-Single: Boosting Large Scene Reconstruction using Distributed Gaussian Splatting"
authors: Minseong Kweon¹, Xuejin Chen², Jinsun Park¹
affiliations: ¹Pusan National University
  ²University of Science and Technology of China
# paper: https://www.cs.virginia.edu/~robins/Turing_Paper_1936.pdf
# video: https://www.youtube.com/results?search_query=turing+machine
# code: https://github.com/topics/turing-machines
# data: https://huggingface.co/docs/datasets
---

<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
This page has been created to share preliminary results from the ongoing project <em>Multi-to-Single: Boosting Large Scene Reconstruction using Distributed Gaussian Splatting</em>. If you have any questions, feel free to reach out to me at wou1202@pusan.ac.kr.
        </div>
    </div>
</div>

---

> Note: This project is being conducted under the supervision of Professor Xuejin Chen from USTC and Professor Jinsun Park from PNU.

## Key Contributions

To be released

## Results

| Methods           | Building  |           |           |       | Rubble    |           |           |      |
| ----------------- | --------- | --------- | --------- | ----- | --------- | --------- | --------- | ---- |
|                   | PSNR ↑    | SSIM ↑    | LPIPS ↓   | # GS  | PSNR ↑    | SSIM ↑    | LPIPS ↓   | # GS |
| MegaNeRF [3]      | 20.93     | 0.547     | 0.504     | -     | 24.06     | 0.553     | 0.516     | -    |
| Switch-NeRF [4]   | 21.54     | 0.579     | 0.474     | -     | 24.31     | 0.562     | 0.496     | -    |
| 3DGS† [1]         | 21.25     | 0.727     | 0.282     | 6.4M  | 24.85     | 0.750     | 0.283     | 3.6M |
| Grendel-GS† [5]   | 21.47     | 0.772     | 0.209     | 11.8M | 25.45     | 0.783     | 0.230     | 6.1M |
| City Gaussian [2] | 21.55     | 0.778     | 0.246     | 13.2M | 25.77     | 0.813     | 0.228     | 9.7M |
| **Ours**          | **23.39** | **0.811** | **0.157** | 8.8M  | **26.18** | **0.816** | **0.187** | 6.2M |

![building-test-result](https://github.com/user-attachments/assets/104494e5-048f-4561-8225-6c7c1a657c22)

_**Fig. 1.** Rendering Results for the 20 Image Test Dataset of Mill 19 - Building_

Results for additional datasets are forthcoming.

## References

```
1. Kerbl, Bernhard, et al. "3D Gaussian Splatting for Real-Time Radiance Field Rendering." ACM Trans. Graph. 42.4 (2023): 139-1.

2. Liu, Yang, et al. "Citygaussian: Real-time high-quality large-scale scene rendering with gaussians." arXiv preprint arXiv:2404.01133 (2024).

3. Turki, Haithem, Deva Ramanan, and Mahadev Satyanarayanan. "Mega-nerf: Scalable construction of large-scale nerfs for virtual fly-throughs." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2022.

4. Zhenxing, M. I., and Dan Xu. "Switch-nerf: Learning scene decomposition with mixture of experts for large-scale neural radiance fields." The Eleventh International Conference on Learning Representations. 2022.

5. Zhao, Hexu, et al. "On Scaling Up 3D Gaussian Splatting Training." arXiv preprint arXiv:2406.18533 (2024).
```
