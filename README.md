# Specific static file
Process:
1) create project
2) enter project
3) create app
4) register app
5) create templates
6) give path of templates
7) register the templates
8) create static files in project folder and app folder
9) In project folder of static folder create js, css folder
10) In app folder of static folder create images folder for keeping our images
11) Then we need to give path to that static folders as;
12) STATIC_DIR_PROJECTNAME=os.path.join(os.path.join(BASE_DIR, projectname),'static')
13) STATIC_DIR_APPNAME=os.path.join(os.path.join(BASE_DIR, appname),'static')
14) Now, register it STATICFILES_DIRS=[ STATIC_DIR_PROJECTNAME,STATIC_DIR_APPNAME]
15) Now we have to make STATIC_ROOT=os.path.join(BASE_DIR,'static')
16) Then we have type this command on our cmd -->   python manage.py collectstatic
17) write views and then write urls
18) then after everything gets correct then runserver
19) search for suffix
