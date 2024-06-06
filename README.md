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
# privadas. Para garantizar Alta disponibilidad, se usaran dos zonas de disponibilidad (zona A y zona B).
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
# privada. Para facilitar la conexión se implementarán parámetros de
# configuracion de la base de datos RDS en el AWS System Manager Parameter Store,
# garantizando acceso seguro y eficiente a los datos almacenados.
## Requerimiento 7
# Se debe garantizar consultas al modulo de calificaciones y contactenos dentro de la pagina del cliente.

