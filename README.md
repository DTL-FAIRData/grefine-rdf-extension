# OpenRefine RDF extension
This project adds a graphical user interface(GUI) for exporting data of Open Refine projects in RDF format. The export is based on mapping the data to a template graph using the GUI.

## Install
- Follow the installation instructions for the [openrefine-maven-shim](https://github.com/DTL-FAIRData/openrefine-maven-shim#usage) project
- Clone this repository to your local machine
- Run `mvn clean compile` and `mvn assembly:single`
- Unpack the zip file in `target` to your `openrefine/extensions` folder