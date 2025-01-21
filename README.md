# Number-to-Words Application

This application processes text files to extract numeric sequences and converts valid numbers into their word equivalents. Invalid numbers are flagged with the message `"number invalid"`. 

The solution is implemented in Python and includes:
1. A Jupyter Notebook that defines and executes the core functionality.
2. Test files to validate the application with real-world examples.

---

## Project Overview

This project demonstrates a solution to process text files by:
- Identifying standalone numeric sequences using regular expressions.
- Converting valid numeric sequences into their English word equivalents (e.g., `123` → `"one hundred and twenty-three"`).
- Flagging invalid numbers (e.g., `12,34`, `23.5`) with the message `"number invalid"`.

---

## Setup Instructions

Follow these steps to clone the repository, set up the environment, and run the application:

### **1. Clone the Repository**
Use the following command to clone the repository:
```bash
git clone https://github.com/PMacmillan1/number-to-words-app.git
```
This will clone the GitHub repository (README, notebook, data) to your current directory.

  Useful Tips:\
    - you can change your current directory with the cd command\
    - you can check your current directory location with the pwd command (mac)

### **2. Setup Environment**
Import relevant libraries (Reference Notebook)

### **3. Set the Directory Within the Notebook**
1. Open the Jupyter Notebook provided in the repository.
2. Modify the notebook’s working directory to match the location of your input files and code.
   ```
   import os
   ```
   os.chdir("<path_to_repository>")

---   

## Instructions on How to Run the App

### **1. Update the Input File Name**
1. Locate the variable in the notebook or script where the input file is defined
3. Update the input_file variable with the correct filename (e.g., test_file_1.txt)
   ```
   input_file = "test_file.txt"

### **2. Ensure the Test File Exists in the Directory**
Verify that the test file is present in the designated directory.

### **3. Run the Main Function**
1. Ensure all setup steps have been completed.
2. Run the main function or notebook cell containing the logic:
   ```
   main()
   ```
4. View the output in the console or the designated output file.
