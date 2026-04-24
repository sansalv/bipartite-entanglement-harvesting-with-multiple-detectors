# Bipartite entanglement harvesting with multiple detectors

This repository contains Mathematica notebooks used in the numerical analysis of the paper *Bipartite entanglement harvesting with multiple Unruh–DeWitt detectors* ([arXiv:2604.13869](https://arxiv.org/abs/2604.13869)).

## Contents

- `main_analysis.nb`: Numerical study of bipartite entanglement harvesting with multiple Unruh–DeWitt detectors.
- `eigenvalue_solver.nb`: Complementary notebook for deriving closed-form expressions for the negativity in selected configurations.

## Physical context

We study bipartite entanglement harvesting from the quantum vacuum of a massless scalar field between two subsystems, each composed of a finite number of Unruh-DeWitt detectors. Using perturbation theory, we show that the leading-order negativity is fully determined by a submatrix of the reduced density matrix, with the submatrix dimension scaling only linearly with the number of detectors.

Within this framework, we analyze how the detectors' spatial arrangement influences harvesting. For all three-detector configurations and several symmetric four-detector configurations, we derive analytic expressions for the negativity and identify the configurations that maximize it. For a linear chain, we find that the harvested entanglement scales linearly with the number of detectors. These results clarify how to arrange multiple detectors to optimize harvesting and show that increasing their number broadens the ranges of energy gaps and separations over which entanglement can be extracted from the field.

## Supplementary material

Additional material supporting the analysis presented in the paper is provided in the `supplementary` folder. The following animation illustrates bipartite entanglement harvesting for a three-detector configuration with a varying energy gap.

<p align="center">
  <a href="supplementary/demo.mp4">
    <img src="supplementary/three_detectors_gaussian_animated_fast.gif" width="400">
  </a>
</p>

## Usage

Open the notebooks in Wolfram Mathematica.

## Citation

If you use these notebooks, please cite the corresponding paper:   [arXiv:2604.13869](https://arxiv.org/abs/2604.13869).

Please also cite this repository using the citation information in `CITATION.cff`.

## License

This project is licensed under the MIT License (see `LICENSE`).