# Transfer LeakGAN
* This is a repo is a fork from https://github.com/nurpeiis/LeakGAN-PyTorch


## Requirements
* **PyTorch r1.1.0**
* Python 3.5+
* CUDA 8.0+ (For GPU)


## File
* Discriminator.py: The discriminator model of LeakGAN including Feature Extractor and classification
* Generator.py: The generator model of LeakGAN including worker and manager units
* data_iter.py: Data loader for Generator and Discriminator
* utils.py: contains all the connecting parts for recurrent & loss functions 
* main.py: running this file will initiate 
* convert.py: Convert one-hot number to real word
* eval_bleu.py: Evaluation of the BLEU scores (2-5) between test dataset and generated data


## Acknowledgements
1. https://github.com/nurpeiis/LeakGAN-PyTorch
2. https://github.com/CR-Gjx/LeakGAN/blob/master/Image%20COCO/
3. https://github.com/deep-art-project/Music/blob/master/leak_gan/
