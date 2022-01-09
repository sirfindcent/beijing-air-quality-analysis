# Beijing-Air-Quality-Analysis
In this project I did some data analysis and data visualization with matplotlib.

<img src=./plot/bar-each-air-polution-4years.png width=550>

## Conclusion
1.Beijing air polution is becoming worse in the period of 2013-2016.

<img src=./plot/air-polution-freq-temp-4years.png width=400 >

2.The air polution frequency is always increasing at the end of the year usually at September until December every year.

<img src=./plot/air-polution-avg-year.png width =550>

## Setup
0.Install Anaconda or Miniconda [here](https://docs.anaconda.com/anaconda/install/)
 
1.Clone the repository, and navigate to the downloaded folder.
```
git clone https://github.com/VincentJonathanz/beijing-air-quality-analysis.git
```
2.Create and activate enviroment.
   - **Anaconda Prompt**:
      ```
      conda env create --prefix ./env -f enviroment.yml
      conda activate beijing-air-quality-analysis/env
      ```
      
   - **Powershell** (you need to run this command first then run the command above):
      ```
      conda init powershell
      Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
      ```
      
3.Start Jupyter
``` 
jupyter notebook
```




