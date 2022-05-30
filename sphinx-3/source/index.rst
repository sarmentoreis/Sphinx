.. Teste_3 documentation master file, created by
   sphinx-quickstart on Tue Sep 21 08:07:25 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.
.. title:: Aqui é o título - Teste_3

Welcome to Teste_3's documentation!
===================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

|
|

-------------------------------

|

Contents
========

.. contents:: Tabela de conteúdo
   teste_3


Documentação 3
==================

* :ref:`genindex` de Classes
* :ref:`modindex`
* :ref:`search` Class

##########
Directives
##########

******
Images
******

* *Ex: 1*

.. image:: ./images/orquidea.jpg
   :scale: 50 %
   :align: center

***********
Admonitions
***********

* *Ex: 1*

.. note:: Isso é um parágrafo.

   - Aqui é uma bullet list.

* *Ex: 2*

.. attention:: Atenção!

* *Ex: 3*

.. hint:: Dica

* *Ex: 4*

.. danger:: Perigo

* *Ex: 5*
  
.. warning:: Aviso

|
|

-------------------------------

|

*********
Container
*********

*Custom CSS*
------------

.. container:: cont  
   
   Escrever algo em :green:`Verde!`. |
   Outra em :orange:`Laranja!`. |
   E por fim :purple:`Roxo!`.

|
|

-------------------------------

|

*************
Body Elements
*************

Rubric
------
.. rubric:: Ex: Titulo de Rubric

Topic
-----
.. topic:: Titulo do Topic

   Conteúdo do Topic.

Sidebar ->
----------
.. sidebar:: Titulo opcional da sidebar
   :subtitle: Subtitulo opcional da sidebars

   Conteúdo da Sidebar.

Line-block (Deprecated)
-----------------------

.. line-block::

   Esse line-block está deprecated.
   Linha 2.
   Linha 3.
      Linha 4.
   Linha 5.

Line block (|)
--------------

| Linha 1.
| Linha 2.
| Linha 3.

Epigraph
--------

.. epigraph::

   No matter where you go, there you are.

   -- Buckaroo Banzai

Compound Paragraph
------------------

.. compound::

   The 'rm' command is very dangerous.  If you are logged
   in as root and enter ::

       cd /
       rm -rf *

   you will erase the entire contents of your file system.

|
|

-------------------------------

|

******************
Special directives
******************

Raw
---

*Ex: 1 - HTML*

.. raw:: HTML

   <h1>Teste de H1 no HTML</h1>
   <h2 style="color:red;">Teste de H2 no HTML, colorido.</h2>

Fim do HTML.

*Ex: 2 - LaTeX*

.. raw:: LaTeX

   \documentclass[12pt]{article}
   \title{LaTeX Básico}.
   \author{Leonardo F. S. dos Reis.}
   \date{\today}

   \begin{document}
   \maketitle

      Aqui é o conteúdo do LaTeX.

   \end{document}

Fim do LaTeX.

-------------------------------

Include
-------

*Include TXT*

.. include:: ./_static/txt/inclusion.txt
   :parser: rst
   
-------------------------------

Class
-----

.. rst-class:: special

   Esse é um parágrafo "special" classe em RST!

.. class:: ClassDirective

   Python possui um Directive chamado "Class", no qual sobrepõe 
   a original do Docutils, com o mesmo nome. Portanto, necessário
   utilizar "rst-class".

|
|

-------------------------------

|

******************
HTML Specifics
******************

Meta
----

*HTML Metadata*

.. meta::
   :description: The Sphinx documentation builder
   :keywords: Sphinx, documentation, builder

| A TAG meta irá para o cabeçalho HTML (Head)
| Ex:
|     .. meta::
|     :description: The Sphinx documentation builder
|     :keywords: Sphinx, documentation, builder

Title
-----

*Title Head*

   \.. title:: Titulo da página, HEAD

|      Além disso, necessário alterar no conf.py,
|      html_title = "Complemento ou null".

|
|

-------------------------------

|

******************
Influencing markup
******************

Default role
------------

.. default-role:: subscript

An exemple of a `default subscript` role.
Another `one`.

.. default-role:: superscript

An exemple of a `default superscript` role.
Another `one`.

.. default-role::

Now without any `default role`.

Role custom
-----------

.. role:: negrito(strong)
   
| Exemplo utilizando role customizada :negrito:`texto interpretado`.
| Outro exemplo: :negrito:`NEGRITO`.

|
|

-------------------------------

|

############
Substitution
############

****************
Replace or image
****************

Image
-----

The |biohazard| symbol must be used on containers used to
dispose of medical waste.

.. |biohazard| image:: ./images/biohazard.png
   :width: 35
   :height: 35

Replace
-------

Utilizando a directive |Aqui|

.. |Aqui| replace:: Replace.


Replace with Hyperlink
----------------------

|RST|_ is a little annoying to type over and over, especially
when writing about |RST| itself, and spelling out the
bicapitalized word |RST| every time isn't really necessary for
|RST| source readability.

.. |RST| replace:: reStructuredText
.. _RST: http://docutils.sourceforge.net/rst.html