# KQC7035-RESEARCH-PROJECT
Deep Learning-based Reflection Removal for Enhanced Image Quality  
基于深度学习的反射消除以提高图像质量
  
This report investigates the problem of single image reflection removal, crucial for
improving image quality in photography, medical imaging, and autonomous systems. A
comparison study was done on three deep learning frameworks: location-aware single
image reflection removal (SIRR), Cooperative Reflection Removal Network (CoRRN),
and Iterative Boost Convolutional LSTM Network (IBCLN). Extensive experiments on
multiple datasets identified IBCLN as the most effective, excelling in metrics like Peak
Signal-to-Noise Ratio (PSNR) and Structural Similarity Index Measure (SSIM). To
further improve IBCLN's performance, Generalized Histogram Equalization (GHE) was
adopted to enhance brightness and visual quality after reflection removal. Although GHE
reduced PSNR and SSIM values slightly, it significantly improved image brightness,
contrast, and visual appeal. Despite IBCLN's strengths, challenges remain in processing
speed and handling complex scenes or varying reflection intensities in real-time
applications. Future work will focus on optimizing the model to balance these trade-offs,
possibly through dynamic adjustment of GHE parameters, while reducing artifacts and
improving real-time processing. This report advances deep learning-based image
reflection removal, highlighting strengths and areas for improvement.
