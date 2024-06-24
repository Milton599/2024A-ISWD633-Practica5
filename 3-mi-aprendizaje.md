## Mi aprendizaje 

Después de realizar la práctica con Docker Compose, he mejorado significativamente en la configuración y gestión de servicios multi-contenedor. Aprendí a definir y organizar servicios utilizando un archivo compose.yaml, configurar correctamente variables de entorno para asegurar el funcionamiento de los servicios, y manejar la persistencia de datos mediante la configuración de volúmenes. Además, adquirí habilidades en la configuración de redes, la implementación de healthchecks para monitorear la salud de los servicios, y la automatización del despliegue de aplicaciones complejas. Esta experiencia también me permitió resolver problemas de configuración entre servicios, fortaleciendo mi comprensión de Docker Compose y su aplicación práctica en entornos de desarrollo y despliegue de software.

## Problemas solucionados 

Tenía problemas al ejecutar el siguiente comando después de haber configurado correctamente el archivo compose.yaml:
```
docker compose up -d
```
El problema se debió a que no tenía los privilegios necesarios, por lo que tuve que ejecutar el comando como administrador en el CMD.



