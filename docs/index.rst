.. AstroLib.jl documentation master file, created by
   sphinx-quickstart on Tue Mar 15 12:20:54 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

AstroLib.jl
=======================================

`AstroLib.jl <https://github.com/giordano/AstroLib.jl>`__ is a
package of small generic routines useful above all in astronomical and
astrophysical context, written in `Julia <http://julialang.org/>`__.

Included are also translations of some `IDL Astronomy User's
Library <http://idlastro.gsfc.nasa.gov/homepage.html>`__ procedures,
which are released under terms of `BSD-2-Clause
License <http://idlastro.gsfc.nasa.gov/idlfaq.html#A14>`__.
``AstroLib.jl``'s functions are not drop-in replacement of those
procedures, Julia standard data types are often used (e.g., ``DateTime``
type instead of generic string for dates) and the syntax may slightly
differ.

Every function provided has detailed documentation that can be
`accessed <http://docs.julialang.org/en/stable/manual/documentation/#accessing-documentation>`__
at Julia REPL with

.. code:: julia

    julia> ?FunctionName

or with

.. code:: julia

    julia> @doc FunctionName

In addition, an extensive error testing suite ensures old fixed bugs
will not be brought back by future changes.

Install
-------

``AstroLib.jl`` is available for Julia 0.4 and later versions, and can
be installed with `Julia built-in package
manager <http://docs.julialang.org/en/stable/manual/packages/>`__. In a
Julia session run the command

.. code:: julia

    julia> Pkg.add("AstroLib")

You may need to update your package list with ``Pkg.update()`` in order
to get the latest version of ``AstroLib.jl``.

Usage
-----

After installing the package, you can start using ``AstroLib.jl`` with

.. code:: julia

    using AstroLib

Development
-----------

``AstroLib.jl`` is developed on GitHub at
https://github.com/giordano/AstroLib.jl. You can contribute by providing
new functions, reporting bugs, and improving documentation.

Related Projects
----------------

This is not the only effort to bundle astronomical functions written in
Julia language. Other packages useful for more specific purposes are
available at https://juliaastro.github.io/.

In addition, there are similar projects for Python (`Python
AstroLib <http://www.hs.uni-hamburg.de/DE/Ins/Per/Czesla/PyA/PyA/pyaslDoc/pyasl.html>`__)
and R (`Astronomy Users
Library <http://rpackages.ianhowson.com/cran/astrolibR/>`__).

License
-------

The ``AstroLib.jl`` package is licensed under the MIT "Expat" License.
The original author is Mosè Giordano.

Notes
-----

This project is a work-in-progress, only few procedures have been
translated so far. In addition, function syntax may change from time to
time. Check
`TODO.md <https://github.com/giordano/AstroLib.jl/blob/master/TODO.md>`__
out to see how you can help. Volunteers are welcome!

Contents:

.. toctree::
   :maxdepth: 2



..
   Indices and tables
   ==================

   * :ref:`genindex`
   * :ref:`modindex`
   * :ref:`search`
