# Pytorch-CycleGAN-Digits
Unofficial Pytorch implementation of [CycleGAN](https://arxiv.org/abs/1703.10593) for MNIST, USPS, SVHN, MNIST-M and SyntheticDigits datasets.

<br>

Change the DB variable to change the dataset.
For using the saved model to generate images, set LOAD_MODEL to True and EPOCHS to 0.
## Generated Samples
### MNIST &#8596; SVHN
MNIST &#8594; SVHN             |  SVHN &#8594; MNIST
:-------------------------:|:-------------------------:
![MNIST_SVHN.](Results/SVHN_MNIST/MNIST_SVHN.png)  |  ![SVHN_MNIST](Results/SVHN_MNIST/SVHN_MNIST.png)

### MNIST &#8596; MNIST-M
MNIST &#8594; MNIST-M             |  MNIST-M &#8594; MNIST
:-------------------------:|:-------------------------:
![MNIST_MNISTM.](Results/MNIST_MNISTM/MNIST_MNISTM.png)  |  ![MNISTM_MNIST](Results/MNIST_MNISTM/MNISTM_MNIST.png)

MNIST &#8594; USPS             |  USPS &#8594; MNIST
:-------------------------:|:-------------------------:
![MNIST_USPS.](Results/MNIST_USPS/MNIST_USPS.png)  |  ![MNISTM_MNIST](Results/MNIST_USPS/USPS_MNIST.png)

SyDigits &#8594; SVHN             |  SVHN &#8594; SyDigits
:-------------------------:|:-------------------------:
![SyDigits_SVHN.](Results/SyDigits_SVHN/SyDigits_SVHN.png)  |  ![SVHN_SyDigits](Results/SyDigits_SVHN/SVHN_SyDigits.png)
