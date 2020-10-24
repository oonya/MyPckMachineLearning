# MyPckMachineLearning

### TransferMachineLearing
VGG16に対し
x = GlobalAveragePooling2D()(x)
x = Dense(1024, activation='relu')(x)
predictions = Dense(N_CATEGORIES, activation='softmax')(x)
をした。
