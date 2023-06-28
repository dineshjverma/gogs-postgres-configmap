# gogs-postgres-configmap
Kubernetes Multi-Tier Application with Gogs and Postgres

This Git repository contains the configuration files and deployment scripts for a multi-tier application deployed on Kubernetes. The application consists of two main components: Gogs, a self-hosted Git service, and PostgreSQL, a powerful open-source relational database.

To ensure seamless integration and efficient communication between the components, this deployment utilizes ConfigMaps in Kubernetes. The application is designed to leverage the following specific configurations:

Host: The PostgreSQL backend is accessed using the hostname postgres.backend.svc.cluster.local. This ensures that the application connects to the correct service within the Kubernetes cluster.

User: The PostgreSQL user used for authentication is set as dinesh. This user is granted the necessary privileges to interact with the database.

Password: The password for the dinesh user is set as alexa. It is recommended to use strong and secure passwords in production environments.

Database: The application employs a PostgreSQL database named unnati. This database stores the relevant data required for the multi-tier application to function correctly.

By utilizing Kubernetes and its powerful features, this repository provides a streamlined approach for deploying a multi-tier application. With Gogs handling the Git service and PostgreSQL managing the database, developers can collaborate effectively while ensuring data persistence and reliability.

Feel free to explore the repository to gain insights into the Kubernetes configuration files and deployment scripts used to orchestrate this multi-tier application.
