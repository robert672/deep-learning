# 如果一个小姐姐不够，那就三个小姐姐一起来
deep learning AI


通过deeplabv3p_xception65_humanseg实现一键抠图
DeepLabv3+ 介绍
DeepLabv3+是DeepLab语义分割系列网络的最新作，其前作有 DeepLabv1，DeepLabv2, DeepLabv3, 在最新作中，DeepLab的作者通过encoder-decoder进行多尺度信息的融合，同时保留了原来的空洞卷积和ASPP层， 其骨干网络使用了Xception模型，提高了语义分割的健壮性和运行速率，在 PASCAL VOC 2012 dataset取得新的state-of-art performance，89.0mIOU。

在PaddleSeg当前实现中，支持两种backbone

MobileNetV2: 适用于移动设备的快速网络，如果对分割性能有较高的要求，请使用这一backbone网络。

Xception: DeepLabv3+原始实现的backbone网络，兼顾了精度和性能，适用于服务端部署。
