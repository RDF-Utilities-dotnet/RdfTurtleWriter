*.snk
=====
This directory contains the community key that is used to sign the release versions of assemblies belonging to this project.

This key has been added to the repository not to undermine security of the signed assemblies, but to enable developers to compile and use a modified version of any of the libraries from this project without having to recompile all dependent assemblies that should use the modified assembly.

apikeys.template.xml
====================
This is a template for a file that stores your personal API keys for a variety of sites. These are used by the release scripts.