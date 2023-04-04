# A Generative Adversarial Network (GAN) Implemented in Python
This project is a Generative adversarial Network which can be trained on both Mnist and Fashion_mnist datasets from Tensorflow.
The network consists of a class called GAN and by creating an instance of the GAN, our model is ready to get trained.
buffer_size is gained from the dataset and batch size is initialized by 256.


## How to Run...!
- 1- Open Generative_Adv_Net.ipynb file in Jupyter Notebook or google colab.
- 2- Make an instance of our GAN class (our model).
- 3- Train the model using the train method. At the end of the training process, it will show the result image made of 16*16 images.
- 4- To test the model, use the predict method by sending array of random noise.

### A gif that is made of results of the training process during 20 epochs...!
![ezgif com-optimize](https://user-images.githubusercontent.com/112881732/229309875-127e6b01-1d55-42a8-8760-531f43f1b6d2.gif)


