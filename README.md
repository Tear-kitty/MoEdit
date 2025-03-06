# MoEdit: On Learning Quantity Perception for Multi-object Image Editing
The source code of MoEdit is coming soon
![image](https://github.com/user-attachments/assets/df89a9f6-f903-4255-8f51-6411a19d9698)

# 1. Todo
- [x] Release training and evaluation code
- [x] Release training dataset

# 2. Introduction
Multi-object images are prevalent in various real-world scenarios, including augmented reality, advertisement design, and medical imaging. Efficient and precise editing of these images is critical for these applications. With the advent of Stable Diffusion (SD), high-quality image generation and editing have entered a new era. However, existing methods often struggle to consider each object both individually and part of the whole image editing, both of which are crucial for ensuring consistent quantity perception, resulting in suboptimal perceptual performance.
To address these challenges, we propose MoEdit, an auxiliary-free multi-object image editing framework. MoEdit facilitates high-quality multi-object image editing in terms of style transfer, object reinvention, and background regeneration, while ensuring consistent quantity perception between inputs and outputs, even with a large number of objects. To achieve this, we introduce the \underline{Fe}ature \underline{Com}pensation (FeCom) module, which ensures the distinction and separability of each object attribute by minimizing the in-between interlacing. Additionally, we present the \underline{Q}uantity A\underline{t}\underline{t}entio\underline{n} (QTTN) module, which perceives and preserves quantity consistency by effective control in editing, without relying on auxiliary tools.
By leveraging the SD model, MoEdit enables customized preservation and modification of specific concepts in inputs with high quality. Experimental results demonstrate that our MoEdit achieves State-Of-The-Art (SOTA) performance in multi-object image editing. The code will be made publicly available.
