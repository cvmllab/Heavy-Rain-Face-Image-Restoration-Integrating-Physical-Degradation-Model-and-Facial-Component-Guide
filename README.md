# Heavy Rain Face Image Restoration: Integrating Physical Degradation Model and Facial Component Guided Adversarial Learning - ([paper](https://arxiv.org/abs/2204.08307))

# Abstract

With the recent increase in intelligent CCTVs for visual surveillance, a new image degradation that integrates resolution conversion and synthetic rain models is required. For example, in heavy rain, face images captured by CCTV from a distance have significant deterioration in both visibility and resolution. Unlike traditional image degradation models (IDM), such as rain removal and superresolution, this study addresses a new IDM referred to as a scale-aware heavy rain model and proposes a method for restoring high-resolution face images (HR-FIs) from low-resolution heavy rain face images (LRHR-FI). To this end, a 2-stage network is presented.
The first stage generates low-resolution face images (LR-FIs), from which heavy rain has been removed from the LRHR-FIs to improve visibility. To realize this, an interpretable IDM-based network is constructed to predict physical parameters, such as rain streaks, transmission maps, and atmospheric light. In addition, the image
reconstruction loss is evaluated to enhance the estimates of the physical parameters. For the second stage, which aims to reconstruct the HR-FIs from the LR-FIs outputted in the first stage, facial component guided adversarial learning (FCGAL) is applied to boost facial structure expressions. To focus on informative facial features and reinforce the authenticity of facial components, such as the eyes and nose, a face-parsing-guided generator and facial local discriminators are designed for FCGAL. The experimental results verify that the proposed approach based on physical-based network design and FCGAL can remove heavy rain and increase the resolution and
visibility simultaneously. Moreover, the proposed heavy-rain face image restoration outperforms state-of-theart models of heavy rain removal, image-to-image translation, and superresolution. 

# Experimental results
![캡처](https://user-images.githubusercontent.com/73872706/173509622-c76f9609-80a2-440e-b9a5-285f7a978128.JPG)

Experimental results : input LRHR-FIs, ground truth HR_FIs, SRGAN, proposed method (HRRM+FPM+SRGAN), proposed method (HRRM+FPM+FCG-GAN), heavy-rain removal, pix2pix, and face SR (left to right)

# Source code

[Link](https://drive.google.com/drive/folders/1M_zvJKF3ilsbYFuj_m1iyQjWgI_wQTx6?usp=sharing)

# Dataset

[Link](https://drive.google.com/drive/folders/1JOLeYkVZBA5uUezmA_Ta9PRJl0Bn5cur?usp=sharing)
