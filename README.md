# YFCC392K Face Attributes Dataset

A large-scale weakly-labeled face attribute dataset derived from YFCC100M for self-/weakly-supervised face recognition methods.

## Dataset Overview

The YFCC392K dataset consists of 392,000 face images with the following characteristics:
- Image resolution: 128x128 pixels
- 40 facial attributes
- Derived from YFCC100M dataset[7]
- Curated subset optimized for face recognition tasks[1]

## Key Features

- **Large-scale Dataset**: Contains 392K images extracted from the YFCC100M collection[1][8]
- **Attribute Annotations**: Includes 40 facial attribute annotations per image
- **Cleaned Data**: Outliers removed using Elliptic Envelope algorithm, resulting in 353K refined face images[8]
- **Pseudo Labels**: Generated using MixMatch algorithm for improved training

## Usage

This dataset is available for research purposes and includes:
- Image IDs
- Image links
- Bounding box coordinates[8]

## Dataset Creation Process

1. Initial extraction from YFCC100M
2. Facial attribute querying
3. Outlier removal using Elliptic Envelope
4. Pseudo-label generation with MixMatch
5. Validation against CelebA dataset

## Citation

```bibtex
@inproceedings{yavuz2021yfcc,
    title={YFCC-CelebA Face Attributes Datasets},
    author={Yavuz, M. C. and Ali Ahmed, S. A. and Kısaağa, M. E. and Ocak, H. and Yanıkğlu, B.},
    booktitle={2021 29th Signal Processing and Communications Applications Conference (SIU)},
    year={2021},
    pages={1-4},
    doi={10.1109/SIU53274.2021.9477959}
}
```

## License

This dataset is available for non-commercial research purposes only.

## Acknowledgments

This work builds upon the YFCC100M dataset and CelebA benchmark dataset.

## Contact

For questions and dataset access, please open an issue in this repository.

Note: This repository contains only metadata and documentation. Image data must be accessed through the provided links following the terms of use.
