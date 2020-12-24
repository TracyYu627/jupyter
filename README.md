# jupyter
jupyter notebook

1. Resouse
https://pandas.pydata.org/docs/user_guide/index.html

2. Envirenment setup：
(1) install Anaconda, you will get jupyter notebook
https://www.anaconda.com/download

(2) (for Chinese users)
>> pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple

(3) build virtual enviroment named 'gluon' based on enviroment .yaml file
>> conda env create -f enviroment .yaml

(4) ativate python environment
>> conda activate gluon

(5) install jupyter andon to help select running enviroment
>> conda install nb_conda

(6) run jupyter notebook under 'jupyter' folder
>> jupyter notebook

(7) choose 'gluon' in 'Server' menu to make jupyter running under 'gluon' evn