# 03 — Construction de la preuve

Le prouveur evalue les matrices de contraintes sur l affectation complete puis calcule le polynome quotient.
Deux aleas de preuve randomisent les elements afin que des preuves du meme temoin ne soient pas triviales a relier.
Les requetes de la cle de preuve sont combinees par multiplication multiscalaire.
Une longueur incoherente entre affectation, requetes et domaine signale une incompatibilite de parametres ou de circuit.
La preuve finale contient trois elements de groupe : cette concision deplace une grande partie du cout vers le setup et la preuve.
La revue doit aussi suivre les chemins ou des entrees invalides produisent une erreur plutot qu une panique.
Source : [`src/prover.rs`](https://github.com/arkworks-rs/groth16/blob/master/src/prover.rs).

[Suite : verification](04-verification-et-appairages.md)
