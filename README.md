# detect-related-individuals

### Work in progress

Competitions on [Kaggle](https://www.kaggle.com)

[Kaggle](https://www.kaggle.com/c/recognizing-faces-in-the-wild) - Northeastern SMILE Lab - Recognizing Faces in the Wild Can you determine if two individuals are related?

![alt txt](https://media.kairos.com/blog-images/crowd.png)


### Description

Do you have your father’s nose?

Blood relatives often share facial features. Now researchers at Northeastern University want to improve their algorithm for facial image classification to bridge the gap between research and other familial markers like DNA results. That will be your challenge in this new Kaggle competition. [More...](https://www.kaggle.com/c/recognizing-faces-in-the-wild)

### Content

1. First approach

Simmilarity Learning approcah: [Link](https://github.com/OleksandrKosovan/detect-related-individuals/blob/master/01-similarity-learning-with-vectorization)

**Deteils**:
- Use ResNet 50 for image embedding

- Structure of NN:

![alt txt](https://github.com/OleksandrKosovan/detect-related-individuals/blob/master/01-similarity-learning-with-vectorization/img/nn.png)

- Training info:
`Epoch 100/100
293865/293865 [==============================] - 303s 1ms/step - loss: 0.0470 - acc: 0.9809 - val_loss: 1.2095 - val_acc: 0.8345`

- Training plot:

![alt txt](https://github.com/OleksandrKosovan/detect-related-individuals/blob/master/01-similarity-learning-with-vectorization/img/train-plot.png)

### Instalation

`git clone https://github.com/OleksandrKosovan/detect-related-individuals`

