<h1 align=center>
  <a href=https://www.itqb.unl.pt/labs/multiscale-modeling>
    <img src="https://raw.githubusercontent.com/MeloLab/mml-assets/main/logo_title.svg"
         alt="Multiscale Modeling Lab logo" width="128">
  </a>
</h1>

Martini 3 Steroid Hormone Parameters
======================================================================

This is the [Melo Lab](https://www.itqb.unl.pt/labs/multiscale-modeling)'s
development repository for Martini 3 steroid hormone parameters.

The `main` branch holds stable topology versions. Beware that any other branch
may hold in-development parameters.

If you use these models, be sure to cite:

>T.Z. Madaloz, K. dos Santos, F. Mustan, F. Neiva Nunes, G. Razzera, M.N. Melo
>
>**Martini 3 Coarse-Grained Models for Steroid Hormones**
>
>J. Chem. Info. Model. 2026 [doi:10.1021/acs.jcim.6c03293](https://doi.org/10.1021/acs.jcim.6c03293)
>
>(Preprint initially at [doi:10.26434/chemrxiv.15002998](https://chemrxiv.org/doi/full/10.26434/chemrxiv.15002998))

## Parameterized molecules and included data

<img src="./hormones.svg">

The `martini_v3.0.0_steroid_hormones_v1.itp` file contains the topologies, in
GROMACS format, for the parameterized hormones.

Each hormone's directory includes the respective mapping index file,
the atomistic cholesterol-aligned structures, their CG-mapped counterparts
and a final CG structure (with added dummy frame particles for the cases that
require them). An exception is 11-deoxycortisol (dHCY), for which no
PDB-deposited structures were available, and which was parameterized based
solely on bead analogy with other hormones. Only the final structure is
available in that case.

## License

<pre><code>
Copyright 2026 Universidade Nova de Lisboa 

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
</code></pre>

The full text of the license is available in the source repository.
