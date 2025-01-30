# flask-app-ecs
Simple flask app to be run on ECS

**Build docker image**
```
docker build -t flask-app . 
```

**Run docker container**
```
docker run -d -p 80:80 flask-app 
```

**Push dockerfile to dockerhub**
```
docker login
docker tag local-image:tagname new-repo:tagname
docker push new-repo:tagname
```

<img src="flask-app.png" alt="drawing" height="30" />
<img src="flask-app-1.png" alt="drawing" height="20" />

