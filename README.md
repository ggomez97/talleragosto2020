# Obligatorio Taller de Linux Agosto 2020
---

## Playbook de Ansible para instalar y configurar apache como reverproxy y balancer
---

Este playbook de ansible instala Apache Web Server en distribuciones Debian, RedHat y sus derivadas.
También crea un archivo de configuración de virtual host para proxy reverso con balanceo de carga.

## Funcionamiento y utilización
---

Se debe editar el archivo balacedvh_vars.yml con las variables deseadas, luego se debe editar el archivo inventario con las maquinas sobre las cuales desea instalar y configurar el proxy reverso con balanceo de carga.
Luego de realizados debe ejecutar el playbook mediante el comando ***ansible-playbook playbook.yml*** con un usuario que pueda conectar mediante ssh y escalar permisos sudo en los equipos objetivo.

``` 
ansible-playbook playbook.yml
```
