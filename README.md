# DNanoBaseCasDevSy
This repository is created for source code and file back-up of the project `DNanoBaseCasDevSy`.

# Five Key Node
1. Origami buliding.
2. Flurescence probe binding and 
3. GFP-Cas-Origami complex construction.
4. EM and electronphoresis structure verification.
5. HDR and NHEJ measure.

## 2021/11/10
### Digest
Used Bathe Lab TALOS（lcbb/TALOS: Designer scaffolded DNA 6HB-based wireframe nanoparticles (github.com)）design a simple icosahedron wireframe structure.

The files are stored in the folder named `Icosahedron_6HB_42bp_Mitered`.
### Discussion
TALOS cannot generate  a wireframe structure with radial line, and the sequences it gives often have a great length up to 9000 bp, so the manual adjustment to the sequences is needed.
### Generation Parameters of the Structure
1. Geometry
     * Geometric name                    : 05_Icosahedron
     * Geometric file type               : primitive
     * The number of faces               : 20
     * The number of points              : 12
2. Cross-section information           : 30
     * The number of duplexes            : 6
     * The number of rows                : 3
     * The number of columns             : 2
     * Reference row                     : 1
3. Edge length min/max column          : 1 / 2
4. Design parameterse length           : 42
     * Junction modification             : opt
     * Vertex design                     : mitered vertex
     * Vertex modification               : mod2
     * Sticky-end for self connection    : off
     * Unpaired scffold nucleotides      : on
     * The number of bases in Tn         : depending on distance
     * Distance btw phosphate groups     : .420
     * Starting base pair ID             : 14
     * Axial rise distance [nm]          : .340
     * Radius of helix [nm]              : 1.000
     * The Gap between helixes           : .250
     * Angle of minor groove             : 150.000
     * Angle correction factor           : .000
     * Gap between two scaf xovers       : 3
     * Gap between xover(stap) and bound : 6
     * Gap between stap and scaf xovers  : 6
     * Gap between xover and first nick  : 10
     * Gap between xover and nick        : 3
     * Staple cutting method             : max
     * Non-circular stap by single xover : off
     * Minimum # of bases in scaf strand : infinite
     * Minimum # of bases in stap strand : 20
     * Midium # of bases in stap strand  : 40
     * Maximum # of bases in stap strand : 60

## 2021/11/20
Reconstitute the file tree and upload the manual sequences and structures.


