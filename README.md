# Cross The Road

## Daftar Anggota

| Nama          | NIM       |  Github                                                 |
| ------------- | ----------|---------------------------------------------------|
| Yogi Immanuel Pinem | 120140011 | YogiPinem |
| Jody Fabian Lingga | 120140035 | JodyFabianLingga-120140035 | 
| Tegar Abimanyu | 120140112 | TegarAbimanyu |
| Raja Josua Simanungkalit | 120140134 | RajaJosuaS |
| Daniel Albertus Turnip | 120140140 | DanielTurnip |
| M.Rafif | 120140148 |RafiifMhd|


## Cross The Road

|Cross The Road

Aplikasi ini merupakan permainan yang dibuat menggunakan library pygame yang bertujuan untuk mencapai kotak harta karun dengan menghindari musuh musuh yang menghalangi jalan. Pada setiap kali pemain berhasil mencapai kotak harta karun maka kesulitan permainan akan berubah setiap kali pemain berhasil mendapatkan kotak harta karun.


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


