<h2> Playbook de post-installation Ubuntu 22.04 LTS</h2>

Il permet d'installer des logiciels supplémentaires ou de s'assurer qu'ils soient présents:

1. vim
2. zsh
3. tmux
4. tilix
5. ccze
6. htop
7. docker.io
8. docker-compose
9. git
10. curl
11. tree
12. nmap 
13. tcpdump 

Il permet ensuite de mettre en place et configurer le prompt zsh avec extensions + police Nerd Font
En cours de dev', pour le moment cela donne ça :

![first step](/images/alpha.png)


Lancement du playbook :
> ansible-playbook playbook.yml -i inventory.ini -K          