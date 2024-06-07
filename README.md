[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

CaDiCaL_PriPro
===============================================================================

CaDiCaL_PriPro is a hack of CaDiCaL v1.4.0 and debuted in the SAT
Competition 2021. It introduced the novel idea of Priority Propagation
and won the "[Special Innovation
Price](https://satcompetition.github.io/2021/slides/ISC2021-fixed.pdf)"
awarded at the [SAT Competition
2021](https://satcompetition.github.io/2021/). The version available
here is the one used in the competition. A later version of
CaDiCaL_PriPro containing minor bug fixes and improvements, which served
as a basis for the publication "[Prioritised Unit Propagation by
Partitioning the Watch Lists](https://ceur-ws.org/Vol-3545/paper2.pdf)"
(for BibTex see below) on Priority Propagation, is going to be released
in the coming weeks (as of June 2024).

The binary created by the build process is still called `cadical`
despite being CaDiCaL_PriPro. Use `./configure && make` to configure
and build `cadical` and the library `libcadical.a` in the default
`build` sub-directory. The header file of the library is
[`src/cadical.hpp`](src/cadical.hpp) and includes an example for API
usage.

See [`BUILD.md`](BUILD.md) for options and more details related to the build
process and [`test/README.md`](test/README.md) for testing the library and
the solver.

The solver has the following usage `cadical [ dimacs [ proof ] ]`.
See `cadical -h` for more options.

If you want to cite CaDiCaL\_PriPro please use our publication on
Priority Propagation:

<pre>
@inproceedings{kaiser2023pripro,
  title={Prioritised Unit Propagation by Partitioning the Watch Lists},
  author={Kaiser, Benjamin and Clausecker, Robert and Mavroskoufis, Michael},
  booktitle={Proceedings of the 14th International Workshop on Pragmatics of SAT co-located with the 26th International Conference on Theory and Applications of Satisfiability Testing (SAT 2023)},
  volume={3545},
  pages={14--34},
  year={2023},
  organization={CEUR Workshop Proceedings}
}
</pre>

To additionally cite the original solver description in the [SAT
Competition 2021 proceedings](http://hdl.handle.net/10138/333647), you
may use:

<pre>
@inproceedings{kaiser2021pripro,
    author="Kaiser, Benjamin and Clausecker, Robert",
    editor="Balyo, Tom\'{a}\v{s} and Froleyks, Nils and Heule, Marijn J. H. and Järvisalo, Matti Juhani and Suda, Martin",
    title={{CleanMaple\_PriPro}, {CaDiCaL\_PriPro} and {CaDiCaL\_PriPro\_no\_bin}},
    booktitle={Proceedings of {SAT Competition 2021} : Solver and Benchmark Descriptions}, 	year="2021",
    volume={{B-2021-1}},
    series= {Department of Computer Science Report Series B},
    publisher="Department of Computer Science, University of Helsinki",
    pages="25",
}
</pre>

Benjamin Kaiser
