# Wine Quality Prediction with MLflow

This project is an end-to-end example of a wine quality prediction system, which combines machine learning, web development, containerization with Docker, and cloud deployment on AWS. The primary technologies used include `Python`, `MLflow`, `YAML`, `HTML`, `CSS`, `JavaScript`, `Docker`, and `AWS`.

## Project Overview

The goal of this project is to predict the quality of wine based on various features. We utilize a machine learning model to make predictions, and `MLflow` helps us manage and track the experimentation process to find the best model parameters.

The project consists of several components:

1. **Machine Learning Model (`Python`)**: `Python` is used to develop a machine learning model for wine quality prediction. We experiment with different hyperparameters like `alpha` and `l1_ratio` to optimize the model's performance.

3. **`MLflow` (`Python`)**: `MLflow` is used for tracking and managing the machine learning experiments. It helps us log and compare different runs, record model parameters and metrics, and store artifacts (e.g., model files).

4. **Web Interface (`HTML`, `CSS`, `JavaScript`)**: We create a user-friendly web interface that allows users to input wine feature values and obtain predictions. The website is designed using `HTML`, styled with `CSS`, and enhanced with `JavaScript` for interactivity.

5. **Docker (`Dockerfile`)**: We containerize the entire project using `Docker`. The `Dockerfile` specifies the environment and dependencies required for the project, ensuring consistent and reproducible deployments.

6. **`AWS` (Amazon Web Services)**: `AWS` is used for cloud deployment. Specifically, we leverage the following services:
   
   - **Amazon Elastic Container Registry (`ECR`)**: We push the Docker image to `ECR`, a fully-managed Docker container registry, for easy and secure storage and distribution.
   
   - **Amazon EC2 (Elastic Compute Cloud)**: We use `EC2` instances to host the Docker container, making the website publicly accessible. The container is pulled from `ECR` and launched on the `EC2` instance.

7. **GitHub Repository**: Hosted this github repository on AWS for accessbility to the public.



## License

This project is licensed under the MIT License.
