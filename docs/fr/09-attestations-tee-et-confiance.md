# 9 — Attestations TEE et modèle de confiance

Une attestation TEE et une preuve ZK ne fournissent pas la même garantie.
Le TEE ajoute des hypothèses sur le matériel, le fabricant, la chaîne de certificats et la fraîcheur du document.
Le registre d’enclaves doit lier une mesure autorisée à une identité et permettre sa révocation.
Les nonces et dates d’expiration réduisent le risque de rejouer une attestation ancienne.
Une rotation de mesure doit conserver une fenêtre de migration explicite, sans accepter toute image par défaut.
La vérification doit échouer si la chaîne de confiance, la région attendue ou les champs critiques sont absents.
Documenter ces hypothèses évite de présenter l’attestation comme une preuve cryptographique interchangeable.

Suite : [challenge et soumission](10-challenge-et-soumission.md).
