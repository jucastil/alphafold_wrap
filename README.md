# alphafold_wrap
A bash wrap over the alphafold docker

- alphafold_setup

alphafold_setup -u

: updates the existing alphafold install on the "alphafold" folder.
Useful to update the docker definition

- alphafold_run

alphafold_run --f sapiens.FASTA --t 2021-08-11 --o results

: command-line run (only monomer configuration, only ask for confirmation)
Useful to run without too many questions

- alphafold_monitor

: starts a background process to monitor your docker.
If it works you will get an email after the docker is done.

- alphafold_complete

alphafold_complete
: Uploading result to web (not sure it's OK yet)

alphafold_complete --c
: Fixes ownership issues on the results folder

alphafold_complete --m
: Manual data upload
