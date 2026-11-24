#####
SEDA - Version 2.4 | Standard d'Echange de Données pour l'Archivage
#####



Vous cherchez `une autre version du SEDA <../main/README.rst#3historique-des-versions>`_ ?






.. section-numbering::

-------------------------------------------------------------

.. contents::



-------------------------------------------------------------



Les caractéristiques du SEDA v2.4
===================================

Introduction au SEDA
---------------

Consulter `la page d'accueil
<../../tree/main/>`_



Genèse du SEDA 2.4
---------------

**La version 2.4** du Standard d'échanges de données pour l'archivage (SEDA) -publiée le **26 novembre 2026** sous l'égide du Service interministériel des Archives de France- comprend six schémas, un dictionnaire et une documentation sommaire des nouveautés. La documentation du standard est en cours de refonte.


Les nouveautés par rapport à la version 2.3 :

La version 2.4 du SEDA vise à optimiser la préservation des **documents audiovisuels** (audio et vidéo) nativement numériques ou numérisés. 

Cette nouvelle version se limite à **l’ajout** de nouveaux éléments **facultatifs** à l’ontologie SEDA. 

**A l’exception de la nouvelle extension générique sur les objets physiques, ils sont exclusivement dédiés aux binaires audiovisuels.**


Il s’agit :

* De disposer d’une zone pour déclarer les référentiels de formats audiovisuels.

* D’incorporer les métadonnées techniques embarquées dans les fichiers.

* D’être en mesure de sourcer les documents soumis au droit d’auteur.

* D’être capable de décrire la chronologie interne des documents.

.. image:: /doc/img/IMG_00.png
	

Note de version (changelog)
---------------
Les principaux changements **par rapport à la version 2.3** sont :

**Documents audiovisuels**

* Possibilité de déclarer des listes de codes (référentiels) pour les formats audiovisuels.

* Possibilité d'incorporer au manifeste une sélection de métadonnées techniques embarquées dans le media.

* Ajout de métadonnées descriptives propres à l'audiovisuel.


**Documents physiques**

* Ajout d'un point d'extension générique, sur le modèle de celui des objets numériques.


.. image:: /doc/img/IMG_01.png


Schémas XML
===================================
`Les schémas </schema/>`_ traduisent la forme des messages échangés au cours des transactions.




Documentation
===================================

Documentation générale
---------------
* `SEDA 2.4 | Documentation sommaire des nouveautés <https://raw.githubusercontent.com/culturecommunication/seda/seda-2.4/doc/SEDA_v2.4_introduction.pdf>`_

* `SEDA 2.4 | Dictionnaire des nouvelles balises <https://raw.githubusercontent.com/culturecommunication/seda/seda-2.4/doc/SEDA_v2.4_dictionnaire_fonctionnel_nouvelles_balises.xlsx>`_

* `SEDA 2.4 | Un manifeste XML d'exemple <https://raw.githubusercontent.com/culturecommunication/seda/seda-2.4/doc/SEDA_v2.4_manifeste_exemple.xml>`_


Documentation technique
---------------

* `SEDA 2.4 | Documentation HTML des schémas XML <https://github.com/culturegouv/seda/raw/refs/heads/seda-2.4/doc/SEDA_v2.4_dictionnaire_technique_XSD.zip>`_ ``[ZIP à télécharger]``

* SEDA 2.4 | Diagrammes SVG des schémas XML  ``[Bientôt]``

* SEDA 2.4 | Consulter la documentation technique en ligne ``[Bientôt]``






Téléchargement
===================================

`Télécharger l'ensemble du SEDA 2.4 <https://github.com/culturegouv/seda/releases/tag/seda_v2.4/>`_ (schémas XML et documentation)


