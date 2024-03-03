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

## SPTINT 4. Hardening SSL
#### En este sprint el objetivo es subir el nivel de seguridad del servicio de SSL
1. Descargar e instalar el servicio de SSL
2. Limitar permisos al servicio
3. Configurar directivas de autentificación
4. Administrar la eejcución del comando sudo
5. Habilitar el doble factor de autentificación de Google
6. Generar tokens 2FA
7. Habilitar tokens 2FA

## SPRINT 5. Escaneo de vulnerabilidades
#### En este sprint veremos como podemos analizar las vulnerabilidades de nuestros servicios anteriormente instalados y asegurados.
1. Crear una máquina con Kali linux
2. Crear una máquina con metasplotable2
3. Configurar laboratorio con las 3 máquinas: Ubuntu_server, metasplotable2 y kali linux
4. Analizar el Cheat Sheet de Nmap
5. Realizar varios ataques con Nmap
6. Analizar los resultados de ambas máquinas y compararlos

## SPRINT 6. Escaneo de Vulnerabilidades
#### Este sprint veremos como instalar y configurar una máquina virtual con un servicio de FireWall con el software Pfsense
1. Instalar máquina virtual de pfsense
2. Crear máquina windows cliente
3. Configurar red: Pfsense; puente, lan-dmz, lan-empleados - windows; lan_empleados - Pfsense; lan_dmz
4.  Descargar las reglas de la comunidad
5.  Aplicar reglas
6.  Comprobar funcionamiento

## SPRINT 7. IDS y VPN con pfSense
#### Aqui veremos la instalación y configuracion del servicio de OpenVPN y suricata en nuestra red empresarial
1. Instalar Suricata en Pfsense
2. Configurar Suricata para rechazar ataques con las reglas SNORT
3. Comprobar el funcionamiento del mismo
4. Instalar y configurar OpenVPN
5. Dar de alta a usuarios y crear sus certificados
6. Comprobar conexion con el VPN mediante certificado y contraseña
7. Comprobar funcionamiento

## SPRINT 8. PROXY INVERSO Y BALANCEADOR DE CARGA
#### En este sprint aprenderemos a configurar un proxy inverso y un balanceador de carga.
### PROXY INVERSO
1. Creamos estructura de ficheros
2. Activamos módulos
3. Abrimos servidor web
4. Configuramos la ruta del servidor proxy en los archivos de configuración
5. Comprobamos su funcionamiento
### BALANCEADOR DE CARGA
1. Creamos estructura de ficheros
2. Desactivamos el proxy inverso
3. Activamos módulos
4. Abrimos servidores web de los miembros del balanceador de carga
5. Creamos el archivo de configuración llamado " loadbalancer.conf "
6. Agregamos el " balancer-manager " en la configuración de apache
7. Comprobamos correcto funcionamiento
