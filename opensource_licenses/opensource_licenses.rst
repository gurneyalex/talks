.. include:: <s5defs.txt>

==============
Licences FLOSS
==============

:Authors: Alexandre Fayolle <alexandre.fayolle@camptocamp.com>
:Date: 13 janvier 2015


Programme
=========

* Qu'est que le Logiciel Libre / Open Source
* Présentation de quelques licences classiques
* Choisir une licence
* Compatibilité


Disclaimer
==========

.. image:: http://fc05.deviantart.net/fs19/f/2007/275/a/a/Conan__IANAL_by_Chibi_Sanzo.png
   :height: 1000 px
..    ©2007-2015 Chibi-Sanzo

En particulier, je ne suis pas à l'aise avec les détails du droit d'auteur, ni le droit des brevets...



Logiciel Libre
==============

De quelles libertés parle-t-on ?

Free Software vs. Open Source

* Querelles philosophiques
* En pratique les 2 classes de logiciels se recouvrent largement
* FLOSS



Libertés selon la FSF
=====================

.. class:: incremental

0. Liberté d'exécuter le programme, sans restriction de but
1. Liberté d'étudier le fonctionnement du programme, et de le modifier pour l'adapter à ses besoins
2. Liberté de redistribuer des copies
3. Liberté de redistribuer les versions modifiées



Libertés selon l'OSI
====================

.. class:: small

.. class:: incremental


1. Redistribution libre
2. Accès au code source
3. Redistribution d'œuvres dérivées
4. Exception: préservation de l'intégrité du code source de l'auteur (patches)
5. Non discrimination contre des personnes ou des groupes
6. Non discrimination contre des champs d'application
7. Application à l'identique pour toutes les personnes qui reçoivent le logiciel
8. La licence ne doit pas être spécifique à un produit
9. Absence de restriction sur d'autres logiciels
10. Neutralité technologique




Les tests de debian-legal
=========================

.. class:: incremental

* Test de l'Ile Déserte
* Test du Dissident
* Test des Tentacules du Mal
* Pour plus d'information voir:

  * `DFSG FAQ <https://people.debian.org/=bap/dfsg-faq.html>`_
  * `Licences incompatibles <https://wiki.debian.org/DFSGLicenses#Licenses_that_are_DFSG-incompatible>`_



Quizz
=====

.. image:: http://ljdchost.com/Oi71uxF.gif
   :height: 800px
   :align: right

Une license de logiciel libre peut elle...

.. class:: small

.. class:: incremental

* exiger que le code modifié soit communiqué à l'auteur original ?

* demander que l'utilisateur envoie une carte postale ?

* interdire d'utiliser le logiciel pour torturer des gens ?

* interdire de modifier la partie client d'un protocole de communication réseau mis en œuvre par le logiciel ? 



Quelques licences libres
========================

.. class:: small

Licences "permissives" :

.. class:: small

 * zlib
 * BSD à 2 clauses
 * X11 / MIT
 * ASL

.. class:: small

Licences "Copyleft" :

.. class:: small

 * GNU GPL
 * GNU LGPL
 * GNU AGPL
 * MPL

zlib
====

.. class:: small

Copyright (c) <''year''> <''copyright holders''>

This software is provided 'as-is', without any express or implied
warranty. In no event will the authors be held liable for any damages arising
from the use of this software.


Permissions zlib
================

Permission is granted to anyone to use this software for any purpose,
including commercial applications, and to alter it and redistribute it
freely, subject to the following restrictions:

.. class:: small

1. The origin of this software must not be misrepresented; you must not
   claim that you wrote the original software. If you use this software
   in a product, an acknowledgement in the product documentation would be
   appreciated but is not required.
2. Altered source versions must be plainly marked as such, and must not be
   misrepresented as being the original software.
3. This notice may not be removed or altered from any source distribution.


BSD à 2 clauses
===============

.. class:: small

Copyright (c) <YEAR>, <OWNER>
All rights reserved.

.. class:: small

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

.. class:: small

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.


Disclaimer BSD
==============

.. class:: tiny

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.



X11 ou MIT
==========

.. class:: small

Copyright (c) <year> <copyright holders>

.. class:: small

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

.. class:: small

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

Disclaimer X11
==============

.. class:: tiny

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.




Apache 2.0
==========

.. class:: small

Copyright [yyyy] [name of copyright owner]

.. class:: small

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

.. class:: small

http://www.apache.org/licenses/LICENSE-2.0

.. class:: small

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.


ASL 2.0: Remarques
==================

.. class:: small
.. class:: incremental

* CLA inclus
* S'applique par fichier, et plus globalement à une logiciel
* La licence continue de s'appliquer sur tous les fichiers non modifiés dans une œuvre dérivée
* Il doit être fait mention de l'existence de modification dans les fichiers visés
* Gestion explicite des brevets (accord de droits, révocation en cas de poursuite)

Vous survivez ?
===============

.. image:: http://ljdchost.com/VLTXiiF.gif
   :height: 1000px
   :align: center


Copyleft
========

.. image:: http://upload.wikimedia.org/wikipedia/commons/thumb/a/a3/GreenCopyleft.svg/197px-GreenCopyleft.svg.png

Le Copyleft (jeu de mots sur "copyright") est une autorisation par le
détenteur d'une œuvre soumis au droit d'auteur (ou au droit du
copyright, suivant la juridiction) de consulter, modifier, diffuser
son œuvre (y compris une version modifiée) à condition que cette
autorisation soit préservée.

