# Disease Prediction - Lettuce

## Description
This repository contains models for predicting diseases in lettuce plants using deep learning techniques. The models utilize CNN architectures such as VGG16, Grad-CAM for visualizing diseased regions, and LIME for model explainability.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/arathypradeep/Disease-Prediction-Lettuce.git
   ```
2. Navigate into the project directory:
   ```sh
   cd Disease-Prediction-Lettuce
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
Run the Jupyter notebooks using:
```sh
jupyter notebook
```
Open the desired notebook from the Jupyter interface.

## Project Structure
```
📦 Disease-Prediction-Lettuce
├── Gradcam (2).ipynb                 # VGG16 model with Grad-CAM for disease visualization
├── lettuce_recomentation_cnn.ipynb    # CNN model for disease prediction in lettuce
├── lime_lettuce (1).ipynb             # LIME for model explainability
├── README.md                          # Project README
├── requirements.txt                   # Python dependencies
```

## Contributing
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

