

# Java notes

 - Install JDK (Java Devlopment kit) and JRE(Java Runtime Environment) on your system first for running eclipse. Different kinds of JDK are used for different purposes, for example android JDK is used for mobile development.
 - To check which version is installed , go to command prompt and type "java -version".
 
 ## How Java works
 
 - We write our program in .java file , which is a text file. This is converted into binary file by JavaC or JDK SE(Standard edition) . Interestingly every class generates a binary class.
 - Binary class has the extension .class which is in the form of bytecode(bytecode is binary code which has instructions for JVM). Computer doesnt not yet understand the binary file so java uses JVM(Java virtual Machine) which comes along with JRE.
 - A virtual machine is used instead of the system directly because there are so many systems each with so many configurations. So in order maintain unique output no matter what kind of a machine JVM is used. JVM converts .class file into binary format which can be run directly on the computer.

