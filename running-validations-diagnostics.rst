================
Running validations and diagnostics
================

The Microdata Management Toolkit includes a useful series of diagnostic and validation modules (see the drop down menu Tools): these range from very simple validations (such as the Tools-Validate Metadata) to complex visual displays that iterate through each variable and provides feedback to the archivist at the variable level. 

*	*Validate Metadata*: verifies that all mandatory fields are filled in.
*	*Validate External Resources*: verifies all mandatory fields in the External Resources are filled in.
*	*DDI Diagnostic*: this provides a visual display and issues warnings if DDI elements are missing. It also displays information at the file level and identifies any variables with missing labels, discrete variables with missing value or code label, variables with the same name or frequency displays with more than 30 modalities.
*	*DDI Diagnostic Detailed*: this provides a more in-depth display as the simpler DDI diagnostic (above). It checks the metadata at the individual variable level and checks: labelling, definitions, universe, source etc. 
*	*Dublin Core diagnostic*: Checks the metadata provided for the External Resources.

In addition to these validations, it is recommended that you generate the DDI document (in the Toolkit, use the Export DDI” command) and verify the size of the resulting [.xml] file. A fully documented survey with a large number of variables should not produce a file larger than 10Mb. Very large DDI files often indicate errors in the selection of summary statistics (for example, frequencies are produced for a variable like the household ID in a sample household file).
