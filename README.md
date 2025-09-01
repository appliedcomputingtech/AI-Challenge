# AI Challenge

Welcome! you are a super star for making it here. This is your time to shine, an opportunity to show off your skills, understanding and more importantly coding abilities 😉. So relax, grab some coffee / whiskey (depending on time of day) and start developing on this take-home exercise.

We recommend that you implement deep learning models, using PyTorch exclusively for any models you develop

## Setup 💿

1. Clone this repository to your local machine.
2. Install the required Python libraries:

```shell
pip install -r requirements.txt
```

Please feel free to install any other repositories of your choice. For any deep learning implementations, please use [`PyTorch`](https://pytorch.org/)

## Challenge Overview 💪

The challenge is split into two parts, where first part involves the implementation of a model, training it on the data and testing it. Second part involves reporting and analysis, we recommend you create a Jupyter Notebook to showcase your analysis and interpretation of your model performance. The following sections go into greater detail for each of the parts.

### Part 1: Time Series Forecasting
In this part you will:

- Implement a time series forecasting model with a **Transformer** backbone and any prediction head design of your choice. (Implemented yourself, do not use externally implemented models) 
- Train the model on the provided dataset.
- Test the model to evaluate its performance.
- Benchmark your model to predict future trend in different time-windows, Select a time window that performs the best.

---
#### Datasets: CO2 Concentration Estimation
This dataset originates from Imperial College’s Carbon Capture Pilot Plant, which simulates industrial-scale CO₂ absorption processes relevant to the Oil & Gas industry. The task involves estimating CO₂ concentration levels at six different sampling points within the absorber unit.

For Oil & Gas industry, CO₂ capture and monitoring are critical components of modern Oil & Gas operations, particularly as companies transition toward low-carbon energy solutions. Accurate forecasting of CO₂ concentration helps improve process efficiency, reduce emissions, and ensure compliance with environmental standards.

- This task utilized a publicly available dataset from Imperial College’s Carbon Capture Pilot Plant, accessible through the [orginal repositry](https://github.com/tonyzyl/CO2-Soft-sensor-for-a-carbon-capture-pilot-plant/tree/main/data/withLabel). 
- This task requires estimating the CO2 concentration at six distinct sampling points in the absorber. For more details on the dataset and preprocessing steps, please refer to the [official notebook](https://github.com/tonyzyl/CO2-Soft-sensor-for-a-carbon-capture-pilot-plant/blob/main/Estimate_CO2_profile.ipynb). 
- If you choose to proceed with this task, we strongly recommend using `140207_1.xlsx` as the test dataset, while the remaining files serve as the training dataset. Our team will send the related paper via email, please feel free to read it for additional background information.

---

### Part 2: Interpretability & Reporting
In this part, you will:

- Analyse the performance of your model.
- Interpret the results and provide the related **ROOT CAUSE ANALYSIS**.
- Document your analysis and findings in a Jupyter Notebook, including visualizations and detailed explanations.

---

### Part 3: Towards a Production-Ready Deployment
If you have additional time, we encourage you to go beyond research prototyping and demonstrate how the model could be deployed in a production-like Oil & Gas environment. This is critical for bridging the gap between proof-of-concept and real-world operational systems.

1. **Database Integration**
    - Load test data (e.g., CO₂ sensor readings) into PostgreSQL with a schema reflecting time-series sensor logs.
2. **Model Serving**
    - Wrap the trained Transformer model in a FastAPI service.
    - Provide a REST endpoint for predictions at given timestamps or time windows.
3. **Containerization & Deployment**
    - Dockerize the pipeline (Postgres + FastAPI + preprocessing).
    - Supply a `docker-compose.yml` for one-command setup.

## What we'd like to see 🙀
We'd like to see:

- Effective use of deep learning models, innovative learning strategies and monitoring techniques, implemented exclusively in PyTorch.
- Clear and concise code, with appropriate comments and documentation. Please share your results in a github repository with instructions on how to run and reproduce your results.
- Analysis and interpretation of your model's performance.
- Insightful visualisations that help explain your results and findings.

## What you'd be assessed on 🔎

You will be assessed on:

- Model Implementation: How well you implement the time series forecasting model using PyTorch.
- Performance: The accuracy and reliability of your model on the test data.
- Analysis: The depth and clarity of your analysis in the Jupyter Notebook.
- Interpretability: How well you interpret and explain the results of your model.
- Code Quality: The readability, organization, and documentation of your code.
- Visualizations: The effectiveness of your visualizations in conveying your findings.

Good luck, and we look forward to seeing your work!

## Additional support 🤝
If you have any questions, or need further clarification of any of the challenges. 

Then please reach out to: 
📣 nick@appliedcomputing.com 📣
