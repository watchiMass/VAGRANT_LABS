Ces labs m'ont permis de comprendre et de maîtriser les concepts d'automatisation dans la création et la configuration de machines virtuelles via Vagrant en utilisant VirtualBox comme provider.

J'ai évidemment exploré la majorité des plugins Vagrant tout au long de mes labs.
Chaque lab montre une progression dans la complexité : configuration basique → personnalisation des ressources → réseau → multi-machines → provisionnement automatique.

NB : Dans chaque lab, je lance un serveur web nginx.

Dans le lab01 :
On crée un Vagrantfile basique pour une VM Ubuntu Trusty 64 pris sur https://portal.cloud.hashicorp.com/vagrant/discover/

Dans le lab02 :
Version simplifiée pour créer ma propre box Ubuntu Trusty avec une version spécifique.
Vous pouvez l'utiliser si vous voulez déployer rapidement une VM Ubuntu sur VirtualBox :
vagrant init sologoUVM/soloUbuntu --box-version 1.0

Dans le lab03 :
J'apprends à personnaliser les ressources de ma VM (RAM, CPU, interface graphique...)

Dans le lab04 :
Configuration réseau avancée.

Dans le lab05 :
Multi-machines avec boucle for.

Dans le lab06 :
Même configuration que le Lab 5 mais avec mise à jour automatique du fichier hosts.

Dans le lab07 :
Serveur nginx avec partage de dossier pour site web statique.

Dans le lab08 :
Cluster web avec load balancer basique (pas très bien implémenté)

Dans le lab09 :
Provisionnement automatique avec playbook Ansible local pour installer nginx.
