# Continuous Integration with GitHub Actions

## Description
This project demonstrates how to set up a continuous integration (CI) pipeline using GitHub Actions. It includes a simple C++ program and a GitHub Actions workflow that builds and runs the program on each push or pull request.

## Setup
To set up the project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/continuous_integration.git
    cd continuous_integration
    ```

2. Build the project:
    ```bash
    mkdir build
    cd build
    cmake ..
    make
    ```

3. Run the executable:
    ```bash
    ./continuous_integration
    ```

## Expected Output
    Hello, Continuous Integration!
