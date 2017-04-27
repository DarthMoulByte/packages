# packages
This repository contains the customizations to packages needed to port them to i686 and/or our environment, as well as other package related informations.

* There are subdirectories `repository/package` which contain new packages and customizations for existent packages to compile for i6868 or adopt to our environment.
In case, the files therein exist in the respective original package, their content is appended to the respective original package files.
* The file `blacklist` containes a list of packages which won't be build for i686 (because they can't be build for or are useless on i686).
