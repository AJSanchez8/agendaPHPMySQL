## Pasos: 

- 1º.- Iniciar contenedor docker-compose con ```bash
 docker-compose up -d```.
- 2º.- Crear base de datos llamada entornoServidor. El docker-compose tiene en el puerto 8081 un phpmyadmin.
- 3º.- Crear tabla dentro de esa base de datos 
    ```sql 
    CREATE TABLE agenda (id INT UNSIGNED AUTO_INCREMENT PRIMARY KEY,
    nombre VARCHAR(100) CHARACTER SET utf8mb4 COLLATE utf8mb4_0900_ai_ci,
    numero VARCHAR(9) CHARACTER SET utf8mb4 COLLATE utf8mb4_0900_ai_ci);
