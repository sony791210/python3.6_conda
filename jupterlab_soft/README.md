# jupyter labextension      
查看你有的套件  
jupyter labextension list   
    
## 可以畫圖及看圖   
jupyter labextension install jupyterlab-drawio  
![image](https://github.com/sony791210/python3.6_conda/jupterlab_soft/photo/drawio.gif) 


## 可以看html:   
jupyter labextension install @mflevine/jupyterlab_html  
![image](https://github.com/sony791210/python3.6_conda/jupterlab_soft/photo/html.gif)    


## 目錄結構化   
jupyter labextension install @jupyterlab/toc     
![image](https://github.com/sony791210/python3.6_conda/jupterlab_soft/photo/toc.gif)    


## 在jupyterlab分頁上網 
pip install jupyterlab_iframe   
jupyter labextension install jupyterlab_iframe  
jupyter serverextension enable --py jupyterlab_iframe   
![image](https://github.com/sony791210/python3.6_conda/jupterlab_soft/photo/iframe.gif)     



## 可以看變數得資料
jupyter labextension install @lckr/jupyterlab_variableinspector 
![image](https://github.com/sony791210/python3.6_conda/jupterlab_soft/photo/variable.gif)        

# jupyter kernelspec    
https://github.com/jupyter/jupyter/wiki/Jupyter-kernels 
查看你的kernel  
jupyter kernelspec list     

## fortran
git clone https://github.com/ZedThree/jupyter-fortran-kernel.git    
pip install -e jupyter-fortran-kernel       
jupyter-kernelspec install fortran_spec/ --uesr 


## JavaScript   
https://github.com/n-riesco/ijavascript 
http://bluegalaxy.info/codewalk/2017/12/04/javascript-how-to-install-javascript-kernel-in-jupyter-notebook/ 
sudo apt-get install nodejs-legacy npm ipython ipython-notebook 
sudo npm install -g ijavascript 
ijsinstall  


## R
https://cran.r-project.org/ 
https://github.com/IRkernel/IRkernel    
install.packages('IRkernel')    
IRkernel::installspec() 


## Jave 
conda config --add channels conda-forge 
conda install scijava-jupyter-kernel    
conda search scijava-jupyter-kernel --channel conda-forge   




## PHP
https://github.com/Litipk/Jupyter-PHP   
https://stackoverflow.com/questions/11333230/how-to-run-composer-from-anywhere  
https://litipk.github.io/Jupyter-PHP-Installer/     
curl -sS http://getcomposer.org/installer | php -- --filename=composer      
chmod a+x composer  
sudo mv composer /usr/local/bin/composer    




## Matlab
要先安裝matlab唷    
pip install matlab_kernel   

相關安裝matlab_2018 
sudo cp license_standalone.lic所在的目录 /usr/local/MATLAB/R2017a/bin/licenses/     
sudo cp libmwservices.so所在的目录 /usr/local/MATLAB/R2017a/bin/glnxa64/    


在 Mac 或 Linux 系统中 -    
找到 MATLAB 文件夹的路径。启动 MATLAB，并在命令行窗口中键入 matlabroot。复制 matlabroot 所返回的路径。  
cd "matlabroot/extern/engines/python"   
python setup.py install 





# ref:  
jupyterlab-drawio:  
https://github.com/QuantStack/jupyterlab-drawio 
jupyterlab_html:    
https://github.com/mflevine/jupyterlab_html
jupyterlab-toc: 
https://github.com/jupyterlab/jupyterlab-toc        
jupyterlab_iframe:      
https://github.com/timkpaine/jupyterlab_iframe      
jupyterlab-variableInspector:       
https://github.com/lckr/jupyterlab-variableInspector    


