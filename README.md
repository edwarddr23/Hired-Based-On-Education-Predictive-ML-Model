Pyspark project created for Big Data Programming course (Spring 2024).
_____________________________________________________________________________
Data Information:
Original data found from here: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic
Information on the data's columns is in file: wdbc.names
The output files here are what results from running these scripts.
_____________________________________________________________________________
ML Model:
Random Forest Tree
_____________________________________________________________________________
Output:
Outputs to OUTPUT whether the test value will be diagnosed with a malignant (1) or benign tumor (0).
_____________________________________________________________________________
How to run each python file:
1. For simplicity, create a dataproc Linux VM environment (Google cloud has tools available).
2. Upload these files into the VM's root: input.txt, assignment8_part1.py, and assignment8_part2.py.
3. Type the following commands into the terminal:
   hdfs dfs -put input.txt input
   spark-submit [python file here]
5. Wait for the script to fully run until it successfully writes to /home/USER/OUTPUT
8. This output text file will hold the output attached to this repository.
