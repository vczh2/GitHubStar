Chinese [here](README_CN.md)
# GitHubStar
Auto star for gitstar.cn
## Usage
### Docker
- Run with Docker
    ```
    docker run --rm \
           -e NAME={NAME} \
           -e PASSWORD={PASSWORD} \
           -e GITNAME={GITNAME} \
           -e GITPASSWORD={GITPASSWORD} \
           setzero/githubstar
    ```
### Source code
#### Step 1
1. Install Python 2.x,run```python --version```and```pip```for a test.  
1. To install pip, securely download [get-pip.py](https://bootstrap.pypa.io/get-pip.py)
1. Then run the following（If you have downloaded it,skip the step.）:
    ```
    python get-pip.py
    ```
> MAKE SURE that you have installed ```requests```.
```
pip install -r requirements.txt
```
#### Step 2
1. Clone the repo  
    ```
    git clone https://github.com/weilaihui/GitHubStar.git && cd GitHubStar
    ```
1. Open`settings.py`, replace variables with your own infomation.
    ```
    #############settings#############
    NAME		= "1" #GitStar username
    PASSWORD	= "1" #GitStar password
    GITNAME		= "1" #Gitee username
    GITPASSWORD	= "1" #Gitee password
    #############settings#############
    ```
#### Step 3
- Run
    ```
    python -u main.py
    ```  
Everything is ok,hooray!