# Compile Source code with depencies
java -cp json.jsar:[other depencies] MyFile.java
# create a jar file with class file, Manifest.txt and dependecy.jae
jar cfm myjar.jar Manifest.txt MyFile.class json.jsar:[other depencies]
# Execute Jar File
Java -cp myjar,jar className [cmdLine Args]
