# Resnet (Family) Result

## ImageNet Result for Data Augmentation
**Provided by '[Yulin Wang](https://github.com/blackfeather-wang)'.**

This experiemntal setting is usually implemented for evaluating Data Augmentation Algorithms. 
The seeting is as follow:

```
Lr = 0.2, Epoch = 300, Lr_schedual = 'cosine', weight_decay = 1e-4
```

****
|Model|Params|Flops|Top-1|Top-5|
|-----|------|-----|-----|-----|
|ResNet50  |25.6M |x|77.0|93.2
|ResNet101 |44.6M |x|78.3|93.9
|ResNet152 |60.3M |x|78.7|94.2
|ResNeXt50, 32X4d |25.0M|x|77.5|93.6
|ResNeXt101, 32x8d|88.8M|x|78.9|94.1

****
