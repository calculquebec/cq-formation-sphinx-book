Matériel d'atelier utilisant Sphinx
===================================

`English <../en/index.html>`_

Bienvenue dans cet exemple de contenu d'atelier avec
`Sphinx <https://www.sphinx-doc.org/fr/master/index.html>`_.

Voici quelques exemples de blocs spéciaux :

.. important::

    Les fichiers :code:`*.rst` ne contiennent pas du Markdown, mais bien du
    `reStructuredText <https://www.sphinx-doc.org/fr/master/usage/restructuredtext/>`_.
    Il y a certains avantages, tels que la possibilité d'inclure le contenu d'un
    fichier :code:`*.rst`, ce qui évite de dupliquer certaines informations.

.. note::

    - On

      - peut
      - faire

    - des

      - listes.

    #. C'est
    #. pratique.

Voir la documentation sur les 
`bases du reStructuredText <https://www.sphinx-doc.org/fr/master/usage/restructuredtext/basics.html>`_.

Les fichiers :code:`index.rst` contiennent les informations nécessaires
à la construction de la table des matières dans le panneau de gauche.

.. toctree::
    :caption: Chapitres
    :maxdepth: 2
    :titlesonly:
    :hidden:

    01-sujetA
    02-sujetB
    extra/index

.. toctree::
    :caption: Aide
    :maxdepth: 2
    :titlesonly:
    :hidden:

    references

.. toctree::
    :caption: Liens externes
    :hidden:

    Documentation technique de l’Alliance <https://docs.alliancecan.ca/wiki/Technical_documentation/fr>
    Formations de Calcul Québec <https://www.calculquebec.ca/services-aux-chercheurs/formation/>
