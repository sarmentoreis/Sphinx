.. Teste_4 documentation master file, created by
   sphinx-quickstart on Thu Sep 23 08:40:15 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Teste_4's documentation!
===================================


.. note::

   This project is under active development.

.. toctree::

   usage



Documentação 4 - Final
=======================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

Add Toctree and adding cross-references
---------------------------------------

*Ex: 1*

   Check out the :doc:`usage` section for further information.

*Ex: 2*

   Check out the :doc:`usage` section for further information, including how to
   :ref:`install <installation>` the project.

|
|

Other roles
-----------

Math
^^^^

   :red:`Ex: 1 - Pitágoras`

Since Pythagoras, we know that :math:`a^2 + b^2 = c^2`.

Utilizado a role: \:math: \`a^2 + b^2 = c^2`.

   :red:`Ex: 2 - Euler`

.. math:: e^{i\pi} + 1 = 0
   :label: euler

Euler's identity, equation :math:numref:`euler`, was elected one of the
most beautiful mathematical formulas.

   :red:`Ex: 3`

.. math::

   (a + b)^2 = a^2 + 2ab + b^2

   (a - b)^2 = a^2 - 2ab + b^2

\
   :red:`Ex: 4`

.. math::

   (a + b)^2  &=  (a + b)(a + b) \\
              &=  a^2 + 2ab + b^2

\
   :red:`Ex: 5`

.. math::
   :nowrap:

   \begin{eqnarray}
      y    & = & ax^2 + bx + c \\
      f(x) & = & x^2 + 2xy + y^2
   \end{eqnarray}

|
|

Other directives
----------------

Paragraph-level markup
^^^^^^^^^^^^^^^^^^^^^^

:green:`Ex: 1 - Version Added`

.. versionadded:: 1.5
   The *spam* parameter

:green:`Ex: 2 - Version Changed`

.. versionchanged:: 1.3
   The *spam* parameter

:green:`Ex: 3 - Deprecated`

.. deprecated:: 1.0  
   The :func:`spam` parameter

:green:`Ex: 4 - See Also`

.. seealso::

      Module :py:mod:`zipfile`
      Documentation of the :py:mod:`zipfile` standard module.

:green:`Ex: 5 - Centered`

.. centered:: LICENSE AGREEMENT

:green:`Ex: 6 - Hlist`

.. hlist::
   :columns: 3

   * A list of
   * short items
   * that should be
   * displayed
   * horizontally

:green:`Ex: 7 - Highlight, code-block's`

*(1)*

.. code-block:: python
   :emphasize-lines: 3,5

   def some_function():
       interesting = False
       print 'This line is highlighted.'
       print 'This one is not...'
       print '...but this one is.'

*(2)*

.. code-block:: python
   :caption: this.py
   :name: this-py

   print 'Explicit is better than implicit.'

|
|

Glossary
--------

:blue:`Ex: 1`

.. glossary::

   environment
      A structure where information about all documents under the root is
      saved, and used for cross-referencing.  The environment is pickled
      after the parsing stage, so that successive runs only need to read
      and parse new and changed documents.

   source directory
      The directory which, including its subdirectories, contains all
      source files for one Sphinx project.

:blue:`Ex: 2`

.. glossary::

   term 1 : A
   term 2 : B
      Definition of both terms.

|
|

Meta-information markup
-----------------------

**Sectionauthor**

.. sectionauthor:: Guido van Rossum <guido@python.org>
  
Necessary configuration value in conf.py - "show_authors = True".

**Codeauthor**

.. codeauthor:: Leonardo Felipe Sarmento dos Reis <lreis@cpqd.com.br>

|
|

Domains
-------

Python Domain
^^^^^^^^^^^^^

**Basic Markup**

*Ex: 1 - functions 1*

.. py:function:: spam(eggs)
                 ham(eggs)

   Spam or ham the foo.

*Ex: 2 - functions 2*

.. py:function:: filterwarnings(action, message='', category=Warning, \
                                module='', lineno=0, append=False)
   :noindex:

*Ex: 3 - functions 3*

.. py:function:: receberDados()
   :async:

*Ex: 4 - methods*

.. py:method:: verLista(int lista)

*Ex: 5 - data*

.. py:data:: preço
   :type: int
   :value: 0

*Ex: 6 - data 2*

.. py:data:: pi
   :type: float
   :value: 3.14
   
*Ex: 7 - exception*

.. py:exception:: IOException
   :final:

*Ex: 8 - class*

.. py:class:: Aluno

   .. py:method:: lista()
   
Into field lists
""""""""""""""""

* **param**, **parameter**, **arg**, **argument**, **key**, **keyword**: Description of a parameter.
* **type**: Type of a parameter. Creates a link if possible.
* **raises**, **raise**, **except**, **exception**: That (and when) a specific exception is raised.
* **var**, **ivar**, **cvar**: Description of a variable.
* **vartype**: Type of a variable. Creates a link if possible.
* **returns**, **return**: Description of the return value.
* **rtype**: Return type. Creates a link if possible.
* **meta**: Add metadata to description of the python object. The metadata will not be shown on output document. 
  For example, :meta private: indicates the python object is private member. It is used in sphinx.ext.autodoc 
  for filtering members.

|
|

  :orange:`--EXEMPLO--`

.. py:function:: send_message(sender, recipient, message_body, [priority=1])

   Send a message to a recipient

   :param str sender: The person sending the message
   :param str recipient: The recipient of the message
   :param str message_body: The body of the message
   :param priority: The priority of the message, can be a number 1-5
   :type priority: integer or None
   :return: the message id
   :rtype: int
   :raises ValueError: if the message_body exceeds 160 characters
   :raises TypeError: if the message_body is not a basestring

|
|
