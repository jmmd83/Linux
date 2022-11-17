## Linux

### Fedora ###

**Saber que zona del firewall está activa**
$ firewall-cmd --get-active-zones

**Cambiar a la zona por defecto (puertos 1025-65536 abiertos)**
$ firewall-cmd --set-default-zone=FedoraWorkstation

**Cambiar a la zona public (más segura)**
$ firewall-cmd --set-default-zone=public

**Conocer datos de zona concreta**
$ firewall-cmd --zone=FedoraWorkstation --list-all
