# paddle_project
Win10环境下用Anaconda创建Python虚拟环境（在Anaconda prompt环境下完成），并使用pycharm进行代码的编写。

paddlepaddle安装参考文档说明网址：
https://www.paddlepaddle.org.cn/documentation/docs/zh/1.6/beginners_guide/install/install_Conda.html

1.查看已有的虚拟环境：conda info --envs

2.创建新的python环境：conda create -n paddle_env python=3.6

3.进入Anaconda虚拟环境：activate paddle_env

4.添加清华源：
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main/
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/Paddle/
conda config --set show_channel_urls yes

5.安装paddlepaddle(强化学习环境)：
pip install paddlepaddle==1.8.5
pip install parl==1.3.1
pip install gym
