Test for Android Annotations for IntelliJ IDEA

This explores configuring and Android project with Android Annotations for IntelliJ IDEA and Gradle.

Currently the annotation processing is added manually to IDEA, as incorporating both API and implemenetation dependencies in the build causes it to fail as both contains the same set of annotations.

I imagine that we can either configure Gradle to apply annotation processing to build and customize IDEA XML to enable annotation processing in the IDEA, or modify the Android Annotations JARs to not duplicate the annotations.  I do understand that this was done in order for us to point to the implementation JAR in our IDEs and have complete annotation processing, but this can be done by simply providing the current implementation JAR as a "complete" JAR.

In the meantime, refer to project-settings-guide.png as a reference to configuring annotation processing in IDEA.
