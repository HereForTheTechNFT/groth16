# 05 — Limites et checklist d integration

Le depot se presente comme un prototype academique non pret pour la production ; cette limite doit rester visible.
Avant integration : figer la revision, identifier la courbe, le circuit, les parametres et l ordre des entrees publiques.
Traiter toutes les erreurs de deserialisation et refuser les donnees de taille inattendue avant verification.
Conserver une separation nette entre cle de preuve, cle de verification et artefacts de ceremonie.
Une verification cryptographique valide une relation, pas la pertinence metier des donnees publiques fournies.
Ce parcours est documentaire, pas un audit. Aucune installation, compilation ou execution de tests n a ete effectuee.
Source de verification future : [`tests`](https://github.com/arkworks-rs/groth16/tree/master/tests).

[Retour au sommaire](README.md)
