# CS 4371 - Assignment 1 - DHL190004

To run the Jar files:
- Open your Ubuntu environment in your Virtual Machine
  
- Find the Directory where Assignment1-DHL190004 is stored
  
- Open your Linux Terminal (ctrl + alt + t)
  
- Start HDFS
  - $ start-dfs.sh
  - $ start-yarn.sh
  
- Set a directory in your HDFS
  - $ hdfs dfs -mkdir <desired directory name>

- Put your input_hw1.txt file in the directory
  - Change cd to Directory where Assignment1-DHL190004 is stored
  - $ hdfs dfs -put <filename in local file system/source> <target directory in HDFS>

- Change cd to Directory where Assignment1-DHL190004 is stored
  - Make sure your first slash is backwards than all the rest are forwards
    - for example, $ cd \Documents/Assignment1

  - To run each JAR file:
    - For 2A
      - Run: $ cd /Assignment_1_2A
      - Next Run: $ hadoop jar Assignment1_2A.jar Assignment1_2A /user/daniel/input/input_hw1.txt /output2A
    - For 2B
      - Run : $ cd ..
      - Next Run: $ cd /Assignment_1_2B
      - Next Run: $ hadoop jar Assignment1_2B.jar Assignment1_2B /user/daniel/input/input_hw1.txt /output2B
    - For 2A
      - Run : $ cd ..
      - Run: $ cd /Assignment_1_2C
      - Next Run: $ hadoop jar Assignment1_2C.jar Assignment1_2C /user/daniel/input/input_hw1.txt /output2C

- Outputs are already in Assignment1-DHL190004:
    - Open folder of corresponding problem i.e. for 2C Assignment_1_2C
    - Click on output<problem number> i.e. output2C
    - Open text file output_<problem number> to see the results for the corresponding problem number i.e.
      output_2C

- To find Java source code files:
  - Open folder of corresponding problem i.e. for 2C Assignment_1_2C
  - Open folder of Java Project i.e. for 2C Assignment1_2C
  - Open src folder and you find the java source code file
