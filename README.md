
Building from the sources:

    mvn install -Dhttps.protocols=TLSv1.2

I've changed the following, with this fork:
- this fork has a local version of the artifact jcifs-ext-0.9.4-patched.jar in the master branch, that is needed to build the package but is not on Maven Central;
- this fork does only build the tomcat JAAS login module.

Note that the jcifs-ext artifact is available on SourceForge **and** in the branch named `jcifs-ext-0.9.4-patch` in the original repository from Serli and in this repository.

Directories:
- archive: local version of jcif-ext;
- libraries: jar files built from the sources.

A. Fenyo
