--> to push image in docker hub

1. Create a Repository by visiting 'https://hub.docker.com/'

2. Signin to docker locally

```
docker login
```

3. Build your Docker Image

```
docker build -t unique-image-name .
```

4. Tag the Docker Image

```
docker tag local-image-name dockerhub-username/repo-name:tag
```

5. Push the image to docker hub

```
docker push dockerhub-username/repo-name:tag
```

User / Password

```
docker login -u username
password
```
