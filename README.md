# neurobox-packages
This repository supplies [ughub](https://github.com/UG4/ughub)
with information on UG4 plugins (and apps) involved in NeuroBox.

To add the sources for these plugins (and apps) to your UG4 installation, use
```
ughub addsource neurobox https://github.com/NeuroBox3D/neurobox-packages.git
```
You should then be able to list the available NeuroBox plugins (and apps) with
```
ughub list neurobox
```
and install one of them using
```
ughub install <plugin name>
```
All dependencies will also be installed / updated to the most recent version.
