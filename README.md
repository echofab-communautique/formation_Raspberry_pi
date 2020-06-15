# Raspberry_Pi

Introduction au Raspberry Pi - Collection de ressources bilingues

##Introduction au matériel

  * Intro Visuelle (Ang):http://www.cl.cam.ac.uk/projects/raspberrypi/tutorials/quick-start/
  * Images de Raspbian pour restaurer sur une carte SD http://www.raspberrypi.org/downloads
  * Comment installer un accès wifi http://www.framboise314.fr/la-framboise-314-et-le-wifi-ou-comment-se-passer-du-cable-ethernet-avec-le-raspberry-pi/			

Les mots de passe: <br>
Login : pi<br>
Password: raspberry<br>

Lancer l'interface graphique: <code>startx</code><br>

Passer en mode terminal:Control+Shift+ F1<br>
Repasser en mode graphique:Control+shift+F7<br>
Faire des mises à jour:

<code>sudo apt-get update</code> <br> <code>sudo apt-get upgrade</code>

ou combiner ces commandes <br><code>sudo apt-get update && sudo apt-get upgrade</code>

Les caractères && combinent les commandes linux

Vous pouvez aussi utiliser la commande <code>aptitude update && aptitude safe-upgrade</code> 



## Configuration initiale

<code>$ ou # indiquent une commande en mode terminal. Il ne faut donc PAS inscrire ce caractère.</code>
  * Changer le clavier par défaut	
En mode terminal, entrer la commande :
<code># sudo raspi-config</code>
Choisir Configure_Keyboard -> Sélectionner un clavier générique -> Langue : Other ->US English
  * Changer le mot de passe par défaut		
Tout les R-Pi sont livrés avec le même mot de passe par défault. Il faut donc modifier ce mot de passer pour s'assurer d'une certaine sécurité.					En mode terminal, entrer la commande :<code># sudo passwd</code>
  * Changer la clé SSH
Tout les R-Pi sont livrés avec la même clé SSH par défault. 
Pour effacer cette clé et en créer une nouvelle pour s'assurer d'une certaine sécurité.	En mode terminal, entrer la commande :
<code># sudo rm /etc/ssh/ssh_host_* && sudo dpkg-reconfigure openssh-serverRessources</code>

## Ressources
  * Cheat Sheet - Fond d'écran avec les commandes de bases : http://www.echofab.org/mediacontent/piback.jpg
  * Site Français sur le R-π : http://www.framboise314.fr/  (Voir section liens)
  * Autre blogue Français avec des projets motivants: http://monframboisepi.free.fr/	
  * Instrucatbles - http://www.instructables.com/id/Raspberry-Pi-Challenge/
