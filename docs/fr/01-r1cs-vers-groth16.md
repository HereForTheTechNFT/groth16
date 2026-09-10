# 01 — De R1CS a Groth16

Groth16 prouve qu un temoin satisfait une relation R1CS encodee par trois familles de combinaisons lineaires.
La reduction transforme ces contraintes en evaluations polynomiales utilisees par le prouveur et le verificateur.
Les entrees d instance sont publiques ; les variables auxiliaires constituent le temoin prive.
Le trait de reduction isole l encodage de la relation du protocole de preuve proprement dit.
Cette separation explique pourquoi une meme implementation peut accueillir plusieurs circuits compatibles.
Le premier controle de revue est la frontiere exacte entre instance et temoin.
Source : [`src/lib.rs`](https://github.com/arkworks-rs/groth16/blob/master/src/lib.rs).

[Suite : generation des parametres](02-parametres-et-ceremonie.md)
