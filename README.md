# Connect4IF

**Connect4IF** est un jeu de Puissance 4 développé en Prolog dans le cadre du cours ALIA à l’INSA Lyon. Il permet de jouer contre un autre joueur ou contre différentes intelligences artificielles (aléatoire, pondérée, offensive, défensive, Minimax).

## Membres du projet

- BONKOUNGOU Mathis  
- FELZINES Joris  
- KUSNO Louis  
- MANTZARIDES Guillaume  
- SCHLEE Adam  
- STEPHAN Justine  

## Lancer une partie

### Prérequis

- SWI-Prolog ou tout autre interpréteur Prolog compatible.

### Commande

Depuis l’interpréteur Prolog, dans le dossier du projet :

```prolog
run.
```

## Fonctions principales

| Fonction       | Description                        |
|----------------|------------------------------------|
| `run`          | Lance le jeu                       |
| `initialize`   | Crée un plateau vide               |
| `set_players`  | Définit les joueurs                |
| `make_move`    | Joue un coup                       |
| `output_board` | Affiche le plateau                 |

## Types d'IA

- `random` : choix aléatoire  
- `ponderee` : choix basé sur une heuristique simple  
- `offensive` : maximise les alignements  
- `defensive` : bloque l’adversaire  
- `minimax` : stratégie optimale via l’algorithme minimax


## Objectifs

- Mise en œuvre d’algorithmes de décision  
- Programmation logique en Prolog  
- Interaction joueur / IA dans un jeu de stratégie
