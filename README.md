# Sprints de seguridad informática

Practicas de la asignatura de Seguridad informática, en este repositorio se recoge unicamente el proyecto por ahora, seguidamente se detallarán los sprints realizados en esta asignatura

## SPRINT 1. Hardening en Ubuntu:
#### El objetivo de este sprint es establecer reglas de serguridad a nuestro sistema operativo, en esta caso ubuntu:
1. Upgradear Sistema Operativo a la versión PRO.
2. instalar herramienta *usg*.
3. auditar con las normas de **cis_level2_server**.
4. crear archivo de configuraciones *tailor.xml*.
5. Modificar el archivo tailor.xml a nuestro antojo.
6. Agregar usuario extra con permisos de **administrador**.
7. Establecer contraseña al GRUB y al usuario root.
8. Limitar permisos en la carpeta de configuracion de GRUB.

## SPRINT 2. Copias de seguridad
#### El objetivo de este sprint es hacer unas copias de seguridad y recuperaciones de unas carpetas del sistema operativo
1. instalación del software *duplicati*.
2. Configuramos la carpeta origen.
3. Configuramos la carpeta de destino *GoogleDrive*.
4. Establecer el tiempo de la copia de seguridad.
5. Reaizar la Copia de Seguridad.
6. Hacer la recuperacion de esa Copia de seguridad para comprobar que hemos asegurado esos datos correctamente.

## SPRINT 3. Hardening Apache2
#### El objetivo es subir la seguridad de nuestro servicio de HTTP y así evitar ataques futuros.
1. Instalación de Apache.
2. Configuraciones globales.
3. Ficheros de configuraciones
4. Configuración de usuarios y grupos
5. Ocultación de versiones. 
6. Exposición mínima de módulos.
7. Creación de virtualhost personalizado.
8. Configuración múltiple y de contexto: directiva options
9. Restricción de acceso al contenido: directiva Auth y Require.
10. Evitar el hotlinking
11. Configuración HTTPS mediante OpenSSL.
12. Crea los certificados para que tu virtualHost sea seguro, y obligatoriamente los accesos sean por HTTPS
13. Activar módulo mod_security.
14. Realiza un ataque DoS mediante Metasploit (Slowloris) y comprueba que efectivamente el servidor está inaccesible.
15. Clona e instala las reglas recomendadas OWASP.
16. Habilitar mod_security
17. Reglas para detectar SQLInjection
19. Realiza de nuevo el ataque DoS y comprueba que el servidor está accesible.
