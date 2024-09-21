# CURE RocketPy Simulation

This repo contains the RocketPy simulations and configurations for our club.

## Setup

Some of our simulations are organized as Jupyter Notebooks, which allow us to run smaller sections of code easily. This makes it more efficient when tweaking a simulation and viewing plots of the results.

Follow these step-by-step instructions to get set up and run the `.ipynb` files with ease.

---

### **Option 1: Using Anaconda (Recommended for Beginners)**

Anaconda is a free distribution of Python that comes with Jupyter Notebook and many scientific libraries pre-installed.

#### **Step 1: Download and Install Anaconda**

1. **Download Anaconda:**
   - Visit the [Anaconda Distribution](https://www.anaconda.com/products/distribution) page.
   - Download the latest version of Anaconda for Python 3.x for your operating system (Windows, macOS, or Linux).

2. **Install Anaconda:**
   - Run the installer and follow the on-screen instructions.
     - **Windows Users:** When prompted, you can leave "Add Anaconda to my PATH environment variable" unchecked to avoid conflicts.

#### **Step 2: Open Anaconda Navigator**

- Launch **Anaconda Navigator**:
  - **Windows:** Search for "Anaconda Navigator" in the Start Menu.
  - **macOS/Linux:** Open it from the Applications folder or via Terminal using `anaconda-navigator`.

#### **Step 3: Install RocketPy**

1. **Open a Terminal:**
   - In Anaconda Navigator, click on the **Environments** tab on the left.
   - Select the **base (root)** environment.
   - Click the **play button (▶)** next to it and choose **"Open Terminal"**.

2. **Install RocketPy:**
   - In the terminal window that opens, type the following command and press Enter:
     ```bash
     pip install rocketpy
     ```

#### **Step 4: Launch Jupyter Notebook**

- In Anaconda Navigator, go back to the **Home** tab.
- Find **Jupyter Notebook** and click **Launch**.

#### **Step 5: Open the Simulation Notebooks**

- In the Jupyter Notebook interface (opened in your web browser), navigate to the folder where you have the repository cloned or downloaded.
- Click on the notebook (`.ipynb`) file you wish to run.

#### **Step 6: Run the Notebook**

- With the notebook open, you can run each cell by:
  - Clicking on a cell and pressing **Shift + Enter**.
  - Or clicking the **Run** button in the toolbar.
- Make sure to run the cells in order for the simulation to function correctly.

---

### **Option 2: Using Python and Pip**

If you prefer a lighter setup without Anaconda, you can install Python and the required packages manually.

#### **Step 1: Install Python 3**

1. **Download Python:**
   - Go to the official Python website: [https://www.python.org/downloads/](https://www.python.org/downloads/).
   - Download the latest Python 3 installer for your operating system.

2. **Install Python:**
   - Run the installer and follow the prompts.
     - **Windows Users:** Ensure you check the box that says **"Add Python to PATH"** during installation.

#### **Step 2: Install Jupyter Notebook and RocketPy**

1. **Open Command Prompt (Windows) or Terminal (macOS/Linux):**

2. **Upgrade pip (Optional but Recommended):**
   ```bash
   pip install --upgrade pip
   ```

3. **Install Jupyter Notebook:**
   ```bash
   pip install notebook
   ```

4. **Install RocketPy:**
   ```bash
   pip install rocketpy
   ```

#### **Step 3: Clone or Download the Repository**

- **Clone using Git:**
  - If you don't already have **Git** installed you can download it from [here](https://git-scm.com/downloads).
  - If you are not already in our **CURocketEngineering** GitHub organization, send a message on Slack to the Software Development Lead with your GitHub username. 
  ```bash
  git clone https://github.com/CURocketEngineering/RocketPy-Simulations.git
  ```
- **Or download the ZIP:**
  - Click on the **"Code"** button on the repository's GitHub page and select **"Download ZIP"**.
  - Extract the ZIP file to a known location.

#### **Step 4: Navigate to the Project Directory**

- In your Command Prompt or Terminal, navigate to the directory where the repository is located:
  ```bash
  cd path/to/your-repo
  ```

#### **Step 5: Launch Jupyter Notebook**

- Start Jupyter Notebook by running:
  ```bash
  jupyter notebook
  ```
- This will open the Jupyter Notebook interface in your default web browser.

#### **Step 6: Open and Run the Notebook**

- Navigate to the `.ipynb` file within the Jupyter interface.
- Click on the notebook to open it.
- Run the cells in order using **Shift + Enter** or the **Run** button.

---

### **Additional Notes**

- **Using Virtual Environments (Optional):**
  - It's good practice to use virtual environments to manage dependencies.
  - Create a virtual environment:
    ```bash
    python -m venv env
    ```
  - Activate the virtual environment:
    - **Windows:**
      ```bash
      env\Scripts\activate
      ```
    - **macOS/Linux:**
      ```bash
      source env/bin/activate
      ```
  - Install Jupyter Notebook and RocketPy within this environment.

- **Troubleshooting:**
  - If you encounter issues, ensure all installations completed without errors.
  - Verify your Python and pip versions:
    ```bash
    python --version
    pip --version
    ```
  - If Jupyter Notebook doesn't launch, check that it's installed in the correct Python environment.

- **Learning Resources:**
  - **Python Tutorial:** [https://docs.python.org/3/tutorial/](https://docs.python.org/3/tutorial/)
  - **Jupyter Notebook Guide:** [https://jupyter-notebook.readthedocs.io/en/stable/](https://jupyter-notebook.readthedocs.io/en/stable/)
  - **RocketPy Documentation:** [https://rocketpy.org/](https://rocketpy.org/)

---

By following these instructions, you should be able to set up your environment and run the RocketPy simulations with ease. If you have any questions or run into issues, feel free to reach out for assistance.