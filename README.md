# NTHU CS34233 Operating System Final Project
## Topic
Implement **preemptive SJF scheduling** on NachOS

## Acknowledgement
Special thanks to [Jonathan Huang](https://github.com/JHuang251998)!!!</br>Although we were not in the same team, you still kept discussing with me, which helped me so much! Had it not been for you, I would have failed finishing this project. Thank you again for your generousity and timely assisstant!

## Getting Started
1. Install `C-Shell` and `g++`
    ```
    sudo apt-get install csh
    ```
    ```
    sudo apt-get install g++
    ```
1. Download `mips-decstation.linux-xgcc.tar.gz` and unzip at root directory.
    ```
    cd /
    ```
    ```
    sudo wget --no-check-certificate https://hsn167.cs.nthu.edu.tw/git/root/nachos/-/raw/master/mips-decstation.linux-xgcc.tar.gz
    ```
    ```
    sudo tar -zxvf mips-decstation.linux-xgcc.tar.gz
    ```
1. Clone my repository.
    ```
    git clone https://github.com/LeoTheBestCoder/Nachos-SJF-Scheduling
    ``` 
1. Compile the OS.
    ```
    cd Nachos-SJF-Scheduling/code
    ```
    ```
    make clean
    ```
    ```
    make
    ```
1. Test
    ```
    userprog/nachos -e test/sjf_test1 -e test/sjf_test2 -d j
    ```

## Report
* [link](report/Final_Report_12.pdf)

## HW Description
* [link](HW_description/1102_OS_programming_project_Nachos.pdf)