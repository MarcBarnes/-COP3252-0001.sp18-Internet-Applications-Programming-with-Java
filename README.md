# -COP3252-0001.sp18-Internet-Applications-Programming-with-Java
Homeworks and Final Project

EXTRACTING A JAR FILE :
From the command line
To create a jar archive from the command line, use this format for the command:
  jar -xvf <filename>.jar 
  ....jar -xvf hw2.jar

Creating a simple jar archive:

From the command line
To create a jar archive from the command line, use this format for the command:
  jar -cvf <filename>.jar <list_of_files>
where you substitute your actual filename above, and then a list of the files you want to pack up.
Example:

  jar -cvf hw2.jar Class1.java Class2.java File3.java
You can double-check the contents of the above packed jar file with this command:

  jar -tvf hw2.jar
In these commands, the c flag stands for "create", and the t flag stands for "table of contents". 
 

Creating a jar archive using Eclipse:

From the "File" menu, select "Export"
In the window that pops up, click on the + sign next to the "java" folder, then click on "JAR file", and click "Next"
On the next window, you'll be asked to select the resources to export. You can pick resources from multiple projects.
Click on the + signs next to the projects to expand the contents choices, then pick the packages that have the source code you want to pack into the jar file. If you have been using the default package selections, click on "default package" for the projects that have the source code you want to pack
Make sure the "Export Java source files and resources" button is the one selected. You can deselect the others, if all you want to pack up is source code
Use the Browse button to pick your export destination (i.e. what folder you want to put the jar archive in), and pick a name for your archive.
Click "Finish"
To check the contents of the jar file you just created
From the "File" menu, pick "Import"
In the select window that comes up, pick the "General" category, then "Archive File", and click "Next"
Use the "Browse" button to locate your jar file
The window will now show a listing of contents in the right half. Verify that it contains the files you were packing up
You can click "cancel" to get out of this window without actually unpacking the archive. Or you can click "Finish", but this will try to unpack, and it will probably ask if you want to overwrite the source code files in their original locations. You don't need to do this
