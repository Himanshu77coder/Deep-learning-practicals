# Experiment 6: Custom Image Dataset

This notebook fine-tunes a pre-trained VGG16 model and compares it with a CNN trained from scratch.

## Dataset setup

Keep the extracted dataset folder beside the notebook while running locally:

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

The dataset ZIP and extracted images are excluded from GitHub to keep the repository lightweight. Download or extract your local copy, then place it in the layout above before running the notebook.
