# grocery_app

Personal project

# setup in docker

```
# create docker image
$ docker build -t grocery_app .

# set up container for client with nginx server at port 8000
$ docker run -it -p 8000:80 --name grocery-app-container grocery_app
```
