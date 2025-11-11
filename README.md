Ces la m'ont permis de pourvoir comprendre et mitriser les conceptes d'automatisation dans la création et la configuration de machines virtuelle via vagrant en ayant
comme provider virtualbox.
J'ai bien évidement explorer la majorité des plugins vagrant tout au long de mes labs.
Chaque lab montre une progression dans la complexité : configuration basique → personnalisation ressources → réseau → multi-machines → provisionnement automatique.
NB: Dans chaque lab je lance un serveur web nginx 
Dans le lab01: 
 on créé un Vagrantfile basique pour une VM Ubuntu Trusty 64 prit sur https://portal.cloud.hashicorp.com/vagrant/discover/

Dans le lab02: 
Version simplifiée pour créer ma propre box Ubuntu Trusty avec version spécifique,
vous pouvez l'utilisez si vous voulez deployer rapidement un vb ubuntu sur virtualbox :
vagrant init sologoUVM/soloUbuntu --box-version 1.0

Dans le lab03: 
J'apprends à personaliser les ressorces de ma vm (ram, cpu, interface graphique ...)

Dans le lab04:
Configuration réseau avancée.

Dans le lab05:
Multi-machines avec boucle for.

Dans le lab06:
Même configuration que Lab 5 mais avec mise à jour automatique du fichier hosts.

Dans le lab07:
Serveur nginx avec partage de dossier pour site web statique.

Dans le lab08: 
Cluster web avec load balancer basic (pas très bien implémenter)

Dans le lab09:
Provisionnement automatique avec playbook Ansible local pour installer nginx.
