# MRI-Transform

## Contrast-to-contrast MRI transformation using unpaired image translation

This project focused on improving diagnostic flexibility in medical imaging by training a CycleGAN model to convert T1‑weighted MRI scans into T2‑weighted scans — and vice versa — without needing paired datasets. The model preserved structural integrity across contrasts, achieving a Structural Similarity Index (SSIM) of 97%, validating the effectiveness of contrast transformation in enhancing radiological interpretation and multi‑modal training.

![image info](mri-transform.gif)

Built using TensorFlow, the pipeline supports seamless model training, evaluation, and visualization via Matplotlib. The final models generate synthetic contrast images that mimic clinical scans, helping augment datasets where certain MRI modalities are underrepresented.
