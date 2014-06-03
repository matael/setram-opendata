:data-transition-duration: 1000
:skip-help: true
:css: css/style.css

.. role:: center
.. role:: important
.. role:: red

.. title:: Setram - OpenData

----

:id: title

OpenData
========

HAUM |---| Mathieu Gaborit

.. image:: img/datalove.png
    :class: datalove

.. image:: img/haum.png
    :width: 250px

.. |---| unicode:: U+02015 .. em dash

----

:id: haum

.. image:: img/haum.png
    :width: 350px

HAUM
----

Hackerspace de l'Université du Maine

~ 20 membres actifs

:important:`@haum72`
:important:`haum.org`

Celui qui cause...
------------------

Mathieu Gaborit

:important:`@matael`
:important:`mathieu@matael.org`
:important:`blog.matael.org`

Co-fondateur du HAUM, datalover...

----

Le décor
========

- SETRAM : le réseau de transport en commun du Mans
- principal fournisseur de données de mobilité au Mans
- Pas d'API fournie ni de possibilité de récupérer automatiquement les données
- un service (Timeo) permet d'obtenir les données en temps réel (ou presque)

*Bref... c'était pas la joie...*

----

Notre idée
==========

Les données de Timeo sont publiques : *on va créer un moyen d'automatiser la récupération*

3 objectifs :

#. un *module* permettant la récupération directe
#. une *API* REST pour faciliter l'accès aux données
#. quelques *blogs posts* pour expliquer tout ça

----

Module Python
=============

- récupération des requètes depuis le site mobile
- écriture d'un client, automatisation
- création d'un module Python : *pytimeo*

PyTimeo, c'est aussi :

- plus de 100 téléchargements/mois sur Pypi
- un module qui a été adapté pour d'autres systèmes de transport
- quelque chose de royalement ignoré par la SETRAM...

----

Bilan sur le module
===================

- parfaitement faisable
- trop long pour qu'une entreprise ne songe à le faire elle même

Dommage de perdre tant de temps et de potentiel utilisateur...

----

API REST
========

- réutilisation du module pour fournir un point d'entrée documenté
- création d'une API en Python (basée sur Bottle.py)
- entièrement documentée ( *timeoapi.rtfd.org* ) et open-source ( *github.com/haum/timeoAPI* )
- utilisée le temps où elle est restée en ligne ( timeoapi.haum.org )
- pas optimisée à dessein...

----

Deux applications
=================

- une map des passages de bus et trams sur Le Mans en temps réel
- un afficheur LED pour prévenir des prochains passages

Du code libre
=============

- GNU/GPL : timeoAPI et pytimeo
- WTFPL : afficheur LED

:important:`Tout est réutilisable !`

----

Articles de Blog
================

- deux articles sur le sujet

  - un technique
  - un pour expliquer le concept général

- plus de milles vues
- des retours de hackers ailleurs en France ayant réutilisé le code

----

Et Le Mans ?
============

- aucun retour de la part de la SETRAM
- pas de suite donnée à cette tentative d'ouverture
- pas non plus d'efforts fait pour rendre le service plus agréable aux usagers...

:important:`Dommage non ?`

----

Des possibilités
================

- optimisation de l'API
- écriture d'un outil de routage et de minimisation d'itinéraire
- évaluation de la couverture du réseau
- journalisation sur une période et identification de points difficiles
- optimisation des lignes, analyse des flux de passagers...
- couplage avec les données de parkings, culturelles, etc...

Bref, une meilleure compréhension du réseau et une meilleure gestion du trafic !

Mais aussi....
--------------

:important:`un meilleur service voyageur !`

----

Bilan
=====

Usagers
-------

- certains usagers attendent vraiment des outils du genre
- des développeurs pourraient inclure le reseau dans leurs applis
- proposer un service bien fait et extensible (pas une appli seule, mais une API)..

Enjeu
-----

- les données de mobilité représentent un enjeu majeur
- important pour le tourisme et la découverte d'une ville

Politique
---------

- ne plus être derniers sur un sujet important et en vue : l'OpenData
- faire des promesses de campagne des actions de mandat

----

:data-x: r2500
:data-y: r0
:data-rotate-z: 0
:id: thanks
:data-scale: 2

.. image:: img/datalove.png
    :class: datalove

Merci !
=======

A vous, à la Ruche Numérique, au HAUM et aux lolcats...

----

:id: overview
:data-x: 4000
:data-y: 2000
:data-scale: 8
