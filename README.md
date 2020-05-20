# DjangoVue


### Django开启一个project：
    django-admin.py startproject Demo
    django-admin.py startapp appback

    setting文件配置：
    将appback添加到INSTALLED_APPS中
    数据库配置 字段DATABASES
    模板路径
    TEMPLATES 的DIRS字段配置新建的vue的路径


### vue-cli安装：
    初始化vue app,如果已经有请跳过
    npm install -g @vue/cli
    npm install -g @vue/cli-init   #新版本的vue-init
    vue init webpack appfront  


    cd appfront
    npm install
    npm install vue-resource
    npm install element-ui
    npm run build #将静态文件整理到appfond/dist中