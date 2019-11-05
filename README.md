# EDA-Tool
Below are the clear step-by-step instructions on how to build, deploy and use the EDA Tool

1. Install Software: Anaconda (Website: https://www.anaconda.com/distribution/) Download link(Windows10 64bit): https://repo.anaconda.com/archive/Anaconda3-2019.10-Windows-x86_64.exe

2. After Anaconda installation is completed successfully, install below Python libraries. Some of them might be already installed along with Anaconda. 

a.. Open Anaconda prompt application -> Navigate to Anaconda folder from start menu and search for Anaconda prompt application.
b.. Run below Commands: 
pip install tkfilebrowser
PiP install matplotlib
pip install scipy
pip install seaborn
pip install plotly
pip install cufflinks

3. Download EDA Tool.ipynb (which holds source code) and USA_Housing.csv (which holds dataset) files from from github reposioty

4. Open jupyter notebook application -> Navigate to Anaconda folder from start menu and search for Jupyter notebook application.

5. Navigate to the location where EDA Tool.ipynb was downloaded. Open the file

6. Go to menu option "cell" and select Run all option

7. EDA tools processing will start and when prompted to browse a file, navigate and select USA_Housing.csv data or any other data if you have in CSV or excel file format. Unless you select correct dataset, the  tool will not execute next steps and will keep on prompting untill correct dataset is provided.

8. In case you face any issues with loading of file or graph plots (sometimes due to unforeseen system memory related issues), you may restart the kernel by going to Kernel and select Restart & Run All option.
