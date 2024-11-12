# k8s-manifests

This repository serves as a centralized location for Kubernetes manifests of applications to be deployed.

## Structure

- `dev/`: Contains development-related Kubernetes manifests.
  - `deployment.yml`: Example deployment configuration for an Nginx application.
- `pro/`: Contains production-related Kubernetes manifests.
  - `deployment.yml`: Example deployment configuration for an Nginx application.

## Usage

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Apply the Kubernetes manifests:
    ```sh
    kubectl apply -f dev/deployment.yml
    ```

## Contents

- `dev/deployment.yml`: Defines a deployment for an Nginx application with 3 replicas.

## Contributing

Feel free to submit issues or pull requests if you have any improvements or suggestions.

## License

This project is licensed under the MIT License.