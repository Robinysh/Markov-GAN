# Markov-GAN

### MNIST
  The data used for training is [here](https://drive.google.com/open?id=0B0LzoDno7qkJdDluZW5DSnpyWTg).
  Download and place the directory in `~/data/mnist_tfrecords`.
## Training   
   python mgan.py mnist mlp -b 4 -m 3 -d 7 --gpus [gpus]
