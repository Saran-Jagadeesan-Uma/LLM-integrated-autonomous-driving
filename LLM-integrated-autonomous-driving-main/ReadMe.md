# LLM Integrated Autonomous Driving

## Overview
The LLM Integrated Autonomous Driving project aims to create a simulation environment for autonomous driving using advanced language models. The system integrates various components to simulate driving scenarios, make decisions based on the environment, and visualize the results.

## Features
- **Scenario Simulation**: Create and manage driving scenarios with multiple vehicles and lanes.
- **Decision Making**: Utilize language models to analyze driving situations and make decisions for the ego vehicle.
- **Data Storage**: Store vehicle and decision information in a SQLite database for later analysis.
- **Visualization**: Generate visual representations of driving scenarios and decisions made by the agent.
- **Web Interface**: A simple web interface to interact with the simulation and view decision information.

## Requirements
To run this project, you need to have the following Python packages installed:

- Flask==2.2.2
- gymnasium==0.28.1
- langchain==0.0.225
- openai==0.27.7
- matplotlib==3.7.1
- numpy==1.24.3
- PyYAML==6.0
- rich==13.4.2

You can install the required packages using pip:

1. pip install -r requirements.txt

## Setup
 - Clone the Repository:
     - git clone <repository-url>
     - cd LLM-integrated-autonomous-driving-main

 - Install the required packages as mentioned above.

 - Configure the OpenAI API settings in config.yaml:
	- Set the appropriate API type (Azure or OpenAI) and provide the necessary keys.
 - Start the simulation by running the main script:
	- python HELLM.py	
 - Open your web browser and navigate to http://127.0.0.1:5000 to access the web interface.
 - Enter the frame value to view the decision information of the Driver Agent.

## Project Structure
LLM-integrated-autonomous-driving-main/
│
├── LLM based AD/
│   ├── scenario/
│   ├── LLMDriver/
│   ├── results-video/
│   ├── templates/
│   ├── HELLM.py
│   ├── requirements.txt
│   └── ...
│
└── README.md

## Contributors

- [Saran-Jagadeesan-Uma](https://github.com/Saran-Jagadeesan-Uma)
- [1AlgoRythm](https://github.com/1AlgoRythm)

## Acknowledgments
- Thanks to the developers of the libraries and frameworks used in this project, including:
  - [Flask](https://flask.palletsprojects.com/)
  - [Gymnasium](https://gymnasium.farama.org/)
  - [Langchain](https://langchain.readthedocs.io/)
  - [OpenAI](https://openai.com/)