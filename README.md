# CelebA-Spoof-Classification
With the growing popularity of facial interaction systems, protecting them from
illegal access is becoming a critical issue. In other words, such systems are prone to
spoofing attacks in different forms, such as a printed photo or a replayed video of the
real user. In this regard, face anti-spoofing is an essential component in facial recognition
systems aiming to make them more robust against these attacks. The existing
models fail in many complex real-world situations, because the available datasets for
face anti-spoofing are limited in terms of the quantity of sample data and the diversity
of spoofing scenarios. CelebA-spoof dataset contains 625,537 images of 10,177 subjects,
with spoof images captured from 8 different scenes using more than 10 different
input sensors as well as a rich annotation of face attributes and spoof types. Therefore,
models trained on this large-scale and diverse dataset would have the potential to
yield a higher generalization to a variety of real-world situations. Among many countermeasures
against presentation attacks, deep learning-based methods have attracted
a great deal of attention because they extract a highly discriminative feature representation
automatically from the images using a Convolutional Neural Network (CNN).
This not only eliminates the need for designing handcrafted features, which would be
even more challenging for large datasets, but also leads to higher classification accuracy.
This project investigates the classification performance of deep CNNs on the CelebA-spoof dataset. Regarding this, I take the visual features extracted by three deep CNNs: VGG-16, ResNet-50, and Xception and utilize them as an input to my own classifiers. Then, I implement a hybrid model by concatenating the features of VGG-16 and
ResNet-50 with the best performance such that the classification accuracy is increased
compared with using the individual CNNs’ features. Finally, in order to validate the
classification performance of the hybrid model in practice, it can be tested on
image samples from the real world.
