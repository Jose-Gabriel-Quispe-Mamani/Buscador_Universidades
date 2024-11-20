# Buscador de Universidades
- Contruccion de la imagen 
    -   ```sh
        docker build -t universidades .
        ```

- Creacion del contenedor en el puerto 8097
    -   ```sh
        docker run -d -p 8094:80 universidades
        ```

- link de la Pagina
    -   ```sh
        http://localhost:8097/
        ```
