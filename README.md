# GNSS_Vel_95CI

A Python program for calculating the 95%CI for GNSS-derived site velocities, by B. Cornelison and G. Wang.

GNSS_Vel_95CI.py is a Python module for the calculation of the site velocity (b) and its 95%CI for GNSS-derived daily displacement time series.
The detailed methods are adressed in:
Wang, G. (2022). The 95% Confidence Interval for GNSS-Derived Site Velocities, J. Surv. Eng. 2022, 148(1): 04021030. 
http://doi.org/10.1061/(ASCE)SU.1943-5428.0000390

Main_cal_95CI.py illustrates the method of implementing "GNSS_Vel_95CI.py" into your own Python program.
You may need to install "pandas", "matplotlib", "statsmodels" on yur computer if you have not used them before.

How--- "pip install pandas", "pip install matplotlib", "pip install statsmodels".

How to run the module on your computer from GitHub?
Download following files into a folder:

Main_cal_95CI.py

GNSS_Vel_95%CI.py

MRHK_GOM20_neu_cm.col  (sample file)

.....

Change your work directory to the folder/directory:

For Linux system users:

Type "./Main_cal_95CI.py" in your terminal

For Windows system users:

Type " python Main_cal_95CI.py" in your CMD window

The main program will create an output folder in your current directory to output the results.

Good Luck!

For comments, please contact: bob.g.wang@gmail.com or bscornelison@gmail.com

Two figures output from the module:

![MRHK_UD_ACF](https://user-images.githubusercontent.com/65426380/144933002-c7eeab12-a110-4031-93b2-120011c5340f.png)


![MRHK_UD_Decomposition](https://user-images.githubusercontent.com/65426380/144967345-ca5b2264-c82e-46cf-8eed-a23d8466f6f9.png)

Detailed Method:
[Methods_Vel_95CI.pdf](https://github.com/bob-Github-2020/GNSS_Vel_95CI/files/7664316/Methods_Vel_95CI.pdf)
