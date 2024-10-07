

## Installation d'Anaconda

Pour commencer, installez Anaconda en consultant ce [lien](https://docs.anaconda.com/anaconda/install/linux/).

## Étapes d'installation

### 1. Ouvrir votre terminal

Lancez votre terminal pour commencer.

### 2. Créer un environnement virtuel

Créez un nouvel environnement virtuel en utilisant la commande suivante :

```bash
conda create -n ex00 python=3.8
```

### 3. Activer l'environnement

Activez l'environnement que vous venez de créer :

```bash
conda activate ex00
```

### 4. Installer les bibliothèques requises

Une fois l'environnement activé, installez les bibliothèques nécessaires (numpy et jupyter) avec la commande suivante :

```bash
pip install numpy jupyter
```

### 5. Enregistrer les packages installés

Pour enregistrer les bibliothèques installées dans un fichier `requirements.txt`, exécutez :

```bash
pip freeze > requirements.txt
```

### 6. Lancer Jupyter Notebook

Pour lancer Jupyter Notebook sur le port 8891, utilisez la commande :

```bash
jupyter notebook --port=8891
```

### 7. Créer un nouveau notebook

Une fois Jupyter Notebook ouvert dans votre navigateur, cliquez sur "New" et sélectionnez "Python 3". Nommez votre notebook `Notebook_ex00`.

## Notes

Assurez-vous de toujours activer votre environnement virtuel avant d'installer de nouvelles bibliothèques ou de lancer Jupyter Notebook. Cela garantit que vous utilisez les bonnes versions des bibliothèques dans votre projet.


