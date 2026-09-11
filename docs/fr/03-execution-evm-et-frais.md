# Execution EVM et frais

L execution reste compatible EVM mais ajoute les regles et contrats systeme de l OP Stack.
Une transaction paie l execution L2 ainsi qu une composante liee aux donnees publiees sur L1.
Le GasPriceOracle expose des parametres permettant d estimer cette seconde composante.
Les depots L1 vers L2 sont representes par des transactions derivees du contexte Ethereum.
Les attributs du bloc transportent notamment origine L1 et informations systeme.
Les mises a niveau doivent synchroniser client d execution, rollup node et contrats L1.
Un outil compatible Ethereum n est pas automatiquement conscient des etats safe et finalized du rollup.

Suite : [04 — Retraits et fault proofs](04-retraits-et-fault-proofs.md).
