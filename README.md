# **Delivery Tracker App**  

Aplicación web diseñada para facilitar la gestión de rutas de entrega entre empresas y sus repartidores. Este proyecto está desarrollado como parte de un portafolio personal y utiliza tecnologías modernas como **Next.js**, **Node.js**, **MongoDB** y **Vercel**.

## **Características principales**  
- **Autenticación con roles**:  
  Los usuarios pueden registrarse e iniciar sesión como **empresa** o **repartidor**.  
  - Las **empresas** pueden visualizar a sus repartidores y el progreso de sus rutas.  
  - Los **repartidores** pueden gestionar sus rutas activas y registrar nuevas entregas.  

- **Gestión de rutas**:  
  - Visualización de rutas activas con mapas interactivos.  
  - Creación de nuevas rutas ingresando origen, destino y medio de transporte.  

- **Relaciones empresa-repartidor**:  
  Los repartidores se asignan a una empresa al registrarse, permitiendo una gestión centralizada.  

- **Almacenamiento seguro**:  
  Contraseñas cifradas y datos almacenados en una base de datos MongoDB.  

## **Tecnologías utilizadas**  
- **Frontend**: Next.js (con soporte para el App Router).  
- **Backend**: Node.js y MongoDB.  
- **Hosting**: Vercel.  
- **Autenticación**: JSON Web Tokens (JWT) y bcrypt para cifrado de contraseñas.  
- **Mapas**: Integración con librerías de mapas (como Leaflet o Google Maps API).  

## **Objetivo del proyecto**  
Este proyecto tiene como finalidad:
1. Aprender y aplicar **Next.js**, **Node.js**, **MongoDB** y **Vercel**.
2. Desarrollar habilidades en la creación de sistemas de autenticación, manejo de bases de datos, y gestión de datos dinámicos.
3. Construir una aplicación funcional que sea útil como parte de un portafolio profesional.
