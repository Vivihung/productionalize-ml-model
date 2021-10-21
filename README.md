# productionalize-ml-model
_\*\*Working in progress.\*\*_

A playground to demonstrate how to productionalize AI/ML models for developers.

Key deliverables
- [ ] Code change management via GitHub.
- [ ] Deploy the model to the cloud (Microsoft Azure) as an API for real time inferencing.
- [ ] CI/CD enabled for ML code update.
- [ ] Enable local model validation.
- [ ] Integrate the workflow with Azure Machine Learning Studio.
- [ ] Model version managment in cloud.


## About the ML model
The code of the ML model is from an [example](https://github.com/ageron/handson-ml2/blob/master/02_end_to_end_machine_learning_project.ipynb) in [Hands-on Machine Learning with Scikit-Learn, Keras & TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) by Aurélien Géron.
It is a linear regression model that predict housing price in Calafornia.

Plan to use the same algorithm to create another house price prediction model in King County, Washington.

## About the application
The front-end will be a simple website that taking user input and display the prediction value.

Note: The data used in this project is not the latest therefore the preduection value is expected to be off.
