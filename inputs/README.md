# microMegas input files

The three input files that define a microMegas (mM) run, as edited for this practical.
They replace the files of the same name in the `in/` directory of a standard mM installation.

| File | Role | Changes from the mM example files |
|---|---|---|
| `Cu` | Material parameters for FCC copper | Shear modulus, Poisson ratio and reference glide direction |
| `ContCu` | Control parameters | Constant-stress mode (`Mode_deformation = 4`), resolved shear stress on the highest-Schmid-factor system, initial stress, number of steps |
| `SegCu` | Initial dislocation configuration | A single pinned segment (Frank-Read source) instead of the random source population of the example |

The files are in the state of the last run of the practical. Stress level, segment length and
segment orientation were varied between tasks as described in
[`frank_read_source_Cu.ipynb`](../frank_read_source_Cu.ipynb).

microMegas itself is not included here. It is distributed under the GNU GPL v2 by its authors;
see the [mM project page](http://zig.onera.fr/mm_home_page/).
