# Compile Files Javac:

## Javac classA.java

•	This creates a .class file associated with the java file

•	You can also run *.java to create class files for all java files


# Run Classes Java:

## Java classA

•	Runs the classA.class file


# Run multiple class together that are in same package:

## Java classA

•	Makes sure all classes are in the same package directory

•	Makes sure all classes contain the same package name

•	Make sure you run java command from the root directory not inside the package directory

•	Make sure you are running the main class (entry point class) that class all other classes and that’s it, no linking required if all classes are in the same package

•	Create a pointer to the class you want to use

1.	Printer myPrinter = new Printer();

2.	myPrinter.myprint();

# Create Jar:

## Create Manifest & jar executable

•	Main-Class: School/HelloWorld      ***** followed by 2 spaces then save as manifest.txt******

•	jar -cvfm example.jar manifest.txt School/*.class

1.	Create

2.	Verify

3.	output file name

4.	manifest file that contains the location of your main class

5.	School/*.class all the relevant class
