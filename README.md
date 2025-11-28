# RETA: Real-Time and Expressive Talking Head Animation without Emotion Label

This repository contains the official results and demonstration for our paper on generating realistic talking heads from audio input.

---

## 🎥 Video Demonstrations

We conduct qualitative comparisons of our RETA against Wav2Lip (MM’20), SadTalker (CVPR’23), RealPortrait (ICLR’24), and KDTalker (IJCV’25). In particular, KDTalker is diffusion-based method.

### Example 1 
https://github.com/user-attachments/assets/61b54306-74c9-481c-8e05-9aa8e5f2df39

### Example 2
https://github.com/user-attachments/assets/d6148a84-5334-4dec-98f8-7cd6be2ad92c

### Example 3
https://github.com/user-attachments/assets/922749c9-17ba-4384-bb16-e4d505dd7bba

## 🎥 Robust Generalization in the Wild
Our model excels at generalizing to data it has never seen before. To demonstrate this, we showcase its performance on challenging "in-the-wild" scenarios. 

### 1. Source Image from unseen (VFHQ) dataset + Audio form HDTF dataset
| Source Img | RETA             | 
|------------|------------|
|<img src="https://github.com/user-attachments/assets/465b7849-3aa6-459d-b104-646ebf5ddba7" width="100%"></img> | <video controls loop src="https://github.com/user-attachments/assets/d241f304-07f3-4da2-82a5-028972964b32" muted="false" width="100%"></video> |

### 2. Source Image from unseen (VFHQ) dataset + Audio form unseen dataset
| Source Img | RETA             | 
|------------|------------|
|<img src="https://github.com/user-attachments/assets/a37fb198-350a-412c-bf9a-caba13f58b89" width="100%"></img> | <video controls loop src="https://github.com/user-attachments/assets/fdf5104f-80bf-46e1-ac5c-695a14e2d7e7" muted="false" width="100%"></video> |

### 3. Source Image from unseen (VFHQ) dataset + Audio form unseen (VFHQ) dataset
| Source Img | RETA             | 
|------------|------------|
|<img src="https://github.com/user-attachments/assets/e881348b-432e-4844-a3a6-7bd794aceb32" width="100%"></img> | <video controls loop src="https://github.com/user-attachments/assets/2adcdce6-7fe6-4228-9d8a-5db174d2cf9e" muted="false" width="100%"></video> |
