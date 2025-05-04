# End-to-End Machine Learning Pipeline with MLflow

This project provides a complete machine learning pipeline with integrated experiment tracking and model management using **MLflow**. The pipeline includes modular components for data processing, training, and evaluation, and is designed for scalability and reproducibility. The solution supports automated deployment to AWS EC2 with Docker and CI/CD through GitHub Actions, while tracking experiments remotely via **DAGsHub**.

---

## Features

* Modular ML pipeline for data, training, and evaluation workflows
* Experiment tracking and model management with MLflow
* Config-driven architecture for easy customization
* CI/CD pipeline for Docker-based deployment to AWS EC2
* Integration with DAGsHub for remote tracking

---

## Project Structure

```
├── config/           # Configuration files (YAML)
├── src/              # Source code for pipeline components
├── app.py            # Application entry point
├── main.py           # Training pipeline
├── Dockerfile        # Containerization setup
├── .github/          # GitHub Actions for CI/CD
```

---

## Setup and Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/End-to-End-Machine-Learning-Project-with-MLflow
```

### 2. Set up the Conda environment

```bash
conda create -n mlproj python=3.8
conda activate mlproj
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python app.py
```

Access the application via localhost.

---

## Deployment

This project includes automated deployment to **AWS EC2** using **Docker** and **GitHub Actions** for CI/CD.

---

## MLflow Tracking

Use MLflow to track experiments and models locally or via **DAGsHub** for remote tracking.

---

Let me know if you'd like any additional details or adjustments!
