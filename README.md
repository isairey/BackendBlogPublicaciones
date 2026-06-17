<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png" />

# 📝 BlogSphere

### Plataforma de publicaciones, artículos y contenido social desarrollada con Spring Boot 🚀

<p align="center">
  <b>BlogSphere</b> es una plataforma moderna para la publicación y gestión de artículos, noticias, tutoriales y contenido digital, permitiendo a los usuarios crear publicaciones, interactuar con la comunidad y administrar contenido desde un panel centralizado.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Spring%20Boot-Backend-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/Java-17+-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/Blog-CMS-orange?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-de-blogsphere">Acerca de</a> •
  <a href="#-preview">Preview</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a>
</p>

</div>

---

# 🌌 Acerca de BlogSphere

**BlogSphere** es una plataforma web diseñada para la publicación de contenido digital, permitiendo a usuarios y administradores compartir información mediante artículos, publicaciones, noticias y contenido multimedia.

La plataforma ofrece herramientas para la gestión de usuarios, publicaciones, comentarios y categorías, convirtiéndose en una solución ideal para blogs personales, portales informativos y comunidades digitales.

La plataforma permite:

- 📝 Crear publicaciones
- 📰 Publicar noticias y artículos
- 💬 Sistema de comentarios
- ❤️ Reacciones y favoritos
- 👤 Gestión de perfiles
- 🏷️ Categorías y etiquetas
- 🔍 Buscador avanzado
- 📊 Estadísticas de contenido

El proyecto fue desarrollado para practicar:

- Spring Boot
- Java Backend
- APIs REST
- Arquitectura MVC
- Seguridad con JWT
- Bases de Datos Relacionales
- Desarrollo Full Stack



---

# ✨ Características

## 👤 Sistema de Usuarios

- 🔐 Registro de usuarios
- 🔑 Inicio de sesión
- 👤 Gestión de perfiles
- 🔒 Roles y permisos
- 📧 Recuperación de contraseña

---

## 📝 Gestión de Publicaciones

- Crear artículos
- Editar publicaciones
- Eliminar contenido
- Programar publicaciones
- Subir imágenes destacadas
- Editor enriquecido

---

## 💬 Interacción Social

- Sistema de comentarios
- Reacciones y likes
- Compartir publicaciones
- Guardar favoritos
- Seguimiento de autores

---

## 🔍 Exploración de Contenido

- Búsqueda avanzada
- Filtrado por categorías
- Etiquetas dinámicas
- Publicaciones destacadas
- Contenido reciente

---

# ⚙️ Panel Administrativo

## 👑 Administración General

- Gestión de usuarios
- Gestión de publicaciones
- Administración de categorías
- Moderación de comentarios
- Control de contenido

---

## 📊 Reportes y Estadísticas

- Publicaciones más vistas
- Usuarios activos
- Estadísticas de interacción
- Actividad reciente
- Métricas generales

---

# 🛠️ Tecnologías Utilizadas

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=java,spring,maven" />
</p>

- Java 17+
- Spring Boot
- Spring MVC
- Spring Security
- Spring Data JPA
- Hibernate
- Maven

---

## 🗄️ Base de Datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql,postgresql" />
</p>

- MySQL
- PostgreSQL
- JPA/Hibernate
- SQL

---

## 💻 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,bootstrap" />
</p>

- HTML5
- CSS3
- JavaScript
- Bootstrap

---

# 📂 Estructura del Proyecto

```bash
BlogSphere/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── controller/
│   │   │   ├── service/
│   │   │   ├── repository/
│   │   │   ├── model/
│   │   │   ├── dto/
│   │   │   └── security/
│   │
│   │   └── resources/
│   │       ├── templates/
│   │       ├── static/
│   │       └── application.properties
│
├── pom.xml
└── README.md
```

---

# ⚡ Instalación

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/BlogSphere
```

---

## 2️⃣ Configurar base de datos

Crear una base de datos:

```sql
CREATE DATABASE blogsphere;
```

---

## 3️⃣ Configurar credenciales

Editar:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/blogsphere
spring.datasource.username=root
spring.datasource.password=
```

---

## 4️⃣ Ejecutar aplicación

```bash
mvn spring-boot:run
```

o

```bash
./mvnw spring-boot:run
```

---

## 5️⃣ Abrir navegador

```bash
http://localhost:8080
```

---

# 🔥 Funcionalidades Técnicas

## 🗄️ Gestión de Datos

- CRUD de usuarios
- CRUD de publicaciones
- CRUD de categorías
- Gestión de comentarios
- Relaciones JPA

---

## 🔐 Seguridad

- Spring Security
- JWT Authentication
- Protección de rutas
- Roles y permisos
- Encriptación de contraseñas

---

## 📱 Responsive UI

- Bootstrap Layouts
- Mobile Friendly
- Responsive Components
- Optimización para tablets
- Diseño moderno

---

# 🧠 Objetivos del Proyecto

## 🎯 Aprender y practicar

- Spring Boot
- Arquitectura MVC
- APIs REST
- Seguridad Web
- Bases de Datos
- Gestión de Contenido
- Desarrollo Backend Profesional

---

# 📊 Roadmap

## 🚧 Próximamente

- 🤖 Recomendaciones con IA
- 📧 Newsletter integrada
- 📱 Aplicación móvil
- 🌙 Dark Mode
- 📈 SEO avanzado
- 🎙️ Publicaciones en audio
- 🔥 Tendencias automáticas
- ☁️ Almacenamiento en la nube

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Haz Fork del proyecto

2. Crear rama

```bash
git checkout -b feature/nueva-funcion
```

3. Realizar cambios

```bash
git commit -m "✨ Nueva funcionalidad"
```

4. Subir cambios

```bash
git push origin feature/nueva-funcion
```

5. Abrir Pull Request 🚀

---

# 👨‍💻 Fundador

<div align="center">

<img width="140" src="https://github.com/isairey.png" />

## Isai Reyes — Java & Full Stack Developer

Desarrollador apasionado por plataformas web, sistemas empresariales, gestión de contenido y desarrollo backend moderno.

</div>

---

# 🌟 Apoya el Proyecto

Si te gusta BlogSphere:

⭐ Dale una estrella al repositorio  
🍴 Haz Fork del proyecto  
📢 Comparte el proyecto con otros desarrolladores

---

# 📜 Licencia

Proyecto Open Source desarrollado con fines educativos y práctica profesional en Spring Boot.

---

<div align="center">

### 📝 BlogSphere — Comparte ideas, crea contenido y conecta con tu comunidad.

</div>
