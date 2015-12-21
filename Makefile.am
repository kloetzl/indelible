bin_PROGRAMS= indelible
indelible_SOURCES= src/indelible.cpp
indelible_CPPFLAGS= -Isrc

dist_man_MANS= indelible.1

# The following files are #included by indelible.cpp
EXTRA_indelible_SOURCES= src/control.cpp src/models.cpp src/paml.cpp src/randoms.cpp src/MersenneTwister.h

nobase_dist_html_DATA= help/index.html help/examples.shtml help/manual.shtml \
	help/example_files/AMINOACID.shtml help/example_files/basicaminoacid.shtml \
	help/example_files/basiccodon.shtml help/example_files/basicnucleotide.shtml \
	help/example_files/basic.shtml help/example_files/branch2.shtml \
	help/example_files/branch.shtml help/example_files/codon_RATES.txt \
	help/example_files/CODON.shtml help/example_files/CODONsites.shtml \
	help/example_files/indels.shtml help/example_files/multi-partitions.shtml \
	help/example_files/mylengthmodel.txt help/example_files/nucleotide-branch.shtml \
	help/example_files/nucleotide_RATES.txt help/example_files/NUCLEOTIDE.shtml \
	help/example_files/random_branch_length_trees.JPG \
	help/example_files/rates.shtml help/example_files/settings.shtml \
	help/example_files/sitebranch.shtml help/example_files/trees.shtml \
	help/example_files/trees.txt help/example_files/userAAmodel.txt \
	help/manual_files/branches.shtml help/manual_files/codon_RATES.txt \
	help/manual_files/evolve.shtml help/manual_files/model.shtml \
	help/manual_files/mylengthmodel.txt help/manual_files/nucleotide_RATES.txt \
	help/manual_files/partitions.shtml \
	help/manual_files/random_branch_length_trees.JPG \
	help/manual_files/settings.shtml help/manual_files/symQmatrix.gif \
	help/manual_files/tree.shtml help/manual_files/trees.txt \
	help/manual_files/type.shtml help/manual_files/userAAmodel.txt
