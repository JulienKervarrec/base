# 7 — Proposer, workers et reprises

Le proposer transforme une demande de preuve en travail traçable confié à un worker.
Chaque tâche doit porter un identifiant stable, le bloc ciblé, la configuration et la version du programme.
Une reprise ne doit pas produire deux soumissions concurrentes pour le même domaine public.
Les temporisations, budgets de tentatives et états terminaux empêchent les boucles de polling infinies.
Le résultat d’un worker n’est accepté que s’il correspond exactement à la demande persistée.
Les erreurs transitoires se distinguent des entrées invalides et des incompatibilités de version.
Cette discipline rend l’orchestration observable sans transformer le worker en autorité de consensus.

Suite : [backend ZK et journal public](08-backend-zk-et-journal-public.md).
