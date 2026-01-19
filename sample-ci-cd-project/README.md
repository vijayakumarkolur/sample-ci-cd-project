# Sample CI/CD Project

A sample project demonstrating CI/CD pipeline with Jenkins integration.

## Project Structure

```
sample-ci-cd-project/
├── app/              # Main application code
├── tests/            # Test suite
├── requirements.txt  # Python dependencies
├── Jenkinsfile       # CI/CD pipeline configuration
└── README.md         # Project documentation
```

## Setup

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Run tests:
   ```bash
   pytest tests/
   ```

3. Run the application:
   ```bash
   python app/main.py
   ```

## CI/CD Pipeline

The project uses Jenkins for continuous integration and deployment. The pipeline includes:
- Code checkout
- Dependency installation
- Running tests
- Building the application
