# Gabarit de contenu didactique utilisant Sphinx

[Site Web](https://calculquebec.github.io/cq-formation-sphinx-book/)

## Installation locale et compilation

```Bash
pip install sphinx==8.1.3 sphinx-intl sphinx-book-theme==1.1.3

./build.sh
```

## Déploiement via GitHub

Dans le dépôt GitHub -> Settings -> Pages :

* Sélectionner la *Source* **Deploy from a branch**
* Sélectionner la branche **gh-pages** et **/ (root)**
* Cliquer sur le bouton *Save*

## Style de programmation

Indentez toujours avec 4 espaces.

Pour configurer Vim:

```Bash
mkdir -p "$HOME/.vim/indent"
cp /usr/share/vim/vim*/indent/rst.vim $HOME/.vim/indent/
sed -e 's/= 3/= 4/' -i $HOME/.vim/indent/rst.vim
```
