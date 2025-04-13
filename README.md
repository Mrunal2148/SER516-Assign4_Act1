# SER516 ASU Assignment 4 GitHub Actions
Name - Mrunal Kapure
ASURITE - mkapure
SER516 Assignment 4 Activity 1

Note -
In Assignment 4 task 4, 
We have been asked to add below code in build.gradle

tasks.register('testFast', Test) {
    useJUnitPlatform() //
    testClassesDirs = sourceSets.test.output.classesDirs
    classpath = sourceSets.test.runtimeClasspath
    filter {
        includeTestsMatching 'edu.asu.amexgi.rest.grocery.controllers.GroceryApi2ApplicationTests'
    }
}

but the relative path of the java file is -
edu.asu.assign.rest.grocery.controllers.GroceryApi2ApplicationTests