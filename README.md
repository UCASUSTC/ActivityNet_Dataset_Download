# ActivityNet_Dataset_Download
a way to download  the dataset of ActivityNet
# 准备工作
1. 下载并安装Anaconda，利用下面命令创建python3.6虚拟环境
```
conda create -n py36 pip python=3.6
```
2. 利用下面命令在虚拟环境中添加youtube-dl
```
pip install youtube-dl
```
3. 利用下面命令在虚拟环境中添加pafy
```
pip inatall pafy
```
4. 也可以利用命令把ffmpeg添加上
```
pip install ffmpeg
```
# 准备相应文件
1. 使用下面命令下载该项目
```
git clone https://github.com/UCASUSTC/ActivityNet_Dataset_Download.git
```
找出里面的ActivityNet_Dataset_Download.py文件  
2. 去ActivityNet官网下载json文件http://activity-net.org/download.html  
最后将ActivityNet_Dataset_Download.py文件和activity_net.v1-3.min.json文件这两个文件放在一个目录下。
# 更改一下路径
打开ActivityNet_Dataset_Download.py文件，修改
directory = '/path/to/your/directory/'
# 开始下载
进入到那两个文件的目录下，并进入py36虚拟环境下，执行下面命令，开始下载
```
python ActivityNet_Dataset_Download.py
```

推荐使用官方网站下载数据集的方法，详见https://www.jianshu.com/p/70d0b315e053
