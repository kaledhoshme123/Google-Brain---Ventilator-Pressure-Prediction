# Google Brain - Ventilator Pressure Prediction
What do doctors do when a patient has trouble breathing? They use a ventilator to pump oxygen into a sedated patient's lungs via a tube in the windpipe. But mechanical ventilation is a clinician-intensive procedure, a limitation that was prominently on display during the early days of the COVID-19 pandemic. At the same time, developing new methods for controlling mechanical ventilators is prohibitively expensive, even before reaching clinical trials. High-quality simulators could reduce this barrier.

![header (1)](https://user-images.githubusercontent.com/108609519/201483257-41eb3799-afbc-447b-8fa6-ac30565c56d5.png)

- Partnering with Princeton University, the team at Google Brain aims to grow the community around machine learning for mechanical ventilation control. They believe that neural networks and deep learning can better generalize across lungs with varying characteristics than the current industry standard of PID controllers.

- I proposed a neural network architecture capable of simulating a ventilator connected to the lung of an anesthetized patient.
The proposed model helps overcome the cost barrier to develop new methods for controlling mechanical ventilation fans. This will pave the way for algorithms that adapt to patients and reduce the burden on clinicians during these new times and beyond. As a result, ventilator treatments may become more widely available to help patients breathe.
# Dataset Link:
https://www.kaggle.com/competitions/ventilator-pressure-prediction/overview

# Neural Network Architecture
![image](https://user-images.githubusercontent.com/108609519/202456223-ebd59234-2a1b-411a-812c-d1b8693a5caa.png)


# Result
## Loss training data vs Loss Validation data
![download (90)](https://user-images.githubusercontent.com/108609519/202456329-15151634-1410-4ed1-a208-308850e8ff2c.png)

## Evaluation Model on all dataset
![image](https://user-images.githubusercontent.com/108609519/202456416-e377c768-7818-4a0c-9e20-c203db4c5ace.png)


## Samples for predicting pressure and comparing them with basic pressure values
![download (91)](https://user-images.githubusercontent.com/108609519/202456516-9b64079b-53b0-4847-87db-2de1e67fd7a5.png)
![download (92)](https://user-images.githubusercontent.com/108609519/202456556-8bac4764-fa58-48ea-816f-373d7991143e.png)
![download (93)](https://user-images.githubusercontent.com/108609519/202456614-e74900ea-644e-40a1-9c9f-65f9d0d4c0f9.png)
![download (94)](https://user-images.githubusercontent.com/108609519/202456671-26b5e45d-2179-4078-83d0-49855c173227.png)

