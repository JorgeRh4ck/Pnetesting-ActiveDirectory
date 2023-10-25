# Pentesting Active Directory
## Introducción
Este repositorio tiene como objetivo proporcionar una amplia gama de herramientas, recursos y documentación para llevar a cabo pruebas de penetración y evaluaciones de seguridad en entornos basados en Active Directory.
### Enumeración
#### Samba
Samba es un servicio que funciona a nivel de red entre dispositivos windows y linux, implementado para compartir archivos entre distintos usuarios y sistemas operativos, además samba permite validación de usuarios haciendo uso del controlador de dominio para terner permisos personalidados en cada recurso de red.
#### CrackMapExec
CrackMapExec es una herramienta que nos permite enumerar información tal como el nombre del dominio, el nombre de la computadora, la version que software que esta corriendo y si el samba esta firmado o no, todo esto mediante smb a nivel de red con el comando:
```bash
cme smb <ip a auditar> 
```
#### RCP
### Explotación
#### ASRepRoasting attack
#### Kerberoasting attack
### Escalada de privilegios
#### Bloodhound
#### Bloodhound Python
### Post-Explotación (Persistencia)
