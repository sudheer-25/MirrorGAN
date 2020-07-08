#  MirrorGAN

This repo consists of an unofficial Pytorch Implementation of the paper [MirrorGAN: Learning Text-to-image Generation by Redescription](https://arxiv.org/abs/1903.05854)

![alt text](https://github.com/sudheer-25/MirrorGAN/blob/master/framework.jpg)

## Getting Started

### Dependencies

* Python == 2.7.12
* torch == 0.4.1
* torchvision == 0.2.0
* EasyDict ==1.9
* Pillow == 7.2.0
* scikit-image == 0.17.2

### Training/Testing

PreTrained Weights for STEM and STREAM Modules

**STEM**

* [image_encoder.pth](https://drive.google.com/drive/u/1/folders/1cgh64vj3BGf71GKKQ4Ic-V6DqapuM0EE)
* [text_encoder.pth](https://drive.google.com/drive/u/1/folders/1cgh64vj3BGf71GKKQ4Ic-V6DqapuM0EE)

**STREAM**

* [decoder-1-700.ckpt](https://drive.google.com/drive/u/1/folders/1Rem1XxZCrXZ6TKjFCqv0pfAZCZXhIwrE)
* [encoder-1-700.ckpt](https://drive.google.com/drive/u/1/folders/1Rem1XxZCrXZ6TKjFCqv0pfAZCZXhIwrE)


STEM Module was pretrained from the code provided here [BERT Model](https://github.com/google-research/bert)

STREAM Module was pretrained from the code provided here [Image Captioning](https://github.com/yunjey/pytorch-tutorial/tree/master/tutorials/03-advanced/image_captioning)


**TRAIN**

cd GLAM
python2 main.py

**TEST**

cd GLAM
python2 mian.py --cfg cfg/eval_bird.yml


## References
[MirrorGAN: Learning Text-to-image Generation by Redescription](https://arxiv.org/abs/1903.05854)

[AttnGAN: Fine-Grained Text to Image Generation with Attentional Generative Adversarial Networks](https://openaccess.thecvf.com/content_cvpr_2018/papers/Xu_AttnGAN_Fine-Grained_Text_CVPR_2018_paper.pdf)

[ImageCaptioning](https://github.com/yunjey/pytorch-tutorial/tree/master/tutorials/03-advanced/image_captioning)

[BERT Model](https://github.com/google-research/bert)
