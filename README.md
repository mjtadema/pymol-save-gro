[![DOI](https://zenodo.org/badge/478109472.svg)](https://doi.org/10.5281/zenodo.15019357)

# pymol-save-gro
Save gro files from within PyMOL

## Usage:
Run save_gro.py from within PyMOL.
The original save command extension will be overwritten.
If the filename suffix is anything but ".gro", the original save api will be used.

## Example:
`save file [,(selection) [,state [,format]] ]`
