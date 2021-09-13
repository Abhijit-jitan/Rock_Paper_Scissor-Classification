# Rock_Paper_Scissor-Classification
**DATA Source:** https://laurencemoroney.com/datasets.html

**MODEL :** rock_paper_scissor classifier-custom model
* ***Model Architecture :***
      _________________________________________________________________
      Layer (type)                 Output Shape              Param #   
      =================================================================
      conv2d_39 (Conv2D)           (None, 222, 222, 32)      896       
      _________________________________________________________________
      max_pooling2d_39 (MaxPooling (None, 111, 111, 32)      0         
      _________________________________________________________________
      conv2d_40 (Conv2D)           (None, 107, 107, 64)      51264     
      _________________________________________________________________
      max_pooling2d_40 (MaxPooling (None, 53, 53, 64)        0         
      _________________________________________________________________
      conv2d_41 (Conv2D)           (None, 49, 49, 64)        102464    
      _________________________________________________________________
      max_pooling2d_41 (MaxPooling (None, 24, 24, 64)        0         
      _________________________________________________________________
      flatten_13 (Flatten)         (None, 36864)             0         
      _________________________________________________________________
      dense_28 (Dense)             (None, 128)               4718720   
      _________________________________________________________________
      dropout_1 (Dropout)          (None, 128)               0         
      _________________________________________________________________
      dense_29 (Dense)             (None, 3)                 387       
      =================================================================
* ***Model Accuracy & Loss :*** 

### To be Continue
**MODEL :** rock_paper_scissor classifier-custom model
* ***Model Architecture :***

* ***Model Accuracy & Loss :*** 
