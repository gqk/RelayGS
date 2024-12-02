# <div align="center"><b> RelayGS: Reconstructing Dynamic Scenes with Large-Scale and Complex Motions via Relay Gaussians </b></div>

<div align="center">

[Qiankun Gao](https://gqk.me)<sup>1, 2</sup>, [Yanmin Wu](https://yanmin-wu.github.io)<sup>1</sup>, Chengxiang Wen<sup>1</sup>, Jiarui Meng<sup>1</sup>, Luyang Tang<sup>1, 2, 3</sup>,<br /> Jie Chen<sup>1, 2 ✉️</sup>, Ronggang Wang<sup>1, 2, 3 </sup>, [Jian Zhang](https://jianzhang.tech)<sup>1, 3 ✉️</sup>

<sup>1</sup>School of Electronic and Computer Engineering, Peking University  
<sup>2</sup>Peng Cheng Laboratory  
<sup>3</sup>Guangdong Provincial Key Laboratory of Ultra High Definition Immersive Media Technology, <br /> Peking University Shenzhen Graduate School

[[`arXiv`](https://arxiv.org/abs/2412.02493)]

<br />

<img src='https://github.com/user-attachments/assets/5f4110de-fc6b-4b6e-94e9-142506b58f32' width="90%" />

</div>

## 🗞️ News
- [2024/12/04] Preprint available on arXiv!

## 🎥 Supplementary Videos

To facilitate comparisons, we showcase the **ground truth (left)**, the rendered results of our **RelayGS (middle)**, and the rendered results of the prior state-of-the-art **ST-GS (right)** for 4 test views in the video below. Each view lasts 10 seconds, resulting in a total duration of approximately 40 seconds.

https://github.com/user-attachments/assets/1e922e94-6a7b-49a6-b987-58439b69794a

It is worth noting that the ST-GS method requires the point clouds from all 250 frames as input to produce its reconstruction results. In contrast, our RelayGS method only utilizes the point cloud from the initial frame, yet achieves significantly better reconstruction results, demonstrating both its efficiency and superior performance.

Additionally, we have uploaded three separate videos to [Google Drive](https://drive.google.com/drive/folders/1uk6JHaRTow5GuN7Nx9x-j7Kr9iYVAXsA?usp=drive_link) for a more detailed examination:

- **VRU_GZ_GT.mp4:** The ground truth video.
- **VRU_GZ_RelayGS_PSNR-28.06.mp4:** The video rendered by our proposed RelayGS method.
- **VRU_GZ_ST-GS_PSNR-27.32.mp4:** The video rendered by the prior state-of-the-art ST-GS method, initialized using the sparse point clouds of all 250 frames.

## 🙌 Acknowledgement

- The upcoming code release will be based on this framework: https://github.com/Awesome3DGS/LibGS
