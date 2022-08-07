# 📰 Écrire un article

Les articles d'I Learned sont écrits au format Markdown. Ils sont stockés sur [ce repo](https://gitlab.ilearned.eu/i-learned/blog/content-fr).

Voici la démarche à suivre pour proposer un article.

> 🆘 Vous avez besoin d'aide ? N'hésitez pas à venir poser vos questions sur [Discord](https://discord.ilearned.eu) !

1. Créer un compte, si ce n'est pas déjà fait, sur [Gitlab](https://gitlab.ilearned.eu).
2. Se rendre sur [le repo](https://gitlab.ilearned.eu/i-learned/blog/content-fr) contenant les articles.
3. Faire un fork du repo
  ![Cliquer sur le bouton fork en haut à droite](/img/fork.png)

4. Valider le fork, ne pas oublier de passer le repo en Internal ou Public !
  ![Passer le repo en Internal ou public](/img/fork_2.png)
5. Une fois le fork créé, cliquer sur le bouton + puis "Upload File"
  ![Uploader le fichier markdown](/img/upload.png)
6. Veillez à bien respecter le template pour remplir les métadonnées de votre article
  ```
  lang: fr
  Author: MonPseudo
  Date: 2022-12-31
  Keywords: un, keyword, autre
  Slug: url-de-larticle
  Summary: Ceci est le résumé de mon super article !
  Title:  Le titre de mon article
  Category: LaCategory

  Ceci *est* le contenu de **mon** article.
  ```
  Les categories possibles sont : Sysadmin, Cybersécurité, Sciences, Pensées du libre, Réseau. Veillez à bien les orthographier.
7. Aller dans la section "Merge Request" à gauche de l'écran.
8. Créer une nouvelle Merge Request
  ![Remplit le champ titre et le corps du message](/img/pr_form.png)
9. Valider la merge request en cliquant sur le bouton "Create merge request", des contributeur-ice-s relirons votre article et il sera publié !
