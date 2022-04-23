# install gcc compiler in docker
note: here we use image "gcc", so that you don't have to install gcc in your docker images.

## 1 search

run:
```
docker search gcc
```

to search for gcc in docker hub:

![alt text](/figures/docker_search_gcc.png)

## 2 pull
download image gcc from docker hub

run:
```
docker pull gcc
```

![alt text](/figures/docker_pull_gcc.png)
you can see the images by:
```
docker images
```

![alt text](/figures/docker_images_gcc.png)