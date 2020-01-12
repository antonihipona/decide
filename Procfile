% prepara el repositorio para su despliegue. 
release: sh -c 'cd decide && python manage.py migrate --run-syncdb'
% especifica el comando para lanzar Decide
web: sh -c 'cd decide && gunicorn decide.wsgi --log-file -'
