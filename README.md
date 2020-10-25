# MyPckMachineLearning

### TransferMachineLearingByVGG16
VGG16に対し<br>
x = GlobalAveragePooling2D()(x)<br>
x = Dense(1024, activation='relu')(x)<br>
predictions = Dense(N_CATEGORIES, activation='softmax')(x)<br>
をした。
