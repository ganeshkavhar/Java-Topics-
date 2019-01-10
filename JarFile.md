# Jar files

Jar (Java Archive) file is a file that contains compressed versions of .class files , audio files , image files or directories.

A *.jar* file can be considered as a *.zip* file. The difference between them is that the *.jar* file can be used as it is but the *.zip* file has to be extracted first to use it.

*.jar* file can also be extracted or unzipped.

# Creating a jar file

1. To create a *.jar* file , we have to use jar commands.
  - c:\jar cf jarfilename.jar packagename       **For windows**
  - $ jar cf jarfilename.jar packagename        **For linux**
  
cf stands for **Create file**

2. After creating, the contents can be viewed using:
  - c:\jar tf jarfilename.jar
  - $ jar tf jarfilename.jar
  
tf stands for **Table view of file**

3. When we create a *.jar* file, it automatically gets a default manifest file. 

check out manifest file at [Manifest Files](https://en.wikipedia.org/wiki/Manifest_file)

4. To extract a *.jar* file, we use
   - jar xf jarfilename.jar
   
xf stands for **Extract file**
