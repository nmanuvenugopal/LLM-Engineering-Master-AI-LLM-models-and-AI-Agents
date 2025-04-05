### 🐍 Setting Up the Environment

1. **Install Anaconda**  
   We will be using **Anaconda** as our primary environment manager throughout this project. You can download it from [Anaconda's official website](https://www.anaconda.com/products/distribution) and follow the installation instructions for your OS.

2. **Create a Virtual Environment**  
   After installing Anaconda, create a virtual environment and install all required dependencies using the provided `environment.yml` file. This file includes all the necessary packages and their versions to run the project.

   ```bash
   conda env create -f environment.yml
   ```

   This command will set up a new environment with all dependencies pre-configured. Make sure you activate the environment before running the project:

   ```bash
   conda activate your_env_name  # replace with the name in environment.yml
   ```
