# 04 — Verification et appairages

La cle preparee met en cache des representations utiles pour reduire le travail repete du verificateur.
Les entrees publiques sont combinees avec la requete gamma-ABC ; leur nombre et leur ordre doivent correspondre au circuit.
Le controle final compare une equation d appairages impliquant les trois elements de preuve et la cle.
Une preuve bien formee mais associee a une autre cle ou a d autres entrees doit echouer.
Verifier seulement le booleen final sans valider le contexte de la cle ouvre une erreur d integration, pas une faille du protocole.
Les clefs doivent donc etre versionnees avec l identifiant du circuit et ses entrees publiques.
Source : [`src/verifier.rs`](https://github.com/arkworks-rs/groth16/blob/master/src/verifier.rs).

[Suite : limites de securite](05-limites-et-checklist.md)
