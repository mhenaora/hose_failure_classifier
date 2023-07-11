# Hose Failure Dataset

> Inside the data folder clone this repo

For clonning the repo via HTTP:

```bash
git clone https://github.com/mhenaora/hose_failure_dataset.git
```

Or via SSH:

```bash
git clone git@github.com:mhenaora/hose_failure_dataset.git
```

## Dataset Description

This dataset was created specifically for the development of a real-time classifier using deep learning for image processing, here solution available at the [Hose Failure Classifier Repository](https://github.com/mhenaora/hose_failure_classifier). The dataset contains images of failures in four types of hoses: SWAN, BICOLOR, GAS, and PRESION, captured from four [ARDUCAM IMX519](https://docs.arducam.com/Raspberry-Pi-Camera/Multi-Camera-CamArray/Multi-Camera-CamArray/ "ARDUCAM IMX519") cameras positioned at 90-degree intervals to analyze the perspective and integrity of the hoses in a 360-degree view. The images were collected at a resolution of 640x360 pixels.

The dataset currently has two versions: 1.0 and 2.0. Each version serves a different purpose  The dataset is organized according to the following directory structure:

```
.
├── 1.0
│   ├── 1-1
│   │   ├── GAS_0
│   │   ├── GAS_1
│   │   ├── SWAN_0
│   │   └── SWAN_1
│   ├── 2-1
│   │   ├── BACKGROUND
│   │   ├── GAS_0
│   │   ├── GAS_1
│   │   ├── SWAN_0
│   │   └── SWAN_1
│   └── 4-1
│       ├── BACKGROUND
│       ├── GAS_0
│       ├── GAS_1
│       ├── SWAN_0
│       └── SWAN_1
└── 2.0
    └── 2-1
        ├── GAS
        │   ├── BACKGROUND
        │   ├── FAILURE
        │   ├── GOOD
        │   └── WARNING
        └── SWAN
            ├── BACKGROUND
            ├── FAILURE
            ├── GOOD
            └── WARNING
```

## Repository Link

The current version of the dataset is available in the following repository: [Hose Failure Classifier Dataset](https://github.com/mhenaora/hose_failure_dataset)
