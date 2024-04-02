# Guide pour installer PyTrx sur votre machine et faire tourner les scripts

## Installation de PyTrx

### Etape 1: créer un environnement virtuel avec conda

On commence par créer un environnement virtuel avec conda avec un python en version 3.7 avec la commande :

```bash
conda create -n pytrx python=3.7
```

On fait bien attention de désactiver l'environnement base avec la commande :

```bash
conda deactivate
```

Puis on active notre environnement pytrx avec la commande :

```bash
conda activate pytrx
```

Remarque: Python 3.7 ne peut pas être installer sur les mac avec les nouvelles puces Apple silicon. On peut tout de même l'installer avec une commade spéciale en utilisant une sorte d'émulation. C'est un problème très classique et on peut trouver la réponse sur stack.

### Etape 2: installer les packages nécessaires

Ensuite il faut installer tous les packages nécessaires à PyTrx avec des versions bien définies sinon on aura des erreurs. Pour cela on utilise les commandes suivantes :

```bash
conda install gdal=2.3.2 
conda install opencv=3.4.2
conda install pillow=8.3.1
conda install scipy=1.7.3
conda install matplotlib=3.5.0
conda install spyder=5.1.5
```

### Etape 3: installer PyTrx en cloneant le dépôt

On clone le dépôt PyTrx avec la commande :

```bash
git clone
```

## Exécuter les scripts

### Etape 1: se placer dans le dossier PyTrx/Exemples

On se place dans le dossier Exemples de PyTrx avec la commande :

```bash
cd PyTrx/Exemples
```

### Etape 2: exécuter un script

On fait premierement attention à ce que notre environnement pytrx soit bien activé. Puis on peut exécuter un script avec la commande :

```bash
python script.py
```

