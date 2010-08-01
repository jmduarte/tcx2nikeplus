Development/Build Prerequisites
===============================
*nix system  
java sdk  
apache ant  


Directory Setup
===============
Name the directory containing this file "git" and put it in what you want to be the root of the project.  
 - In my setup this README is located at ~/projects/tcx2nikeplus/git/README.md


Building
========
From the project root run  
`ant -f git/build/build.xml`

This will build everything, you can call other ant targets if you want to be more specific.


Running
=======
After building, files are generated in dist/app/bin for conversion/upload on the command-line and a war is generated if you wish to deploy as a webapp.
