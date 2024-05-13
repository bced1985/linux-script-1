# Scripts shell Linux et Unix
Ce document est un résumé de ma lecture du livre ___Scripts shell Linux et Unix___ de **Christophe Blaess**.  
Voici le [lien vers le site web du livre](https://www.blaess.fr/christophe/livres/scripts-shell-linux-et-unix/)

Ce document est structuré de cette manière :  

Un  chapitre du livre est représenté par un répertoire dans ce projet/dépôt GitHub.  

Dans chaque répertoire, se trouve un ou des fichiers shell. 

Chaque fichier shell contient les notions sur un concept (exemple : la commande ***getopts***).  

Le fichier shell est structuré comme suit :  

1. Descriptif du concept
2. Syntaxe de base d'utilisation du concept (le cas échéant)
3. Code shell

## Sommaire

#### Chapitre 1 :  
*Mots-clés : ... - ...*

#### Chapitre 2 :  
*Mots-clés : ... - ...*  

#### Chapitre n :
*Mots-clés : ... - ...*  


#The most universal way is to create a view over the top of the table. This contains the query excluding "deleted" rows. You change your application to query the view instead of the table.
``` sql
create or replace view active_toys as
  select * from toys
  where is_deleted = 'N';

select * from active_toys;
```
[//]: # (This may be the most platform independent comment)

