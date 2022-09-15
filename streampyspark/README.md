# Langkah - langkah
sblmnya if ingin run maka ganti nama folder pyspark-kafka jd kafka baru jalankan perintah dibawah ini<br>
1. Install kafka, bisa memakai docker atau lebih baik sesuai dengan di web resmi
nya yaitu di https://kafka.apache.org/quickstart<br>
2. jalankan kafka, caranya ikuti dari link tsb STEP 2 dimana pertama run dulu zo
okeeper (ingat buat dulu config/zookeeper.properties) dengan perintah<br>
bin/zookeeper-server-start.sh config/zookeeper.properties<br>
kemudian run juga kafka nya (ini juga sama harus buat config/server.properties)
dg perintah<br>
bin/kafka-server-start.sh config/server.properties<br>
PERHATIKAN KE2 NYA HARUS RUNNING & folder config yg kita buat harus ada di direc
tory yg sama dg bin<br>
3. install spark. INGAT SPARK PERLU JAVA JD INSTALL DULU JAVA, & REQUIREMENT YG DIBUTUHKAN OLEH SPARK AGAR DPT BERJALAN
4. Install dependency yg diperlukan yaitu pip install kafka-python, pyspark, fin
dspark, py4j<br>
dimana py4j digunakan untuk converter dr python ke java karena spark berbasis ja
va<br>
### INGAT SAAT INSTALL DG PIP, VERSI PYSPARK == VERSI SPARK, JIKA != MAKA AKAN ERROR
### UNTUK MEMPERLAJARI KAFKA SILAHKAN BUKA REPOSITORY YG TELAH DIBUAT YAITU KAFKA & KAFKA-PZN
