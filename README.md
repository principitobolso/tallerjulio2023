# tallerjulio2023 - Obligartorio

Se urtilizo como server Bastion Rocky Linux 8.7

Se instalo ansible con el comando #sudo DNF install ansible

Se creo el usuario Ansible para realizar las ejecuciones de los Playbooks utilizados.

Por medio deuna ventana SSH generamos la clave pública en el equipo Bastión con ssh-keygen

Se distribuyo la clave publica en los equipos a administrar con el comando ssh-copy-id

Se instala coleccion para hardening del sistema operativo ansible-galaxy collection install devsec.hardening


