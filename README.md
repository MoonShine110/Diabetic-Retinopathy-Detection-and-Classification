# Diabetic-Retinopathy-Detection-and-Classification

## Diabetic Retinopathy Detection and Classification Using EfficientNet-B3 model

- [Link to the IEEE Journal](https://ieeexplore.ieee.org/document/10169756)
- [Link to the dataset (source: Kaggle)](https://www.kaggle.com/datasets/stefankrsteski/diabetic-retinopathy) 
- [Link to the Kaggle competition dataset](https://www.kaggle.com/competitions/aptos2019-blindness-detection)

**ABSTRACT**

Diabetic retinopathy is an eye disease that progressively degrades a person's vision. It affects 40- 45% of people with diabetes and it is one of society's leading causes of blindness. Diabetic retinopathy has 4 different phases and with each stage, the eyesight of a person degrades. If diabetic retinopathy is detected in its early phases, its effects and progression can be slowed down and save the person from permanent blindness. We aim to utilize ML to detect the disease and classify diabetic retinopathy into its 4 classes based on severity, helping in early detection. This readme file gives a glimpse into diabetic retinopathy and proposes a methodology to develop a machine-learning model.

**Introduction**

Individuals with diabetes are prone to Diabetic retinopathy, which is an eye disorder. When this happens, elevated blood sugar levels harm the retina's blood vessels. They have the potential to expand and leak. Alternatively, they could close, preventing blood flow. On the retina, abnormally new blood vessels can occasionally form. These various changes can adversely affect the eyesight of the person.

**Output Classes**

DR: Diabetic Retinopathy

- 0: No_DR
- 1: Mild
- 2: Moderate
- 3: Severe
- 4: Proliferate_DR

**Features to Consider**
[Image Source:Nera](https://www.retinamd.com/retinal-conditions-and-diseases/diabetic-retinopathy/)

- The presence of yellow "flakes", is caused due to the leaking of substances like proteins and lipids into the visceral fluid inside the eye.
  

- Red dots (microaneurysms) are present in the eye and are mainly caused due to blood clots occurring due to damaged blood vessels.
  

- An increase in blood vessels is also observed as the already existing blood vessels get blocked and hence the oxygen supply to all parts of the eye is hindered. Therefore, new blood vessels are formed to recover from the lack of oxygen.
  

For the training of the model, we will be using the EfficientNet model, it is a transfer learning model. It can perform a wide variety of image classification tasks and is based on the CNN architecture. It outperforms the existing CNNs in terms of accuracy and efficiency. The model achieves cutting-edge performance while being extremely efficient in terms of both computational resources and parameter count. It accomplishes this by employing a compound scaling method that optimizes the neural network's balance of depth, width, and resolution, allowing it to achieve high accuracy with fewer computational resources than other models of comparable performance.

**Model Architecture**

![Model Architecture Image](https://github.com/MoonShine110/Diabetic-Retinopathy-Detection-and-Classification/blob/main/Model_Architecture/Model_architecture.PNG)
