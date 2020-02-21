# Django-Polls
Django polls 练习项目

这是根据Django官方文档写的第一个项目，练习用途。
详细官网说明：https://docs.djangoproject.com/en/3.0/intro/tutorial01/

# 本代码使用说明
1. 下载代码。
2. 进入mysite目录，修改settings.py中的数据库配置。
3. 打开命令行窗口，在mysite目录下执行：python manage.py makemigrations 
4. 创建数据表：python manage.py migrate
5. 创建管理员账户：python manager.py createsuperuser 
6. 运行项目：python manager.py runserver
7. 访问网站。
   http://127.0.0.1:8000/polls/
   http://127.0.0.1:8000/admin （网站后台）
   
# 打包发布&安装
1. 打包，在django-polls目录下执行：python setup.py sdist
2. 安装：python -m pip install --user django-polls/dist/django-polls-0.1.tar.gz
