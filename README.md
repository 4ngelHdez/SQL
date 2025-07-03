### Análisis de Preferencias y Tendencias en Libros Durante la Pandemia

# Descripción del Proyecto<br>
Este proyecto se centró en el análisis de datos de una plataforma de libros digitales, con el objetivo de identificar patrones de comportamiento de los usuarios durante el auge del consumo de contenido en casa ocasionado por la pandemia de COVID-19. Aprovechando una base de datos relacional que contiene información sobre libros, autores, editoriales, calificaciones y reseñas, se desarrollaron consultas SQL para responder preguntas clave sobre las publicaciones, la calidad percibida de los libros y las editoriales más activas en el mercado.

# Objetivos<br>
   - Determinar la cantidad de libros publicados después del 1 de enero del año 2000.<br>
   - Calcular el número de reseñas y la calificación promedio para cada libro.<br>
   - Identificar la editorial con mayor volumen de libros publicados (excluyendo folletos).<br>
   - Encontrar al autor mejor valorado considerando libros con al menos 50 calificaciones.<br>
   - Calcular el número promedio de reseñas textuales entre los usuarios más activos.<br>

# Metodología<br>
Se utilizó Python para conectarse a una base de datos PostgreSQL mediante la librería SQLAlchemy, y se realizaron múltiples consultas SQL para explorar la base de datos. Se aplicaron filtros, agrupamientos, funciones de agregación y subconsultas para responder cada una de las preguntas analíticas planteadas.<br>
<br>
Las tablas analizadas incluyeron:<br>
    * books: información de cada libro (título, número de páginas, fecha, etc.).
    * authors: datos de los autores.
    * ratings y reviews: calificaciones y reseñas escritas por los usuarios.
    * publishers: editoriales responsables de las publicaciones.

# Conclusiones<br>
   - Se identificaron 819 libros publicados después del 1 de enero de 2000, demostrando que la industria editorial se mantiene activa incluso en la era digital.<br>
   - El libro “Twilight” fue el más reseñado (1120 reseñas) aunque no fue el mejor calificado. “Harry Potter and the Prisoner of Azkaban” tuvo una calificación más alta (4.41) con una gran cantidad de reseñas.<br>
   - La editorial Penguin Books lideró en volumen de publicaciones con libros de más de 50 páginas, con 42 libros registrados.<br>
   - El autor con la mayor calificación promedio fue J.K. Rowling/Mary GrandPré con una media de 4.29, considerando únicamente libros con más de 50 calificaciones.<br>
   - Los usuarios más activos, aquellos que calificaron más de 50 libros, escribieron en promedio 163 reseñas textuales, reflejando un alto nivel de compromiso.<br>

# Lenguajes y herramientas principales:<br>
   * SQL (PostgreSQL) para consultas y análisis de datos.<br>
   * Python (pandas, SQLAlchemy) para conexión, ejecución de queries y visualización.<br>
   * Jupyter Notebook para documentar el flujo del análisis.<br>

Este proyecto proporcionó insights útiles sobre el comportamiento de los lectores durante la pandemia y puede servir como base para estrategias de desarrollo de producto, recomendaciones personalizadas o campañas de marketing para plataformas de lectura digital.
