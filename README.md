# Weather App

Este repositorio contiene una aplicación completa que incluye un **frontend** desarrollado con **React** y **Vite**, y un **backend** desarrollado con **NestJS**. La aplicación permite consultar el clima de distintas ciudades, gestionar favoritos y visualizar datos meteorológicos de manera interactiva.

---

## 🛠️ Tecnologías Utilizadas

### Frontend
- **React**: Biblioteca principal para construir la interfaz de usuario.
- **Vite**: Herramienta de desarrollo rápido para aplicaciones web.
- **Zustand**: Manejo del estado global.
- **TailwindCSS**: Framework CSS para estilización rápida y consistente.

### Backend
- **NestJS**: Framework para construir la API REST.
- **TypeORM**: ORM para interactuar con la base de datos (PostgreSQL).
- **Swagger**: Documentación interactiva de la API.

---

## 🚀 Cómo cargar el repositorio con submódulos

Este repositorio incluye submódulos para el frontend y el backend. Para clonar el repositorio con los submódulos, utiliza el siguiente comando:

```bash
git clone --recurse-submodules https://github.com/adiazt01/weather-app.git
```

Si ya has clonado el repositorio sin los submódulos, puedes inicializarlos con:

```bash
git submodule update --init --recursive
```

---

## 🧑‍💻 Etapa de Desarrollo

En la etapa de desarrollo, es necesario acceder directamente a cada proyecto (frontend y backend) y configurarlos según la documentación específica de cada uno.

### Frontend
1. Accede al directorio del frontend:
   ```bash
   cd frontend
   ```
2. Sigue las instrucciones en el archivo `frontend/README.md` para configurar y ejecutar el proyecto.

### Backend
1. Accede al directorio del backend:
   ```bash
   cd backend
   ```
2. Sigue las instrucciones en el archivo `backend/README.md` para configurar y ejecutar el proyecto.

---

## 📚 Documentación por Submódulos

Cada submódulo del proyecto (frontend y backend) incluye su propia documentación detallada. Puedes encontrar instrucciones específicas para configurar, ejecutar y probar cada submódulo en los archivos `README.md` dentro de sus respectivos directorios:

### Frontend
- Ubicación: `frontend/README.md`
- Contiene detalles sobre cómo configurar y ejecutar el frontend, así como las herramientas y tecnologías utilizadas.

### Backend
- Ubicación: `backend/README.md`
- Contiene detalles sobre cómo configurar y ejecutar el backend, incluyendo la configuración de la base de datos y la documentación de la API.

---

## 📝 Notas
- Asegúrate de tener instalados **Node.js**, **Docker**, y **Docker Compose** en tu sistema.
- Para levantar ambos proyectos en producción, puedes utilizar el archivo `docker-compose.yml` en la raíz del repositorio.

---

## 📝 Notas Finales

- **Testing**: Aunque el backend está completamente testeado, no se pudo completar el testing del frontend debido a limitaciones de tiempo.
- **PWA e Internacionalización**: No se logró convertir el frontend en una PWA ni implementar la internacionalización de la aplicación.


## 📝 Agradecimientos
Eternamente agradecido por visualizar la resolución de esta prueba técnica, espero que a pesar de los errores cometidos, haya sido de su agrado para poder evaluar mis conocimientos y habilidades. Estoy abierto a cualquier consulta o aclaración que necesiten, no duden en contactarme.