# KQC7035-RESEARCH-PROJECT
Deep Learning-based Reflection Removal for Enhanced Image Quality  [Download PDF](blob:https://github.com/d6523623-8428-4504-acc0-ee0341f4a2b8)
  
基于深度学习的反射消除以提高图像质量
  
# Abstract  
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
  
 本报告研究了单幅图像反射消除问题，这对于提高摄影、医学成像和自主系统中的图像质量至关重要。对三个深
度学习框架进行了比较研究：位置感知单幅图像反射消除 (SIRR)、协同反射消除网络 (CoRRN) 和迭代增强
卷积 LSTM 网络 (IBCLN)。在多个数据集上进行的大量实验表明，IBCLN 是最有效的，在峰值信噪比 (PSNR) 和
结构相似性指数测量 (SSIM) 等指标方面表现出色。为了进一步提高 IBCLN 的性能，采用了
广义直方图均衡 (GHE) 来增强反射消除后的亮度和视觉质量。虽然 GHE 略微降低了 PSNR 和 SSIM 值，但它显著
提高了图像亮度、对比度和视觉吸引力。尽管 IBCLN 具有优势，但在处理速度和处理实时应用中的复杂场景或变化的
反射强度方面仍然存在挑战。未来的工作将侧重于优化模型以平衡这些权衡，可能通过动态调整 GHE 参数，同时减少
伪影并改善实时处理。本报告推进了基于深度学习的图像反射消除，突出了优势和需要改进的领域。
  
