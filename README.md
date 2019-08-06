# python-rest-api
Source code for python rest api using django

Vagrant is unable to sync the folder from guest to host and vice versa:
- Install guest plugin: vagrant plugin install vagrant-vbguest
- Add line: config.vm.synced_folder ".", "/vagrant", type: "virtualbox"

docker-compose run app sh -c "django-admin.py startproject app ."
docker-compose run app sh -c "python manage.py test && flake8"
docker-compose run app sh -c "python manage.py startapp core"
docker-compose run app sh -c "python manage.py makemigrations core"
