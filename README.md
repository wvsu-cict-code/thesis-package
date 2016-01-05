# Thesis Software Package Guide
WVSU Institute of Information and Communications Technology guidelines for thesis software packaging.

***

Your thesis software development files are combined into a single source tree. It should contain all the components and documentation needed to build and run the software on its target platform (Linux/Windows/OS X/Andriod/iOS/others). This document provides the specifications of what your package should contain.

### Package directories overview
A common naming scheme should also be observed. Directory names are **lowercased** and words are separated by an underscore.

```python
# Thesis package source tree
[app_name]/
    src/
    lib/
    config/
    dist/
    doc/
    README.md
    DISCLAIMER.md
```
#### Package Source Tree Description

| Node | Description |
| ---- | :---- |
| [app_name] | This is the root folder. Its name quickly identifies your thesis software. Very long directory names are not recommended. |
| src | Contains code to build your thesis software. Includes the frontend and backend(if exists) components. |
| lib | Contains the third-party libraries used by your thesis software. |
| config | This is not required but it can contain custom configuration files needed by your software to work (```*.cfg```, ```*.sql```, etc). |
| dist |Packaged release build of your thesis software ready for deployment (installers/deployment files). |
| doc | Software documentation of any kind can include your thesis software manual. |
| README.md | Contains information about the other files in your source code directory. It can also contain essential instructions on how to use or deploy your software. Please see this [example template](https://gist.github.com/jxson/1784669) as your guide|
| DISCLAIMER.md | Includes the disclaimer documentation of your thesis software. |

#### Submission
* Your thesis source code root folder should be compressed (zip, rar, tar.gz, etc)
* It should be saved on a CD or DVD disc which is enclosed in a **keep case** for submission.
* The keep case and disc cover design should include the logo of the University and Institute.

![case](case.png "case")
