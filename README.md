# Tinkar Starter Reasoned

This is the current process for generated a reasoned data artifact.  The output of the tinkar-starter project needs to be imported into KOMET.  Then 
it needs to run the reasoner on it.  Then it needs to be stored into this repo as the data file, which can be shipped to maven central using
the release and sign workflow.  The goal is to replace this with an automated process, which runs the ikm-reasoner on the data automatically using
tinkar-core.
