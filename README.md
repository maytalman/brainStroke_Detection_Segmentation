
# Derin Öğrenme ile Beyin BT Görüntülerinden İnme Tespiti ve Segmentasyonu

Beyin BT görüntülerinden oluşan bir veri setimizde, inme olmayan BT görüntüleri ile inmenin iki türü olan iskemik ve hemorojik(kanamalı) beyin BT görüntüleri bulunmaktadır.
Bu projede bu veri setini kullanarak görüntüleri inme var, iskemik ve hemorojik olarak sınıflandırmayı amaçladık. Bu sebeple Resnet50, EfficientB5, VGG16, VGG19, InceptionResnet_V2 gibi Deep Learning modelleriyle çalıştık. En yüksek doğruluk oranını Resnet50 modelinde aldığımız için projede bu modeli kullandık.

Diğer bir amacımız BT görüntülerindeki inmeli alanları segmente etmekti. Bunun içinde Biyomedikal görüntüleri segmente etmek amacıyla kullanılan U-Net mimarisi tercih edilmiştir.

Aşağıdaki görüntüde segmente edilmiş inmeli alanı görebilirsiniz.

![u-net_stroke](https://user-images.githubusercontent.com/52465630/157931961-15105573-72cb-4505-85e2-d1aed9dfbc2c.png)
