# python-rest-api
Source code for python rest api using django

Vagrant is unable to sync the folder from guest to host and vice versa:
- Install guest plugin: vagrant plugin install vagrant-vbguest
- Add line: config.vm.synced_folder ".", "/vagrant", type: "virtualbox"

docker-compose run app sh -c "django-admin.py startproject app ."
