# first-project-c1

## Création d'un projet en local via git

Dans le projet de travail sur notre ordinateur, `first-proj-c1`, nous avons créé un fichier `README.md` et un dossier `img` qui contiendra des captures d'écran.

Pour l'exemple, on va créer un dossier `test` vide:

Lorsque l'on fait un `git status`, on constate le dossier `test` n'est pas reconnu. Les dossiers vides ne sont reconnus !

### Création d'un dépôt `git` 

Ouvrez la console et tapez :

```bash
git init
```

### Zone de `working`

Ouvrez la console et tapez :

```bash
git status
```

Lorsque le texte après un `git status` est en **rouge**, c'est que `git` les a détectés, mais qu'ils ne sont pas mis dans la future sauvegarde.

### Zone de `staging`

Nous allons utiliser `git add` pour ajouter les fichiers au staging :

```bash
# ajoute un seul fichier
git add lenomdunfichier.txt

# ajoute tous les fichiers
git add .
```

Lorsque nous allons refaire un `git status`, les fichiers qui sont prêts à être sauvegardés seront en **vert**, ceux qui ne seront pas envoyés restent en **rouge**


### Zone de `repository local`

Nous allons sauvegarder un fichier en utilisant le `commit` :

```bash
# sauvegarde avec commentaire
git commit -m"First commit with README.md "
```



