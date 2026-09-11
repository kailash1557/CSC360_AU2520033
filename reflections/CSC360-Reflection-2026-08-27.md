# CSC360 Reflection — 27/08/2026

This session continued from where we left off with the build system, focusing on the Maven lifecycle and going deeper into pom.xml. We covered the install command, which builds a jar file and stores it in the local repository so it can be reused later without needing to rebuild or redownload it. Package pulls in the required dependencies from the Apache repository over the web, and deploy is used to publish a finished program to a repository so other developers can access it.

We also spent time on unit testing with JUnit. Unlike manual testing, which is limited to checking certain outcomes by hand, JUnit lets us write test code that verifies smaller individual units of the program, making the overall testing process far more accurate and detailed.

On the JavaFX side, we learned that it ships as a single version to keep all of its artifacts easier to manage together. Within that, javafx-controls covers standard GUI elements like buttons, fxml provides a way to define layout structure separately from code, javafx-web handles browser related functionality, and javafx-media deals with audio and video.

Finally we touched on character encoding, comparing UTF-8, UTF-16, and ASCII. Even though UTF-8 is more modern and widely used, ASCII still shows up in certain programs since it takes up less memory per character, which can make a program noticeably more efficient when full Unicode support isn't needed.
