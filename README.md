Note de Musique - Projet AJAX (Demande 1)
Présentation
Ce projet est une application simple permettant d'afficher la notation américaine correspondant à une note musicale classique (do, ré, mi, etc.).

L'utilisateur sélectionne une note dans une liste déroulante HTML, et une requête AJAX est envoyée à un fichier PHP qui renvoie la correspondance.
La réponse est affichée dynamiquement sans recharger la page.

📌 Objectifs pédagogiques
Mettre en œuvre une interaction client-serveur via AJAX.

Utiliser JavaScript unobstrusive (pas de JS inline dans le HTML).

Manipuler un tableau associatif PHP.

Afficher dynamiquement une réponse dans la page.

⚙️ Fonctionnalités
Liste déroulante générée en JavaScript.

Lorsqu'une note est sélectionnée :

Une requête AJAX est envoyée à un fichier PHP.

Le serveur recherche la correspondance dans un tableau PHP.

Le résultat est renvoyé au client sous forme de message.

Le message est affiché dynamiquement dans la page.

Ouvrir index.html dans un navigateur.

Une liste déroulante apparaît avec les notes classiques.

Choisir une note → une requête est envoyée à process_note.php.

Le message s’affiche dynamiquement dans la page (ex:
"La notation américaine pour la note sol est G").

📚 Technologies utilisées
HTML5 / CSS3

JavaScript (AJAX, DOM)

PHP (tableau associatif, requêtes POST)

Aucune dépendance externe

🧠 Concepts appliqués
AJAX avec XMLHttpRequest : communication asynchrone

Unobstrusive JavaScript : séparation claire du HTML et JS

Sécurité : htmlspecialchars pour éviter l'injection HTML dans le message

Modularité : un fichier dédié au traitement (process_note.php)


cf doc-consigne