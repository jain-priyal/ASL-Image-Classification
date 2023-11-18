# IMPORTANT: PLEASE OPEN THE FOLDER WITH TITLE "COMP9444-Group-Project" IN YOUR VS-CODE ENVIRONMENT
This folder contains 3 notebook files.
1. Our first custom model, NetConv, which is located at: CNN Model/comp9444-cnn_model.ipynb 
2. Our second custom model, KeyPointsNet, which is located at: keyPoint_Model/KeyPointsNet.ipynb
3. Our third program, to extract keypoints, which is located at: keyPoint_Model/KeypointsGenerator.ipynb

# IMPORTANT: YOU DO NOT NEED TO CHANGE ANY PATH RELATED VARIABLES. OUR ENTIRE CODEBASE IS SETUP FOR RELATIVE PATH EXECUTION. THIS MEANS THAT ONCE YOU DOWNLOAD THE FOLDER YOU CAN RUN THE CODE DIRECTLY AND DO NOT NEED TO CHANGE ANYTHING.

# STEP 1 - INSTALLING REQUIRED LIBRARIES
## Please run the following commands in your terminal to ensure all the relevant libraries are installed:

- pip install opencv-python
- pip install numpy
- pip install matplotlib
- pip install torch torchvision
- pip install scikit-learn
- pip install pandas
- pip install mediapipe

# STEP 2 - Running the Inference Examples for NetConv (CNN) Model
Please follow these steps in order: 
1. Open the "comp9444-cnn_model.ipynb" file located in the "CNN Model" folder.
2. Next, execute the cell with comment "# README CELL 1.1" at the top. This cell is under the "Data Source" heading.
3. Next, execute the cell with comment "# README CELL 1.2" at the top. This cell is under the "CNN Model Implementation" heading.
4. Next, execute the cell with comment "# README CELL 1.3" at the top. This cell is under the "Results" heading after the confusion matrix output.
5. Next, execute the cell with comment "# README CELL 1.4" at the top. This cell is under the "Inference Tests" heading.
6. Now you can run all the cells in the "Correct Inference Examples" and "Incorrect Inference Examples" heading sections to check the validity of our inference examples.

# STEP 3 - Running the Inference Examples for KeyPointsNet Model
## PLEASE NOTE: YOU DO NOT HAVE TO RUN THE "KeypointsGenerator.ipynb" FILE AS THIS HAS ALREADY BEEN EXECUTED AND KEYPOINTS EXTRACTED. THAT IS WHY ALL CODE IS COMMENTED OUT.
Please follow these steps in order: 
1. Open the "KeyPointsNet.ipynb" file located in the "keyPoint_Model" folder.
2. Next, execute the cell with comment "# README CELL 2.1" at the top. This cell is under the "Problem Statement" heading.
3. Next, execute the cell with comment "# README CELL 2.2" at the top. This cell follows the previously executed cell.
4. Next, execute the cell with comment "# README CELL 2.3" at the top. This cell is under the test function.
5. Next, execute the cell with comment "# README CELL 2.4" at the top. This cell is under the "Results" heading after the confusion matrix output.
6. Next, execute the cell with comment "# README CELL 2.5" at the top. This cell is under the "Inference Section" heading.
7. Next, execute the cell with comment "# README CELL 2.6" at the top. This cell follows the previously executed cell.
8. Now you can run all the cells in the "Correct Predicted Inferences" and "Inferences With No Landmarks Detected" heading sections to check the validity of our inference examples.