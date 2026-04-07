To test locally with Docker:

* Ensure Docker Desktop is running

```console
> docker compose up --build                                              
```

* Connect to- http://localhost:8080/  




To push containers to DockerHub:

```console
> docker compose up --build # locally
> docker tag map-viewer-backend <username>/map-viewer-backend:vX
> docker push <username>/map-viewer-backend:vX
> docker tag map-viewer-frontend <username>/map-viewer-frontend:vX
> docker push <username>/map-viewer-frontend:vX
```

