---
lab:
  title: "Parcours d’apprentissage\_5\_-\_Labo\_5.1\_: Créer des ordres de travail dans Dynamics\_365 Field Service"
  learning path: Learn the Fundamentals of Dynamics 365 Field Service
  module: Explore Dynamics 365 Field Service
---

Module 1 : Explorer Dynamics 365 Field Service
========================

# Labo pratique 5.1 - Créer des ordres de travail dans Dynamics 365 Field Service

## Mise en place du labo

**Note pour les instructeurs :** *Pour que ce labo fonctionne comme prévu pour les étudiants, vous devez effectuer quelques étapes de configuration. Les étapes de configuration sont expliquées dans le Guide de préparation de l’instructeur pour MB-910T00A. Les données de démonstration Field Service se trouvent ici : [https://github.com/MicrosoftLearning/MB-910T00A-Microsoft-Dynamics-365-Fundamentals-Customer-Engagement-Apps/tree/master/Instructions/Labs ]*

  - **Durée estimée** : 20 minutes

## Instructions

1. Ouvrez l’application **Dynamics 365 Field Service** si elle n’est pas déjà ouverte.

2. Dans le volet de navigation de gauche, sélectionnez  **Incidents**.

3. Dans la **Barre de commandes**, sélectionnez le bouton **Nouveau** pour créer un nouvel enregistrement d’incident.

4. Complétez votre nouvel enregistrement d’incident comme suit :

    - **Titre de l’incident :** Surchauffe de l’unité de contrôle (Vos initiales)

    - **Client** : A. Datum Corporation

    - **Origine :** Phone

5. Sélectionnez l’onglet **Field Service**

6. Définissez le champ **Type d’incident** sur **Surchauffe de l’unité**.

7. Dans la **Barre de commandes**, sélectionnez le bouton **Enregistrer et fermer** pour enregistrer et quitter l’enregistrement d’incident.

Nous reviendrons ultérieurement à l’enregistrement d’incident que vous avez créé. Examinons ensuite comment créer manuellement un ordre de travail.

8. Dans le volet de navigation de gauche, sélectionnez **Ordres de travail**.

9. Dans la **Barre de commandes**, sélectionnez le bouton **Nouveau** pour créer un nouvel ordre de travail.

10. Renseignez les détails de l’ordre de travail comme suit :

    - **Compte de service :** Adventure Works

    - **Liste de prix :** Utiliser les taux de facturation standard

    - **Type d’incident principal** : Connexion de ligne perdue

11. Sélectionnez l’onglet **Paramètres**.

12. Définissez le champ **Secteur de vente du service** sur **WA**.

13. Sous **Préférences**, configurez les préférences temporelles comme suit :

    - **Temps écoulé depuis la promesse :** Aujourd’hui à 9h00

    - **Temps jusqu’à la promesse :** Aujourd'hui à 11:00

14. Sélectionnez **Enregistrer et fermer** pour enregistrer vos modifications et quitter le nouvel ordre de travail.

Une autre manière de générer des ordres de travail consiste à réaffecter des enregistrements d’incident. Dans cet exemple, nous allons remonter l’incident de surchauffe de l’unité de contrôle que nous avons créé précédemment.

15. Dans le volet de navigation de gauche, sélectionnez **Incidents**.

16. Ouvrez l’incident **Surchauffe de l’unité de contrôle** **(Vos initiales)** que vous avez créé précédemment.

17. Dans la **Barre de commandes**, sélectionnez le bouton **Convertir en ordre de travail**.

18. Une fois la création de l’ordre de travail terminée, cliquez sur le bouton **OK** dans l’écran contextuel pour consulter les détails de l’ordre de travail.

19. Sélectionnez l’onglet **Services** et vérifiez que les services **Inspecter l’intégrité du système** et **Inspecter l’amplitude de mouvement** ont été ajoutés à l’ordre de travail.

**REMARQUE :** Si vous ne les voyez pas initialement, appuyez sur F5 pour actualiser votre écran.

20. Sélectionnez l’onglet **Tâche de service** et vérifiez que la tâche **Inspecter l’unité** a été ajoutée.

Vos nouveaux ordres de travail sont prêts à être planifiés.

