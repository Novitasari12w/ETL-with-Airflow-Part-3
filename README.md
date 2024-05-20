op_mysql dan op_postgresql adalah operator dalam Apache Airflow yang digunakan untuk mengeksekusi tugas-tugas terkait dengan basis data MySQL dan PostgreSQL. Kedua operator ini memungkinkan integrasi dan eksekusi perintah SQL dalam alur kerja (workflow) yang dikelola oleh Airflow.

Sebelum dijalankannya DAG:
op_mysql: * Menyambungkan ke database MySQL yang ditentukan. 
* Menyiapkan pernyataan SQL yang akan dijalankan. op_postgresql:
* Menyambungkan ke database PostgreSQL yang ditentukan.
* Menyiapkan pernyataan SQL yang akan dijalankan.

Sesudah dijalankan:

op_mysql: * Menjalankan pernyataan SQL terhadap database MySQL. 
* Mengambil hasil query (jika ada). * Menyimpan hasil query ke dalam variabel Airflow. op_postgresql:
* Menjalankan pernyataan SQL terhadap database PostgreSQL.
* Mengambil hasil query (jika ada). 
* Menyimpan hasil query ke dalam variabel Airflow.

