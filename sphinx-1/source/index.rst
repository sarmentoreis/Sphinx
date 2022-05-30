.. Teste documentation master file, created by
   sphinx-quickstart on Tue Sep 14 11:52:01 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


Welcome to Sphinx documentation!
=================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

..
   Versão

.. versionadded:: 1.0

..
   Método deprecated, depreciado.

.. deprecated:: 0.9
   Use :func:`metodo` instead.
 
    



Documentação
=====================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

term 1
   *Esse é o termo 1.*

term 2
   Definition 2, paragrafo 1.

   Definition 2, paragrafo 2.

horario : Integer
   Armazena um número inteiro, horário.

term 4 : Classificador 1 : Classificador 2
   Definicao 4.
   

.. 
   Abaixo não irá quebrar linha.
   
These lines are
broken exactly like in
the source file.

| These lines are
| broken exactly like in
| the source file.

-------------------------------------------------------

..
   Field List abaixo:

- **Field List**

:Date: 2001-08-16
:Version: 1
:Authors: - Me
          - Myself
          - I
:Indentation: Since the field marker may be quite long, the second
   and subsequent lines of the field body do not have to line up
   with the first line, but they must be indented relative to the
   field name marker, and they must line up with each other.
:Parameter i: integer

-------------------------------------------------------

..
   Quoted Literal Blocks abaixo:

- **Quoted Literal Blocks**

John Doe wrote::

>> Great idea!
>
> Why didn't I think of that?

You just did!  ;-)

-------------------------------------------------------

..
   Doctest Blocks abaixo:

- **Doctest Blocks**

   This is an ordinary paragraph.

>>> print 'this is a Doctest block'
this is a Doctest block

>>> 1+1
2

The following is a literal block::

    >>> This is not recognized as a doctest block by
    reStructuredText.  It *will* be recognized by the doctest
    module, though!

-------------------------------------------------------

..
   Tables, Grid Table

- **Table, Grid Table**
  
  *Ex: 1*

+------------+-----------+-----------+
| Header, col| Head 2    | Head 3    |
|  head opt  |           |           |
+============+===========+===========+
| Row, col1  | col2      | col3      |
+------------+-----------+-----------+
| Row2, col1 | col2      | col3      |
+------------+-----------+-----------+

   *Ex: 2*

+------------+-----------+-----------+
| Header, col| Head 2    | Head 3    |
|  head opt  |           |           |
+============+===========+===========+
| Row, col1  |  col 2 ......         |
+------------+-----------+-----------+
| Row2, col1 | col2      | col3      |
+------------+-----------+-----------+

   *Ex: 3*
  
+------------+-----------+-----------+
| Header, col| Head 2    | Head 3    |
|  head opt  |           |           |
+============+===========+===========+
| Row, col1  | col2      | col3      |
+------------+   row     +-----------+
| Row2, col1 |           | col3      |
+------------+-----------+-----------+ 

-------------------------------------------------------

..
   Tables, Simple Table

- **Table, Simple Table**

  *Ex: 1*

=====  =====  =======
  A      B    A and B
=====  =====  =======
False  False  False
True   False  False
False  True   False
True   True   True
=====  =====  =======

   *Ex: 2*

=====  =====  ======
   Inputs     Output
------------  ------
  A      B    A or B
=====  =====  ======
False  False  False
True   False  True
False  True   True
True   True   True
=====  =====  ======

   *Ex: 3*

=====  ======
col 1  col 2
=====  ======
1       Second column of row 1.
2       Second column of row 2.
        Second line of paragraph.
3       - Second column of row 3.

        - Second item in bullet
          list (row 3, column 2).
\       Row 4; column 1 will be empty.
5       Row 5; número 5.
\       Row 6. vazia.
=====  ======

-------------------------------------------------------

..
   Table, CSV Table

- **Table, CSV Table**
  
   *Ex: 1*

.. csv-table:: CSV Table!
   :header: "head1", "head2", "head3"
   :widths: 15, 10, 30 

   "param1", param2, "param3"
   "Bala", 0.49, "doce"
   "Pizza", 40.00, "salgada"
   "Bolo", ,"doce"
   "Refrigerante", 7.00, 

-------------------------------------------------------

..
   Table, List Table

- **Table, List Table**

   *Ex: 1*

.. list-table:: List Table!
   :widths: 15 10 30
   :header-rows: 1

   * - 1
     - 2
     - 3
   * - 4
     - 5
     - 6
   * - 7
     - 8
     - 9,
       9.1
   * - 10
     - 11
     - 12

-------------------------------------------------------

