# Deep Learning Image Classification with CNN
### Dataset: Types of Rice Images
Model: "sequential"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 conv2d (Conv2D)             (None, 248, 248, 5)       140       
                                                                 
 max_pooling2d (MaxPooling2D  (None, 124, 124, 5)      0         
 )                                                               
                                                                 
 conv2d_1 (Conv2D)           (None, 122, 122, 7)       322       
                                                                 
 max_pooling2d_1 (MaxPooling  (None, 61, 61, 7)        0         
 2D)                                                             
                                                                 
 flatten (Flatten)           (None, 26047)             0         
                                                                 
 dense (Dense)               (None, 10)                260480    
                                                                 
 dense_1 (Dense)             (None, 5)                 55        
                                                                 
=================================================================
Total params: 260,997
Trainable params: 260,997
Non-trainable params: 0
