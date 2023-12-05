# BACKDOOR ATTACKS

This repository contains the code and resources for the project on detecting and mitigating backdoor attacks in neural networks. The project focuses on the implementation of a pruning strategy to defend against backdoor attacks in a convolutional neural network.

## Author Details

- **Name**: [AMAN MITTAL]
- **Net ID**: [AM11982]

## Repository Structure

The repository includes the following components:

- **Colab Notebook (`BackDoor_am11982.ipynb`)**: Contains the complete code for the project, including data loading, model setup, pruning strategy, and evaluation.

- **Lab Report (`lab2.pdf`)**: Detailed report of the laboratory work related to this project.

- **Project Report (`Report__BackDoor_Attacks_am11982_.pdf`)**: A comprehensive report on the methodology, results, and conclusions of the project.

- **Models Directory (`models/`)**: Contains the pre-trained BadNet model (`bd_net.h5`) and its weights (`bd_weights.h5`).

- **Data Directories**: Please create the following directories and upload the respective datasets:
    ```
    ├── data 
    │   ├── cl
    │   │   ├── valid.h5 // Clean validation data
    │   │   └── test.h5  // Clean test data
    │   └── bd
    │       ├── bd_valid.h5 // Sunglasses poisoned validation data
    │       └── bd_test.h5  // Sunglasses poisoned test data
    ├── models
    │   ├── bd_net.h5
    │   └── bd_weights.h5
    ├── architecture.py
    └── eval.py // Evaluation script
    ├── BackDoor_am11982.ipynb
    ├── lab2.pdf
    └── Report__BackDoor_Attacks_am11982_.pdf
    ```

## Running the Code

To execute the project code, follow these steps:

1. **Open the Notebook**: Load the `BackDoor_am11982.ipynb` file in Google Colab or a Jupyter Notebook environment.

2. **Download and Upload Datasets**: 
   - Access the datasets from this [Google Drive link](https://drive.google.com/drive/folders/1vw09supPHdXDhlBL_cZMru0k8cQi0gdX?usp=drive_link).
   - Upload the datasets to the corresponding directories as specified in the repository structure.

3. **Upload Model Files**: Upload the `bd_net.h5` and `bd_weights.h5` files to the `models/` directory.

4. **Run the Notebook**: Execute each cell in the notebook sequentially to perform the pruning strategy and evaluate the model.

## Expected Results

Upon successful execution, the notebook will provide the accuracy on clean test data and the attack success rate for the different levels of pruning applied to the BadNet model.
