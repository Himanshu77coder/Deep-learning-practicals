# Experiment 6: Custom Image Dataset

This notebook fine-tunes a pre-trained VGG16 model and compares it with a CNN trained from scratch.

## Dataset setup

The complete dataset is included alongside the notebook:

```text
Experiment-6/
├── Experiment_6.ipynb
└── custom_image_dataset/
    ├── circle/
    ├── square/
    ├── triangle/
    └── star/
```

Each class folder should contain its corresponding image files. The notebook detects class folders automatically and creates train, validation, and test splits.

The dataset contains four class folders with image files. Run the notebook from the `Experiment-6` directory so its relative dataset path resolves correctly.
