# OpenRefine RDF extension
This project adds a graphical user interface(GUI) for exporting data of Open Refine projects in RDF format. The export is based on mapping the data to a template graph using the GUI.

## Install
- clone the OpenRefine repository to your local machine
- in the Open Refine repository, run `refine linux_dist`
- clone this repository to your local machine
- in the rdf extension repository, run `mvn package -Dopenrefine.basedir=/path/to/OpenRefine -Dmaven.test.skip=true`
- copy the zip file in `target` to your openrefine/extensions folder