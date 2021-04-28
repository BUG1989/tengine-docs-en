# Model Support

Tengine has finished supporting mainstream computer vision models, including classification, detection, recognition, segmentation, key points and other functions.

| Catalog | Model          | Support Platform         |
| ------- | -------------- | ------------------------ |
| classification    | MobileNet V1   | ARM、X86、MIPS、GPU、NPU |
| detection    | MobileNet-SSD  | ARM、X86、MIPS、GPU、NPU |
| recognition    | MobileFaceNets | ARM、X86、GPU            |
| recognition    | YOLOv3         | ARM、X86、GPU            |
| recognition    | YOLOv3-Tiny    | ARM、X86、GPU            |
| recognition    | YOLOv4         | ARM、X86、GPU            |
| recognition    | YOLOv4-Tiny    | ARM、X86、GPU            |
| segmentation    | YOLCAT         | ARM                      |

**Tips**：

- The model link comes from Tengine Model ZOO, and we will continue to update it;
- Among the NPUs in the list of supported platforms, some models are implemented by heterogeneous computing, namely CPU+NPU.

