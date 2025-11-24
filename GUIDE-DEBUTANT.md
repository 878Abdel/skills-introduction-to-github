# Guide GitHub pour Débutants / GitHub Guide for Beginners

## 🇫🇷 Version Française

### Qu'est-ce que GitHub ?

GitHub est comme un **Google Drive pour le code**, mais en beaucoup mieux ! C'est un endroit où vous pouvez :
- Sauvegarder votre code en ligne
- Collaborer avec d'autres personnes
- Suivre **chaque modification** avec un historique complet (qui a changé quoi, quand et pourquoi)
- Créer des versions parallèles (branches) pour expérimenter sans risque

### Concepts de Base

#### 1. **Repository (Dépôt)**
C'est comme un **dossier** qui contient tous les fichiers de votre projet.

#### 2. **Branch (Branche)**
Imaginez que vous voulez essayer quelque chose de nouveau sans casser votre projet principal. Une branche est comme une **copie temporaire** où vous pouvez expérimenter.

```
main (branche principale)
  |
  |--- ma-nouvelle-fonctionnalite (votre branche)
```

#### 3. **Commit**
Un commit est comme une **photo** de votre code à un moment précis. Chaque fois que vous faites des changements importants, vous prenez une "photo" avec un message expliquant ce que vous avez fait.

#### 4. **Pull Request (PR)**
C'est comme dire : "Hey, j'ai fait des modifications, pouvez-vous les vérifier et les ajouter au projet principal ?"

#### 5. **Merge (Fusion)**
C'est quand vos modifications sont **acceptées** et ajoutées au projet principal.

### Exemple Simple : Créer Votre Premier Fichier

#### Étape 1 : Créer une branche
1. Cliquez sur le menu déroulant qui dit `main`
2. Tapez un nom pour votre nouvelle branche : `mon-premier-test`
3. Cliquez sur "Create branch"

#### Étape 2 : Créer un fichier
1. Cliquez sur "Add file" → "Create new file"
2. Nommez votre fichier : `hello.txt`
3. Écrivez quelque chose dedans : `Bonjour GitHub ! Ceci est mon premier fichier.`

#### Étape 3 : Faire un commit
1. En bas de la page, écrivez un message : `Ajouter mon premier fichier`
2. Cliquez sur "Commit new file"

#### Étape 4 : Créer une Pull Request
1. GitHub vous proposera de créer une Pull Request
2. Cliquez sur "Compare & pull request"
3. Ajoutez une description : `Mon premier changement sur GitHub !`
4. Cliquez sur "Create pull request"

#### Étape 5 : Merger vos changements
1. Cliquez sur "Merge pull request"
2. Confirmez avec "Confirm merge"
3. 🎉 Félicitations ! Vos changements sont maintenant dans la branche principale !

### Commandes Git de Base (Terminal)

Si vous utilisez Git en ligne de commande :

```bash
# Cloner un repository (télécharger sur votre ordinateur)
git clone https://github.com/username/repository.git

# Vérifier l'état de vos fichiers
git status

# Ajouter vos modifications
git add .

# Créer un commit
git commit -m "Description de vos changements"

# Envoyer vos changements en ligne
git push

# Télécharger les dernières modifications
git pull
```

### Conseils pour Débutants

1. **Commencez petit** : Ne vous inquiétez pas de tout comprendre immédiatement
2. **Pratiquez** : Créez un repository de test et expérimentez
3. **Lisez les messages d'erreur** : Ils sont là pour vous aider
4. **N'ayez pas peur de casser quelque chose** : Git garde l'historique de tout !
5. **Demandez de l'aide** : La communauté GitHub est très accueillante

---

## 🇬🇧 English Version

### What is GitHub?

GitHub is like **Google Drive for code**, but much more powerful! It's a place where you can:
- Save your code online
- Collaborate with other people
- Track **every change** with complete history (who changed what, when, and why)
- Create parallel versions (branches) to experiment safely

### Basic Concepts

#### 1. **Repository**
It's like a **folder** that contains all the files of your project.

#### 2. **Branch**
Imagine you want to try something new without breaking your main project. A branch is like a **temporary copy** where you can experiment.

```
main (main branch)
  |
  |--- my-new-feature (your branch)
```

#### 3. **Commit**
A commit is like a **snapshot** of your code at a specific moment. Every time you make important changes, you take a "picture" with a message explaining what you did.

#### 4. **Pull Request (PR)**
It's like saying: "Hey, I made some changes, can you check them and add them to the main project?"

#### 5. **Merge**
This is when your changes are **accepted** and added to the main project.

### Simple Example: Creating Your First File

#### Step 1: Create a branch
1. Click on the dropdown menu that says `main`
2. Type a name for your new branch: `my-first-test`
3. Click "Create branch"

#### Step 2: Create a file
1. Click "Add file" → "Create new file"
2. Name your file: `hello.txt`
3. Write something in it: `Hello GitHub! This is my first file.`

#### Step 3: Make a commit
1. At the bottom of the page, write a message: `Add my first file`
2. Click "Commit new file"

#### Step 4: Create a Pull Request
1. GitHub will prompt you to create a Pull Request
2. Click "Compare & pull request"
3. Add a description: `My first change on GitHub!`
4. Click "Create pull request"

#### Step 5: Merge your changes
1. Click "Merge pull request"
2. Confirm with "Confirm merge"
3. 🎉 Congratulations! Your changes are now in the main branch!

### Basic Git Commands (Terminal)

If you're using Git from the command line:

```bash
# Clone a repository (download to your computer)
git clone https://github.com/username/repository.git

# Check the status of your files
git status

# Add your changes
git add .

# Create a commit
git commit -m "Description of your changes"

# Push your changes online
git push

# Download the latest changes
git pull
```

### Tips for Beginners

1. **Start small**: Don't worry about understanding everything immediately
2. **Practice**: Create a test repository and experiment
3. **Read error messages**: They're there to help you
4. **Don't be afraid to break something**: Git keeps a history of everything!
5. **Ask for help**: The GitHub community is very welcoming

---

## 📚 Ressources Supplémentaires / Additional Resources

- [GitHub Docs](https://docs.github.com)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
- [GitHub Skills](https://skills.github.com)
- [GitHub Community](https://github.com/community)

## 🤝 Besoin d'Aide ? / Need Help?

N'hésitez pas à :
- Poser des questions dans les [Discussions GitHub](https://github.com/orgs/skills/discussions)
- Consulter la [documentation GitHub](https://docs.github.com)
- Rejoindre des communautés de développeurs

Remember / Souvenez-vous : **Tout le monde était débutant un jour ! / Everyone was a beginner once!** 🌟
