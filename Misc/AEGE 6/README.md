# **Challenge AEGE 6**
## <u>**Catégorie**</u>

OSINT / GEOINT

## <u>**Description**</u> :

Déterminez le lieu exact de la prise de cette photographie.
(Des coordonnées GPS sont attendues)

## <u>**Auteur**</u> :

Club OSINT & Veille - AEGE

## <u>**Hints**</u> :

Estoy cerca de una frontera.

(Si j'avais vu le hint, j'aurais pu m'en servir mais... je l'ai vu après haha, ce pourquoi il ne figurera pas dans ce WU)

## <u>Solution</u> :

On va commencer par regarder la photo (jusque là, ça va)

![](./images/photo.png)

On remarque très rapidement plusieurs éléments intéressants :

![](./images/analyse.png)

- En rouge, on observe des montagnes (évidemment..)
- En bleu, des maisons typiques du sud de la France
- En rose, un mémorial ou une tombe
- En jaune, un panneau
- En vert, la configuration atypique du lieu

À partir de ces éléments, on imagine alors qu'on est sur un lieu militaire, ou tout du moins un mémorial d'une guerre ou d'un conflit militaire passé.

Nous allons désormais nous focaliser sur le panneau en premier, afin de voir les choses qui y sont écrites.

En zoomant et en cleanant l'image, puis en applicant un effet miroir, on se retrouve avec ce résultat :

![](./images/inverse.png)

On peut voir qu'il y a écrit "Centre National Entrainement Commando 1er Régiment de Choc". 

On va désormais chercher où se trouve ce centre. En cherchant ce qu'il y a indiqué sur le panneau sur Google, le moteur de recherche nous permet de compléter la recherche avec la ville de... Mont-Louis !

![](./images/google.png)

En jouant avec les différentes photos sur Google Maps, notamment :  

![https://www.google.fr/maps/@42.5088022,2.1211021,3a,53y,93.5h,85.11t/data=!3m8!1e1!3m6!1sAF1QipNpAwBpbDS23Tqu7WQ2ZtPFbaCwuVUJKSuWqnZt!2e10!3e11!6shttps:%2F%2Flh5.googleusercontent.com%2Fp%2FAF1QipNpAwBpbDS23Tqu7WQ2ZtPFbaCwuVUJKSuWqnZt%3Dw203-h100-k-no-pi-0-ya249.09784-ro0-fo100!7i10752!8i3648](./images/resultat1.png) 

![https://www.google.fr/maps/@42.5088022,2.1211021,3a,53y,93.5h,85.11t/data=!3m8!1e1!3m6!1sAF1QipNpAwBpbDS23Tqu7WQ2ZtPFbaCwuVUJKSuWqnZt!2e10!3e11!6shttps:%2F%2Flh5.googleusercontent.com%2Fp%2FAF1QipNpAwBpbDS23Tqu7WQ2ZtPFbaCwuVUJKSuWqnZt%3Dw203-h100-k-no-pi-0-ya249.09784-ro0-fo100!7i10752!8i3648](./images/resultat2.png) 

On remarque que le panneau est en face du fort et proche d'un chemin avec un grand virage (qui mène justement à l'intérieur de la base).

On trouve également une photo prise devant la statue, qui nous confirme bien que c'est un mémorial : 

![](./images/memorial.png)

Une photo prise depuis un drone est également disponible et nous permet de confirmer notre hypothèse.

![](./images/croix.png)

La croix violette correspond donc à l'endroit où la photo a été prise.

On vient confirmer ça avec la vue satellite de Google Maps 

![](./images/resultat.png)

Il ne reste plus qu'à noter les coordonnées GPS, et on obtient le flag ! 

**Flag : 42.509306, 2.119389**