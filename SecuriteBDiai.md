
Le systèmes informatique est souvent confronté à des problèmes qui deviennent de plus en plus des attaques.
Les differents types d'attaques les plus récurent, sont en détaillés dans le tableau ci-dessou. 

|----------------------------------------------------------------------------
|  Types d'attaque  | Attaque Frauduleuse     |  Attaque Non Frauduleuse     |
|----------------------------------------------------------------------------
|                   |Sabotage, Attaque de     |                              |
|                   |l'homme du milieu par    |-Panne logiciel ou Matérielle,|
|      Intégrité    |DDOS distribué à         |                              |
|                   |travers l'empoisonnement |                              |
|                   |du cache ARP,            |                              |
|                   |Le phishing et le spear  |                              |
|                   |phishing.                |                              |
|---------------------------------------------                               |
|                   |Les Attaques par         |                              |
|                   |harmeçonnage(phishing),  | -Catastrophe naturelle,      |
|                   |Cross site scriping(XSS),|                              | 
|                   |Injection SQL,           |                              |
| Confidentialité   |Ecoute clandestine,      |                              |
|                   |Les Attaques par déni de |                              |
|                   |service(DOS)             |                              | 
|                   |Téléchargement furtif    |                              |
|                   |( drive-by download)     | -Erreurs Humaines            |
|---------------------------------------------                               |
|                   |Logiciel malveillant     |                              |
|                   |(malware),               |                              |
|   Disponibilité   |Cassage de mot de passe, |                              |
|                   |Déni de service,         |                              |
|                   |chevaux de Troie.        |                              |
|------------------------------------------------------------------------------


Parmis ces dernières, se trouvent des attaquent qui elles visent directement la base de données ,parmis lesquel on peut citer :
1. Abus de privilège excessif
2. Abus de privilège légitime
3. Elévation de privilège
4. Exploitation de failles des bases de données vulnérables ou   mal  configurées 
5. Injection SQL
6. Faiblesse de l’audit natif
7. Déni de service
8. Vulnérabilités des protocoles de communication des bases de données
9. Copies non autorisées de données sensibles 
10. Exposition de données de sauvegarde

Face à ces genres de problèmes les bases de données sont constemment confrontés à des problèmes et se doivent d'être entretenus régulièrement 
au risque de perdre des données sensible ou même les serveurs.


Présentation des extensions des Fichiers des SGBD suivant :

* MYSQL

 Dossier de stockage des données : "/var/lib/mysql/" Sous Linux et "c:\Wamp\bin\mysql\mysql5. 7.13\data" Sous Windows

 .mwb : est l'extension du fichier qui contient les données de la table Mysql.

* POSTGRESSQL
Dossier de stockage des données : C:\Program Files\PostgreSQL\ numéro_version \data\.

.pgsql : est l'extension du fichier qui contient les données de la table   PostgresSQL.


-Oracle : Les fichiers de données (dont l'extension est . dbf)
    Les fichiers Redo Log (dont l'extension est . rdo )
    Les fichiers de contrôle (dont l'extension est . ctl)

* MsSQLServer
Dossier de stockage des données : C:\Program Files\PostgreSQL\ numéro_version \data\.
.mdf : est l'extension du fichier qui contient les données de la table MSSQLserver.





