# Role que crea maquinas virtuales en VMWARE

 
# Descripcion



 
## Requisitos
 
en modo de lista poner cada uno de los requisitos que se requieren para que se garantice la correcta ejecucion del playbook, a continuacion unos ejemplos:

- **Colecciones:** vmware.guest
- **Colecciones:** ansible.builtin
- Los instaladores deben estar en una ruta en los servidores remotos donde se va a realizar la instalacion, comprimidos en .tar.gz
- La ruta anterior debe ser puesta como valor en el archivo de variables.yml en la variable llamada instaladores 
- Se debe llenar el archivo hosts con las ips de los hosts donde se va a realizar la instalacion.
- El instalador del antivirus debe de estar en la ruta \\DC01\instaladores\sophos.msi
 
## Ambiente

Se encuentra en ambiente de Panama Desarrollo

- **AAP Costa Rica:** https://automationcr.gbmcloud.com/#/login
- **Nombre del Template:** Azalia | Mi primer Playbook
 
## Variables de entrada al momento de ejecución

nombre:  
apellido: 
usuarios:
ruta_instalador:
 
## Autores
 
- Cesar Cascante
