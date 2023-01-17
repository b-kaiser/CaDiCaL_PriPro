[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

CaDiCaL_PriPro
===============================================================================

CaDiCaL_PriPro is a hack of CaDiCaL v1.4.0 and debuted in the SAT
Competition 2021. It introduced the novel idea of Priority Propagation.

The binary created by the build process is still called `cadical`
despite being CaDiCaL_PriPro.  Use `./configure && make` to configure
and build `cadical` and the library `libcadical.a` in the default
`build` sub-directory.  The header file of the library is
[`src/cadical.hpp`](src/cadical.hpp) and includes an example for API
usage.
  
See [`BUILD.md`](BUILD.md) for options and more details related to the build
process and [`test/README.md`](test/README.md) for testing the library and
the solver.

The solver has the following usage `cadical [ dimacs [ proof ] ]`.
See `cadical -h` for more options.

If you want to cite CaDiCaL please use the solver description in the
latest SAT competition proceedings:

<pre>
@inproceedings{BiereFazekasFleuryHeisinger-SAT-Competition-2020-solvers,
  author    = {Armin Biere and Katalin Fazekas and Mathias Fleury and Maximillian Heisinger},
  title     = {{CaDiCaL}, {Kissat}, {Paracooba}, {Plingeling} and {Treengeling} Entering the {SAT Competition 2020}},
  pages     = {51--53},
  editor    = {Tomas Balyo and Nils Froleyks and Marijn Heule and Markus Iser and Matti J{\"a}rvisalo and Martin Suda},
  booktitle = {Proc.~of {SAT Competition} 2020 -- Solver and Benchmark Descriptions},
  volume    = {B-2020-1},
  series    = {Department of Computer Science Report Series B},
  publisher = {University of Helsinki},
  year      = 2020,
}
</pre>

You might find more information on CaDiCaL at <http://fmv.jku.at/cadical>.

Armin Biere
