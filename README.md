# EducaTrival
Juego de preguntas para evaluar por equipos con tablero interactivo, puntuaciones y ranking en tiempo real. Backend con Node.js y Prisma, frontend con React, Tailwind y JavaScript totalmente conectado a la base de datos MySQL.


# 🎲 Proyecto Trival Interactivo - Desarrollo de Aplicaciones Web

Este proyecto es el resultado de una **colaboración de 6 compañeros** durante las prácticas de desarrollo de aplicaciones web. Hemos trabajado en equipo, coordinándonos mediante **GitHub** y su control de versiones, además de crear diseños en **Figma** .  

Destacar el **aprendizaje autodidacta y colaboración constante** , ya que fuimos capaces de desarrollar un sistema funcional y bastante completo.

---

## 🚀 Características principales

- Sistema de partidas interactivo con tablero y casillas especiales (dobles, volver a tirar, etc.).
- Registro y cálculo automático de puntos de los equipos.
- Visualización de **rankings en tiempo real**, con efecto visual en caso de empates.
- Descarga de resultados en Excel directamente desde la aplicación.
- Integración completa entre **vistas de React** y **controladores en Node.js/Prisma**.
- Datos persistentes en la base de datos para poder consultarlos y exportarlos.

---

## 🖥️ Contribuciones destacadas 


### Vista Ranking
- Interfaz interactiva donde se muestran los equipos y su puntuación.
- Ordenación dinámica según los puntos obtenidos.
- Destaca visualmente los equipos con puntuaciones iguales.
- Los datos se extraen directamente de la base de datos usando los controladores de `rankingController`.
- Permite descargar los resultados en formato Excel.
- Fondo interactivo y diseño responsivo con imágenes de tablero y banderines.
-  Reutilización de controladores en otras vistas, manteniendo coherencia en el ranking y las puntuaciones.
-  Diseño responsivo y visualmente atractivo con Tailwind CSS, imágenes de tablero y banderines.  
  
### Interactividad y lógica
- Controladores para actualizar puntos, registrar respuestas y mantener historial de juego.  
- Manejo de movimientos de fichas, activación de casillas especiales y apertura de modales según el estado del juego.  
- Asegura que la información gestionada en backend se refleje de manera coherente en todas las vistas.  


### Excel / Subida de datos
- Componente que permite subir archivos Excel y convertirlos a JSON.
- Datos enviados al backend para ser almacenados en la base de datos.
- Posibilidad de descargarlos posteriormente para análisis o reporte.
- Totalmente integrado con el sistema de puntuaciones y ranking.

---

## 🛠️ Tecnología utilizada

- **Frontend:** React, TailwindCSS, hooks personalizados.
- **Backend:** Node.js, Express, Prisma ORM.
- **Base de datos:** MySQL (con Prisma para consultas y actualizaciones).
- **Gestión del proyecto:** GitHub para control de versiones, Figma para diseños.
- **Otros:** Trello para planificación y seguimiento de tareas (opcional en README).

---

## 📱 Responsive Design
Todas las vistas están optimizadas para **móviles, tablets y escritorio**, garantizando una experiencia fluida y visualmente atractiva.

---

## 🖼️ Vista previa del proyecto

[![Ver video en YouTube](https://img.youtube.com/vi/1-ijTKdGmtQ/0.jpg)](https://youtu.be/1-ijTKdGmtQ)  

👉 Haz clic en la imagen o en el siguiente enlace para ver el proyecto en funcionamiento:  
🔗 [Ver video en YouTube](https://youtu.be/1-ijTKdGmtQ)

---

## 🙋‍♀️ Autora y equipo

Proyecto desarrollado por: **Leticia Migueláñez Fuentetaja** y 5 compañeros.  
📧 Contacto: [leticia.miguelanez@gmail.com](mailto:leticia.miguelanez@gmail.com)

