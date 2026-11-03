# Astronomical Python - An Introduction to Modern Scientific Programming

This repository serves as a comprehensive Python code companion for Imad Pasha's *Astronomical Python*. Developed within a Windows virtual machine environment, the project bridges foundational radio astronomy computations with practical data analysis, featuring interactive green-and-white HTML dashboards to visualize the outputs of core research libraries.

## Setup Instructions

1.  **Clone the repository:**
    ```bash
    git clone <repository_url>
    cd astronomical-python-project
    ```
2.  **Set up the Conda Environment:**
    Ensure you have Miniconda or Anaconda installed, especially if you are using Windows Subsystem for Linux (WSL).
    ```bash
    conda env create -f environment.yml
    conda activate astropython
    ```
3.  **Run the Scripts:**
    Navigate to the respective chapter directories and execute the Python scripts or open the HTML dashboards.

## Project Structure

*   **Part_I_Unix_and_Basic_Python:** Scripts demonstrating variables, data types, conditional statements, and loops.
*   **Part_II_Core_Research_Libraries:** Subdirectories dedicated to the primary data analysis tools (Matplotlib, Numpy, SciPy, Astropy).
*   **Part_III_Intermediate_Applications:** Advanced modules covering Object Oriented Programming, data science with astronomical catalogs (Pandas, 3DHST), vectorization, and astronomical inference (MCMC).
*   **Dashboards:** Single-page HTML dashboards to display plotted outputs and theoretical summaries.

## Data Availability
The data sets used in this project are publicly available. Refer to the specific chapter scripts for download instructions or dataset paths.
