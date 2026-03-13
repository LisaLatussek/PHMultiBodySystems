[![arXiv](https://img.shields.io/badge/arXiv-2512.19408-b31b1b.svg)](https://arxiv.org/abs/2512.19408)
[![DOI](https://zenodo.org/badge/1178606555.svg)](https://doi.org/10.5281/zenodo.18998378)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

# `PHMultiBodySystems`

This repository contains the simulation results of the paper
_Latussek, L., Kinon, P. L., & Betsch, P. (2026): 
Port-Hamiltonian multibody dynamics:
Lagrangian formulation, consistent interconnection, structure-preserving simulation and index-reduction_ .
<!-- [Port-Hamiltonian multibody dynamics:
Lagrangian formulation, consistent interconnection, structure-preserving simulation and index-reduction](url_arxiv)_ . -->
This repository is licensed under the [MIT License][url_license].

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li><a href="#citation">Citation</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#references">References</a></li>
  </ol>
</details>

## Citation

If you found our work helpful and you have used it in your academic work, please cite it as:

```bibtex
@misc{latussek_kinon_betsch_2026,
  title         = {Port-Hamiltonian multibody dynamics: Lagrangian formulation, consistent interconnection, structure-preserving simulation and index-reduction},
  author        = {L. Latussek and P. L. Kinon and P. Betsch},
  year          = {2026},
  eprint        = {2512.19408},
  archiveprefix = {arXiv},
  primaryclass  = {math.NA},
  url           = {https://arxiv.org/abs/2512.19408}
}
```
see also the [CITATION.bib](CITATION.bib) file for download.


## Usage

The implementation has been done in the open-source code base [`pydykit`][pydykit_repo]. The results are documented here for reproducibility and verification purposes.

1. [Clone][url_how_to_clone] this repository to your machine.
2. Open a terminal and navigate to your local clone.
3. Extract your desired result data as `.csv`-file data from the [results folder](results). This folder contains subfolders for each experiment documented in the manuscript.
4. Use your favorite plotting tool to visualize the data.

## References
In the manuscript, we compare our formulation to two other approaches from the literature: [Masoudi][url_masoudi_2025] and [Zhou et al. (2022)][doi_zhou_etal_2022]. The data are included in [this file](results/example_03_slider_crank/slider_crank_h001_incl_reference_results.csv) for your convenience. Please cite those works appropriately if you use the data.

[pydykit_repo]: https://github.com/pydykit/pydykit
[url_license]: LICENSE
[url_how_to_clone]: https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository
[url_masoudi_2025]: https://www.iftomm-multibody.org/benchmark/problem/Spatial_rigid_slider-crank_mechanism/
[doi_zhou_etal_2022]: 
https://doi.org/10.1007/s11044-022-09825-0
