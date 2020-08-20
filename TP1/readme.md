# Projet AWS terraform

# Créer une VM

 - Generer une clef SSH 
 - Créer l'instance de la VM a partir de la console AWS : 
 - Renseigner la clef SSH lors de la configuration de la VM
```
sss
```


# Se connecter à la VM

- Faire un chmod 400 sur le fichier ssh.pem
- Se connecter à la machine grace a l'adresse IP de la machine avec la commande :
  "ssh -i ./votrefichierssh.pem ubuntu@ip"
