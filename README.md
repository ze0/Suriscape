# Suriscape

Un escape game avec des suricate 

### Principe du jeu

On incarne un/une jeune suricate né/ée d'une [mère non dominante](https://fr.wikipedia.org/wiki/Suricate#Reproduction_et_mise_bas)
La mêre dominante décide d'un coups de jalousie de tuer tout les petits qui ne sont pas les siens.

Vous devez donc vous enfuir, un terrier ayant de multiple sortie vous tentez donc votre chance dans une gallerie.

Là le jeu commence mais des suricates vous barrent la route, pour passer il faut résoudre leurs énigmes.

le temps est limité car quand la dominante aura tué tout les autres elle viendra nous tuer.



### Enigme & Puzzle game
Chaque suricat proposera donc une enigme répartie en 6? niveau de difficulté

#### par exemple le suricate

> Hé toi ! Tu ne passera pas a moins de me montrer que tu est suffisament inteligent pour survivre dans notre monde arride et sauvage!
Voici 2 récipient, 50cl et 30cl, donnes moi 40cl !

```
solution:
  source -> 50cl            Etat: 50cl/50cl 0cl/30cl
  50cl -> 30cl              Etat: 20cl/50cl 30cl/30cl
  30cl -> vider dans source Etat: 20cl/50cl 0cl/30cl
  50cl -> 30cl              Etat: 0cl/50cl  20cl/30cl
  source -> 50cl            Etat: 50cl/50cl 20cl/30cl
  50cl -> 30cl              Etat: 40cl/50cl 30cl/30cl
  
  Donner le 50cl au suricate
```

> Félicitation, maintenant court, fuit pour ta vie !

Il faudra bien sur trier les énigmes par difficulté


### Fin du jeu

Il faudrait résoudre 6? énigmes pour réussir à sortir.

Et le jeu nous félicite puis nous dit que nous avons sauver 1 suricate et qu'on peu en sauver d'autre pour encourager le joueur à recommencer et découvir de nouvelle énigme

