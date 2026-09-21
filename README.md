# OnePixelAttack

It has been shown that the output of Deep Neural Networks (DNN) can be easily altered by small changes to the input. These can leave machine learning systems to be vulnerable to adversarial attacks. In this repo we implement a black-box sparse adversarial attack, where we aim to change the output of the neural network by only making a tiny change to the input. We attack an image classification Convolutional Neural Network (CNN) by only modifying one pixel of the input image. With only modifying one pixel we were able to change the classification of the original image, thus showing how fragile these systems can be.

I did this as part an undergraduate research project where I replicated the implementation of the [One Pixel Attack Research Paper](https://arxiv.org/abs/1710.08864)[1].

## References

[1] J. Su, D. V. Vargas, and K. Sakurai, "One pixel attack for fooling deep neural networks," arXiv preprint arXiv:1710.08864v7 [cs.LG], Oct. 2019.
