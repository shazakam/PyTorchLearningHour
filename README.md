# SLB PyTorch Learning Hour

This Notebook was used for a talk / learning session I held on the basics of PyTorch for the Data and Domain Team at SLB whilst on placement. The data used for the tutorial comes from the NAB NYC Taxi Dataset.
The notebook contains the fundamentals for creating a Deep Learning Time Series Forecasting Model starting with:
  1. Data Pre-Processing - Splitting into Train, Validation and Test Data
  2. PyTorch Datasets and DataLoaders
  3. Creating Model Architecture using torch.nn Module
  4. Specifying Training Hyperparameters
  5. Creating a basic PyTorch Model Training Loop
  6. Visualising Training and Validation Loss
  7. Visualising Model Inference on Test Data
The Model presented in the Notebook only forecasts the next datapoint, but this can be increased by simply changing the forward_window parameter
<img width="1191" alt="Screenshot 2024-04-14 at 2 38 26 PM" src="https://github.com/shazakam/PyTorchLearningHour/assets/76884408/ddc47ff7-49cc-41ca-bd3f-45394ae81391">
