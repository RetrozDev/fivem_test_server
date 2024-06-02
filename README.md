
# Serveur de test fivem

Ce serveur est un serveur de test, avant de pouvoir lancer le serveur il y'a quelques choses à faire:





# I: Configurer votre serveur

### 1 : Télécharger les artifacts

- a : créer un dossier artifact à la racine
- b : télécharger le dernier [dernier build](https://runtime.fivem.net/artifacts/fivem/build_server_windows/master/) (en cliquant  sur latest recommended)
- c: mettre tout ce qui est dans le .zip dans artifact

### 2 : Mettre sa clé de license fivem 

- a : aller sur le site [keymaster](https://keymaster.fivem.net/)
- b : se connecter
- c : enregistrer un nouveau serveur 
- d : aller chercher son [ip publique ](https://www.monippublique.com/) et la copier
- e : aller sur keymaster et remplir les informations suivante:
    - display name : le nom que vous voulez
    - Initial server IP address: votre ip publique (copier avant)
    - Server type: Other / home hosted
    - Which server provider are you using?: home 
 ![infos](https://raw.githubusercontent.com/RetrozDev/fivem_test_server/main/%C3%A0%20effacer/keymaster1.png)
- f : cliquer sur generate
- g : cliquer sur copy
- h : coller la clé dans server cfg ici: 
        ```set sv_licenseKey votre_clé_fivem``` (ligne 58)

### 3 : Démarrer le serveur 

- a : Supprimer le dossier nommé "à effacer"
- b : faire un double clique sur start.bat 