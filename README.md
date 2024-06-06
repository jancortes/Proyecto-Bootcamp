# Proyecto-Bootcamp
Proyecto final despliegue infraestructura altamente disponible
# Planificacion
# Requerimientos
# Arquitectura
Este es el diagrama de arquitectura para una infraestructura altamente disponible en una libreria.
![arquitectura nube](images/arquitecturanube.PNG)
## Requerimiento 1 
# Desarrollar la plataforma web que permita a los clientes explorar los
# diferentes libros.
## Requerimiento 2
# Implementar la red en la nube de AWS con 6 subredes: dos públicas y cuatro
# privadas.
## Requerimiento 3
# La subred pública actuará como la puerta de entrada a la plataforma en línea,
# brindando a los usuarios acceso a internet y una experiencia de navegación
# fluida a traves del balanceador de carga. Se usara un auto scaling para redirigir volumen de 
# trafico creando nuevas instancias que permitan alojar ese trafico.
## Requerimiento 4
# Las subredes privadas  estarán protegidas contra accesos no autorizados
# desde internet garantizando la seguridad de los datos sensibles de la librería.
## Requerimiento 5
# La instancia EC2 debe poder conectarse a la base de datos en la subred
# privada. Para facilitar esta conexión se implementarán parámetros de
# conexión de la base de datos en el AWS System Manager Parameter Store,
# garantizando acceso seguro y eficiente a los datos almacenados.
