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

If you want to cite CaDiCaL\_PriPro please use the solver description in
the latest SAT competition proceedings:

<pre>
@inproceedings{KaiserClausecker-SAT-Competition-2020-solvers,
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
