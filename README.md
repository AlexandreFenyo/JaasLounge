
Building from the sources:

    mvn install -Dhttps.protocols=TLSv1.2

I've added the following to this fork:
- this fork has a local version of the artifact jcifs-ext-0.9.4-patched.jar, that is needed to build the package but that is not on Maven Central;
- this fork does only build the tomcat JAAS login module;
- the 

A. Fenyo
