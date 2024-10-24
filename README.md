# A Large-Scale Dataset for Segmentation and Classification

## General Introduction

This dataset comprises samples of nine different seafood types collected from a supermarket in Izmir, Turkey, as part of a university-industry collaboration project at Izmir University of Economics. The findings were published in ASYU 2020. The included seafood types are:

1. **Gilt Head Bream (Sargoz)** 🐟
2. **Red Sea Bream (Kızıl Bıyık)** 🐠
3. **Sea Bass (Levrek)** 🎣
4. **Red Mullet (Barbun)** 🦐
5. **Horse Mackerel (İskorpit)** 🐡
6. **Black Sea Sprat (Karadeniz İstavriti)** 🌊
7. **Striped Red Mullet (Şeritli Barbun)** 🦈
8. **Trout (Alabalık)** 🐠
9. **Shrimp (Karides)** 🍤

## Purpose of the Work  

1. **Facilitate Research**  
   The dataset enables researchers to perform segmentation, feature extraction, and classification of various seafood types.

2. **Compare Algorithms**  
   It provides a platform for comparing common segmentation and classification algorithms, including:  
   - **Semantic Segmentation**  
   - **Convolutional Neural Networks (CNNs)**  
   - **Bag of Features**  

3. **Robustness through Augmentation**  
   Each class contains 2000 images (1000 original and 1000 augmented) to enhance the robustness of machine learning models. Augmentation techniques used include flipping and rotating images.  

4. **Validate Usability**  
   Experimental results confirm the dataset's effectiveness for segmentation, feature extraction, and classification tasks, demonstrating its practical applications in real-world scenarios.

## Data Gathering and Augmentation

Images for this dataset were captured using two cameras: the **Kodak Easyshare Z650** and the **Samsung ST60**, with resolutions of **2832 x 2128** and **1024 x 768** pixels, respectively.

Prior to the segmentation process, the dataset was resized to **590 x 445** pixels while maintaining the aspect ratio. To enhance the dataset, labels were augmented through flipping and rotating techniques. As a result, each class contains a total of **2000 images**: **1000 RGB fish images** and **1000 corresponding ground truth labels**.

## Dataset Description  
This dataset contains 9 types of seafood, each with 1000 original and 1000 augmented labeled images.  

### Directory Structure  
- Each type resides in the `Fish_Dataset/` directory.  
- Inside each type's folder:  
  - **Images/**: Fish images numbered from `00000.png` to `01000.png`.  
  - **GT/**: Corresponding ground truth images with matching names.

## Acknowledgments  
This dataset is based on the work by **Oguzhan Ulucan**, **Diclehan Karakaya**, and **Mehmet Turkan**, titled *"[A Large-Scale Dataset for Fish Segmentation and Classification](https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset)."* It was presented at the *2020 Innovations in Intelligent Systems and Applications Conference (ASYU)*, organized by IEEE. Their efforts in creating and sharing this dataset have been invaluable for advancing research in fish segmentation and classification.

## Fish Dataset Classification using ANN

Bu projeye Kaggle üzerinden aşağıdaki linkten ulaşabilirsiniz:  
[Kaggle - Classifying a Fish Dataset using ANN](https://www.kaggle.com/code/smeyrabayrak/classifying-a-fish-dataset-using-ann)
