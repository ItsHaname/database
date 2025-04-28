# database
# Guide rapide pour MySQL sous Ubuntu

## 1. **Installer MySQL**

```bash
sudo apt update
sudo apt install mysql-server mysql-client
```
---
# 2. Se connecter au serveur MySQL
```
sudo mysql -u root -p
```
# 3. Exporter une base de données depuis MySQL

Pour exporter une base de données dans un fichier .sql, utilise la commande suivante :

```
mysqldump -u [utilisateur] -p [nom_de_la_base] > [fichier_backup].sql
```
