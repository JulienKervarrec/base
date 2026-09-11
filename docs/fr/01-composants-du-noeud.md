# Composants du noeud Base

Le depot regroupe les composants et configurations utilises pour executer Base.
Base suit l architecture OP Stack avec un client d execution et un client de rollup.
Le client d execution applique les transactions EVM et maintient l etat de la chaine.
Le rollup node derive les blocs L2 depuis les donnees et signaux publies sur Ethereum.
Le sequencer ordonne rapidement les transactions mais ne constitue pas la racine ultime de confiance.
La derivation L1 permet aux autres noeuds de reconstruire la chaine canonique selon les regles du protocole.
Les configurations de reseau relient chain IDs, contrats L1, genesis et parametres de forks.

Suite : [02 — Derivation et disponibilite](02-derivation-et-disponibilite.md).
