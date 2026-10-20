Deep Learning-Based Diabetic Retinopathy Detection | Research Paper Implementation

Based on: Tymchenko, B., Marchenko, P., & Spodarets, D. (2020). “Deep Learning Approach to Diabetic Retinopathy Detection.” arXiv:2003.02261.

•	Implemented a transfer learning pipeline using EfficientNet-family CNN architectures to classify diabetic retinopathy severity from retinal fundus images.

•	Designed a three-stage training workflow comprising pretraining, main training, and post-training to adapt pretrained models to the target task.

•	Addressed class imbalance using Focal Loss to improve model learning across underrepresented classes.

•	Achieved 98.36% test accuracy for binary classification (no DR vs. DR) and 84.44% test accuracy for five-class diabetic retinopathy severity classification.

Results for Binary Classification:

<img width="590" height="51" alt="image" src="https://github.com/user-attachments/assets/6c957e6c-60a0-4557-ae71-72a3abc03c0e" />

<img width="631" height="566" alt="image" src="https://github.com/user-attachments/assets/5369c5a6-bf0d-4b84-82dd-e4adef6eb4b6" />

<img width="758" height="566" alt="image" src="https://github.com/user-attachments/assets/bebeb6b7-3bf9-47ab-aeca-03e888ee53f3" />

Results for Multiclass Classification:

<img width="588" height="51" alt="image" src="https://github.com/user-attachments/assets/97b3e4bc-4ce8-43d3-88c0-e9671dca8f94" />

<img width="635" height="570" alt="image" src="https://github.com/user-attachments/assets/8db952ab-1555-4e2b-9286-b34e41a23428" />

<img width="812" height="607" alt="image" src="https://github.com/user-attachments/assets/6e64f70a-e829-41b6-96ae-0edaf843ccbb" />


