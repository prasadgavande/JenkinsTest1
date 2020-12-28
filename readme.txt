create Hello.java file
then to complile this file enter command as below

javac hello.java 

it will create new file named Hello.class

then to run the file
enter command as 
java Hello

it will run the problem .


next step is create jenkins job to run problem

Create new project
in build select Execute windows batch command and enter following commands there

cd D:\Installations\Jenkins\learning
javac hello.java
java Hello 

save and build now
check console. it should run


next step to add project to git and github

testing
