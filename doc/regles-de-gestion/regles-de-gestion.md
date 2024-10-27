Voici la numérotation des règles de gestion en commençant par "RG00" :

---

# Règles de gestion SimplonCommunity

## Règles de Gestion 📋

### Fonction principale :
- **RG00** : Les Administrateurs ainsi que les modérateurs pourront modifier les ressources.
- **RG01** : Les Administrateurs ainsi que les modérateurs pourront supprimer les ressources.
- **RG02** : Tous les membres, excepté les nouveaux arrivants, peuvent créer une ressource.
- **RG03** : Les membres autorisés à partager ne peuvent modifier que leurs propres ressources.
- **RG04** : Les membres autorisés à partager ne peuvent supprimer que leurs propres ressources.
- **RG05** : Les administrateurs pourront démarrer le bot.
- **RG06** : Les administrateurs pourront redémarrer le bot.
- **RG07** : Les administrateurs pourront arrêter le bot.

## Journalisation
### Gestion de l'historique d'événements :
- **RG08** : Tout signalement d'une ressource sera enregistré dans l’historique d’événements.
- **RG09** : Toute création d'une ressource sera enregistrée dans l’historique d’événements.
- **RG10** : Toute modification d'une ressource sera enregistrée dans l’historique d’événements.
- **RG11** : Toute suppression d'une ressource sera enregistrée dans l’historique d’événements.
- **RG12** : Les utilisateurs ayant liké ou disliké une ressource signalée seront enregistrés dans l’historique d’événements.

## Gestion des ressources

### Propriétés d'une ressource :
- **RG13** : Une ressource doit obligatoirement contenir un titre.
- **RG14** : Une ressource doit obligatoirement contenir une description.
- **RG15** : Une ressource peut contenir un contenu image.
- **RG16** : Une ressource peut contenir un lien.
- **RG17** : Une ressource peut contenir un fichier local.
- **RG18** : Une ressource sans contenu ne peut être postée.
- **RG19** : Une ressource doit contenir un ou plusieurs tags.

### Partage de ressource :
- **RG20** : Les nouveaux arrivants ne sont pas autorisés à partager avant leur admission à une formation.
- **RG21** : Tous les membres, excepté les nouveaux arrivants, peuvent **créer** une ressource.
- **RG22** : Tous les membres, excepté les nouveaux arrivants, peuvent **lire** une ressource.
- **RG23** : Tous les membres, excepté les nouveaux arrivants, peuvent **mettre à jour** une ressource.
- **RG24** : Tous les membres, excepté les nouveaux arrivants, peuvent **supprimer** une ressource.

### Évaluation des ressources :
- **RG25** : Tous les membres autorisés peuvent **liker** une ressource.
- **RG26** : Tous les membres autorisés peuvent **disliker** une ressource.
- **RG27** : Tous les membres autorisés peuvent **signaler** une ressource.
- **RG28** : Tous les membres autorisés peuvent rendre une ressource **obsolète**.

### Tri des ressources :
- **RG29** : Chaque lien partagé sera analysé par rapport aux liens déjà présents.
- **RG30** : S'il y a 2 liens identiques, le partage du deuxième sera bloqué.
- **RG31** : Les ressources seront triées par catégorie de tags.
- **RG32** : Les ressources seront classées par grande catégorie.
- **RG33** : Grâce à leurs tags, les ressources seront classées en sous-catégorie.

### Gestion des Forums :
- **RG34** : Lors de la création d'un post, si le tag n'existe pas, il sera automatiquement créé dans le forum.

## Système de récompenses

### Participation et Classement :
- **RG35** : Un système de classement évaluera la participation des utilisateurs.
- **RG36** : Chaque membre pourra faire partie du classement.
- **RG37** : Ce classement affichera les membres qui participent le plus.

### Types de récompenses :
- **RG38** : L'utilisateur gagnera des points en postant une ressource.
- **RG39** : Si un signalement aboutit à une suppression de ressource, l'utilisateur gagne des points.
- **RG40** : Plus il y a de membres qui signalent des ressources, plus il y a de points à gagner.
- **RG41** : Les membres ayant participé à de faux signalements subiront un retrait de points.
- **RG42** : L'utilisateur qui reçoit des likes sera récompensé par un gain de points.
- **RG43** : Un utilisateur qui reçoit des dislikes sera sanctionné par un retrait de points.

### Classement :
- **RG44** : Pour monter de niveau, l'utilisateur pourra investir les points cumulés.
- **RG45** : Quand l'utilisateur aura assez de points pour monter de niveau, une notification sera envoyée.
- **RG46** : Un classement des membres les plus participatifs sera affiché.
- **RG47** : Un grade spécial sera attribué tous les 10 niveaux.
- **RG48** : Chaque grade aura une couleur unique.
- **RG49** : Tous les trois mois, le classement sera réinitialisé.
- **RG50** : Les trois membres les plus participatifs recevront des badges éphémères.

## Modération

### Blacklist :
- **RG51** : Une liste noire est mise en place pour contenir des liens et des mots-clés interdits.
- **RG52** : La liste noire empêchera la soumission de ressources interdites.
- **RG53** : À chaque création d'un post, celui-ci sera comparé avec la liste noire.
- **RG54** : À chaque modification d'un post, celui-ci sera comparé avec la liste noire.

## Signalement

- **RG55** : Un utilisateur ne peut signaler chaque ressource **qu'une seule** fois.
- **RG56** : Un utilisateur doit **obligatoirement** choisir une catégorie de signalement.
- **RG57** : Un signalement doit être envoyé via un bouton dédié sous chaque ressource.
- **RG58** : Les membres autorisés à partager peuvent signaler n'importe quelle ressource.

### Catégories de signalements de haute priorité :
- **RG59** : Pour la catégorie **contenu illégal**, un message d'alerte menant à la ressource est directement envoyé au modérateur.
- **RG60** : Pour la catégorie **contenu impliquant des mineur(e)s**, un message d'alerte menant à la ressource est directement envoyé au modérateur.
- **RG61** : Pour la catégorie **contenu sexuellement inapproprié**, un message d'alerte menant à la ressource est directement envoyé au modérateur.

### Catégories de signalements de priorité normale :
- **RG62** : Pour la catégorie **Spam**, un message sera envoyé au modérateur au bout de 10 signalements.
- **RG63** : Pour la catégorie **Offensant / Harcèlement ou menace**, un message sera envoyé au modérateur au bout de 5 signalements.
- **RG64** : Pour la catégorie **Autres**, un message sera envoyé au modérateur au bout de 7 signalements.