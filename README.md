# PythonTools
Scripts for NGS processing

Download_FTP_ENA.py

Usage:
1. Search the project in ENA to get the information page of one study.  
2. Click "Read Files" tag next to "Navigation".  
3. Download the TEXT file (save as ENA_description.txt).  
4. Write the shell scripts to download fastq files (The master shell submit downloding jobs to one queue on clusters).  
python2.7 Download_FTP_ENA.py  ./  ENA_description.txt  

./ : is the current directory and can changed into the directoy to store th fastq files.  