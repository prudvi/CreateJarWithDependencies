# Compile Source code with depencies
java -cp json.jsar:[other depencies] MyFile.java
# Manifest.txt has to be created by ourself, other jar creation will autotake manifest.txt
# create a jar file with class file, Manifest.txt and dependecy.jar []
jar cfm myjar.jar Manifest.txt MyFile.class json.jsar:[other depencies]
# Execute Jar File
Java -cp myjar.jar className [cmdLine Args]
