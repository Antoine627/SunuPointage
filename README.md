# SunuPointage
Une structure de formation veut améliorer son système de pointage avec ses employés et ses apprenants. Il s’agit de mettre en place un système qui permet de faire le pointage des employés et des apprenants.
Le système permet d’enregistrer les apprenants par cohorte et les
employés par département avec leurs informations personnelles (nom, prénom,
photo,email, adresse, téléphone, fonction(pas de fonction pour les apprenants),
département(cohorte pour les apprenants), matricules, cardId). Le système permet
d’ouvrir la porte avec une carte et la porte se referme après 10 secondes
automatiquement. Le système enregistre en même temps l’heure du premier pointage de
chaque utilisateur et le dernier pointage tous les jours. Le système permettra de voir
l’historique des absences et retards des employés et des apprenants par jour, semaine et
mois.➔ Utilisateur Simple (employé et apprenant)
Il utilise sa carte pour pointer en même temps ouvrir la porte.
Si la carte est active une fois qu’il se badge un signal vert s’allume, un court bip du
buzzer et la porte s’ouvre, au cas contraire le signal rouge s’allume avec un bip long
du buzzer avec message accès refusé.
➔ Vigile
Il se connecte via son interface par un email et mot de passe pour valider le
pointage.
Une fois qu’un utilisateur se badge l’interface affiche sa photo nom prénom et
matricule et il va vérifier s’il s’agit bien de l’utilisateur qui a badgé pour valider
sinon il rejette le pointage.
Il peut aussi ouvrir ou fermer la porte avec un bouton.
➔ Administrateur
Il se connecte via son interface par un email et mot de passe ou par carte.
Il peut créer, modifier ou supprimer un département ajouter(un à un ou uploader
un fichier csv pour ajouter plusieurs), lister, modifier, bloquer(un ou plusieurs
utilisateurs), supprimer(un ou plusieurs) des employés et attribuer des rôles
utilisateur ou admin.
Il peut créer, modifier ou supprimer une cohorte ajouter( un à un ou uploader un
fichier csv pour ajouter apprenant), lister, modifier, bloquer(un ou plusieurs
utilisateurs) et supprimer des employés.
Il peut lire une carte et l’assigner à un employé ou apprenant.
Il peut aussi modifier le pointage d’un employé en cas de congés, maladie, voyage
il peut voir les listes des employés par département et pour les apprenant par
cohorte
Il peut voir l’historique des retards et absences

