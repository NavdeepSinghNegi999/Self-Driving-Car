# Udacity Car Simulator

This project is a simulation of a self-driving car, developed as part of the Udacity course.

## Project Setup Instructions

Follow these steps to set up and run the Udacity Car Simulator project:

1. **Download the Project**
   - Clone or download the Udacity Car Simulator repository into any project folder of your choice.

2. **Install Anaconda**
   - Ensure that **Anaconda3** is installed on your system. If you haven't installed it yet, download it from the [Anaconda website](https://www.anaconda.com/products/distribution#download-section).

3. **Create a New Conda Environment**
   - Open the Anaconda Prompt and run the following command to create a new environment:
     ```bash
     conda create -n car python=3.7 -y
     ```

4. **Activate the Conda Environment**
   - After creating the environment, activate it by running:
     ```bash
     conda activate car
     ```

5. **Install Required Libraries**
   - Install the necessary packages using the requirements file:
     ```bash
     pip install -r requirements.txt
     ```

6. **Troubleshooting**
   - If you encounter any errors during the installation, you may need to install additional libraries manually:
     ```bash
     pip install python-engineio==3.13.2
     pip install python-socketio==4.6.1
     ```

7. **Run the Simulator**
   - Finally, start the car simulator by executing the following command:
     ```bash
     python drive.py
     ```

