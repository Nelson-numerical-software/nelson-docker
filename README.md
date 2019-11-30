# nelson-docker
Docker official image for Nelson.

See the Docker Hub page for the full readme on how to use this Docker image and for information regarding contributing and issues.

 ## build docker
```bash
docker build -t nelson .
```

## download nelson image

```bash
docker pull nelsonsoftware/nelson
```

 ## run docker
```bash
docker run -ti nelsonsoftware/nelson
```

With graphical user interface:
```bash
docker run -it --env="DISPLAY" --env="QT_X11_NO_MITSHM=1" --volume="/tmp/.X11-unix:/tmp/.X11-unix:rw" --entrypoint /nelson/bin/linux64/nelson-gui nelsonsoftware/nelson
```
