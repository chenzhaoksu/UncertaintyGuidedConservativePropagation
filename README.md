# Uncertainty Guided Conservative Propagation

Accurate coronary artery segmentation plays a critical role in coronary artery disease diagnosis and treatment planning. However, existing deep learning approaches typically rely on independent pixel/voxel-wise predictions and do not explicitly model structural interactions during inference. This limitation becomes particularly evident in regions with ambiguous image evidence or weak structural support. We propose an Uncertainty-Guided Conservative Propagation (UGCP) framework that performs structure-aware refinement in logit space via constrained neighborhood updates inspired by conservative interaction. The update is driven by local prediction discrepancies and modulated by voxel-wise uncertainty, allowing high-confidence regions to guide structurally unstable areas in a controlled manner. A source term anchors the update to the initial logits, preventing excessive drift during structural correction. We evaluate the proposed framework on convolutional and Transformer-based segmentation backbones using public 2D invasive coronary angiography (ICA) and 3D coronary CT angiography (CCTA) datasets (616 ICA images and 1,000 CCTA volumes). Experimental results demonstrate consistent improvements in the Dice similarity coefficient (DSC), clDice, and boundary metrics across architectures. The proposed framework enhances inference-stage structural consistency and shows strong potential for improving the robustness of coronary artery analysis in clinical settings.

# Training instruction

# Testing instruction

# Environment
