# 项目配置

您需要根据自己MySQL数据库的情况，修改`backend/backend/settings.py`文件118-127行：

```python
DATABASES = {
    'default': {
    'ENGINE': 'django.db.backends.mysql',
    # 您的数据库名
    'NAME': 'paddle',
    # 数据库登录用户名
    'USER': 'root',
    # 数据库登录密码
    'PASSWORD': 'goodnight',
    'HOST': '127.0.0.1',
    # 数据库访问端口
    'PORT': '3306',
    }
}

```
