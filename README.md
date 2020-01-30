#### Thomas Lassalle et  Baptiste Morini

__hosts.yaml:__ Fichier inventaire de nos hyperviseurs.

## Ansible-playbooks:

__deployVM.yaml:__ Création de machine virtuelle avec ISO, CPU, RAM, interface réseau, disque dur. Ce fichier permet aussi de démarrer la machine virtuelle.

__new_user.yaml:__ Création de l'utilisateur *itesciadmin* avec un mot de passe haché (SHA 512). L'utilisateur est également ajouter dans des groupes..

__iptables:__ Création des règles de Firewall pour ne permettre que les ports 22 et 8006


