# Buscador de Universidades
- Contruccion de la imagen 
    -   ```sh
        docker build -t universidades .
        ```

- Creacion del contenedor
    -   ```sh
        docker run -d -p 8094:80 universidades
        ```

- link de la Pagina
    -   ```sh
        http://localhost:8094/
        ```
