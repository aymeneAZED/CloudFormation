# CloudFormation
Ce modèle est destiné à un VPC contenant 3 sous-réseaux (1 pour la base de données privée, 2 pour le serveur Web public). 
Chaque sous-réseau a une instance. 
L'instance privée n'est accessible que par les sous-réseaux publics. 
Il déploie une passerelle Internet, avec une route par défaut sur les sous-réseaux publics.
 Il déploie une paire de passerelles NAT, et des routes par défaut.
outil utilisé : YAML
