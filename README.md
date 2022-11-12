# Google Brain - Ventilator Pressure Prediction
What do doctors do when a patient has trouble breathing? They use a ventilator to pump oxygen into a sedated patient's lungs via a tube in the windpipe. But mechanical ventilation is a clinician-intensive procedure, a limitation that was prominently on display during the early days of the COVID-19 pandemic. At the same time, developing new methods for controlling mechanical ventilators is prohibitively expensive, even before reaching clinical trials. High-quality simulators could reduce this barrier.

- Partnering with Princeton University, the team at Google Brain aims to grow the community around machine learning for mechanical ventilation control. They believe that neural networks and deep learning can better generalize across lungs with varying characteristics than the current industry standard of PID controllers.

- I proposed a neural network architecture capable of simulating a ventilator connected to the lung of an anesthetized patient.
The proposed model helps overcome the cost barrier to develop new methods for controlling mechanical ventilation fans. This will pave the way for algorithms that adapt to patients and reduce the burden on clinicians during these new times and beyond. As a result, ventilator treatments may become more widely available to help patients breathe.
# Dataset Link:
https://www.kaggle.com/competitions/ventilator-pressure-prediction/overview

# Neural Network Architecture
![image](https://user-images.githubusercontent.com/108609519/201482772-0f5b43bf-964b-4d86-8c69-8c2590f7f1d0.png)

# Result
## Loss training data vs Loss Validation data
![download (86)](https://user-images.githubusercontent.com/108609519/201482804-a6e7e0d6-7fdb-4fe2-9787-76eb2c70e0eb.png)
## Evaluation Model on all dataset
![image](https://user-images.githubusercontent.com/108609519/201482953-39a9ab12-a137-497f-9a41-68c7b9db1c6c.png)

## Samples for predicting pressure and comparing them with basic pressure values
![download (87)](https://user-images.githubusercontent.com/108609519/201482815-2b3d37dc-2f38-42d7-8db9-4b04139895ed.png)
![download (88)](https://user-images.githubusercontent.com/108609519/201482903-633a3810-9bca-40df-844a-1bd4975d21e6.png)
![download (89)](https://user-images.githubusercontent.com/108609519/201482914-1ff2c4b5-3f79-4312-a223-d8bcc7da5fb0.png)
