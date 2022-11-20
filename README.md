# Install
```
pip install Ezclient
```

Warning:

from pip you will download the corresponding .whl file according to your OS and python version.
All the .whl files have been created from the compilation of C code. The files on pypi have been compiled
for the x86_64 architecture with the extensions "-mavx2". So, if you have a pentium for example
or a processor that does not support the extension avx2 you can find in the github repo in the releases
the different .whl files with: no extensions, sse extension, sse2 extension, avx extension.

# Import the library in python

```
import ezclient
```

# Ezclient supports

- Version: 1.1.1

 - [x] Ez-spark client tunneling protocol
 - [x] 3.6 <= python < 3.11
 - [x] MacOS, Linux, Windows
 
