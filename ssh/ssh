# Secure Shell

## ¿Qué es SSH?

*Secure Shell* es un protocolo de red destinado a la conexión con máquinas a las que se accede por línea de comandos.  
Utiliza una arquitectura `cliente-servidor` i.e  
* Cliente SSH: Máquina local que busca acceder a un servidor remoto. (OpenSSH o puTTY)
* Servidor SSH: Máquina remota que se configura para describir que conexiones ssh son aceptadas.
* Autenticación: Proceso en que se verifican credenciales.

## Commandos

1. Creación de una llave `ssh`.
`bash
ssh-keygen -t rsa -b 2048 -C "<comentario>" -f ~/.ssh/myKey
`
`-t` indica el tipo de algoritmo que genera la llave.  
`-b` indica el tamaño en bytes de la llave.  
`-C` indica que se introduce un comentario a la llave.  
`-f` indica la ruta de la llave.
