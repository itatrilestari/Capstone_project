# Medical Waste Classification

This is a model that classify types of medical waste. Medical Waste has 4 types, there are : 
1. Cytotoxic waste : drug waste used for chemotherapy
2. infectious waste : Waste containing blood or body fluids which usually results from certain medical procedures.
3. Pathological waste : medical waste in the form of human tissue, internal organs, produced after surgical procedures.
4. Pharmaceutical : expired medicines, unused vaccines

This model has 1000 datasets which are split into train, validation, and test sets.
![Screenshot (275)](https://github.com/itatrilestari/Capstone_project/assets/126906101/426af005-8397-481e-b802-511630b69f50)

And we use InceptionResnetV2 as a base model because InceptionResNetV2 was trained on a large-scale image classification task, ImageNet, and achieved state-of-the-art performance. This pre-training on a diverse dataset helps the model to learn rich hierarchical features, which can be beneficial when fine-tuning for a specific classification task.

![Screenshot (276)](https://github.com/itatrilestari/Capstone_project/assets/126906101/c6f31c47-1c71-43e9-ad33-a41cb2c87d56)





