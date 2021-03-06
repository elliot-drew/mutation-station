# Mutation-Station

Try it [here](https://elliot-drew.github.io/mutation-station/).

Prepare inputs for a variety of computational mutagenesis
tools from a protein sequence or a PDB file.

* Click the amino acid buttons to toggle on/off substitutions with this amino acid

* Specify residue numbers, or leave blank to do all residues in the protein/chain.

* If you are using a PDB file, the chain is required.

* Enter sequence or upload PDB file.

* Pick the tool/website you want to generate input for.

* Download text files with results.

Variety of tools targeted:

* PolyPhen2
* SIFT
* FoldX
* Dynamut
* DeepDDG
* SDM2

Written in Javascript and HTML. PDB files uploaded and sequences submitted are never sent to a server - everything happens client side.

Uses:

* [Material Design Bootstrap](https://mdbootstrap.com/)