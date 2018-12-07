# Orchestration using Docker Compose

* Step 1 - Defining First Container

Langkah pertama yang dilakukan adalah mengidentifikasi container dengan mencopy web build seperti gambar dibawah ini.
![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/1.png)
* Step 2 - Defining Settings

Langkah kedua yaitu mengidentifikasi setting dengan cara mencopy links dan port
![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/2.png)

![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/3.png)

* Step 3 - Defining Second Container

Langkah ketiga yaitu melakukan identifikasi kedua pada container dengan cara 
mencopy nama redis yang digunakan image redis

![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/4.png)

* Step 4 - Docker Up

Langkah keempat yaitu melakukan docker up dengan menggunakan perintah seperti dibawah 

![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/5.png)

![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/6.png)

![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/7.png)

* Step 5 - Docker Management

Langkah kelima yaitu melakukan docker manajemen dengen perintah :

*Perintah docker-compose ps

![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/8.png)

*Perintah docker-compose logs

![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/9.png)

![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/10.png)

![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/11.png)

*Perintah docker-compose

![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/12.png)

![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/13.png)

![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/14.png)

![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/15.png)

![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/16.png)

* Step 6 - Docker Scale

Langkah keenam yaitu melakukan docker scale dengan perintah :

*Perintah docker-compose scale web=3

![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/17.png)

*Perintah docker-compose scale web=1

![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/18.png)

* Step 7 - Docker Stop

Langkah keenam yaitu melakukan penghentian pada docker 

*Perintah docker-compose stop

![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/19.png)

*docker-compose rm

![On Demand](https://github.com/Rohmatul1/tct-docker-2/blob/master/20.png)