# **Learn PySpark**
---

- Merupakan bahan ajar untuk pertemuan 9 - 10 dan 15 - 16 materi Data Pipeline Pacmann Sekolah Engineering
- Agar proses belajar lancar, bisa menggunakan repository ini
- Untuk menjalankan seluruh container, masukkan command `docker compose up --build --detach`
- Untuk bisa melakukan data processing terhadap data source yang bertipe database, pastikan file `driver/postgresql-42.6.0.jar` sudah ada. Setelah itu run command berikut:

    ```bash
    docker cp driver/postgresql-42.6.0.jar pyspark_container:/usr/local/spark/jars/postgresql-42.6.0.jar
    ```