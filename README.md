# IIC_Wordpres
Configuracion + Docker compose para levantar una instalacion de wordpress de manera local, con persistencia de datos.

### ¿Cómo levantar wordpress de manera local?
  1. Cree una capeta nueva
  2. Dentro de esa carpeta clone este repositorio en su maquina
  3. Sin salir de la carpeta, cree otra carpeta llamada "mysql"
  4. Sin salir de la carpeta, cree otra carpeta llamada "html"<br>
    *La carpeta del paso 1 tendría que verse así:*<br>
     .<br>
     ├── docker-compose.yaml<br>
     ├── html/<br>
     └── mysql/<br>

  5.  En la termina, ejecute el comando *docker-compose up -d* 
