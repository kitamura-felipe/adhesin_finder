# adhesin_finder
Compiled binaries for SPAAN.

## Introduction

SPAAN is a software program for prediction of adhesins and adhesin-like proteins using neural networks.

This repo is a compiled version of SPAAN (compiled in Ubuntu 14.04, but also tested in 16 and 18). 

If you use SPAAN, please cite the original authors:

SPAAN: a software program for prediction of adhesins and adhesin-like proteins using neural networks 
Gaurav Sachdeva  Kaushal Kumar  Preti Jain  Srinivasan Ramachandran
Bioinformatics, Volume 21, Issue 4, 15 February 2005, Pages 483–491, https://doi.org/10.1093/bioinformatics/bti028

## Instructions

You may use adhesin_finder in two ways:

  A. Telegram App interface:
    1. Download Telegram App
    2. Register your phone number
    3. Add "adhesin_finder_bot" to your contacts.
    4. Send a FASTA file to the bot.
    5. Wait a few seconds.
    6. Download the "query.out" file. This is the file with the results.
    
  B. Command-line in unix based OS:
    1. Clone this repo.
    2. Put your protein sequence in a file named "query.dat", inside the SPANN root folder. THis should be a FASTA format.
    3. Run: "./askquery"
    4. After a few seconds, your result will be in the "query.out" file.
    
## Troubleshooting

MAke sure your yout FASTA file has only linefeed characters and NO carriage return character.
