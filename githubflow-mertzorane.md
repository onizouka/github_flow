# Travail de recherche pour répondre aux questions suivantes :

## Pourquoi ne travailles-tu pas uniquement sur main ?

La branche `main` doit idéalement représenter la version stable et utilisable du projet. Si on pousse un code qui contient un bug directement sur `main`, on peut casser le projet pour tout le monde.
On travaille généralement sur une branche à part pour éviter l'anarchie notamment via le travail en équipe, les conflits deviendraient un cauchemar quotidien.
Le fait de travailler sur une branche à part permet aux collègues de faire une revue de code et ainsi vérifier le travail finalisé et éviter les potentiels bugs qui pourrait affecter la branche `main`.

---
## Pourquoi éviter de créer une seule branche par personne ?

Travailler avec une branche par personne est une erreur classique en début de projet. Au lieu de diviser le travail par individu, on le divise par objectif. Cette approche permet d'éviter les divergeances trop importantes de branches et ainsi une fusion rapide sur une courte durée.

---