# Apache-Airflow

![Apache Airflow logo](https://user-images.githubusercontent.com/115605874/221374795-a7798141-da31-4030-89ce-7c6254f211a7.png)

This is a sample project demonstrating how to create your first DAG (Directed Acyclic Graph) using Apache Airflow and Python. In this DAG, we have three training models that return fake accuracies between 0 and 10. The second task is to classify the model as accurate or inaccurate, and the third task is to display whether the model is accurate or not to the user interface.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Install Apache Airflow by running the command `pip install apache-airflow` or use the yaml file install apache airflow with Docker (Simply, run "docker-compose up airflow-int" to intialise the database and "docker-compose up -d" to the container running an dyou are good to go.).
3. Start the Airflow web server by running the command `airflow webserver -p 8080`.
4. Access the Airflow web interface by opening a web browser and navigating to `http://localhost:8080`.
5. Define your DAG as a Python script, using the Airflow API to specify the tasks and dependencies.
6. Execute your DAG by triggering it in the Airflow web interface.

<img width="929" alt="image" src="https://user-images.githubusercontent.com/115605874/221375175-17834dff-1afe-4186-be49-91440169b664.png">


## License

This repository is licensed under the Apache License, Version 2.0. See the [LICENSE](LICENSE) file for more information.
