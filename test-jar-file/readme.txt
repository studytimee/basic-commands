--------------Command for creating execute able jar file

C:\Users\ali\test-jar-file>javac App.java

C:\Users\ali\test-jar-file>echo Main-Class: App > myManifest.txt

C:\Users\ali\test-jar-file>jar cfm exe.jar myManifest.txt App.class

This command for runing on commad line

C:\Users\ali\test-jar-file>java -jar exe.jar
Hello World!


type: jar on command line for options 