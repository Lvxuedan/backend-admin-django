##1.django-admin 
`django-admin startproject [project name]`

`python3 manage.py startapp [app name]`

`python3 manage.py makemigrations`

`python3 manage.py sqlmigrate transaction 0001`

`python3 manage.py migrate`

`python3 manage.py inspectdb > models.py` 已存在数据库表导出Model.py

###Q:
django网页中：
#####1. 左侧banner默认进入第一个子页面；
#####2. inspectdb > models.py; 已存在的数据库中，Json格式问题，大写问题，部分id确实问题；
#####3. 可以去掉其中一些组件，如： "add" button;
######"add" button 可解决 
    def has_add_permission(self, request):
        return False
#####4. action code! 
#####5. view permission in Django! 查看权限 
