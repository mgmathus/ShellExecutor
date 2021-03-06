Shell Executor
==============

###### [![Dorkbox](https://badge.dorkbox.com/dorkbox.svg "Dorkbox")](https://git.dorkbox.com/dorkbox/ShellExecutor) [![Github](https://badge.dorkbox.com/github.svg "Github")](https://github.com/dorkbox/ShellExecutor) [![Gitlab](https://badge.dorkbox.com/gitlab.svg "Gitlab")](https://gitlab.com/dorkbox/ShellExecutor) [![Bitbucket](https://badge.dorkbox.com/bitbucket.svg "Bitbucket")](https://bitbucket.org/dorkbox/ShellExecutor)


Shell and JVM command execution on Linux, MacOS, or Windows for Java 6+.

 
Ironically, there are a considerable number of 'gotchas' when launching shell/JVM processes via Java. This library solves problems with:
1. Redirecting in/out/err streams correctly
1. Enabling single-character input
1. Correctly reading out/err process output streams to prevent memory issues.

- This is for cross-platform use, specifically - linux 32/64, mac 32/64, and windows 32/64. Java 6+


&nbsp; 
&nbsp; 

Release Notes 
---------
 
  
Maven Info
---------
```
<dependencies>
    ...
    <dependency>
      <groupId>com.dorkbox</groupId>
      <artifactId>ShellExecutor</artifactId>
      <version>1.1</version>
    </dependency>
</dependencies>
```

Gradle Info
---------
````
dependencies {
    ...
    compile "com.dorkbox:ShellExecutor:1.1"
}
````

Or if you don't want to use Maven, you can access the files directly here:  
https://repo1.maven.org/maven2/com/dorkbox/ShellExecutor/  


https://repo1.maven.org/maven2/net/java/dev/jna/jna/  
https://repo1.maven.org/maven2/net/java/dev/jna/jna-platform/  
https://repo1.maven.org/maven2/org/slf4j/slf4j-api/    

License
---------
This project is © 2010 dorkbox llc, and is distributed under the terms of the Apache v2.0 License. See file "LICENSE" for further references.

