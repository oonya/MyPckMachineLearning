# MyPckMachineLearning

### TransferMachineLearingByVGG16
VGG16に対し<br>
x = GlobalAveragePooling2D()(x)<br>
x = Dense(1024, activation='relu')(x)<br>
predictions = Dense(N_CATEGORIES, activation='softmax')(x)<br>
をした。


### iv2_2Keras
[illustration2vec](https://github.com/rezoo/illustration2vec)の訓練済みモデル(caffemodel)をmmdnnを用いてkerasに変換した

### UseI2v.ipynb
本番で使うモデル。
illustration2vecを使って抽出した、画像に対してのベクトルを入力にするモデル
