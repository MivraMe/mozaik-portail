# Seulement une liste des requetes qui pourrait être utile que j'ai trouvé. Je ne connais pas encore les requetes.

Avec le cookie pp il est possible d'acceder au information du compte mozaik a l'adresse suivante
­­­´´´https://portailparents.ca/connect/authentificationinfo?authType=pp­­­­­­´´´
Ont obtient donc le token qui vas etre utilisé dans toute les requetes, une liste des enfants, le ID d'établissement et d'autre information.

Voici les requete pour le moment :

Retourne les notes
https://apiaffaires.mozaikportail.ca/api/evaluation/resultats/CODE ÉTABLISSEMENT/anneeCourante/eleves/NUMÉRO FICHE/travaux/visibleParentEleve

Retourne seulement les enfants
https://apiaffaires.mozaikportail.ca/api/individu/parent/enfants

La photo en base64
https://apiaffaires.mozaikportail.ca/api/individu/eleves/CODE ÉTABLISSEMENT/NUMÉRO FICHE/identification/photo

Une liste des congés ainsi que une liste des ''jourcycle''
https://apiaffaires.mozaikportail.ca/api/organisationScolaire/preparatifs/CODE ÉTABLISSEMENT/anneeCourante/NUMÉRO FICHE/grilleHoraire

Liste des matieres avec différentes informations
https://apiaffaires.mozaikportail.ca/api/evaluation/apprentissage/CODE ÉTABLISSEMENT/anneeCourante/matieres/eleves/NUMÉRO FICHE

Une liste des absences, a voir si ont peut voir une nouvelle absence non motivée / école buissonnière
https://apiaffaires.mozaikportail.ca/api/comportement/assiduite/CODE ÉTABLISSEMENT/anneeCourante/NUMÉRO FICHE/absences/parent?historiqueAbsencesDateDebut=&historiqueAbsencesDateFin=2023-12-26&exclude=absencesAMotiver,avisAbsences
Le nombre d'absence total
https://apiaffaires.mozaikportail.ca/api/comportement/assiduite/CODE ÉTABLISSEMENT/anneeCourante/NUMÉRO FICHE/absences/parent?historiqueAbsencesDateDebut=2023-12-27&historiqueAbsencesDateFin=&exclude=

Autobus
https://apiaffaires.mozaikportail.ca/api/transport/trajets/CODE ÉTABLISSEMENT/anneeCourante/NUMÉRO FICHE/parentConnecte
