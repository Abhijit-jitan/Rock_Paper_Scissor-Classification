# Rock_Paper_Scissor-Classification
**DATA Source:** https://laurencemoroney.com/datasets.html

**MODEL:1** rock_paper_scissor classifier-custom model
* ***Model Architecture :***
     * Conv2D(32,(3),strides=(1),activation='relu',input_shape=(224,224,3))
     * MaxPooling2D(pool_size=(2),strides=(2))
     * Conv2D(64,(5),strides=(1),activation='relu'))
     * MaxPooling2D(pool_size=(2,2),strides=(2,2))
     * Conv2D(64,(5,5),strides=(1,1),activation='relu')
     * MaxPooling2D(pool_size=(2,2),strides=(2,2))
     * Flatten()
     * Dense(128,activation='relu')
     * Dropout(0.3)
     * Dense(3,activation='softmax')
    
* ***Info:*** 
    * ``optimizer:Adam(lr=0.0001); loss:'categorical_crossentropy'; metrics:'accuracy'; epochs:15``    
* ***Model Accuracy & Loss :*** 
   * ``loss:0.0345; accuracy:1.0000; val_loss:0.0244; val_accuracy:1.0000``

### To be Continue
**MODEL :** rock_paper_scissor classifier-custom model
* ***Model Architecture :***

* ***Model Accuracy & Loss :*** 
