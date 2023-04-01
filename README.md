# MS-FPN
In the remote sensing field, synthetic aperture radar (SAR) is a type of active microwave
imaging sensor working in all-weather and all-day conditions, providing high-resolution SAR
images of objects such as marine ships. Detection and instance segmentation of marine ships
in SAR images has become an important question in remote sensing, but current deep learning
models cannot accurately quantify marine ships because of the multi-scale property of marine ships
in SAR images. In this paper, we propose a multi-scale feature pyramid network (MS-FPN) to
achieve the simultaneous detection and instance segmentation of marine ships in SAR images. The
proposed MS-FPN model uses a pyramid structure, and it is mainly composed of two proposed
modules, namely the atrous convolutional pyramid (ACP) module and the multi-scale attention
mechanism (MSAM) module. The ACP module is designed to extract both the shallow and deep
feature maps, and these multi-scale feature maps are crucial for the description of multi-scale
marine ships, especially the small ones. The MSAM module is designed to adaptively learn and
select important feature maps obtained from different scales, leading to improved detection and
segmentation accuracy. Quantitative comparison of the proposed MS-FPN model with several
classical and recently developed deep learning models, using the high-resolution SAR images dataset
(HRSID) that contains multi-scale marine ship SAR images, demonstrated the superior performance
of MS-FPN over other models.
# Citation
## If you use this toolbox or benchmark in your research, please cite this project.
Sun, Z.; Meng, C.; Cheng, J.; Zhang, Z.; Chang, S. A Multi-Scale Feature Pyramid Network for Detection and Instance Segmentation of Marine Ships in SAR Images. Remote Sens. 2022, 14(24), 6312.
