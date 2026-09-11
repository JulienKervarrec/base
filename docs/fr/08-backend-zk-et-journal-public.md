# 8 — Backend ZK et journal public

Le backend ZK prouve une exécution, mais le contrat ne doit vérifier que des sorties publiques non ambiguës.
Le journal public lie au minimum la chaîne, le numéro de bloc, la racine d’état et la version du programme.
Une séparation de domaine empêche de réutiliser une preuve sur une autre chaîne ou pour un autre type de requête.
Les octets encodés doivent suivre un format canonique partagé par l’hôte, le prouveur et le contrat.
La preuve cryptographique ne corrige ni une entrée mal sélectionnée ni une racine publique incomplète.
Le hash du programme vérifié doit être gouverné et auditable lors des mises à niveau.
La propriété essentielle est donc : mêmes entrées engagées, même exécution, mêmes sorties publiques.

Suite : [attestations TEE](09-attestations-tee-et-confiance.md).
