---
lab:
  title: "Parcours d’apprentissage\_2\_- Labo\_2.1\_- Créer un parcours client simple"
  learning path: Explore the fundamentals of Dynamics 365 Marketing
  module: Explore Dynamics 365 Marketing
---

Parcours d’apprentissage 2 - Module 1 : Explorer Dynamics 365 Marketing
========================

## Labo pratique 2.1 - Créer un parcours client simple

## Objectifs

Durant cet exercice, vous constaterez que les parcours des clients sont un composant clé de Dynamics 365 Marketing. Vous allez créer des parcours du client comme base de tout effort marketing. Leur but est de guider le chemin emprunté par un client lors de ses interactions avec le processus marketing de votre organisation. Le but du parcours, une fois terminé, est de le transformer en revenus.

## Mise en place du labo

  - **Durée estimée** : 20 minutes

## Instructions

1. Ouvrez l’**application Dynamics 365 Marketing**.

2. Passez à la zone **Marketing sortant**. 

3. Dans le volet de navigation de gauche, sélectionnez **Contacts** sous le groupe **Clients**

4. Dans la barre de commandes, sélectionnez **Nouveau**.

5. Remplissez la page **Nouveau contact** comme suit.

    - **Prénom** : Jenny

    - **Nom** : Jones (Vos initiales)

    - **E-mail** : Entrez une adresse e-mail dont vous pouvez recevoir du courrier.

    - **Adresse 1 Rue 1 :** 101 Avenue Exemple

    - **Adresse 1 : Ville** : Fargo

    - **Adresse 1 État :** ND

    - **Adresse 1 Code postal :** 58103

6. Une fois que vous avez fini de remplir la page du contact, sélectionnez **Enregistrer et fermer**.

7. Dans la barre de commandes, resélectionnez Nouveau pour créer un autre contact

8. Remplissez la page du second contact comme suit :

    - **Prénom** : Marco

    - **Nom** : Gomez (Vos initiales)

    - **E-mail** : Entrez une adresse e-mail dont vous pouvez recevoir du courrier.

    - **Adresse 1 Rue 1 :** 101 Avenue Exemple

    - **Adresse 1 : Ville** : Fargo

    - **Adresse 1 État :** ND

    - **Adresse 1 Code postal :** 58103

**REMARQUE :** Nous utilisons les mêmes informations d’adresse pour faciliter l’identification des contacts en tant qu’exemples de données. 

9. Une fois que vous avez fini de remplir la page du contact, sélectionnez **Enregistrer et fermer**.

**IMPORTANT :** En raison de l’adresse, les paramètres de détection des doublons des systèmes peuvent se déclencher. Si vous obtenez l’écran des enregistrements en double, sélectionnez le bouton **Ignorer et enregistrer**. 

**Tâche 2 : Créer un segment Fargo** 

Nous allons ensuite créer un segment et ajouter les contacts que nous avons créés dans la tâche précédente. 

1. Dans le volet de navigation de gauche, sélectionnez **Segments** sous **Marketing**. 

    2. Dans la barre de commandes, sélectionnez **Nouveau**.

    3. Dans le menu déroulant qui apparaît, sélectionnez **Nouveau segment dynamique**.

    4. Dans la boîte de dialogue **Modèles de segment** qui s’ouvre, sélectionnez **Ignorer** pour la fermer et passer à l’écran **Nouveau segment**.

    5. Sélectionnez **Ajouter un bloc de requête** pour créer une requête sur l’entité de contact. 

    6. Sélectionnez le texte fantôme **Sélectionner un attribut**. 

    7. Tapez ensuite « ville » pour filtrer la liste, puis choisissez **Adresse 1 : Ville** dans la liste.

    8. Laissez la liste déroulante suivante définie sur **Égal à**. 

    9. Sélectionnez la troisième liste déroulante qui contient le texte fantôme **Entrer le texte à rechercher**, puis tapez **Fargo**.

    10. Cliquez pour sélectionnez le champ **Nom** en haut de la requête, puis tapez **Contacts Fargo (Vos initiales)** . (Vous devrez peut-être sélectionner la flèche vers le bas en regard du Motif du statut.)

    11. Sélectionnez **Enregistrer** dans la barre de commandes pour enregistrer le segment.

    12. Sélectionnez **Mise en service** pour publier le segment.

    13. Attendez environ une minute, puis sélectionnez **Actualiser** dans la barre de commandes pour actualiser la page. 

    14. Vous devriez maintenant voir qu’un onglet **Membres** a été ajouté. 

 

**Tâche 3 : Créer un e-mail simple.** 

Ensuite, nous allons créer un e-mail simple à partir d’un modèle existant que nous serons en mesure d’utiliser avec le parcours de nos clients. 

1. Dans le volet de navigation de gauche, sélectionnez **E-mails marketing** sous le groupe **Exécution marketing**.

2. À l’aide de la barre de commandes, sélectionnez **+ Nouveau**.

3. Dans l’écran **Modèles de marketing par courrier électronique**, sélectionnez **1 colonne**, puis choisissez le bouton **Sélectionner**. 

4. En haut à gauche de l’e-mail, sélectionnez le champ Nom. (Aura un texte similaire à E-mail ypl (1 colonne))

5. Remplacez le nom par « **Exemple de message électronique (Vos initiales) »** .

6. Dans le champ **Objet**, entrez le texte « **Découvrez ce que nous avons à offrir »** . 

7. Sélectionnez le bouton **Enregistrer**. 

8. Sélectionnez le bouton **Démarrer** pour publier l’e-mail. 

 

**Tâche 4 : Créer un parcours client.** 

Maintenant que nous avons notre public cible, ainsi que l’activité d’e-mail que nous voulons utiliser, nous allons créer un parcours client. 

1. Dans le volet de navigation de gauche, sélectionnez **Parcours client** sous le groupe **Exécution marketing**.

    2. À l’aide de la barre de commandes, sélectionnez **+ Nouveau**.

    3. Dans la fenêtre contextuelle **Modèles de parcours client**, sélectionnez **Ignorer** pour commencer à créer un parcours à partir de zéro.

    4. Sélectionnez **Définir l’audience** (ou sinon, sélectionnez **+** ). Vérifiez que le **Type de source** est défini sur **Segment**, puis sélectionnez le segment **Contacts Fargo** (Vos initiales) que vous avez créé dans l’exercice précédent. Le premier titre est alors rempli avec le nom du segment et le volet **Audience** affiche les propriétés du segment.

    5. Sélectionnez **+** sur le canevas, puis sélectionnez **Envoyer un courrier électronique** dans le menu contextuel.

    6. Dans la section Envoyer un e-mail, sélectionnez **Exemple de message électronique** (Vos initiales) que vous avez créé précédemment.

    7. Sélectionnez l’onglet Général qui se trouve vers le haut de l’enregistrement Parcours du client. Entrez les informations suivantes dans l’onglet **Général** :

        - **Nom** : Parcours client Fargo (Vos initiales)

        - **Date et heure de début** : Entrez la date d’aujourd’hui

        - **Date et heure de fin** : Un mois à compter d’aujourd’hui

        - **Fuseau horaire** : Sélectionnez votre fuseau horaire local

8. Dans la barre de commandes, sélectionnez **Enregistrer** pour enregistrer le travail que vous avez réalisé jusqu’à présent.

9. Votre parcours est maintenant prêt à démarrer. Pour le démarrer, publiez-le en sélectionnant **Mise en service** dans la barre de commandes.

 