C'est la base des licences "Xxxx Public License". 



GNU General Public License 3
============================

http://www.gnu.org/licenses/gpl.html

.. class:: small
.. class:: incremental

* Libertés classiques (art 2)
* Copyleft fort (art 4, art 5) : les œuvres dérivées doivent être distribuées dans leur totalité sous GPL

  * exceptions pour les bibliothèques système
  * exception pour certains plugins (processus séparés ou interactions minimes)

* Accès au code source et aux informations d'installation (art 6)
* Certaines permissions additionnelles possibles (art 7)
* Gestion de la révocation de la licence en cas de non respect (art 8)
* Gestion des brevets (art 11)
* Information visible dans le logiciel



GNU Lesser General Public License 3
===================================

http://www.gnu.org/licenses/lesser.html

Pensée pour les bibliothèques

.. class:: incremental

* Libertés classiques (art 2)
* Copyleft faible (art 4, art 5)

  * en cas de combinaison avec d'autres composants, l'œuvre combinée composite
    n'est pas concernée par le copyleft

  * seules les œuvres dérivées le sont

GNU Affero Public License 3
===========================

http://www.gnu.org/licenses/agpl.html

.. class:: incremental

* Semblable à GPLv3, mais donne des droits non seulement aux personnes qui reçoivent une copie du programme, mais également aux personnes qui utilisent le programme à travers le réseau. (art 13)
* Faite pour éviter le détournement de la GPL via du SaaS.
* Copyleft fort, avec une exception pour les portions de code GPL qui ne sont pas "contaminées" par l'AGPL dans le cadre d'une combinaison. 




Mozilla Public License 2.0
==========================


https://www.mozilla.org/MPL/2.0/

.. class:: incremental

* Licence copyleft faible. 
* L'unité d'œuvre n'est pas la bibliothèque ou l'exécutable (comme dans la LGPL) mais le fichier source. 
* Gestion des brevets



Choisir une licence
===================

.. class:: incremental

* Rester sur des choses connues, et ne pas inventer sa propre licence

.. image:: http://ljdchost.com/cMLpbLc.gif
   :height: 1000px
   :align: center

.. class:: incremental

* Utiliser la licence de l'écosystème quand c'est possible

* Selon le contexte, je recommande Apache 2.0 (or later) ou GPLv3 (or later)

Choisir une licence
===================

.. class:: incremental

* ASL 2.0 pour les petits programmes
* ASL 2.0 pour les implémentations de références de bibliothèques dont on souhaite une très large diffusion

  *  En particulier pour celles qui sont des alternatives à des bibliothèques propriétaires

* ASL 2.0 pour les bibliothèques javascript
* GPLv3 pour tout le reste, ou AGPLv3 si le logiciel est utilisé via une interface Web.



Compatibilité des licences
==========================

.. image:: http://ljdchost.com/sMePFu5.gif
   :height: 1000 px
   :align: right

Si je prends 2 bouts de code, avec deux licences différentes, est-ce que j'ai le droit de les combiner ?

.. class:: incremental

* Réponse: ça dépend des licences. Oui, si j'ai le droit d'appliquer simultanément les 2 deux licences à l'œuvre résultante.
* Globalement, tant qu'il n'y a pas de licence à Copyleft dans l'équation, c'est bon.



Tableaux de compatibilité
=========================

.. image:: http://upload.wikimedia.org/wikipedia/commons/thumb/d/dc/Quick-guide-gplv3-compatibility.svg/1000px-Quick-guide-gplv3-compatibility.svg.png
   :align: center

Author: A. Hawrylyshen, CC-BY-SA-3.0




Contributor License Agreement
=============================

Un CLA est un accord qu'un contributeur passe avec l'organisme qui s'occupe de la maintenance d'un logiciel (et qui en détient généralement les droits) pour lui donner pouvoir en particulier sur la défense de la licence et l'évolution de la licence du logiciel. 

En l'absence de CLA, un changement de licence copyleft nécessite l'accord de l'ensemble des contributeurs. 


CLA et tentacules du mal ?
===========================

Lecture intéressante: 
`Michael Meeks on LibreOffice and code ownership <http://lwn.net/Articles/414051/>`_ (Nov 2010, Linux Plumbers Conference)


Références
==========

* `WP: comparaison des licenses <http://en.wikipedia.org/wiki/Comparison_of_free_and_open-source_software_licenses>`_
* `GPL for dummies <http://blog.milkingthegnu.org/2008/04/gpl-for-dummies.html>`_
* `Patent clauses in software licenses <http://en.swpat.org/wiki/Patent_clauses_in_software_licences>`_
* `FSF: licensing <http://www.fsf.org/licensing/>`_
* `OSI: licenses <http://opensource.org/licenses>`_
* `GPL FAQ: Compatibility <http://www.gnu.org/licenses/gpl-faq.html#AllCompatibility>`_
* `GNU: license list <https://www.gnu.org/licenses/license-list.html>`_
* `DFSG licenses <https://wiki.debian.org/DFSGLicenses>`_

Questions ?
===========

.. image:: http://i.imgur.com/moo0BtB.gif
   :height: 1000px
   :align: center

Annexe
======

`Source de cette présentation <https://github.com/gurneyalex/talks>`_ sur gitub 

(licence: ASL 2.0) 
