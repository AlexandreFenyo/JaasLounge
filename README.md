
Building from the sources:

    mvn install -Dhttps.protocols=TLSv1.2

I've added the following to this fork:
- This fork has a local version of the artifact jcifs-ext-0.9.4-patched.jar, that is not on Maven Central.
- This fork does only build the tomcat JAAS login module.

A. Fenyo
