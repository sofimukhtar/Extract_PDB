# Extract_PDB
A bash script to extract PDB files using PDB codes
Steps to execute:
    1. Download batch_download.sh into directory
    2. Extract pdb codes or PDB IDS (4 letter) into a text file. Each pdb code must be seperated by a comma
        2.1 if you need to extract pdb codes from fasta file of protein sequences. get the python 
                script at :** https://github.com/sofimukhtar/Python_snippets_for_bioinformatics.git**
    3. open the terminal and run : **./batch_download.sh -f pdb_codes_file.txt -p**
