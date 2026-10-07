# Personnages 3D

| Fichier | Personnage | Source | Licence |
| --- | --- | --- | --- |
| `dame-de-rayon.glb` | Dame de rayon de la Bijouterie (« Rogue » du pack) | KayKit Character Pack : Adventurers 1.0, Kay Lousberg — https://github.com/KayKit-Game-Assets/KayKit-Character-Pack-Adventures-1.0 (aussi https://kaylousberg.itch.io/kaykit-adventurers) | CC0 1.0 (domaine public) : usage commercial permis, sans attribution. Texte d'origine : `LICENSE-kaykit.txt`. |

Transformations faites sur `Rogue.glb` (gltf-transform 4) : armes retirées (couteaux, arbalètes, projectile),
7 animations gardées sur 75 (`Unarmed_Idle`, `Walking_A`, `PickUp` et `Interact` pour ranger, `Cheer`,
`2H_Melee_Attack_Spin` et `Jump_Full_Short` pour ses trois danses), resample + prune + dedup, géométrie
compressée Draco (décodeur dans `public/draco/`). 3,6 Mo → 0,33 Mo. Le carton et le balai sont dessinés dans le jeu.

Format attendu pour un nouveau personnage : GLB (glTF 2.0 binaire), un seul squelette, animations repos / marche
dans le fichier, texture ≤ 1024 px, < 1 Mo après Draco, licence permettant l'usage commercial (CC0 ou CC-BY), source notée ici.
