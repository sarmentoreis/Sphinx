.. Teste 2 documentation master file, created by
   sphinx-quickstart on Fri Sep 17 08:07:32 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Teste 2's documentation!
===================================

.. toctree::
   :maxdepth: 2
   :caption: Conteúdo:
   :name: Referenciando_documentos.
   :numbered:   

   Cross-referencing documents

.. toctree::
   :caption: Google:
   :hidden:

   Acessar <https://google.com.br>


..
   Fim toctree

--------------------------------------

#####################
* **Title-reference**
#####################

.. [CIT01] Citação de title-reference.

--------------------------------------

###############
* **Footnotes**
###############

  *Go Footnotes*

*Ex: 1*

Footnote reference auto-numbered [#]_

*Ex: 2*

| Footnote reference auto-number label [#note]_
| Another footnote reference auto-number label [#note]_

--------------------------------------

*Ex: 3*

| Footnote auto-symbol 0  [*]_
| Footnote auto-symbol 1  [*]_
| Footnote auto-symbol 2  [*]_
| Footnote auto-symbol 3  [*]_
| Footnote auto-symbol 4  [*]_
| Footnote auto-symbol 5  [*]_
| Footnote auto-symbol 6  [*]_
| Footnote auto-symbol 7  [*]_
| Footnote auto-symbol 8  [*]_
| Footnote auto-symbol 9  [*]_

* **Internal links, references**

IR para: :ref:`Referencia <referencia>`.

.. _voltar:

|
|
|
|

**Voltei**

--------------------------------------

Documentação 2
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

--------------------------------------


..
   Hyperlinks

..
   External Links

|
|

**Hyperlinks**
================

   *Ex: 1*
      *External links:*

      `Google.com <https://google.com/>`_

   *Ex: 2*
      *Embedded URI:*

      Site do Google: `Google.br <https://google.com.br/>`_.

   *Ex: 3*
      *Hyperlink targets:*
   
         .. Hyperlink targets, Param1(Youtube, nome do link a seguir), Param2(Youtube_, target a ser chamada para atribuir um link)
         .. Param3(_Youtube, atribuindo o link), Param4(URL, link em si).



      Youtube: Youtube_.
      
.. _Youtube: https://youtube.com.br

|
|

---------------------------------------------

|
|

- *Internal Links*
  
  *Ex: 1*
      *Cross-referencing arbitrary locations*

.. _referencia:

**REFERENCIANDO AQUI!**

Voltar: :ref:`Voltar <voltar>`.

   *Ex: 2*
      *Figuras*

.. _figura:
.. figure:: rosa.jpg
   :name: rosa_vermelha
   
   Essa é o caption da figura.

|
|

-----------------------------------------

|
|

  *Ex: 1*
      *Cross-referencing documents*
   
Documento: :doc:`Cross-referencing documents <Cross-referencing documents>`

   *Ex: 2*
      *Referencing downloadable files*

Visual Studio Code: :download:`Download <VSCodeUserSetup-x64-1.60.0.exe>`

.. only:: text

   Broken link: :download:`download <VSCodeUserSetup-x64-1.60.0.exe>`

   *Ex: 3*
      *Cross-referencing figures by figure number*

Imagem: :numref:`Rosa (Fig. %s) <rosa_vermelha>` 

|
|

-----------------------------------------

|
|

**Sections**
==============

*Ex: 1*
      *Sections*

This is Sections, H1.
=====================

#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#

*Ex: 2*
      *Overline, for parts*

################################
This is Overline, for parts, H2.
################################

#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#

*Ex: 3*
      *Overline, for chapters,*

***********************************
This is Overline, for chapters, H3.
***********************************

#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#

*Ex: 4*
      *Subsections*

This is Subsections, H4.
------------------------

#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#

*Ex: 5*
      *Subsubsections*

This is Subsubsections, H5.
^^^^^^^^^^^^^^^^^^^^^^^^^^^

#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#

*Ex: 6*
      *Paragraphs*

This is Paragraphs, H6.
"""""""""""""""""""""""

#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#-#

|
|

-----------------------------------------

|
|

**Customization**
=================

   *Ex: 1*
      Emphasis

|  *Emphasis é itálico.*
|  :emphasis:`:emphasis: é itálico.`

   *Ex: 2*
      Strong
   
|  **Strong é negrito.**     
|  :strong:`:strong: é negrito.`

   *Ex: 3*
      Literal

|  ``Literal é literal.``
|  :literal:`:literal: é literal.`
  
   *Ex: 4*
      Subscript

|  Subscript é sobrescrito, H\ :sub:`2`\ O. 
|  Outra fórmula é utilizando .. replace:: |N2O|.

.. |N2O| replace:: N\ :sub:`2`\ O

*Ex: 5*
      Superscript
   
|  Superscript é superescrito, E = mc\ :sup:`2`\.
|  Outra fórmula é utilizando .. replace:: |E=MC2|.

.. |E=MC2| replace:: E = mc\ :sup:`2`\

*Ex: 6*
      Title-reference

   `Citação título de referência` [CIT01]_ <<Click.

--------------------------------------

**Footnotes**
=============

*Ex: 1*

.. [#] Footnote referenced auto-numbered.

*Ex: 2*

.. [#note] Footnote referenced auto-numbered label.

*Ex: 3*

.. [*] Footnote auto-symbol 0
.. [*] Footnote auto-symbol 1
.. [*] Footnote auto-symbol 2
.. [*] Footnote auto-symbol 3
.. [*] Footnote auto-symbol 4
.. [*] Footnote auto-symbol 5
.. [*] Footnote auto-symbol 6
.. [*] Footnote auto-symbol 7
.. [*] Footnote auto-symbol 8
.. [*] Footnote auto-symbol 9 