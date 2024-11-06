# SCREENMATCH - FRASES

Proyecto Back-End que devuelve frases emblemáticas de Series destacadas de manera aleatoria.
## Instalación

1 - Crear una carpeta en repositorio local y clonar el repositorio de Back-End:
https://github.com/ClauJulian/screenmatch-frases.git
2 - Crear Base de Datos en Postgres. 
    DB-NAME: screen-frases
3 - Abrir el proyecto en el IDE y realizar el primer Run para crear la tabla en la Base de Datos.
4 - Ir a Postgres, buscar la tabla "frases" e inyectar los siguientes datos a modo de ejemplo:

insert into frases(id, frase, personaje, titulo, poster) values (1, 'Amigos no mienten', 'Eleven', 'Stranger things', 'https://m.media-amazon.com/images/M/MV5BMDZkYmVhNjMtNWU4MC00MDQxLWE3MjYtZGMzZWI1ZjhlOWJmXkEyXkFqcGdeQXVyMTkxNjUyNQ@@._V1_SX300.jpg');
insert into frases(id, frase, personaje, titulo, poster) values (8, '¡Que la fuerza te acompañe!', 'Obi Wan Kenobi', 'Star Wars', 'https://m.media-amazon.com/images/M/MV5BOTA5NjhiOTAtZWM0ZC00MWNhLThiMzEtZDFkOTk2OTU1ZDJkXkEyXkFqcGdeQXVyMTA4NDI1NTQx._V1_SX300.jpg');
insert into frases(id, frase, personaje, titulo, poster) values (9, 'Me salvaste de todas las formas que alguien puede ser salvado.', 'Rose Dawson', 'Titanic', 'https://m.media-amazon.com/images/M/MV5BMDdmZGU3NDQtY2E5My00ZTliLWIzOTUtMTY4ZGI1YjdiNjk3XkEyXkFqcGdeQXVyNTA4NzY1MzY@._V1_SX300.jpg');

5 - Crear una carpeta en repositorio local y clonar el proyecto Front-End para poder visualizar la aplicación:
https://github.com/alura-es-cursos/2086-java-desafio-front.git
6 - Abrir el proyecto Front-End en IDE - Visual Studio Code
7 - Instalar la extensión Live Server y seleccionar Go Live
8 - Verificar si el puerto de front-end es 5500 ó 5501. Si es 5501 ir al proyecto Back-End y cambiar el puerto en la carpeta /config/CorsConfiguration 
## Uso

Una vez instalados ambos proyectos, presionando en la tecla "ver más frases" activarás la selección aleatoria de nuevas frases.
## Contribución

Gracias Alura Latam y Globant por compartir tan valiosos conocimientos!

## Desarrollador

Soy Claudia Edith Julian, Licenciada en Administración, Asesora de Imagen y Desarrolladora Full Stack con mucha inclinación en el desarrollo Back-End.
Linkedin - https://www.linkedin.com/in/claudiaedithjulian/
GitHub - https://github.com/ClauJulian

