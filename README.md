# Pentesting Active Directory
## Introducción
Este repositorio tiene como objetivo proporcionar una amplia gama de herramientas, recursos y documentación para llevar a cabo pruebas de penetración y evaluaciones de seguridad en entornos basados en Active Directory.
### Enumeración
#### CrackMapExec
CrackMapExec es una herramienta que nos permite enumerar información tal como el nombre del dominio, el nombre de la computadora, la versión de software que esta corriendo y si el samba esta firmado o no, todo esto mediante smb a nivel de red con el comando:
```bash
cme smb <ip a auditar> 
```
Enumerar los recursos (archivos) compartidos de smb:
```bash
cme smb <ip a auditar> -u '' -p '' --shares
```
#### Samba
Samba es un servicio que funciona a nivel de red entre dispositivos windows y linux, implementado para compartir recursos de red (archivos, discos, impreosras, etc.) entre distintos usuarios y sistemas operativos, además samba permite validación de usuarios haciendo uso del controlador de dominio para terner permisos personalidados en cada recurso.
#### RCP
### Explotación
#### ASRepRoasting attack
#### Kerberoasting attack
### Escalada de privilegios
#### Bloodhound
#### Bloodhound Python
### Post-Explotación (Persistencia)
