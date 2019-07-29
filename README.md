<h1>Analysis of Protein Complexes and Ovarian Cancer</h1>
This directory includes code and files for the analysis of the role of disrupted protein complexes in ovarian cancer.

<h2>Jupyter Notebooks</h2>

<h3>Analysis_Functions.ipynb</h3> Analysis and plotting functions used in other notebooks. Includes data and package
imports, functions involved in performing statistical tests on ratios within protein complexes, and visualization functions.

<h3>Ratio_Analysis.ipynb</h3> Broad analysis of differences in mean ratios and variance for all protein complexes. Includes
some work on searching for mutations in proteins within each complex and/or mutations in proteins involved in transcriptional
regulation.

<h3>Interesting_Complexes.ipynb</h3> Brief explanations of how various complexes might be involved in ovarian cancer,
including references to publications, plots, and summaries of what our analyses revealed.

<h3>Clean_Dataset.ipynb</h3> The code used to clean up the original dataset to prepare it for analysis, including selecting
the correct rows/columns, splitting up combined rows, and querying Uniprot to map Uniprot IDs to gene names.

<h2>Data Files</h2>

<h3>proteinGroups_cleaned.txt</h3> Output of Clean_Dataset.ipynb. This is the file we used in our analyses, and contains
proteomics data for both tumor and normal samples, some of which are matched.

<h3>proteinGroups_simplified.txt</h3> The original data file, before it was cleaned up.

<h3>allComplexes.txt</h3> Data about protein complexes downloaded from CORUM (http://mips.helmholtz-muenchen.de/corum/#download)

<h3>trrust_rawdata.human.tsv.txt</h3> Data on transcription factors and their target genes downloaded from TRRUST v.2 
(https://www.grnpedia.org/trrust/downloadnetwork.php)
