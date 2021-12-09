# AnimeGanV2

Creator: https://tachibanayoshino.github.io/AnimeGANv2

#

### Train 
#### 1. Download vgg19    
  > [vgg19.npy](https://github.com/TachibanaYoshino/AnimeGAN/releases/tag/vgg16%2F19.npy)  

#### 2. Download Train/Val Photo dataset  
  > [Link](https://github.com/TachibanaYoshino/AnimeGAN/releases/tag/dataset-1)  

#### 3. Do edge_smooth  
  > `python edge_smooth.py --dataset Hayao --img_size 256`  

#### 4. Train  
  >  `python train.py --dataset Hayao --epoch 101 --init_epoch 10`  
  
#### 5. Extract the weights of the generator  
  >  `python get_generator_ckpt.py --checkpoint_dir  ../checkpoint/AnimeGANv2_Shinkai_lsgan_300_300_1_2_10_1  --style_name Shinkai`  
  
____  
  
## License  
This repo is made freely available to academic and non-academic entities for non-commercial purposes such as academic research, teaching, scientific publications. Permission is granted to use the AnimeGANv2 given that you agree to my license terms. Regarding the request for commercial use, please contact us via email to help you obtain the  authorization letter.  
## Author  
Xin Chen
