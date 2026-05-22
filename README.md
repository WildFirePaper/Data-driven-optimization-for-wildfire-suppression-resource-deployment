# Data-driven-optimization-for-wildfire-suppression-resource-deployment

## Data Availability

The real wildfire data used in this study cannot be publicly shared due to data privacy and confidentiality restrictions associated with the collaborating organization.

To support reproducibility while respecting these restrictions, we provide:

* The complete implementation code for the forecasting, queueing, and optimization framework
* A sample date instance that allows users to execute and verify the entire pipeline
* Example input files required for the optimization and queueing components
* Pretrained/saved models required for running the example pipeline

The provided example enables users to reproduce the computational workflow and verify the integration between the prediction, transient queueing, and optimization modules.

```

## Running the Pipeline

1. Download the pretrained models from the shared storage link below and place them inside the `models/` directory.

2. Open and run:

```python
Data_Code_Pipeline.ipynb
```

3. The notebook executes the full workflow for the provided sample date instance, including:

   * Demand prediction
   * Queueing calculations
   * Optimization-based resource deployment

## Pretrained Models

The pretrained models can be downloaded from:

[[MODEL_LINK_HERE](https://drive.google.com/drive/folders/139fXmXd2cQf4AXN6efnmEAOjhjTdzp3_?usp=drive_link)]

After downloading, place the files in:

```text
models/
```

## Notes

* The provided example is intended solely for piple analysis and demonstration purposes.
* The operational wildfire dataset used in the paper is confidential and therefore not included in this repository.
* The repository contains all necessary code to reproduce the computational framework.
* To run the optimization, you need a valid Gurobi license. 
* The computations involved in Figure 9 are presented in full detail.
