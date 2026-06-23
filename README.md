# Plataforma Educativa Moodle

## Descripción

Este proyecto consiste en la implementación y configuración de una plataforma educativa basada en **Moodle**, un sistema de gestión del aprendizaje (LMS, *Learning Management System*) de código abierto. La plataforma está diseñada para proporcionar un entorno virtual que facilite la creación, administración y distribución de cursos en línea, permitiendo la interacción entre docentes y estudiantes mediante recursos digitales y herramientas de evaluación.

La implementación busca ofrecer una solución flexible, segura y escalable para apoyar los procesos de enseñanza-aprendizaje, promoviendo el acceso a la educación desde cualquier lugar y dispositivo con conexión a Internet.

---

## Objetivos

- Implementar una plataforma educativa basada en Moodle.
- Facilitar la gestión de cursos, usuarios y recursos académicos.
- Proporcionar herramientas para la evaluación y seguimiento del aprendizaje.
- Promover la educación a distancia y el acceso a contenidos digitales.
- Garantizar un entorno seguro y accesible para estudiantes y docentes.

---

## Características

- Gestión de cursos y contenidos educativos.
- Administración de usuarios y roles.
- Creación de tareas, cuestionarios y actividades.
- Foros de discusión y herramientas de comunicación.
- Seguimiento del progreso y desempeño de los estudiantes.
- Gestión y almacenamiento de recursos digitales.
- Acceso desde distintos dispositivos mediante navegador web.
- Plataforma extensible mediante plugins y complementos.

---

## Tecnologías Utilizadas

| Tecnología | Descripción |
|-------------|-------------|
| Moodle | Plataforma LMS de código abierto |
| PHP | Lenguaje principal de Moodle |
| MySQL / MariaDB | Sistema de gestión de bases de datos |
| Apache | Servidor web |
| Linux (Ubuntu) | Sistema operativo del servidor |

---

## Arquitectura del Sistema

```
Usuarios
    │
Navegador Web
    │
Servidor Apache
    │
  Moodle
    │
Base de Datos (MySQL/MariaDB)
```

---

## Funcionalidades Principales

- Gestión de usuarios y permisos.
- Administración de cursos.
- Creación de actividades y evaluaciones.
- Publicación de materiales didácticos.
- Seguimiento del progreso académico.
- Comunicación entre docentes y estudiantes.
- Generación de reportes y estadísticas.

---

## Requisitos

### Hardware recomendado

- Procesador: 2 núcleos o superior.
- Memoria RAM: 4 GB mínimo.
- Almacenamiento: 20 GB libres.
- Conexión a Internet.

### Software

- Ubuntu Server 22.04 LTS.
- Apache 2.
- PHP 8.
- MySQL 8 o MariaDB.
- Moodle 4.11.

---

## Instalación

1. Clonar el repositorio:

```bash
git clone https://github.com/usuario/plataforma-moodle.git
```

2. Acceder al directorio del proyecto:

```bash
cd plataforma-moodle
```

3. Configurar el servidor web y la base de datos.

4. Instalar Moodle siguiendo el asistente de configuración.

5. Acceder desde el navegador:

```
http://localhost/moodle
```

---

## Evidencias en documentación

Se pueden agregar imágenes de:

- Página de inicio.
- Panel de administración.
- Vista de cursos.
- Actividades y cuestionarios.
- Gestión de usuarios.

---

## Autor colaborativo

Angel Rodrigo Gutiérrez Pedroza

Egresado en proceso de Residencias Profesionales de Ingeniería en Sistemas Computacionales con especialidad en Redes. 

Proyecto desarrollado como parte de la implementación de una **Plataforma Educativa basada en Moodle**, orientada a proporcionar un entorno virtual para la gestión del aprendizaje y la administración de cursos en línea.

---

## Licencia

Este proyecto utiliza Moodle, software de código abierto distribuido bajo la licencia **GNU General Public License (GPL)**.
