# DH2016

This repository contains the documents that will be edited during the CTS Workshop at the DH 2016 Conference in Krakow.

The steps to make these texts [CapiTainS](https://capitains.github.io) compliant are:

    Rename the files (ger0001.ger001.opp-{ger,fre}1.xml)
    Create Repository structure (data/ger0001/ger001/)
    Run HookTests
    Create the __cts__.xml metadata file for the text group ger0001
    Run HookTests
    Create the __cts__.xml metadata file for the work group ger001
    Run HookTests
    Add URN to ger0001.ger001.opp-ger1.xml
    Run HookTests
    Add line numbers
    Add refsDecl
    Run HookTests
    Check out Nemo!

The finished texts and repository structure will be added after the workshop is finished.

## CapiTainS Software 

- [Nautilus](https://github.com/Capitains/Nautilus) is a python based CTS API using XML TEI files following CapiTainS guidelines
- [Nemo](https://github.com/Capitains/flask-capitains-nemo) is a user interface, starting to grow as a CMS (Content Manager System) which reads its core data from standard CTS API calls (and so is compliant with any standard CTS API normally) and is starting, as of the beta of 1.0.0, to accept annotation resources such as treebank and images
in the form of plugins
- [Hooktest](https://github.com/Capitains/hooktest) is a software developed to make unit tests on XML repository regarding CapiTainS Complances
