==============
Licences FLOSS
==============

Alexandre Fayolle <alexandre.fayolle@camptocamp.com>

13 janvier 2015

* Qu'est que le Logiciel Libre / Open Source
* Présentation de quelques licences classiques
* Choisir une licence
* Compatibilité

----

Disclaimer
==========

.. image:: http://fc05.deviantart.net/fs19/f/2007/275/a/a/Conan__IANAL_by_Chibi_Sanzo.png

©2007-2015 Chibi-Sanzo

En particulier, je ne suis pas à l'aise avec les détails du droit d'auteur, ni le droit des brevets...

----

Logiciel Libre
==============

De quelles libertés parle-t-on ?

Free Software vs. Open Source

* querelles philosophiques
* en pratique les 2 classes de logiciels se recouvrent largement
* FLOSS

----

Libertés selon la FSF
~~~~~~~~~~~~~~~~~~~~~

0. liberté d'exécuter le programme, sans restriction de but
1. liberté d'étudier le fonctionnement du programme, et de le modifier pour l'adapter à ses besoins
2. liberté de redistribuer des copies
3. liberté de redistribuer les versions modifiées

----

Libertés selon l'OSI
~~~~~~~~~~~~~~~~~~~~

1. redistribution libre
2. accès au code source
3. redistribution d'œuvres dérivées
4. exception: préservation de l'intégrité du code source de l'auteur (patches)
5. non discrimination contre des personnes ou des groupes
6. non discrimination contre des champs d'application
7. application à l'identique pour toutes les personnes qui reçoivent le logiciel
8. la license ne doit pas être spécifique à un produit
9. absence de restriction sur d'autres logiciels
10. neutralité technologique


----

Les tests de debian-legal
~~~~~~~~~~~~~~~~~~~~~~~~~

* Test de l'île déserte
* Test du dissident
* Test des Tentacules du Mal

https://people.debian.org/~bap/dfsg-faq.html

https://wiki.debian.org/DFSGLicenses#Licenses_that_are_DFSG-incompatible

----

Quizz
~~~~~

Est-ce qu'une licence de logiciel libre peut exiger que le code modifié soit communiqué à l'auteur original ?

----

Quizz
~~~~~

Est-ce qu'une licence de logiciel libre peut demander que l'utilisateur envoie une carte postale ?


----

Quizz
~~~~~

Est-ce qu'une licence de logiciel libre peut interdire d'utiliser le logiciel pour torturer des gens ?

----

Quizz
~~~~~

Est-ce qu'une licence de logiciel libre peut exiger que le code modifié soit communiqué à l'auteur original ?

----

Quizz
~~~~~

Est-ce qu'une licence de logiciel libre peut interdire de modifier la partie client d'un protocole de communication réseau mis en œuvre par le logiciel ? 

----

Quelques licences libres
========================

Licences "permissives" :

* BSD à 2 clauses
* X11 / MIT
* zlib
* Apache

Licences "Copyleft" :

* GPL
* LGPL
* AGPL
* MPL

----

BSD à 2 clauses
~~~~~~~~~~~~~~~

Copyright (c) <YEAR>, <OWNER>
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

----

X11 ou MIT
~~~~~~~~~~

Copyright (c) <year> <copyright holders>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

----

zlib
~~~~

Copyright (c) <''year''> <''copyright holders''>

This software is provided 'as-is', without any express or implied
warranty. In no event will the authors be held liable for any damages
arising from the use of this software.

Permission is granted to anyone to use this software for any purpose,
including commercial applications, and to alter it and redistribute it
freely, subject to the following restrictions:

1. The origin of this software must not be misrepresented; you must not
   claim that you wrote the original software. If you use this software
   in a product, an acknowledgement in the product documentation would be
   appreciated but is not required.
2. Altered source versions must be plainly marked as such, and must not be
   misrepresented as being the original software.
3. This notice may not be removed or altered from any source distribution.

----

Apache 2.0
~~~~~~~~~~

Copyright [yyyy] [name of copyright owner]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.


Remarques:

* CLA inclus
* s'applique par fichier, et plus globalement à une logiciel
* la licence continue de s'appliquer sur tous les fichiers non modifiés dans une œuvre dérivée
* il doit être fait mention de l'existence de modification dans les fichiers visés
* gestion explicite des brevets (accord de droits, révocation en cas de poursuite)

----


Copyleft
~~~~~~~~

.. image:: http://upload.wikimedia.org/wikipedia/commons/thumb/a/a3/GreenCopyleft.svg/197px-GreenCopyleft.svg.png

