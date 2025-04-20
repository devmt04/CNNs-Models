# CNNs Models

##  1. **Image Classification (Prediction)**
| Model        | Highlights                             |
|--------------|-----------------------------------------|
| **LeNet-5**      | Classic, for digits (MNIST)            |
| **AlexNet**      | ReLU, Dropout, ImageNet winner 2012    |
| **VGG-16/19**    | Simple 3x3 conv blocks                 |
| **GoogLeNet**    | Inception modules, multi-scale         |
| **ResNet**       | Skip connections, deep architectures   |
| **DenseNet**     | Dense connections, efficient           |
| **EfficientNet** | Compound scaling, SOTA                 |
| **ConvNeXt**     | Transformer-inspired CNN               |
| **RegNet**       | Scalable regular patterns              |

---

##  2. **Object Detection**
| Model         | Highlights                                       |
|---------------|--------------------------------------------------|
| **R-CNN**         | Region proposal + CNN                        |
| **Fast R-CNN**    | ROI pooling + faster inference               |
| **Faster R-CNN**  | Adds Region Proposal Network (RPN)           |
| **YOLO (v1–v8)**  | Real-time detection, end-to-end              |
| **SSD (Single Shot Detector)** | One-stage detector             |
| **RetinaNet**     | Focal loss to fix class imbalance            |
| **DETR**          | Transformer-based object detection           |

---

##  3. **Semantic Segmentation**
| Model          | Highlights                                    |
|----------------|-----------------------------------------------|
| **FCN (Fully Conv Net)** | First full-CNN for segmentation  |
| **U-Net**         | Encoder-decoder with skip connections     |
| **SegNet**        | Uses pooling indices from encoder         |
| **DeepLabV3/V3+** | Atrous (dilated) convolutions, ASPP       |
| **PSPNet**        | Pyramid pooling module                    |
| **HRNet**         | High-res features maintained throughout   |

---

##  4. **Instance Segmentation**
| Model              | Highlights                                     |
|--------------------|------------------------------------------------|
| **Mask R-CNN**         | Faster R-CNN + mask branch                 |
| **YOLACT**             | Real-time instance segmentation             |
| **SOLO (v1/v2)**       | Segmenting objects by locations             |
| **BlendMask**          | Combines instance + semantic features       |

---

##  5. **Pose Estimation**
| Model           | Highlights                                   |
|-----------------|----------------------------------------------|
| **OpenPose**        | Multi-person keypoint detection          |
| **HRNet**           | High-res pose heatmaps                   |
| **PoseNet**         | MobileNet-based, lightweight             |
| **SimpleBaseline**  | ResNet backbone + deconv head            |

---

##  6. **Scene Understanding / Panoptic Segmentation**
| Model               | Highlights                                       |
|---------------------|--------------------------------------------------|
| **Panoptic FPN**        | Combines semantic + instance segmentation   |
| **UPSNet**              | Unified panoptic segmentation                |
| **Swin Transformer**    | Modern panoptic vision tasks                 |

---

##  7. **Super-Resolution**
| Model         | Highlights                                |
|---------------|--------------------------------------------|
| **SRCNN**         | First CNN-based super-resolution      |
| **FSRCNN**        | Faster version of SRCNN               |
| **EDSR**          | Enhanced deep SR                      |
| **ESRGAN**        | GAN-based, photorealistic textures    |

---

##  8. **Image-to-Image Translation / Style Transfer**
| Model        | Highlights                                       |
|--------------|--------------------------------------------------|
| **Pix2Pix**      | Conditional GAN, paired image translation    |
| **CycleGAN**     | Unpaired image translation                   |
| **StyleGAN**     | Style-based generation                       |
| **DeepArt**      | Artistic style transfer                      |

---

##  9. **Medical Imaging Models**
| Model        | Highlights                                  |
|--------------|----------------------------------------------|
| **U-Net (3D)**    | Volumetric segmentation (CT/MRI)       |
| **V-Net**         | 3D segmentation model                   |
| **nnU-Net**       | Auto-configured U-Net for any dataset  |
| **TransUNet**     | Transformer + U-Net hybrid              |
