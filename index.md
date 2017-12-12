---
layout: default
---

<div class="twocolumn">
<div class="column" markdown="1">
# Overview
This website contains a number of N-body simulation data products
from the Abacus project, including halos catalogs, particle subsamples, power spectra,
and initial conditions. Each of these data products is described in
[Data Specifications]({{ site.baseurl }}{% link data_specifications.md %});
the simulations are described in [Simulations]({{ site.baseurl }}{% link simulations.md %}).

# Problems?
If you encounter any problems with the catalogs, please
[file an issue on Github](https://github.com/lgarrison/AbacusCosmos/issues). Also be sure to check the
[Data Specifications]({{ site.baseurl }}{% link data_specifications.md %}), as your issue may be covered there.
If your question is related to loading the catalogs, the [Code Examples]({{ site.baseurl }}{% link code.md %})
may also be helpful.

# About
The Abacus Cosmos suite was run by [Lehman Garrison](http://lgarrison.github.io/) on the GPU nodes of the University of Arizona's
[El Gato super computer](http://elgato.arizona.edu/) using the new N-body code Abacus.  Abacus is written by Doug Ferrer, Lehman Garrison,
Daniel Eisenstein, Marc Metchnik, and Phil Pinto.  See the [Papers]({{ site.baseurl }}{% link papers.md %}) for more information.
</div>

<div class="column">
<figure>
<img src="{{ site.baseurl }}{% link abacus_slice.png %}" alt="abacus slice"/>
<figcaption markdown="1">
A slice through an Abacus simulation box at \\(z=1.0\\) rendered with the [Gotetra code](https://github.com/phil-mansfield/gotetra).  The slice is \\(125 \mathrm{~Mpc}/h\\) \\(\times\\) \\(125 \mathrm{~Mpc}/h\\) \\(\times\\) \\(12.5 \mathrm{~Mpc}/h\\).
</figcaption>
</figure>
</div>
</div>