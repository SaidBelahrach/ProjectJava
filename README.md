<h2>Projet</h2>
Il s'agit d'une app desktop qui permet , soit aux étudiants ou aux professeurs,  de passer, suivre et gérer ses examens facilement et en ligne. 

cette app est connectée avec un serveur d'examens qui s'occupe de l'envoie d'examens, enregistrement des résultats , création des examens...  ce qui renforc la sécurité des données et d'éviter les tentatives de fraude.

<h2>Demo:</h2>https://youtu.be/Vlww0NbxD94

<h2>les outils utilisés:</h2>
<pre>
   Eclipse.
   Java :swing + socket.
   MySql. (wampserver)
</pre>

<h2>Base de données:</h2>
<pre>
SGBD: Mysql
Restaurer script de base de données: script-db.sql 
</pre>

<h2>Cahier de charge</h2>
<pre>
Réaliser ce projet sous forme : 
• Application Client-Serveur en utilisant les sockets java

Une question est définit par : 
• La description textuelle (* : peut être illustrée par une image, son, ou vidéo) 
• Les 4 choix à présenter à l’utilisateur (* : plus de 4) 
• La bonne réponse (* : plusieurs réponse justes) 

Un examen QCM est définit par : 
• Un titre 
• Le professeur créateur 
• La filière concernée 
• La matière concernée 
• Une base de données contenant 30 questions examinant la matière (* : plus que 30) 
• 20 questions seront présentées au candidat d’une manière aléatoires tirées de la base de 
données (* : Nombre de questions est propre à chaque QCM, pas fixé à 20) 
• La cible du QCM : que les étudiants de la filière. 
• La note pour chaque question sera 1 pour une réponse juste sinon 0 
(* : une autre notation (-1 : réponse fausse, 0 : sans réponse, 1 : réponse juste) 

Un professeur est définit par : 
• Le nom 
• La spécialité 
• La liste des QCM crées 

Un étudiant est définit par : 
• Le nom 
• La filière 

En plus des 4 entités décrites ci-dessus, la modélisation de votre base de données peut faire apparaitre 
d’autres entités telles que : Examen (représente le résultat du passage d’un QCM par un étudiant), etc. 
Votre application doit proposer à l’étudiant la liste des QCMs disponibles pour sa filière. L’étudiant
choisit un QCM et commence l’examen. 
Votre base de données doit être capable de stocker la liste des étudiants ayant passé un examen donné 
et le score obtenu par chacun. 
L’étudiant peut afficher ses résultats concernant les QCM qu’il a déjà passés 
Le professeur propriétaire d’un QCM doit être capable d’afficher, la liste des étudiants et leurs notes. 

</pre>
