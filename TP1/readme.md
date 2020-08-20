# Projet AWS terraform

# Créer une VM

 - Generer une clef SSH 
 - Créer l'instance de la VM a partir de la console AWS : 
 - Renseigner la clef SSH lors de la configuration de la VM


# Se connecter à la VM

- Faire un chmod 400 sur le fichier ssh.pem
- Se connecter à la machine grace a l'adresse IP de la machine avec la commande :
  ```
  ssh -i ./votrefichierssh.pem ubuntu@ip
  ```

# Installer un serveur web 

```
ubuntu@ip-172-31-44-116:~$ sudo apt -y update && sudo -y apt upgrade
```
```
ubuntu@ip-172-31-44-116:~$ sudo apt -y update && sudo -y apt upgrade
```
```
ubuntu@ip-172-31-44-116:~$ sudo wget -O - http://localhost/
```
```
ubuntu@ip-172-31-44-116:~$ sudo apt -y install w3m
```
```
ubuntu@ip-172-31-44-116:~$ sudo w3m http://localhost/
```



