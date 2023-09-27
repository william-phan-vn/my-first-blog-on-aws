# my-first-blog-on-aws

## Create a django app
```buildoutcfg
python -m venv venv
source venv/bin/activate
pip install django
django-admin startproject <app_name>
cd <app_name>
python manage.py runserver
```
The app will look like this
![django_first_app](django_blog/document/django_first_app.png)

## Create a user on AWS
- Check aws cli
```buildoutcfg
aws --version
```
![img.png](django_blog/document/check_aws_cli.png)
- Configure aws profile


## Deploy using zappa
```buildoutcfg
pip install zappa
pi 
```
## References
[Django deploy - Zappa onto AWS Lambda + API Gateway
](https://www.youtube.com/watch?v=WaiL4sbaj_o)