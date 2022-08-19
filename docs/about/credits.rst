.. _credits:

Credits
===============================================================================

ProDy makes use of the following great software:

pyparsing_ is used to define the sophisticated atom selection grammar.
This makes every user a power user by enabling fast access to and
easy handling of atomic data via simple selection statements.

Biopython_ KDTree package and TreeConstruction module, which are distributed ProDy,
significantly enrich and improve the ProDy user experience.  KDtree package
allows for fast distance based selections making atom selections suitable for
contact identification.  TreeConstruction module enables the calculation of phylogenetic trees.

ProDy requires NumPy_ for almost all major functionality including, but not
limited to, storing atomic data and performing normal mode calculations.
The power and speed of NumPy makes ProDy suitable for interactive and
high-throughput structural analysis.

CEalign is distributed with ProDy. The original CE method was developed by 
Ilya Shindyalov and Philip Bourne. The Python version which is used by ProDy 
is developed by Jason Vertrees and available under the New BSD license. 

Finally, ProDy can benefit from SciPy_ and Matplotlib_ packages.  SciPy
makes ProDy normal calculations more flexible and on low memory machines
possible.  Matplotlib allows greatly enriches user experience by allowing
plotting protein dynamics data calculated using ProDy.
