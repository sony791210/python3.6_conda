#python3.6_conda   

根據步驟將 Python 快速安裝的方式   

Keras                     2.2.2                     <pip>   
Keras-Applications        1.0.4                     <pip>  
Keras-Preprocessing       1.0.2                     <pip>  
tensorboard               1.10.0           py36hf484d3e_0     anaconda   
tensorflow                1.10.0          gpu_py36h97a2126_0    anaconda   
tensorflow-base           1.10.0          gpu_py36h6ecc378_0    anaconda   
tensorflow-gpu            1.10.0               hf154084_0    anaconda   
jupyterlab                0.34.7                   py36_0    conda-forge   




# This is for linux(ubuntu) 

## get conda_python3.6 

##download conda.tgz 
https://drive.google.com/open?id=1iI73dU_bCBFs64HImbHla5Rd-j08ccuq 



## put it into /opt 
### 將此解壓縮且放在/opt 裡面  
cd /opt 
sudo cp ~/Download/conda.tgz . 
sudo tar -xzvf conda.tgz 

### 將conda資料夾賦予使用者能用 
sudo chown -R your_username conda/ 
ex: 
sudo chown -R apple791210 conda/ 
 
### 建立環境變數設定 

vi ~/.bashrc 
 
加入 下面2行 
 
export PATH=/opt/conda/bin:$PATH 
export ANACONDA_PATH=/opt/conda 
 

### 啟動環境 
source ~/.bashrc 
 
 
### 執行jupyter lab 
jupyter lab 


