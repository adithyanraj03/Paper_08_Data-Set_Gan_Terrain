
## Overview
This repository contains a structured dataset of terrain information designed for advanced computational research in geographic data modeling. The data combines synthetically generated terrain models with real-world geographic data from authoritative sources.
This sample represents a subset of a larger comprehensive dataset used in our research. The data has been organized into clusters for easier navigation and sampling.

## Repository Structure
The repository is organized into multiple data clusters, each containing approximately 100 terrain samples:

```
├── data-cluster00/
│   ├── generator0001.json
│   ├── generator0001_h.png
│   ├── generator0001_i2.png
│   ├── generator0001_ih.png
│   ├── generator0001_t.png
│   ├── generator0001_matrices.npz
│   ├── generator0001_stats.csv
│   └── ... 1000 cluster files in each batch folders
├── data-cluster01/
├── data-cluster02/
└── ... 1000 cluster files in each batch folders
```

## File Description

Each terrain sample includes multiple representations:
- `*.json` - Complete terrain data including height matrix and statistical metadata
- `*_h.png` - Height map visualization
- `*_i2.png` - Secondary interpretation visualization
- `*_ih.png` - Integrated height visualization
- `*_t.png` - Texture map
- `*_matrices.npz` - Compressed numerical matrices for computational processing
- `*_stats.csv` - Statistical summary including data type, min/max values, mean, and standard deviation

## Data Sources

This dataset incorporates:
- Procedurally generated synthetic terrain models
- Geographic data from reputable sources including:
  - NASA Visible Earth topography data
  - Natural Earth Data cultural vectors
  - NASA Earth Observatory night lights data

## Sample Visualizations

Below are examples of the different visualization types included in this dataset:

*Cluster : generator0028*

### Heightmap Representation

![generator0028_h](https://github.com/user-attachments/assets/75db6267-6791-4de7-b694-d3ba845fabc3)

Grayscale representation of elevation values where brightness corresponds to height

### Classification Map

![generator0028_i2](https://github.com/user-attachments/assets/ae1e3c21-d554-4d64-a06e-073755c51464)

Color-coded representation of terrain types and surface features

### Texture Map

![generator0028_t](https://github.com/user-attachments/assets/27536ff1-39d0-4163-89d5-7db995c183a0)

Color-textured visualization with relief shading to highlight topographical features



### Feature Intensity Map

![generator0028_ih](https://github.com/user-attachments/assets/40dc8414-e31d-4306-b577-641711934e4c)

Heat map visualization showing intensity of specific terrain features with corresponding value scale

### Analytical Overlay


![generator0028_it](https://github.com/user-attachments/assets/871e405d-9a92-4633-9944-7e247cb19e15)

Multi-channel representation with feature detection highlighting typical geomorphological patterns



Example of statistical distribution metrics stored in generator0028_stats.csv :

| data_type                | min_value              | max_value | mean_value        | std_dev           |
|--------------------------|------------------------|-----------|-------------------|-------------------|
| height                   | 1.0                    | 27955.0   | 11861.979527      | 4600.279871       |
| terrain                  | 91.0                   | 251.0     | 213.504738        | 16.407035         |
| correlation              | -0.321435              |           |                   |                   |
| height_gradient_magnitude| 242848.954             |           |                   |                   |
| terrain_gradient_magnitude| 110.756687            |           |                   |                   |

Each visualization type corresponds to different analytical aspects of the same underlying data structure. Statistical distributions for these representations are available in the accompanying CSV files.

*Note: The images in the repository README would display samples of your visualizations, which would be helpful for users to understand the data format without revealing your specific research methodology.*

## Usage Notes

This dataset is designed for researchers working on advanced computational modeling of geomorphological features. While we've provided multiple visualization formats, the core data is contained in the JSON and NPZ files for computational use.
This dataset is provided primarily for research verification purposes. The complete methodology and implementation details are available in our research paper (see citation below).

## Citation

If you use this data in your research, please cite our upcoming paper:
```
[Citation placeholder - will be updated upon publication]
```

## License
This project is licensed under the GNU General Public License v3.0 (GPL-3). This means:
* The software is free to use and open source
* You can modify and distribute the software
* Commercial use requires licensing from the original authors

For full license details, see the LICENSE file.

## Full Data Access
This is a sample of our complete dataset. Researchers interested in collaboration or requiring access to the full dataset should contact directly.

## Contact

For questions regarding this dataset, please open an issue in this repository or contact the repository owner directly mail : adithyanraj03@gmail.com .