Le Copyleft (jeu de mots sur "copyright") est une autorisation par le
détenteur d'une œuvre soumis au droit d'auteur (ou au droit du
copyright, suivant la juridiction) de consulter, modifier, diffuser
son œuvre (y compris une version modifiée) à condition que cette
autorisation soit préservée.

C'est la base des licences "Xxxx Public License". 

----

GNU General Public License 3
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

http://www.gnu.org/licenses/gpl.html

* Liberté classiques (art 2)
* Copyleft fort (art 4, art 5) : les œuvres dérivées doivent être distribuées dans leur totalité  sous GPL
  - exceptions pour les bibliothèques système
  - exception pour certains plugins (processus séparés ou interactions minimes)
* Accès au code source et aux informations d'installation (art 6)
* Certaines permissions additionnelles possibles (art 7)
* Gestion de la révocation de la licence en cas de non respect (art 8)
* Gestion des brevets (art 11)
* information visible dans le binaire

----

GNU Lesser General Public License 3
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

http://www.gnu.org/licenses/lesser.html

Pensée pour les bibliothèques

* Liberté classiques (art 2)
* Copyleft faible (art 4, art 5) : en cas de combinaison avec d'autres composants, l'œuvre combinée composite n'est pas concernée par le copyleft, seules les œuvres dérivées le sont

----

GNU Affero Public License 3
~~~~~~~~~~~~~~~~~~~~~~~~~~~

http://www.gnu.org/licenses/agpl.html

Semblable à GPLv3, mais donne des droits non seulement aux personnes
qui reçoivent une copie du programme, mais également aux personnes qui
utilisent le programme à travers le réseau. (art 13)

Faite pour éviter le détournement de la GPL via du SaaS.

Copyleft fort, avec une exception pour les portions de code GPL qui ne sont pas "contaminées" par l'AGPL dans le cadre d'une combinaison. 


----

Mozilla Public License 2.0
~~~~~~~~~~~~~~~~~~~~~~~~~~

https://www.mozilla.org/MPL/2.0/

Licence copyleft faible. 

L'unité d'œuvre n'est pas la bibliothèque ou l'exécutable (comme dans la LGPL) mais le fichier source. 

Gestion des brevets

-----

Choisir une licence
===================

Rester sur des choses connues, et ne pas inventer sa propre licence

Utiliser la licence de l'écosystème quand c'est possible

Selon le contexte, je recommande Apache 2.0 (or later) ou GPLv3 (or later)

* Apache 2.0 pour les petits programmes
* Apache 2.0 pour les implémentations de références de bibliothèques dont on souhaite une très large diffusion, en particulier pour celles qui sont des alternatives à des bibliothèques propriétaires
* Apache 2.0 pour les bibliothèques javascript
* GPL v3 pour tout le reste, voir AGPLv3 s'il y a un risque d'emprisonnement par un SaaS

----

Compatibilité des licences
==========================

Si je prends 2 bouts de code, avec deux licences différentes, est-ce que j'ai le droit de les combiner ?

Réponse: ça dépend des licenses. Oui, si j'ai le droit d'appliquer simultanément les 2 deux licences à l'œuvre résultante.

Globalement, tant qu'il n'y a pas de licence à Copyleft dans l'équation, c'est bon

----

Tableaux de compatibilité
~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: http://upload.wikimedia.org/wikipedia/commons/thumb/d/dc/Quick-guide-gplv3-compatibility.svg/500px-Quick-guide-gplv3-compatibility.svg.png

Author: A. Hawrylyshen, CC-BY-SA-3.0


----

Contributor License Agreement
=============================

Un CLA est un accord qu'un contributeur passe avec l'organisme qui s'occupe de la maintenance d'un logiciel (et qui en détient généralement les droits) pour lui donner pouvoir en particulier sur la défense de la licence et l'évolution de la licence du logiciel. 

En l'absence de CLA, un changement de licence copyleft nécessite l'accord de l'ensemble des contributeurs. 


----

Références
==========

http://en.wikipedia.org/wiki/Comparison_of_free_and_open-source_software_licenses
http://blog.milkingthegnu.org/2008/04/gpl-for-dummies.html
http://en.swpat.org/wiki/Patent_clauses_in_software_licences
http://www.fsf.org/licensing/
http://opensource.org/licenses
http://www.gnu.org/licenses/gpl-faq.html#AllCompatibility
https://www.gnu.org/licenses/license-list.html
https://wiki.debian.org/DFSGLicenses
