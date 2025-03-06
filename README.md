# MoEdit: On Learning Quantity Perception for Multi-object Image Editing
The source code of MoEdit.

![image](https://github.com/user-attachments/assets/df89a9f6-f903-4255-8f51-6411a19d9698)

# 1. Todo
- [ ] Release evaluation code
- [ ] Release training code
- [ ] Release training dataset

# 2. Introduction
Multi-object images are prevalent in various real-world scenarios, including augmented reality, advertisement design, and medical imaging. Efficient and precise editing of these images is critical for these applications. With the advent of Stable Diffusion (SD), high-quality image generation and editing have entered a new era. However, existing methods often struggle to consider each object both individually and part of the whole image editing, both of which are crucial for ensuring consistent quantity perception, resulting in suboptimal perceptual performance.
To address these challenges, we propose MoEdit, an auxiliary-free multi-object image editing framework. MoEdit facilitates high-quality multi-object image editing in terms of style transfer, object reinvention, and background regeneration, while ensuring consistent quantity perception between inputs and outputs, even with a large number of objects. To achieve this, we introduce the Feature Compensation (FeCom) module, which ensures the distinction and separability of each object attribute by minimizing the in-between interlacing. Additionally, we present the Quantity Attention (QTTN) module, which perceives and preserves quantity consistency by effective control in editing, without relying on auxiliary tools.
By leveraging the SD model, MoEdit enables customized preservation and modification of specific concepts in inputs with high quality. Experimental results demonstrate that our MoEdit achieves State-Of-The-Art (SOTA) performance in multi-object image editing. 

# 3. Results

![image](https://github.com/user-attachments/assets/d432bc25-a098-4fab-b313-c4298be88c2f)

# 4. How to use

# 5. Contact
* [p2424484@mpu.edu.mo](p2424484@mpu.edu.mo)  
* [taotan@mpu.edu.mo](taotan@mpu.edu.mo)
