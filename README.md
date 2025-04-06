# Gamma vs Hadron: Predicting Particle Type in MAGIC Gamma Telescope

This project focuses on classifying events detected by the MAGIC Gamma Telescope as either gamma rays or hadrons, utilizing the [MAGIC Gamma Telescope dataset](https://archive.ics.uci.edu/ml/datasets/MAGIC+Gamma+Telescope) from the UCI Machine Learning Repository.

## Project Overview

Accurate classification of gamma and hadron events is crucial for astrophysical analyses conducted with the MAGIC (Major Atmospheric Gamma Imaging Cherenkov) telescope. This project employs machine learning techniques to distinguish between these two types of particles based on recorded event parameters.

## Dataset

The dataset comprises 19,020 instances with 11 attributes:

- **fLength**: Continuous variable representing the major axis of the ellipse [mm].
- **fWidth**: Continuous variable representing the minor axis of the ellipse [mm].
- **fSize**: Continuous variable representing the sum of content of all pixels [photo-electrons].
- **fConc**: Continuous variable representing the ratio of sum of two highest pixel contents to fSize [ratio].
- **fConc1**: Continuous variable representing the ratio of highest pixel content to fSize [ratio].
- **fAsym**: Continuous variable representing the distance from the shower centroid to the highest pixel [mm].
- **fM3Long**: Continuous variable representing the third root of third moment along the major axis [mm].
- **fM3Trans**: Continuous variable representing the third root of third moment along the minor axis [mm].
- **fAlpha**: Continuous variable representing the angle of major axis with vector to origin [deg].
- **fDist**: Continuous variable representing the distance from the origin to the shower centroid [mm].
- **Class**: Categorical variable indicating the type of event ('g' for gamma rays and 'h' for hadrons).

For more details, refer to the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/MAGIC+Gamma+Telescope).

## Usage Instructions

To replicate the analysis:

1. **Download the Dataset**: Obtain the `magic04.data` file from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/MAGIC+Gamma+Telescope).

2. **Open the Notebook**: Access the `MAGIC_dataset.ipynb` file in [Google Colab](https://colab.research.google.com/).

3. **Upload the Dataset**: In the Colab interface, upload the `magic04.data` file to the session storage.

4. **Execute the Notebook**: Run all cells in the notebook to preprocess the data, train, validate, and test the classification models. The notebook provides detailed explanations and outputs for each step.

## Contributing

Pull requests are welcome.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Acknowledgments

Special thanks to the UCI Machine Learning Repository for providing the [MAGIC Gamma Telescope dataset](https://archive.ics.uci.edu/ml/datasets/MAGIC+Gamma+Telescope), which forms the foundation of this project.
