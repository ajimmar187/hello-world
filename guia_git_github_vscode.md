# 📘 Guía Completa para Principiantes: Control de Código Fuente con Git y GitHub en Visual Studio Code

...[contenido anterior sin cambios]...

---

## 6. Pull Requests y colaboración con GitHub

### 🔁 ¿Qué es un Pull Request?
Un *Pull Request* (PR) es una solicitud para fusionar los cambios realizados en una rama (normalmente de un colaborador) dentro de otra rama principal del proyecto (como `main`). Es una forma segura y organizada de revisar, discutir y aprobar cambios antes de que se integren en la versión final del proyecto.

Es especialmente útil cuando se trabaja en equipo o en proyectos colaborativos, como los que se encuentran en GitHub.

### 🎯 ¿Para qué sirve?
- Permite revisar código antes de integrarlo.
- Facilita la colaboración entre desarrolladores.
- Registra la discusión sobre los cambios propuestos.
- Permite a otros aprobar o sugerir mejoras antes de aceptar los cambios.

### 🧪 Ejemplo práctico
1. Estás trabajando en una rama `mejora-pagina`.
2. Cuando terminas tu trabajo, subes (push) los cambios a GitHub.
3. En GitHub, verás un botón para “Comparar y crear Pull Request”.
4. Rellenas el título y descripción del PR, explicando qué hiciste y por qué.
5. Otros compañeros pueden comentar, revisar y aprobar.
6. Cuando esté todo correcto, se fusiona con la rama principal (`main`).

### 🧩 Usar la extensión “GitHub Pull Requests and Issues” en VS Code
Esta extensión te permite gestionar PRs directamente desde VS Code:

#### ¿Qué puedes hacer?
- Ver todos los Pull Requests abiertos.
- Crear nuevos PRs sin salir del editor.
- Revisar línea por línea los cambios propuestos.
- Hacer comentarios y aprobar cambios.
- Fusionar un PR si tienes permiso.

#### ¿Cómo se instala?
1. Abre VS Code y presiona `Ctrl+Shift+X`.
2. Busca `GitHub Pull Requests and Issues`.
3. Haz clic en “Instalar”.
4. Conéctate con tu cuenta de GitHub.

#### ¿Cómo se usa?
1. En la barra lateral izquierda, haz clic en el ícono de GitHub.
2. Verás la lista de PRs disponibles en tu repositorio.
3. Haz clic en uno para ver los cambios propuestos.
4. Puedes comentar, aprobar o fusionar (si tienes permisos).

---

## 7. Preguntas frecuentes para estudiantes novatos

### ❓ ¿Puedo usar Git sin Internet?
Sí, puedes trabajar localmente. Solo necesitas conexión para clonar, hacer push o pull.

### ❓ ¿Qué hago si me equivoqué en un archivo?
Puedes hacer clic derecho > "Descartar cambios".

### ❓ ¿Y si me equivoqué en un commit?
Usa el comando `Git: Amendar commit` o `Git: Deshacer último commit`.

### ❓ ¿Qué pasa si dos personas cambian el mismo archivo?
Aparecerá un "conflicto de fusión". VS Code te mostrará los cambios de ambas personas y podrás elegir cuáles mantener.

### ❓ ¿Qué es un commit?
Es como una foto del estado de tus archivos en un momento. Incluye un mensaje que explica lo que hiciste.

### ❓ ¿Cuándo debo hacer commits?
- Cuando termines una pequeña parte del trabajo.
- Antes de probar algo nuevo.
- Antes de hacer un cambio importante.

---

## 8. Buenas prácticas

- ✅ Haz commits con frecuencia, con mensajes breves y claros.
- ✅ Usa ramas para nuevas funcionalidades o correcciones.
- ✅ Sube tu trabajo a GitHub al terminar el día.
- ❌ No hagas commits con el mensaje "cambios varios" o "cosas".
- ❌ No trabajes directamente en la rama `main`.

---

## 🧪 Actividad paso a paso para practicar

### Objetivo: Crear, guardar y publicar tu primer proyecto en GitHub

1. Abre Visual Studio Code.
2. Crea una carpeta llamada `proyecto-prueba`.
3. Dentro, crea un archivo `index.html` con un título.
4. Inicializa el repositorio Git.
5. Haz tu primer commit.
6. Crea una cuenta en GitHub (si no la tienes).
7. Publica el repositorio en GitHub.
8. Crea una rama llamada `experimentos`, cambia a ella y modifica el HTML.
9. Haz commit en la nueva rama y vuelve a `main`.
10. Fusiona la rama `experimentos` en `main`.
11. Sube los cambios finales a GitHub.
12. Comparte el enlace del repositorio con tu profesor/a.

---

¡Felicidades! Acabas de dar tus primeros pasos en el mundo del desarrollo profesional con Git y GitHub. Este conocimiento será esencial en cualquier entorno de trabajo colaborativo o proyecto de programación que emprendas.
