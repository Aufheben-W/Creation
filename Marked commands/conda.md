# Commands in Anaconda
## 创建环境
conda create -n py36 python=3.6
## 删除环境
conda remove -n py36 --all
## 查看环境安装包
conda list
## 克隆环境
**把py36拷贝到env_py36**
conda create -n env_py36 --clone py36
