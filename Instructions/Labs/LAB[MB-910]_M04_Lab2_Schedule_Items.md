---
lab:
  title: 'Labo 4.2 : Planifier des éléments avec Dynamics 365 Field Service'
  module: 'Module 4: Learn the Fundamentals of Dynamics 365 Field Service'
ms.openlocfilehash: abbdb5d7f8c2507bebf634a9b0fb1afea8fc8da4
ms.sourcegitcommit: 600ccb76999dbc6fe9f7eaece0c235b0e85706ed
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/27/2022
ms.locfileid: "137908818"
---
<a name="module-4-learn-the-fundamentals-of-dynamics-365-field-service"></a>Module 4 : apprendre les notions de base de Dynamics 365 Field Service
========================

## <a name="practice-lab-42---schedule-items-in-dynamics-365-field-service"></a>Labo pratique 4.2 - Planifier des éléments avec Dynamics 365 Field Service

## <a name="lab-setup"></a>Mise en place du labo

  - **Durée estimée** : 20 minutes

  **Remarque :** Il n’est pas possible d’ouvrir le volet Besoins en réservations dans Internet Explorer. Nous vous recommandons d’utiliser Microsoft Edge ou Google Chrome pour effectuer cet exercice.
  
## <a name="instructions"></a>Instructions

1. Ouvrez l’application **Dynamics 365 Field Service** si elle n’est pas déjà ouverte. 

2. Dans le volet de navigation de gauche, sélectionnez la zone **Ressources**, puis sélectionnez **Ressources**.

3. Dans la **Barre de commandes**, sélectionnez le bouton **Nouveau** pour créer un nouvelle ressource pouvant être réservée.

    - **Type de ressource :** Contact

    - **Contact :** Eleanor Ribeiro

4. Dans la **Barre de commandes**, sélectionnez le bouton **Enregistrer et fermer**.

5. Répétez les étapes pour créer trois autres ressources pouvant être réservées.

    - **Type de ressource :** Contact

    - **Contact :** Abbie Gardiner


    - **Type de ressource :** Contact

    - **Contact :** Aidan Knaggs
    
    - Sélectionnez l’onglet Associé et ajoutez un nouveau territoire associé : WA


    - **Type de ressource :** Contact

    - **Contact :** Cacilia Viera
    
    - Sélectionnez l’onglet Associé et ajoutez un nouveau territoire associé : WA


6. Dans la **Barre de commandes**, sélectionnez le bouton **Enregistrer et fermer**.

Dans le volet de navigation de gauche, sélectionnez la zone **Ressources**, puis sélectionnez **Ordres de travail**.

8. Dans la **Barre de commandes**, sélectionnez le bouton **Nouveau** pour créer un nouvel ordre de travail.

9. Renseignez les détails de l’ordre de travail comme suit :

    - **Compte de service :** Adatum Corporation

    - **Type d’ordre de travail :** Service

    - **Liste de prix :** CRM Service USE (exemple)

    - **Imposable :** Non

10. Sélectionnez **Enregistrer** pour enregistrer vos modifications.

    - **Type d’incident principal :** Surchauffe de l’appareil (créer un nouveau)

11. Dans la **Barre de commandes** de l’**Ordre de travail**, cliquez sur le bouton **Réserver**. L’**Assistant Planifier** s’ouvre alors. 

12. Des options de planification de l’élément devraient vous être proposées. Sélectionnez l’enregistrement **Abbie Gardiner**.

13. Dans la fenêtre **Créer une réservation de ressource**, définissez **Heure de début** sur le début de l’heure suivante.

14. Définissez **Heure de fin** sur les **2,5 heures** suivantes. 

15. Sélectionnez le bouton **Réserver et quitter** pour réserver l’élément et quitter la fenêtre de planification. 

16. Une fois revenu dans l’ordre de travail, sélectionnez le bouton **Enregistrer et fermer** dans la barre de commandes. 

17. Dans le volet de navigation de gauche, sélectionnez **Ordres de travail**. Sélectionnez la vue **Ordres de travail non planifiés**.

18. Le volet Besoins en réservations s’affiche en bas de l’écran. Utilisez la poignée dans la partie intermédiaire supérieure du volet pour l’ouvrir. Sélectionnez l’onglet **Ordres de travail non planifiés**.

19. Sélectionnez l’ordre de travail **Adventure Works** que vous avez créé précédemment en utilisant le n° d’ordre de travail que vous aviez noté. Dans les options qui s’affichent, sélectionnez **Rechercher la disponibilité**. 

20. L’**Assistant Planifier** s’ouvre alors. 

21. Des options de planification de l’élément devraient vous être proposées. Sélectionnez l’enregistrement Aidan Knaggs.

22. Dans la fenêtre **Créer une réservation de ressource**, définissez **Heure de début** sur le début de l’heure suivante.

23. Définissez **Heure de fin** sur les **2,5 heures** suivantes. 

24. Sélectionnez le bouton **Réserver et quitter** pour réserver l’élément et quitter la fenêtre de planification. 

25. Il peut arriver que vous deviez replanifier un ordre de travail en raison de conflits entre techniciens ou autres facteurs. Les répartiteurs peuvent facilement effectuer cette tâche à l’aide du tableau de planification. 

26. Sélectionnez la zone Rechercher des ressources dans le tableau de planification (à droite au-dessus de la colonne du nom de la ressource), entrez Abbie et localisez l’ordre de travail planifié pour Abbie à une heure ultérieure du jour. 

27. Cliquez avec le bouton droit sur l’ordre de travail et dans le menu qui apparaît, sélectionnez **Substituer la ressource** et sélectionnez **Rechercher une substitution** **.**

