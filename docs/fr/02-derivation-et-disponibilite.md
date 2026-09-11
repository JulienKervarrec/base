# Derivation et disponibilite

Les transactions L2 sont regroupees puis publiees comme donnees accessibles depuis Ethereum.
Le pipeline de derivation lit les blocs L1, extrait les batches et reconstruit les payloads L2.
Les blobs EIP-4844 reduisent le cout de disponibilite tout en gardant un engagement verifiable.
Les canaux decoupent et compressent les donnees avant leur inclusion dans des frames.
Un noeud doit gerer reorgs, fenetres de sequence et donnees temporairement manquantes.
La tete unsafe vient du sequencer, safe suit les donnees L1 et finalized herite de la finalite L1.
Confondre ces niveaux conduit a surestimer la finalite d une transaction recente.

Suite : [03 — Execution EVM et frais](03-execution-evm-et-frais.md).
