## Templates de Referencia
- Travelix (Base)
- Travelista (Packages)
- Direngine
- Dorne


## Features
- Registro de usuario tanto local como usando las redes sociales (Google y Facebook principalmente)
- Sistema de preserva mediante token.
    . una vez q se confirme la reserva por parte del usuario se le generara un token
      con validez por X tiempo. durante ese periodo de tiempo se le guardara la reserva
    . un proximo paso que no debe demorar mucho es soportar en el portal el pago online
- Soportar opiniones/valoraciones sobre los tours/excursiones del sitio (similiar a tripadvisor)
- Incluir pagina con informacion relativa a la empresa
- Crear categorias de notificaciones y permitir a los usuarios suscribirse a ciertos grupos
- Posibilitar intercambio en tiempo real con el equipo de atencion al cliente

## Site Map 
### BACKEND
- Servicios
  . enviar promociones a los usuarios basado en sus reserva
  . enviar el front preguntas a los usuarios con prereservas
 
- Pagina de administracion para:
  . reviews (el equipo de soporte debe aprobar/eliminar los reviews)
  . fotos de los usuarios (debe ser aprobada por soporte)
  . ofertas
  . Preservas
  . Tours
    - nombre
    - descripcion
    - fotos
    - precio
    - Disponibilidad
  . Tags
  . Destinos
    - nombre
    - descripcion
    - fotos
    - precio
    - Disponibilidad

### FRONTEND
Multilenguaje
#### Home Page
  . carousel con fotos cuquis
  . login/register
  . menu con principales opciones (aun por definir)
  . opcion para hacer busqueda avanzada
  . users review
  . tours mas populares
  . destinos mas populares
  . contacto de las redes sociales
  . promociones
  . ofertas del dia
  . boton para intercambiar con el equipo de soporte

#### Search Packages
  . opcion para filtrar por:
    - destino
    - tipo de servicio
    - grid con los resultados de la busqueda con opciones para ordenar por:
      . precio
      . reviews
      . duracion
      . etc
    - destacar cuales son los mas populares y recomendados (tanto por la agencia como por los usuarios)

#### Detalles de un package

#### Search Tours

#### Pagina de Detalles de un tour
  - foto cuqui
  - fotos subidas por los viajeros
  - descripcion
  - precio
  - duracion
  - iconos relacionados a las actividades incluidas
  - reviews
    . foto
    . valoracion
    . texto (por definir la cantidad de caracteres)
    . permitir q los users le den like y dislike a los reviews
  - posibilidad de recomendar, darle like y compartir en las redes sociales de los usuarios
  - posibilidad de pre reserva

Perfil de usuario
  - datos del usuario
  - manejar susbscripciones

About us Page
  . info de la agencia


------
Servicios de backend

---------------------------
DUDAS

- Los tours tienen predefinidas todas las opciones o se permite customizar el hotel y otros detalles
- Es posible reservar casas, hoteles, etc de manera individual o solo mendiante los tours q oferta la
  agencia
