# Demo Django + Tailwind CSS 🐳

Este es un proyecto de demostración simple desarrollado en **Django 5.1.3** y estilizado con **Tailwind CSS** mediante CDN, completamente contenedorizado utilizando **Docker**.

## 🚀 Tecnologías Utilizadas

- **Python 3.12-slim** (Imagen base del contenedor)
- **Django 5.1.3** (Framework web backend)
- **Tailwind CSS** (Framework de diseño de interfaces)
- **Docker & Docker Compose** (Orquestación del entorno de desarrollo)
- **SQLite** (Base de datos local)

## 🛠️ Cómo Ejecutar el Proyecto Localmente

Para levantar el entorno de desarrollo, asegúrate de tener Docker instalado y sigue estos pasos:

1. Clona este repositorio o ubícate en la carpeta raíz del proyecto.
2. Ejecuta el siguiente comando para construir la imagen, aplicar las migraciones de base de datos automáticamente y encender el servidor:

```bash
docker-compose up
