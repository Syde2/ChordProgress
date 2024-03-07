# Chord Progress

 Intégration des principales Progression d'Accord au Piano 
 
 On selectionne 1 accord ou +, on choisi une progression et les autres accords sont affichés, avec un lien vers une liste de titre qui ont utilisé cette progression.

## DEV NOTES 

1- Je sélectionne 1 accord
2- Je choisi parmi une liste de progression
3- La liste des accords s’affiche

Je peux sélectionner plusieurs accords ? 
Je peux ajouter de nouvelles progression 
J’utilise la notation internationale
Je peux accéder a une liste de chansons avec leur progression 



Comment stocker mes progressions ? 
 Array ? Object ?  Class  ? 
Factory Model 

Prend en Entrée un Array de Notes  Retourne la Progression 
Avoir une Class par Progression ? Qui extend d’une class Progression Factory ? 

## DB 

MajorScaleByPosition : 

| Name  | A  | Asharp  | Bflat  | B  | C | Csharp | | G♭ | G
|---|---|---|---|---|---|---|---|---|---|
| C  |  6 | Null  | Null | 2  | 3  | 4 | null | null | 5 
...

MajorScaleByNote

| Name  | 1  |2  | 3  | 4  | 5 |6 |7 |
|---|---|---|---|---|---|---|---|
| C  | C |D  | E | F  | G  | A | B 
| D  | D | E  | F# | G  | A  | B | C# 

...