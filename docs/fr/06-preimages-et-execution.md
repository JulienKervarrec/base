# 6 — Préimages et exécution déterministe

Une preuve rejoue une exécution à partir de données adressées par leur empreinte.
Le couple chaîne/bloc doit faire partie du domaine de cache afin d’éviter une préimage valide dans le mauvais contexte.
Les entrées couvrent notamment l’état, les en-têtes, les transactions et les données de bloc.
Un cache utile vérifie l’empreinte avant restitution et ne confond jamais absence et valeur vide.
La version du fork et la configuration de chaîne doivent accompagner tout artefact reproductible.
Une préimage manquante est une erreur explicite, pas une invitation à poursuivre avec un défaut silencieux.
Cette frontière relie disponibilité des données et déterminisme de l’exécuteur.

Suite : [proposer et workers](07-proposer-workers-et-reprises.md).
