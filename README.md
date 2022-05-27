# Hands-On-4

#RUN DOCKER
#NYALAKAN XLauch
#BUILD DOCKER IMAGE
```
docker build -t docker-game .
```

#RUN DOCKER CONTAINER
```
docker run --rm -it -e DISPLAY=192.168.1.49:0.0 -v D:\jodi\Hands-On-4:/usr/project docker-game /bin/bash
```

Note:
1. ganti ip address sesuai ip kalian
2. ganti D:\jodi\Hands-On-4 sesuai lokasi main.py

#RUN GAME DI CONTAINER
```
python main.py
```


