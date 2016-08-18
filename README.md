# Build Tools

Docker image with build tools I use.

## Tags

* jdk\<n>-latest
* jdk\<n>-\<version>

_n_ - Indicates the installed jdk version
_version_ - Indicates specific version of this image. In order to know
which tools are installed in a given tag, find the corresponding
tag in the repository and check the README file.

##Tools

* JDK 7 (v1.7.0_111)
* Rake (v10.3.2)
* Leiningen (v2.6.1)
* App Engine SDK (v1.9.42) (available only on jdk7 tags)