# Models_Reproduce_Pytorch

This repository contains pytorch codes for popular deep CNN architectures and real-time updated results on ImageNet. The results can serve as baseline results for our research group. We aim to accelarate the advance of Deep Learning Research and make reproducible results in Pytorch. We also hope this repository is helpful for your research.

# ImageNet Results

Experimental setting:
```
Batch_size(B) , Lr , Epoch , Lr_schedualr (LrS), weight_decay = 1e-4
```

## ResNet
**Provided by [Yizeng Han](https://github.com/thuallen), [Yulin Wang](https://github.com/blackfeather-wang)'.**


|Model|Params|Flops|Top-1|Top-5|B|Lr|Epoch|LrS|Provider|
|-----|------|-----|-----|-----|---|---|---|---|---|
|ResNet34  |21.8M |3.67G|74.21|91.86|1024|0.4|90|warm5+cosine|Y Han
|ResNet34  |21.8M |3.67G|74.52|91.99|1024|0.4|120|warm5+cosine|Y Han
|ResNet50  |25.6M |4.10G|76.78|93.34|1024|0.4|90|warm5+cosine|Y Han
|ResNet50  |25.6M |4.10G|77.28|93.46|1024|0.4|120|warm5+cosine|Y Han
|ResNet101 |44.6M |7.82G|78.71|94.28|1024|0.4|90|warm5+cosine|Y Han
|ResNet101 |44.6M |7.82G|-|-|1024|0.4|120|warm5+cosine|Y Han
|ResNet50  |25.6M |-|77.0|93.2|512|0.2|300|cosine|Y Wang
|ResNet101 |44.6M |-|78.3|93.9|512|0.2|300|cosine|Y Wang
|ResNet152 |60.3M |-|78.7|94.2|512|0.2|300|cosine|Y Wang
|ResNeXt50, 32X4d |25.0M|-|77.5|93.6|512|0.2|300|cosine|Y Wang
|ResNeXt101, 32x8d|88.8M|-|78.9|94.1|512|0.2|300|cosine|Y Wang

## DenseNet
**Provided by [Haojun Jiang](https://github.com/jianghaojun), [Yulin Wang](https://github.com/blackfeather-wang)'.**

|Model|Params|Flops|Top-1|Top-5|B|Lr|Epoch|LrS|Provider|
|-----|------|-----|-----|-----|---|---|---|---|---|
|DenseNetBC121 |8.0M |2.85G|75.02|92.32|1024|0.4|90|step-0.1-[30,60]|H Jiang
|DenseNetBC121 |8.0M |2.85G|75.71|92.72|1024|0.4|90|cosine|H Jiang
|DenseNetBC169 |14.2M |3.38G|76.20|93.12|1024|0.4|90|step-0.1-[30,60]|H Jiang
|DenseNetBC169 |14.2M |3.38G|77.35|93.62|1024|0.4|90|cosine|H Jiang
|DenseNetBC201 |20.0M |4.32G|77.04|93.50|1024|0.4|90|step-0.1-[30,60]|H Jiang
|DenseNetBC201 |20.0M |4.32G|78.06|93.92|1024|0.4|90|cosine|H Jiang
|DenseNetBC265 |33.3M |5.79G|77.60|93.78|1024|0.4|90|step-0.1-[30,60]|H Jiang
|DenseNetBC265 |33.3M |5.79G|78.17|94.01|1024|0.4|90|cosine|H Jiang
|DenseNetBC121 |8.0M |2.85G|76.30|93.20|512|0.2|300|cosine|Y Wang
|DenseNetBC265 |33.3M |5.79G|78.10|93.90|512|0.2|300|cosine|Y Wang

****
Still under construction.
