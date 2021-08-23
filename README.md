# camel-dbi

_**Dynamic Behavior Identification**_

For the more agile movements of the robots, we need to identify the dynamic states of the robots.
we estimate the dynamic states of the robots through machine learning (especially Neural Networks) with current states of the robots.
Let's Start with us!!!

_**Get started (Windows 10)**_

**1. Environment settings (Anaconda3)**
  - Anaconda3 : easy to manipulate the versions of the libraries and create virtual environments
  
  1) Download Anaconda3 : https://www.anaconda.com/
  2) Initiate 'Ananconda Navigator'
  3) Create New Virtual Environment
      : 'Environment' Tab - 'Create' - Name : Your own virtual env. name - Package : Python 3.8
  4) Download libraries
      : 'Play' button - 'Open Terminal'
       
        You can download libraries through under commands
        -----------------------------------------------------------------------
        | **Library**       **Required version**  **Command**                 |                 
        | Tensorflow    2.5.0             pip install tensorflow==2.5.0       |
        | Scikit-learn  0.24.2            pip install scikit-learn==0.24.2    | 
        -----------------------------------------------------------------------
        
        we use tensorflow.keras for training of neural networks
        And scikit-learn will be used to divide test sets and validation sets.
        
  5) Anaconda3 setting is done! check the environment with example code.
      : 'Play' button - 'Open with Jupyter Notebook' - $Your Path of dir - examples - example1_environment_check.ipynb
      
**2. Data collection**
  - Collect data from simulators or your robots
  - NOTE : we have to save the data in **Numpy Array format** In order to use it in the training sequence.

**3. Init. Machine Learning!**
  - Open example2_DNN.ipynb
  - Each code is described in the code! please follow the sequence step by step.
  - learning sequence consists in 3steps
      1) Data load & Data pre-processing
      2) Construct Neural Network architecture
      3) Start learning
