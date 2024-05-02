# Geminus

## Introduction
This is the repository is collection of jupyter notebooks for CARLA simulation environment for autonomous driving using Generative AI. The project is developed using Gemini API and CARLA simulation environment. The project is developed as a part of the Google Hackathon @Devpost.


## Installation and Prerequisites

### Prerequisites
Before proceeding with the installation, ensure you have the following prerequisites installed:

- **Anaconda**: Anaconda is a distribution of Python that includes many popular packages for data science and machine learning. You can download and install Anaconda from [here](https://www.anaconda.com/products/distribution).

- **CARLA Simulator (Version 0.9.14)**: CARLA is an open-source simulator for autonomous driving research. Version 0.9.14 is required for this project. You can download it from the [CARLA GitHub releases](https://github.com/carla-simulator/carla/releases/tag/0.9.14).


### Installation
Once you have the prerequisites installed, follow these steps to install and set up the project:

1. Clone the repository:
    ```bash
    git clone https://github.com/pritisolanki/Geminus.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Geminus
    ```

3. Create a new Anaconda environment (optional but recommended):
    ```bash
    conda create --name project_env python=3.8
    ```

4. Activate the Anaconda environment:
    ```bash
    conda activate project_env
    ```

5. Install the required Python packages from `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```

6. Download and extract the CARLA Simulator (Version 0.9.14) to a desired location on your system.

7. Open jupyter notebook Stage_0.ipynb
    ```bash
    jupyter notebook
    ```
8. You're all set! You can now run the project using Python.

---


## Utilities
### 1. image_verifier.ipynb
Playground notebook for setting up camera configuration and openCV. OpenCV is a great tool for image processing and performing computer vision tasks. 

### 2. video_data_collector.ipynb
Playground notebook for collecting video data from the CARLA simulation environment. The notebook uses the CARLA Python API to collect video data from the simulation environment.

## Stage_0.ipynb
This notebook is the first stage of the project. The notebook is used to setup the CARLA simulation environment and the Python API. The notebook is used to setup the environment and showcase communication between CARLA and GEMINI. The api integration code is written in [Node JS Codebase](https://github.com/pritisolanki/gemini_api). 
In stage 0 we are controlling forward motion by applying throttle and brakes based on the traffic signal state.
