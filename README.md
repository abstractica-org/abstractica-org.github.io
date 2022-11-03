# abstractica github overview

## From java to OpenSCAD
OpenSCAD is a great tool for constructive solid geometry (CSG) from a programmers perspective. But the language lacks the ease of use from a modern IDE like IntelliJ, Netbeans or Eclipse and it does not support OOP.

[JavaOpenSCAD](https://github.com/abstractica-org/JavaOpenSCAD) is a project that exposes the core functionality of OpenSCAD to java. This project is ment to be the lowest level wrapper for the functionality needed to do CSG.
It outputs files in the .scad format, that can be viewed in OpenSCAD. OpenSCAD automatically reloads the file if it changes, so this gives a nice workflow.

JavaOpenSCAD will soon be relased in version 1.0

### Work in progress

[JavaCSG](https://github.com/abstractica-org/JavaOpenSCAD) is a layer on top of [JavaOpenSCAD](https://github.com/abstractica-org/JavaOpenSCAD) that extends the basic functionality with shapes and helper functions. It does not mimic OpenSCAD, but instead tries to give a flexible and easy way to work with CSG through a java interface. 

JavaCSG is still work in progress...

[Java3DPrint](https://github.com/abstractica-org/Java3DPrint) is a layer on top of [JavaCSG](https://github.com/abstractica-org/JavaOpenSCAD), that are used to create geometry suited for 3D print. It deals with tolerences in objects, that can change between different 3D printers. This way you can make a 3D printer profile for different printers and generate the geometry with these different profiles.

Java3DPrint is still work in progress...

[OpenBuildSystem](https://github.com/abstractica-org/OpenBuildSystem) is a project on top of [Java3DPrint](https://github.com/abstractica-org/Java3DPrint) that aims to create a building system for 3D printed parts that fits together and can be used to build almost anything.

OpenBuildSystem is still work in progress...

<!--
## Digital dna
Digital dna is an experiment to represent data in an abstract, structured, flexible and efficient format consisting of four base values instead of the normal two binary values. The four values are BEGIN, END, TRUE and FALSE. This way data is represented as a tree and can travesed in a flexible way.
-->
