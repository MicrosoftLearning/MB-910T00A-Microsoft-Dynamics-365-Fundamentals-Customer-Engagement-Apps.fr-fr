---
lab:
  title: "Labo\_5.2\_: Planifier des éléments dans Dynamics\_365\_Field\_Service"
  module: 'Module 5: Learn the Fundamentals of Dynamics 365 Field Service'
---

<a name="module-5-learn-the-fundamentals-of-dynamics-365-field-service"></a>Module 5 : Exposer les principes fondamentaux de Dynamics 365 Field Service
========================

## <a name="practice-lab-52---schedule-items-in-dynamics-365-field-service"></a>Labo pratique 5.2 - Planifier des éléments avec Dynamics 365 Field Service

## <a name="lab-setup"></a>Mise en place du labo

  - **Durée estimée** : 20 minutes

  **Remarque :** Il n’est pas possible d’ouvrir le volet Besoins en réservations dans Internet Explorer. Nous vous recommandons d’utiliser Microsoft Edge ou Google Chrome pour effectuer cet exercice.
  
## <a name="instructions"></a>Instructions

1. Ouvrez l’application **Dynamics 365 Field Service** si elle n’est pas déjà ouverte.

2. Dans le volet de navigation de gauche, sélectionnez **Ordres de travail**.

3. Dans la **Barre de commandes**, sélectionnez le bouton **Nouveau** pour créer un nouvel ordre de travail.

4. Renseignez les détails de l’ordre de travail comme suit :

    - Compte de service : Adatum Corporation

    - Type d’incident principal : Scanner MRI en panne

    - Liste de prix : Utiliser les taux de facturation standard

    - Type d’ordre de travail : sélectionner Appel de service dans la recherche

    - Imposable : Non

5. Sélectionnez **Enregistrer** pour enregistrer vos modifications et rester sur l’enregistrement nouvellement créé.

6. Dans la **Barre de commandes** de l’**Ordre de travail**, cliquez sur le bouton **Réserver**. L’Assistant **Planifier** s’ouvre.

7. Des options de planification de l’élément devraient vous être proposées. Sélectionnez l’enregistrement **Ryan Brim**.

8. Dans la fenêtre **Créer une réservation de ressource**, définissez **Heure de début** sur le **début de l’heure suivante**.

9. Définissez l’**Heure de fin** sur 2 heures 30 après.

10. Sélectionnez le bouton **Réserver et quitter** pour réserver l’élément et quitter la fenêtre de planification.

11. Une fois revenu dans l’ordre de travail, cliquez sur le bouton **Enregistrer et fermer** dans la **barre de commandes**.

12. Dans le volet de navigation de gauche, sélectionnez **Tableau de planification**.

13. Au bas de l’écran du volet Besoins, sélectionnez **Ordres de travail non planifiés**.

14. Sélectionnez l’ordre de travail **Adventure Works** que vous avez créé précédemment et utilisez le n° d’ordre de travail que vous aviez noté. Dans les options qui s’affichent, sélectionnez **Rechercher la disponibilité**.

15. L’Assistant **Planifier** s’ouvre.

16. Des options de planification de l’élément devraient vous être proposées. Sélectionnez l’enregistrement Bob Kozak.

17. Dans la fenêtre **Créer une réservation de ressource**, définissez **Heure de début** sur le **début de l’heure suivante**.

18. Définissez l’**Heure de fin** sur 2 heures 30 après.

19. Sélectionnez le bouton **Réserver et quitter** pour réserver l’élément et quitter la fenêtre de planification.

20. Il peut arriver que vous deviez replanifier un ordre de travail en raison de conflits entre techniciens ou autres facteurs. Les répartiteurs peuvent facilement effectuer cette tâche à l’aide du tableau de planification.

21. Cliquez dans la zone Rechercher dans les ressources dans le tableau de planification (à droite au-dessus de la colonne du nom de la ressource), entrez Ryan et localisez l’ordre de travail planifié pour Ryan à une heure ultérieure du jour.

22. Cliquez avec le bouton droit sur l’ordre de travail et dans le menu qui apparaît, sélectionnez **Substituer la ressource** et sélectionnez **Rechercher une substitution**.
