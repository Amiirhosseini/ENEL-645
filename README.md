# Neural Network Applications in SO2 Saturation Monitoring

## Project Overview
This repository contains the implementation and documentation of the ENEL 645 project, which explores the application of neural networks in spectroscopic analysis for oxygen saturation (SO2) monitoring. Using diffuse reflectance spectroscopy and multilayer perceptrons (MLP), the project promises to provide accurate and real time estimated levels of oxygenation in biological tissues.

## Contents
- `so2_saturation_monitoring.ipynb`: A Jupyter notebook implementing the neural network model for SO2 saturation monitoring with data preprocessing, training and evaluation.
- `project_report_neural_networks_so2.pdf`: Detailed project report covering the methodology, results and future directions.
- `requirements.txt`: List of dependencies that need to be installed to run the code.

## Key Features
- Implementation of Monte Carlo simulations that have been developed to generate spectral data for training and validation.
- Deep Multilayer Perceptron (MLP) model for feature extraction and prediction.
- Evaluation metrics Assigning RMSD and R2 for validation of model performance.
- Tested for robustness with numerous scenarios inter-animal and inter-time variation.

## Getting Started
### Clone the Repository
```bash
git clone https://github.com/yourusername/neural-network-so2-monitoring.git
cd neural-network-so2-monitoring
```

### Install Dependencies
Ensure you have Python 3.8+ installed. Use the following command to install all necessary libraries:
```bash
pip install -r requirements.txt
```

### Directions for Running
1. **Opening The Jupyter Notebook**: 
   Run a Jupyter Notebook server within your terminal via the command below:
   ```bash
   jupyter notebook
   ```
   Your default browser will display the Jupyter interface.

2. **Run The Notebook**:
   Open the file now called `so2_saturation_monitoring.ipynb` in the Jupyter interface. Sequentially run the cells and all of the code. Hence:
   - Normalize data.
   - Train the neural network model.
   - Evaluate results and visualize the same.

3. **Find The Results**: 
   It includes all the different visualizations and performance metrics which are then created after running the cells present in the notebook.

Methodology 
The project is very systematic: 
1. Simulated - data generation: simulated spectral data.
2. The maximum-minimum normalization is foreseen as the preprocessing applied to spectral data, whereby feature relationships are kept alive.
3. Design of neural network: solid MLP network and trained with Adam Optimizer for robustness.
4. Evaluation: cross-validation and metrics (RMSD, R²) to ensure model reliability.

## Results
Performance of the MLP model was found to be better than that from the state of the art: 
- R²: 0.89 on test data
- Robust against noise

## Future Work
- In vivo validation to test clinical applicability.
- Integration with imaging modalities for enhanced diagnostic accuracy.
- Deployment on low-resource systems for wider accessibility.

## Contributors
- **Amirreza Hosseini** (University of Calgary)
- **Ali Mohammadi Ruzbahani** (University of Calgary)

## References
Refer to `project_report_neural_networks_so2.pdf` for detailed citations.

## License
[MIT License](LICENSE)
