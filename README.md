PicTalk - application de communication par pictogrammes
=======================================================

INSTALLER L'APPLICATION (Android)
1. Ouvrir l'adresse de PicTalk dans Chrome, sur la tablette.
2. Menu ⋮ > "Installer l'application".
3. Lancer l'application une première fois avec du réseau. Ensuite, elle fonctionne aussi sans connexion.


UTILISER L'APPLICATION
- Touchez les cases pour construire la phrase : les mots apparaissent en haut.
- Une case avec une flèche › ouvre une page ; une case à contour pointillé est un dossier qui n'est pas prononcé.
- 🔊 prononce la phrase. ⌫ efface le dernier mot. ✕ efface tout (touchez-le deux fois). ↩ revient à la page précédente. 🏠 retourne à l'accueil.
- La barre du bas (Oui, Non, Stop, Attends, Aide, Toilettes) est toujours visible : une seule touche suffit, la phrase est prononcée tout de suite.


MODIFIER LES CASES (mode édition)
1. Appui long (1 seconde) sur le bouton ⚙. Un cadre jaune en pointillé indique que le mode édition est actif.
2. Touchez une case pour la modifier, ou une case vide (+) pour en créer une. Vous pouvez choisir :
   - le libellé affiché et, si besoin, un texte prononcé différent ;
   - si le mot est prononcé ou non (dossier muet) ;
   - la page liée : aucune, une page existante ou une nouvelle page (autant de niveaux que souhaité) ;
   - la couleur ;
   - l'image : un emoji, une photo ou une image de l'appareil.
3. "Déplacer" échange la case avec une autre. "Supprimer" vide la case.
4. En haut : ✎ renomme la page, 🗑 la supprime.
5. Pour quitter : nouvel appui long sur ⚙. Le mode édition se ferme aussi tout seul après 3 minutes sans toucher l'écran, ou quand l'application passe en arrière-plan.


CODE D'ACCÈS
Le code empêche de modifier la grille par accident.
- À la première entrée en mode édition, l'application propose de créer un code (4 caractères ou plus) et affiche un CODE DE SECOURS. Notez-le et gardez-le à part : il ne sera plus montré.
- Ensuite, le code est demandé à chaque entrée en mode édition. Après 5 erreurs, il faut attendre 30 secondes.
- Code oublié : "Code oublié ?", puis saisir le code de secours et choisir un nouveau code.
- Changer ou retirer le code : ⚙ (appui court, en mode édition) > "Code d'accès...".
- Le code reste sur la tablette : il n'est pas inclus dans les sauvegardes et n'est pas modifié par un import.
Ce code dissuade un enfant de modifier la grille ; il ne protège pas contre quelqu'un qui maîtrise les outils du navigateur.


METTRE À JOUR LES PICTOGRAMMES
Quand de nouveaux pictogrammes sont disponibles (fichier extra-picto.json publié avec l'application) :
1. Connectez la tablette à Internet.
2. Mode édition (appui long sur ⚙, code demandé), puis ⚙ (appui court) > "Mettre à jour les pictogrammes".
3. Confirmez. L'application indique le nombre d'entrées mises à jour.
Ce que fait la mise à jour :
- les emojis et les anciens pictogrammes sont remplacés par les nouveaux, pour les entrées de même nom ;
- vos propres photos sont conservées ;
- les entrées, pages et réglages que vous avez ajoutés ou modifiés ne sont pas touchés.
Si la mise à jour échoue, vérifiez la connexion et réessayez.


SAUVEGARDER ET RESTAURER
- ⚙ > "Exporter la sauvegarde" crée un fichier pictalk-sauvegarde-DATE.json (grille, images, réglages). À refaire régulièrement, et toujours avant d'effacer les données de Chrome.
- ⚙ > "Importer" restaure un fichier de sauvegarde. ATTENTION : l'import REMPLACE tout le contenu de l'application.
- ⚙ > "Réinitialiser" remet la grille d'origine : vos modifications sont perdues.


RÉGLAGES (⚙ en mode édition)
- Retour à l'accueil après une phrase.
- Parler automatiquement en fin de phrase.
- Genre des accords (Garçon / Fille) : fatigué / fatiguée, heureux / heureuse, etc.
- Vitesse de la voix. La voix dépend de celle installée sur Android.


EN CAS DE PROBLÈME
- Pas de son : vérifier le volume et la voix de synthèse française dans les réglages d'Android.
- Une modification n'apparaît pas : fermer complètement l'application, puis la rouvrir avec du réseau.
- Les données (grille, photos, réglages) sont enregistrées sur la tablette, dans Chrome. Les effacer supprime tout : exportez une sauvegarde avant.


PICTOGRAMMES ARASAAC
Auteur : Sergio Palao. Propriétaire : Gouvernement d'Aragon (https://arasaac.org). Licence CC BY-NC-SA 4.0 : usage non commercial, mention de l'auteur obligatoire, partage dans les mêmes conditions.


POUR LA PERSONNE QUI GÈRE LE DÉPÔT GITHUB
- Fichiers à la racine : index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, extra-picto.json.
- Pour publier de nouveaux pictogrammes : remplacer extra-picto.json et valider (commit). Les utilisateurs lancent ensuite "Mettre à jour les pictogrammes".
- Si index.html ou sw.js change : modifier le nom du cache dans sw.js (pictalk-v2, puis pictalk-v3...), sinon les tablettes gardent l'ancienne version.
