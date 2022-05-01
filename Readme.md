<h2> Playbook de post-installation Ubuntu 22.04 LTS</h2>

<h3> Installation des logiciels supplémentaires ou s'assurer qu'ils soient présents:</h3>

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
14. discord
15. brave-browser
16. code
17. virtualbox
18. virtualbox-dkms
19. vlc
20. protonvpn
21. protonvpn-gui
22. wireshark
23. steam
24. lutris
25. deja-dup

<h3> Installation de la police utilisée dans le futur shell : Fonts-firacode </h3>

<h3> Mise en place de l'interpréteur zsh et récupération des extensions suivantes :</h3>

1. zsh-autossugestions
2. zsh-completions
3. zsh-syntax-highlighting

<h3> Configuration du fichier .zshrc : </h3>

1. Modification du thème utilisé (*Powerlevel10K*)
2. Ajout des alias
3. Ajout des extensions


En cours de dev', pour le moment cela donne ça :

![first step](/images/alpha.png)


Lancement du playbook :
> ansible-playbook playbook.yml -i inventory.ini -K          