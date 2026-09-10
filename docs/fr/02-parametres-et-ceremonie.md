# 02 — Parametres et ceremonie

La generation echantillonne des secrets toxiques puis construit des puissances et combinaisons dans les groupes de la courbe.
Les parametres de preuve contiennent les elements necessaires au prouveur ; la cle de verification peut etre preparee separement.
Si les secrets de la ceremonie sont recuperes, des preuves fausses peuvent devenir possibles.
Une application doit donc documenter provenance, circuit exact et methode de destruction ou de contribution multipartite.
Toute modification du circuit exige des parametres compatibles : le setup est specifique a la relation.
Le code montre les objets produits, mais ne prouve pas a lui seul la surete operationnelle d une ceremonie.
Source : [`src/generator.rs`](https://github.com/arkworks-rs/groth16/blob/master/src/generator.rs).

[Suite : construction de la preuve](03-preuve-et-aleas.md)
