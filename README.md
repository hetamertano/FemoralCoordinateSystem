# FemoralCoordinateSystem
MATLAB function for the automatic identification of femoral landmarks, axes, planes and bone coordinate systems using a 3D surface model.

## How to cite
### Publication
Fischer, M. C. M. *et al.* A robust method for automatic identification of femoral landmarks, axes, planes and bone coordinate systems using surface models. *Sci. Rep.* **10**, 20859; [![10.1038/s41598-020-77479-z](https://img.shields.io/badge/DOI-10.1038/s41598--020--77479--z-gree.svg)](https://doi.org/10.1038/s41598-020-77479-z) (2020).

### Releases
- v2.0.0 [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4280957.svg)](https://doi.org/10.5281/zenodo.4280957) was used in [![10.1038/s41598-020-77479-z](https://img.shields.io/badge/DOI-10.1038/s41598--020--77479--z-gree.svg)](https://doi.org/10.1038/s41598-020-77479-z)

## Example of use 
Clone with the recursive option to get the submodules and run *automaticFemoralCS_example.m* in MATLAB.<br/>
![FCS](https://user-images.githubusercontent.com/43516130/99557046-882d5a80-29c2-11eb-8a3d-27e3d4ddf3fa.jpg)

## Input requirements
The mesh quality of the surface representation of the femur should be similar to the cases from https://github.com/MCM-Fischer/VSDFullBodyBoneModels used in the example above.

This means the mesh should: 
- consist only of one component; and
- have a closed outer surface without holes or tunnels; and
- have no duplicate, non-manifold and unreferenced vertices; and
- have no boundary, non-manifold and conflictingly oriented edges; and
- have no duplicate and degenerated faces.

More information regarding the meshing process can be found in: <br/>
Fischer, M. C. M. Database of segmentations and surface models of bones of the entire lower body created from cadaver CT scans. *Sci. Data* **10**, 763; [![10.1038/s41597-023-02669-z](https://img.shields.io/badge/DOI-10.1038/s41597--023--02669--z-green.svg)](https://doi.org/10.1038/s41597-023-02669-z) (2023).

## License
[![License: EUPL v1.2](https://img.shields.io/badge/License-EUPL_v1.2-orange.svg)](https://eupl.eu/1.2/en/)