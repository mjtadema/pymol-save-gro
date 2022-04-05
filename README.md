# pymol-save-gro
Save gro files from within PyMOL

## Usage:
Run save_gro.py from within PyMOL.
The original save command extension will be overwritten.
If the filename suffix is anything but ".gro", the original save api will be used.

## Example:
`save file [,(selection) [,state [,format]] ]`
