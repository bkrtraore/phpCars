# phpCars
Site web de location de voiture en ligne réalisé en PHP/MySql

Télécharger le projet et le placer dans le www de votre serveur web.
Dans le dossier _config.php, se trouve les chemin vers les differents dossier de l'application.
Ligne 15 et 18, vous devrez modifer le chemin du fichier et le remplacer par le vôtre.

Exemple :
Chemin initial HOST => define('HOST', 'http://'.$host.'/ProjetPweb'.'/');
Chemin initial ROOT => define('ROOT', $root.'/ProjetPweb'.'/');
Si votre chemin est "Projet/Eleve1" remplacer les lignes par votre chemin.
Chemin initial HOST => define('HOST', 'http://'.$host.'/Projet/Eleve1'.'/');
Chemin initial ROOT => define('ROOT', $root.'/ProjetPweb/Projet/Eleve1'.'/');


Pour la base de données
Importer le fichier contenu dans asset et nommer la base "projetpwebbd.sql"
