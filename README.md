# Aron maven

Apache maven with some additions:

- settings.xml 
- toolchains.xml
- bash-completion
 
Packaged into an rpm. 

To update with a new upstream version:
* Change the maven.version property
* Change the project version to match
* Update the obsoletes directive if needed
* Do a release

## Project Version visavi maven version

The first part of the the project version is the same as the property that controls upstream maven version. 
The buildNumber property comes next and represents the version of the additions described above. 
This is inteded to make the pom file and the resulting rpm's have the same version. 
