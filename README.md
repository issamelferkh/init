init
####
En bleu : une commande
En vert : une sortie de commande
En rouge : une déduction écrite avec vos propres mots
############################################################
dossier de chaque partie 
s’appeler network, system et scripts. 
les réponses dans un fichier => network/01
############################################################
partie 1 “Network” -> réaliser sur les Macs
partie 2 “System” et 3 “Scripting” -> réaliser sur une VM Debian
############################################################

network
#######
01 -> okv
02 -> ok -> pas suuur !!!
03 -> okv
04 -> okv
05 -> okv
06 -> okv
07 -> okv
08 -> okv
09 -> okv -> cmd "dig +short 42.fr"
10 -> okv
11 -> okv
12 -> okv
13 -> okv -> nslookup `ipconfig getifaddr en0` | grep name | cut -c32-
14 -> okv
15 -> okv

system
######
01 -> ok
02 -> ok -> hostname or hostname "new name"
03 -> ok
04 -> ok
05 -> ok -> check network: ip address | install ssh: 
sudo apt-get update
sudo apt-get install -y openssh-server openssh-client
06 -> ok
07 -> ok
08 -> ok
09 -> ok
10 -> ok
11 -> ok
12 -> ok
13 -> ok
14 -> ok
15 -> ??? -> how can I know the PID processs
16 -> ok
17 -> ??? -> ntconnecta l localhost "ssh test1@localhost" ou fine ? "ssh iel-fer@10.12.8.13"
18 -> ok
19 -> prob -> pas de chkonfig cmd
20 -> ok
21 -> user reel ???
22 -> ok -> ??? creer user ou just cmd
23 -> ??? -> expliquation
24 -> ok

scripts
#######
01 -> ok -> Not Verif
02 -> ok -> Not Verif
03 -> ok -> Not Verif

Questions
#########
* oublier pas "sudo" pour les cmd partie systeme et script
* user: user, pwd: live

