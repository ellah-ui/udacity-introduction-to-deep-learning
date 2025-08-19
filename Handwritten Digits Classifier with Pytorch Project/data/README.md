# Data Directory

This `data/` folder contains some of the datasets required to train and evaluate the Handwritten Digits Classifier built using PyTorch. It includes:

- Raw or preprocessed MNIST data (images, labels, or Torch tensors)
- Subdirectories (if any) for structured data storage (`train/`, `test/`, etc.)
- Any custom splits or auxiliary files used during development

---

##  What’s Inside

| File / Folder         | Description                                           |
|-----------------------|-------------------------------------------------------|
| `MNIST/raw/`          | Original MNIST files downloaded from torchvision      |
| `processed/` (optional) | Preprocessed datasets for quick loading               |
| Other data-related files | e.g., helper scripts or lookup tables (if included) |

---

##  Usage in Project

- The project scripts/notebooks use PyTorch’s `torchvision.datasets.MNIST`, which will automatically download and populate this folder.
- If you’re running offline or need reproducibility:
  - Place your MNIST `.pt`, `.pkl`, or raw image files here.
  - Ensure to set `download=False` in your data loading code to avoid re-downloading.

---

##  Note for Contributors

If you're modifying data loading or formats:
- Update the paths in your training/evaluation scripts.
- Ensure consistency in folder structure and naming for seamless integration.

---

**Summary**: This directory centralizes all data assets—clean, organized, and ready for your data pipelines in the MNIST digit classification project.

