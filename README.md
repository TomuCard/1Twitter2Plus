Projet My_Twitter

Collaboration entre Tom, Ryad, Mathéo et Pavel.

Lancer le serveur PHP dans le dossier /public:

> **php -S localhost:5500**

Lancer Tailwindcss au moins une fois dans :

> **npx @tailwindcss/cli -i ./public/css/input.css -o ./public/css/output.css --watch**

Pour s'assuré du bon fonctionement des messages de la database : 

-> dans le mysql >  **SOURCE ./config/common_database.sql** pour rafraichir la bd a 0.
->         mysql >  **SOURCE ./config/insert.sql** pour ajouter les Inserts.  
-- Si vous souhaitez modifié les inserts pour rajouté un tweet ou autre il faut rafraichir la db et les inserts.

