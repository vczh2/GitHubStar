Engish [here](README.md)
# GitHubStar
gitstar自动点赞工具
# 快速入门
## Linux
### 使用Docker运行
> 如果你机器上安装有Docker，可以按命令直接运行镜像即可。
- 执行以下命令即可，注意以下环境变量把它们改成你自己的信息。
    ```
    docker run --rm \
           -e NAME={NAME} \
           -e PASSWORD={PASSWORD} \
           -e GITNAME={GITNAME} \
           -e GITPASSWORD={GITPASSWORD} \
           setzero/githubstar
    ```

### 使用源码运行
#### 第一步
1. 安装python2.x版本，执行`python --version`确认版本。
1. 安装pip，从这里下载[get-pip.py](https://bootstrap.pypa.io/get-pip.py)脚本。
    ```
    python get-pip.py
    ```
1. 安装依赖
    ```
    pip install -r requirements.txt
    ```

#### 第二步
1. 克隆本项目
    ```
    git clone https://github.com/weilaihui/GitHubStar.git && cd GitHubStar
    ```
1. 打开项目下`settings.py`，替换以下内容，把它们改成你自己的信息。  
    ```
    #############settings#############
    NAME		= "1" #GitStar用户名
    PASSWORD	= "1" #GitStar密码
    GITNAME		= "1" #github用户名
    GITPASSWORD	= "1" #github密码
    #############settings#############
    ```
#### 第三步
- 运行程序
    ```
    python -u main.py
    ```  

## Windows
我好久没用过Windows了~    
你可以百度一下```windows python2.x安装教程```看看，祝你好运！:)
