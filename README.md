# [ChanchiTec](http://127.0.0.1:5500/Proyecto%20final/Paginaprincipal.html)

[![ChanchiTec](https://i.postimg.cc/xdyZQgFR/Captura-de-pantalla-2024-07-08-021759.png)]
(http://127.0.0.1:5500/Proyecto%20final/Paginaprincipal.html)

# 🖥️ Equipo Digital 🖥️

## 📄 Documentación Técnica 📄

### 🌐 Blog Cineplanet 🌐
#### 📄 Guía para Desarrolladores 📄

##### 🧑‍💻 Elliot Garamendi 🧑‍💻
##### 📅 2024 📅

## 📑 Índice 📑
1. [📄 Introducción 📄](#📄-introducción-📄)
2. [🎯 Objetivo 🎯](#🎯-objetivo-🎯)
   1. [Objetivo General](#objetivo-general)
   2. [Objetivos Específicos](#objetivos-específicos)
3. [🚀 Proyecto 🚀](#🚀-proyecto-🚀)
   1. [Funcionalidades Principales](#funcionalidades-principales)
   2. [Público Objetivo](#público-objetivo)
   3. [Tecnologías Utilizadas](#tecnologías-utilizadas)
4. [🛠️ Instalación y Configuración 🛠️](#🛠️-instalación-y-configuración-🛠️)
   1. [Requisitos Previos](#requisitos-previos)
   2. [Instalación](#instalación)
      1. [Desarrollo](#desarrollo)
      2. [Producción](#producción)
5. [📂 Estructura del Proyecto 📂](#📂-estructura-del-proyecto-📂)
   1. [Descripción de la Estructura de Directorios](#descripción-de-la-estructura-de-directorios)
   2. [Descripción de Componentes Clave](#descripción-de-componentes-clave)
6. [🌐 Uso de la API 🌐](#🌐-uso-de-la-api-🌐)
   1. [Configuración de Endpoints](#configuración-de-endpoints)
   2. [Ejemplos de Consumo de API](#ejemplos-de-consumo-de-api)
7. [🚀 Despliegue 🚀](#🚀-despliegue-🚀)
   1. [Preparación para el Despliegue](#preparación-para-el-despliegue)
   2. [Despliegue en Servidores](#despliegue-en-servidores)
      1. [Configuración de Docker](#configuración-de-docker)
      2. [Despliegue en JenKins](#despliegue-en-jenkins)
      3. [Despliegue en Azure DevOps](#despliegue-en-azure-devops)
8. [🔧 Mantenimiento 🔧](#🔧-mantenimiento-🔧)
   1. [Actualización de Dependencias](#actualización-de-dependencias)
   2. [Monitoreo y Logging](#monitoreo-y-logging)
9. [✔️ Buenas Prácticas ✔️](#✔️-buenas-prácticas-✔️)
   1. [Estilo de Código](#estilo-de-código)
   2. [Control de Versiones](#control-de-versiones)
10. [❓ Preguntas Frecuentes ❓](#❓-preguntas-frecuentes-❓)
11. [📞 Contacto 📞](#📞-contacto-📞)

## 📄 Introducción 📄

Blog Cineplanet es una aplicación web que utiliza Astro 4 para el frontend y Strapi como CMS. Diseñada para informar a los usuarios sobre las últimas novedades en cine y entretenimiento en Perú, ofrece artículos, videos y contenido multimedia. Este documento proporciona una guía detallada sobre la configuración, estructura y mejores prácticas para asegurar una transición fluida y eficiente, para comprender y mantener el proyecto de manera efectiva.

## 🎯 Objetivo 🎯

### Objetivo General
Proveer una documentación clara y completa que facilite a los desarrolladores comprender y continuar el desarrollo del Blog Cineplanet eficientemente.

### Objetivos Específicos
- Facilitar la instalación y configuración del entorno de desarrollo.
- Describir la estructura del proyecto y sus componentes clave.
- Guiar en el proceso de despliegue y mantenimiento del blog.
- Asegurar la calidad y consistencia del código con herramientas y prácticas recomendadas.

## 🚀 Proyecto 🚀
- **Nombre:** Blog Cineplanet
- **Nombre corto:** Blog CP
- **Descripción:** Conoce lo último del cine, películas y entretenimiento en un solo lugar del Perú. Notas y videos de los temas de tu interés en el mejor Blog Peruano.

### Funcionalidades Principales
- Artículos: Publicación y gestión de artículos relacionados con el cine y el entretenimiento.
- Videos y Contenido Multimedia: Integración de videos y otros tipos de contenido multimedia para mejorar la experiencia del usuario.
- SEO Optimizado: Configuración optimizada para motores de búsqueda, garantizando mejor visibilidad en línea.
- Diseño Responsivo: Adaptación del contenido y diseño para diversos dispositivos y tamaños de pantalla.

### Público Objetivo
El blog está dirigido a todos los interesados en el cine y el entretenimiento, incluyendo cinéfilos, críticos de cine y el público general que busca información actualizada sobre películas y eventos relacionados.

### Tecnologías Utilizadas
El proyecto se basa en las siguientes tecnologías y herramientas:
- Astro 4: Framework de frontend para la construcción de sitios web rápidos y optimizados.
- Strapi: CMS de código abierto para la gestión y publicación de contenido.
- Node.js y npm: Entorno de ejecución para JavaScript y gestor de paquetes para instalar dependencias.
- Bootstrap Icons: Iconos SVG de Bootstrap.
- Day.js: Biblioteca ligera para manejar fechas y horas.
- Swiper: Librería para implementar sliders.
- TypeScript: Superset de JavaScript que añade tipado estático opcional.

## 🛠️ Instalación y Configuración 🛠️

### Requisitos Previos
- Node.js (versión 18 o superior)
- npm (versión 8 o superior)
- Git

### Instalación
1. Clona el repositorio del proyecto:
```
git clone <url>
cd blog-cineplanet
```

2. Configura las variables de entorno:
```
cp .env.example .env.local
```
Edita _.env.local_ con los valores necesarios para tu entorno.

3. Instala las dependencias del proyecto:
```
npm install
```

#### Desarrollo
Para iniciar la aplicación en modo de desarrollo:
```
npm run dev
```
Esto iniciará la aplicación en http://localhost:3000.

#### Producción
Para compilar el proyecto y generar una versión optimizada para producción:
```
npm run build
```

Para previsualizar la versión de producción:
```
npm run preview
```
Esto iniciará un servidor local que servirá los archivos compilados en http://localhost:3000.

## 📂 Estructura del Proyecto 📂

### Descripción de la Estructura de Directorios
La estructura del proyecto se organiza de la siguiente manera:
```
/project-root
├── nginx/                   # Configuraciones y archivos para el servidor Nginx
├── public/                  # Archivos estáticos
├── src/
│   ├── components/          # Componentes reutilizables
│   ├── layouts/             # Diseños de página
│   ├── pages/               # Páginas del sitio
│   ├── services/            # Servicios y lógica de negocio
│   ├── styles/              # Estilos CSS
│   ├── utils/               # Utilidades y funciones auxiliares
│   └── ...                  # Otros directorios y archivos relevantes
├── .env.example             # Variables de entorno locales
├── Dockerfile               # Configuración para Docker
├── package.json             # Dependencias y scripts del proyecto
└── README.md                # Documentación básica del proyecto
```

### Descripción de Componentes Clave
- **/layouts/Head.astro:**
  El componente Head.astro gestiona las etiquetas <head> del documento HTML. Se utiliza para configurar metaetiquetas importantes como título, descripción, imagen, entre otros. Esto facilita la optimización para SEO y para compartir en redes sociales.

## 🌐 Uso de la API 🌐

### Configuración de Endpoints
Los endpoints de la API se configuran en los archivos de servicio ubicados en /src/services. Cada archivo de servicio contiene funciones que realizan solicitudes a la API. Los endpoints se construyen utilizando la URL base definida en las variables de entorno y se añaden parámetros de consulta según sea necesario.

### Ejemplos de Consumo de API
Para consumir la API, se utilizan las funciones definidas en los archivos de servicio correspondientes. Estas funciones utilizan el archivo de utilidades /src/utils/fetch.util.ts, que contiene la lógica para realizar solicitudes HTTP y gestionar las respuestas. A continuación, se detallan los archivos de servicio específicos para cada recurso:

- **/src/services/advertisement.service.ts:** Gestiona las solicitudes relacionadas con los anuncios.
- **/src/services/layout.service.ts:** Gestiona las solicitudes para redes y enlaces.
- **/src/services/post.service.ts:** Gestiona las solicitudes relacionadas con las publicaciones.

### Manejo de Autenticación
La autenticación en las solicitudes a la API se realiza mediante tokens. El token de autenticación está definido en el archivo de variables de entorno .env bajo la variable BACKEND_API_TOKEN. Este token se incluye en las cabeceras de las solicitudes HTTP para asegurar el acceso seguro a los endpoints protegidos.

## 🚀 Despliegue 🚀

### Preparación para el Despliegue
Antes de desplegar el proyecto, asegúrate de seguir estos pasos:
- Verifica que todas las dependencias estén actualizadas.
- Realiza pruebas exhaustivas para asegurarte de que todo funciona correctamente.
- Configura las variables de entorno necesarias para el entorno de producción.

### Despliegue en Servidores
El proyecto se despliega utilizando Docker y Jenkins, ejecutándose en Azure. A continuación, se detallan los pasos generales necesarios:

#### Configuración de Docker:
- Utiliza un archivo Dockerfile para construir la imagen del contenedor.
- Define el entorno de construcción y ejecución utilizando Node.js y Nginx.
- Incluye configuración de variables de entorno necesarias.

#### Despliegue en Jenkins:
- Utiliza un script en Jenkins para construir y desplegar la imagen Docker.
- El script detiene y elimina contenedores existentes, construye una nueva imagen con variables de entorno necesarias, y ejecuta un nuevo contenedor con la imagen construida.

#### Despliegue en Azure DevOps
Para el despliegue en producción, se utiliza Azure DevOps, asegurando una implementación eficiente y segura del proyecto Blog Cineplanet en Azure.

## 🔧 Mantenimiento 🔧

### Actualización de Dependencias
Para mantener el proyecto actualizado y seguro, sigue estos pasos:
- Revisa periódicamente las dependencias en el archivo package.json.
- Utiliza herramientas como npm outdated para identificar dependencias desactualizadas.
- Prueba el proyecto después de actualizar las dependencias para asegurarte de que todo funciona correctamente.

### Monitoreo y Logging
Es crucial monitorear la aplicación en producción para identificar y solucionar problemas rápidamente:
- Implementa soluciones de monitoreo como Azure Monitor, AWS CloudWatch o Google Stackdriver.
- Configura el logging adecuado para registrar errores y eventos importantes. Herramientas como Loggly, ELK Stack o Papertrail pueden ser útiles.

## ✔️ Buenas Prácticas ✔️

### Estilo de Código
Para mantener la coherencia y calidad del código:
- Sigue una guía de estilo de código, como la de Airbnb para JavaScript.
- Utiliza herramientas de linting como ESLint para identificar y corregir problemas de estilo automáticamente.
- Escribe comentarios claros y útiles para explicar partes complejas del código.

### Control de Versiones
El control de versiones es fundamental para gestionar el código fuente:
- Utiliza Git para el control de versiones.
- Crea ramas para desarrollar nuevas características o corregir errores.
- Realiza revisiones de código (code reviews) antes de fusionar cambios a la rama principal.

## ❓ Preguntas Frecuentes ❓

- ¿Qué hago si encuentro un error en la API?
  - Verifica los logs para identificar la causa del error.
  - Revisa la documentación de la API para asegurarte de que estás utilizando los endpoints correctamente.
  - Si no puedes resolver el problema, consulta con el equipo de desarrollo o revisa los issues en el repositorio del proyecto.

## 📞 Contacto 📞

Para más información o soporte, puedes contactar a los desarrolladores principales del proyecto:
- Elliot Garamendi: Desarrollador principal, responsable tanto del frontend con Astro como del CMS con Strapi.

No dudes en comunicarte con nosotros para cualquier consulta relacionada con el proyecto Blog Cineplanet.
