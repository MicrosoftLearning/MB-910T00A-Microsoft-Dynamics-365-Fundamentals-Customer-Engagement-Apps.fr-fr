---
lab:
  title: 'Labo 1.5 : Créer un segment dans Dynamics 365 Marketing'
  module: 'Module 1: Learn the Fundamentals of Dynamics 365 Marketing'
ms.openlocfilehash: 5f75e433fe8d38d32000c7de20878e3b471f0fca
ms.sourcegitcommit: 600ccb76999dbc6fe9f7eaece0c235b0e85706ed
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/27/2022
ms.locfileid: "137908859"
---
<a name="module-1-learn-the-fundamentals-of-dynamics-365-marketing"></a>Module 1 : apprendre les notions de base de Dynamics 365 Marketing
========================

## <a name="practice-lab-15---create-a-segment-in-dynamics-365-marketing"></a>Labo pratique 1.5 - Créer un segment dans Dynamics 365 Marketing

## <a name="objectives"></a>Objectifs

Lors de cet exercice, vous constaterez qu’il est très facile de créer des segments client qui ciblent des contacts spécifiques en fonction d’informations démographiques communes telles que leur lieu de résidence ou leurs centres d’intérêt. La création de segments client dans Dynamics 365 Marketing est extrêmement courante, car ils sont utilisés pour des activités marketing clés telles que la définition des contacts cibles dans les parcours du client.

## <a name="lab-setup"></a>Mise en place du labo

  - **Durée estimée** : 20 minutes

## <a name="instructions"></a>Instructions


1. Ouvrez l’application Dynamics Marketing. La zone **Marketing** devrait être sélectionnée. Sélectionnez **Segments** sous **Clients**.

2. Dans la barre de commandes, sélectionnez **Nouveau**.

3. Dans le menu déroulant qui apparaît, sélectionnez **Nouveau segment dynamique**.

4. Dans la boîte de dialogue **Modèles de segment** qui s’ouvre, sélectionnez **Ignorer** pour la fermer et passer à l’écran **Nouveau segment**.

5. Sélectionnez **Ajouter un bloc de requête** pour créer une requête concernant la table des contacts. 

6. Sélectionnez le contrôle **Sélectionner un attribut**.

7. Tapez « ville » pour filtrer la liste et sélectionnez **Adresse 1 : Ville**.

8. Laissez la liste déroulante suivante définie sur **Égal à**. 

9. Cliquez sur **Type à rechercher** et saisissez **Chicago**.

10. Sélectionnez le champ **Nom** en haut de la requête et saisissez **Contacts Chicago - Vos initiales**.

11. Sélectionnez **Enregistrer** dans la Barre de commandes pour enregistrer votre segment.

12. Sélectionnez **Mise en service** pour publier le segment. 

13. Attendez environ une minute, puis sélectionnez **Actualiser** dans la barre de commandes pour actualiser la page. 

14. Vous devriez maintenant voir qu’un onglet **Membres** a été ajouté. Jackson Anderson apparaît dans la liste.
