.. prac documentation master file, created by
   sphinx-quickstart on Thu Nov 16 16:11:03 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to prac's documentation!
================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   c

.. toctree::
   :maxdepth: 2
   :caption: A:

   A/a_1
   A/a_2

.. toctree::
   :maxdepth: 2
   :caption: B:

   B/b_1
   B/b_2


*italics*

**boldface**

``code samples``


This is an ordinary paragraph, introducing a block quote.
   "It is my business to know things. That is my trade."
   -- Sherlock Holmes

* This is a bulleted list.
* It has two items,

1. This is a numbered list.
2. It has two items too.

#. This is a numbered list.
#. It has two items too.


* this is
* a list

   * with a nested list 
   * and some subitems

* and here the parent list continues 


term 1 
   Definition 1.

term 2 
   Definition 2, paragraph 1.

   Definition 2, paragraph 2.

term 3 : classifier
   Definition 3.

:Date: 2001-08-16
:Version: 1
:Authors: - Me
      - Myself
      - I 
:Indentation: Since the field marker may be quite long, the second and subsequent lines of the field body do not have to line up with the first line, but they must be indented relative to the field name marker, and they must line up with each other.
:Parameter i: integer

Grid table:

+------------+------------+-----------+
| Header 1   | Header 2   | Header 3  |
+============+============+===========+
| body row 1 | column 2   | column 3  |
+------------+------------+-----------+
| body row 2 | Cells may span columns.|
+------------+------------+-----------+
| body row 3 | Cells may  | - Cells   |
+------------+ span rows. | - contain |
| body row 4 |            | - blocks. |
+------------+------------+-----------+

Simple table:

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


CSV Table:

.. csv-table:: Frozen Delights!
   :header: "Treat", "Quantity", "Description" 
   :widths: 15, 10, 30

   "Albatross", 2.99, "On a stick!"
   "Crunchy Frog", 1.49, "If we took the bones out, it wouldn't be crunchy, now would it?"
   "Gannet Ripple", 1.99, "On a stick!"


List Table:

.. list-table:: Title
   :widths: 25 25 50
   :header-rows: 1

   * - Heading row 1, column 1
     - Heading row 1, column 2
     - Heading row 1, column 3
   * - Row 1, column 1
     -
     - Row 1, column 3
   * - Row 2, column 1
     - Row 2, column 2
     - Row 2, column 3


.. DANGER::
   Beware killer rabbits!

.. note::
   Beware killer rabbits!

`google link <https://google.co.kr>`_

See the Python_ home page for info.

`Write to me`_ with your questions.

.. _Python: http://www.python.org 
.. _Write to me: jdoe@example.com


.. _my-reference-label:

Section to cross-reference
--------------------------

This is the text of the section.

It refers to the section itself, see :ref:`my-reference-label`.



Lorem ipsum [#f1]_ dolor sit amet ... [#f2]_

.. rubric:: Footnotes

.. [#f1] Text of the first footnote.
.. [#f2] Text of the second footnote.


Lorem ipsum [Ref]_ dolor sit amet.

.. [Ref] Book or article reference, URL or whatever.


Autonumbered footnotes are
possible, like using [#]_ and [#]_.

.. [#] This is the first one.
.. [#] This is the second one.

They may be assigned 'autonumber
labels' - for instance,
[#fourth]_ and [#third]_.

.. [#third] a.k.a. third_

.. [#fourth] a.k.a. fourth_


Auto-symbol footnotes are also
possible, like this: [*]_ and [*]_.

.. [*] This is the first one.
.. [*] This is the second one.

This is climbing jpg
------------------------------------

.. image:: climb.jpg

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
