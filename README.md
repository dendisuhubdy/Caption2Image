﻿# Probabilistic Graphical Models Project: Caption to Images

Combining both the image captioning and VAE tutorial

https://github.com/yunjey/pytorch-tutorial/tree/master/tutorials/03-advanced/image_captioning
https://github.com/yunjey/pytorch-tutorial/tree/master/tutorials/03-advanced/variational_auto_encoder

follow instructions from the image_captioning tutorial to build the vocabulary and resize the images.

``` python build_vocab.py --caption_path <path to captions_train2014.json> ```

``` python resize.py --image_dir <path to train2014> ```

then train the model with ```python train.py ```


--

Supporting Slides: http://cs.mcgill.ca/~nangel3/ift6269-pgm/variational_encoder_decoder[slides].pdf

Project Repor: http://cs.mcgill.ca/~nangel3/ift6269-pgm/variational_encoder_decoder[report].pdf

--

Original repository: https://github.com/ppartha03/PGM-Project
