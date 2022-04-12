#环境准备
1. download python
2. 安装虚拟环境 
    "pip install virtualenv"
3. 创建项目文件夹 fastapi-demo1, 打开项目路径指向cmd
    "mkdir fastapi-demo1"
    "cd fastapi-demo1"
4. 创建虚拟环境 "virtualenv env"
5. 激活虚拟环境 
    "cd env", 
    "cd scripts"
    "activate"
6. 回到fastapi-demo1, 安装fastapi, uvicorn
    "pip install fastapi"
    "pip install uvicorn"
7. 导出引用包到文件 requirements.txt
    "pip freeze > requirementx.txt"
8. 新环境，安装依赖。用引用文件安装需要的包
    "pip install -r requirements.txt"
9. "code ."
10. 启动网站
    "python app/main.py"