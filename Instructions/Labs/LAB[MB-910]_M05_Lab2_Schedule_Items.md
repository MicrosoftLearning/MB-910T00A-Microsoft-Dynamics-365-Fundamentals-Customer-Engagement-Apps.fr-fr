---
lab:
  title: 'Labo 4.2 : Planifier des éléments avec Dynamics 365 Field Service'
  module: 'Module 4: Learn the Fundamentals of Dynamics 365 Field Service'
ms.openlocfilehash: ca0728e865cf16478ab84f160cf34538e521c91e
ms.sourcegitcommit: 6065e6a662bd0407d37fcc565c1b2da1c916255d
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/29/2022
ms.locfileid: "144404992"
---
<a name="module-4-learn-the-fundamentals-of-dynamics-365-field-service"></a>Module 4 : apprendre les notions de base de Dynamics 365 Field Service
========================

## <a name="practice-lab-42---schedule-items-in-dynamics-365-field-service"></a>Labo pratique 4.2 - Planifier des éléments avec Dynamics 365 Field Service

## <a name="lab-setup"></a>Mise en place du labo

  - **Durée estimée** : 20 minutes

  **Remarque :** Il n’est pas possible d’ouvrir le volet Besoins en réservations dans Internet Explorer. Nous vous recommandons d’utiliser Microsoft Edge ou Google Chrome pour effectuer cet exercice.
  
## <a name="instructions"></a>Instructions

1.  Ouvrez l’application **Dynamics 365 Field Service** si elle n’est pas déjà ouverte.  

2.  Dans le volet de navigation de gauche, sélectionnez **Ordres de travail**.

3.  Dans la **Barre de commandes**, sélectionnez le bouton **Nouveau** pour créer un nouvel ordre de travail.

4.  Renseignez les détails de l’ordre de travail comme suit :
    - Compte de service : ADatum Corporation
    - Type d’incident principal : Scanner MRI en panne
    - Imposable : Non
    
5.  Sélectionnez **Enregistrer et fermer** pour enregistrer vos modifications et quitter le nouvel ordre de travail.

6.  Dans la **Barre de commandes** de l’**Ordre de travail**, cliquez sur le bouton **Réserver**.  L’Assistant **Planifier** s’ouvre.  

7.  Des options de planification de l’élément devraient vous être proposées.  Sélectionnez l’enregistrement **Ryan Brim**.

8.  Dans la fenêtre **Créer une réservation de ressource**, définissez **Heure de début** sur le **début de l’heure suivante**.

9.  Définissez **Heure de fin** sur les 2,5 heures suivantes.  

10. Sélectionnez le bouton **Réserver et quitter** pour réserver l’élément et quitter la fenêtre de planification.  

11. Une fois revenu dans l’ordre de travail, cliquez sur le bouton **Enregistrer et fermer** dans la **barre de commandes**.  

12. Dans le volet de navigation de gauche, sélectionnez **Tableau de planification**.

13. Au bas de l’écran du volet Besoins, sélectionnez **Ordres de travail non planifiés**.

14. Sélectionnez l’ordre de travail **Adventure Works** que vous avez créé précédemment en utilisant le n° d’ordre de travail que vous aviez noté. Dans les options qui s’affichent, sélectionnez **Rechercher la disponibilité**.  

15. L’Assistant **Planifier** s’ouvre.  

16. Des options de planification de l’élément devraient vous être proposées.  Sélectionnez l’enregistrement Bob Kozak.

17. Dans la fenêtre **Créer une réservation de ressource**, définissez **Heure de début** sur le **début de l’heure suivante**.

18. Définissez **Heure de fin** sur les 2,5 heures suivantes.
  
19. Sélectionnez le bouton **Réserver et quitter** pour réserver l’élément et quitter la fenêtre de planification. 

20. Il peut arriver que vous deviez replanifier un ordre de travail en raison de conflits entre techniciens ou autres facteurs.  Les répartiteurs peuvent facilement effectuer cette tâche à l’aide du tableau de planification.  

21. Cliquez sur la zone Rechercher des ressources dans le tableau de planification (à droite au-dessus de la colonne du nom de la ressource), entrez Ryan et localisez l’ordre de travail planifié pour Ryan à une heure ultérieure du jour.  

22. Cliquez avec le bouton droit sur l’ordre de travail et dans le menu qui apparaît, sélectionnez **Substituer la ressource** et sélectionnez **Rechercher une substitution**.


