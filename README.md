# examNord
This is a package with Rmarkdown template for producing Exam tasks.
The usage of template ensures a compliance with requirements as they are in Spring 2018.

To use package, it should be installed with. Before installation, download a full folder "examNord" in a location, its full path you know.

# Installation


1.  if "examNord" is downloaded in the working directory):

`devtools::install("examNord")`

2.  any other location:

`devtools::install("<full path>/examNord")`

# To use

After the installation, this package needs to be loaded:

`library("examNord", lib.loc="<local_library_location>")`



When creating a new Rmarkdown, choose an option *"From Template"* and select the one with name *"Exam tasks at Nord University"*.

If package `"examNord"` is loaded, but there is no mentioned template in the list, restart R session.
