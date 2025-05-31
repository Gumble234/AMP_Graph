generated_graphs: The generated graphs

AMP1000.csv: Contains 100 AMP data entries, but there are issues with missing/irregular IDs

ESM_2.py: Uses ESM2 to perform embedding on sequences

Fasta_trans.py: Converts the CSV file into FASTA format and fixes the ID discontinuity issue

GVAE.py: The GVAE model

construct_graph.py: Uses the embedding data as node features and combines it with an adjacency matrix to convert the data into graphs

distance.py: Calculates the distances between alpha carbon atoms in PDB files

loss_plot.png: Loss function plot of the model

output_AMP1000.fasta: The data after conversion

processed_AMP1000_data.csv: The data with fixed ID discontinuities

run_ESMfold.py: Uses ESMFold to convert sequences into PDB files and extract spatial structure information
