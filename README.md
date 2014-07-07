java_notes
==========

#Java Getting Started
* [Index](http://www.oracle.com/technetwork/java/index.html)

* [Getting Started](http://docs.oracle.com/javase/tutorial/getStarted/index.html)

* [Java Basics](http://docs.oracle.com/javase/tutorial/java/index.html)

* [Java Platform Standard Edition 7 Documentation](http://docs.oracle.com/javase/7/docs/index.html) 

* [An Introduction to the Java EE Platform](http://docs.oracle.com/javaee/7/firstcup/doc/intro.htm)

* [JDK 7 Download](http://www.oracle.com/technetwork/java/javase/downloads/jdk7-downloads-1880260.html)

* [J2EE7 Download](http://www.oracle.com/technetwork/java/javaee/downloads/java-ee-sdk-7-downloads-1956236.html) 

* Shell Customization
  * Terminal Preferences  
  * ``` ~/java_setup.sh ```

* [IntelliJ](http://www.jetbrains.com/idea/)
  * Tools->Create command line launcher


* [J2EE 7 Developer Bundle (samples and jdk)](http://www.oracle.com/technetwork/java/javaee/downloads/java-ee-7-sdk-with-jdk-u45-2066865.html)
  * ```chmod +x ./java_ee_sdk-7-jdk7-macosx-x64.sh ```
  * ```export DISPLAY=:0```
  * ```sh ./java_ee_sdk-7-jdk7-macosx-x64.sh```


* [Java Versions](http://en.wikipedia.org/wiki/Java_version_history) 
  * JDK - Prior to Java 2 
  * J2SE - Java 2 Platform Standard Edition (c 1998)
  * J2EE - Java 2 Platform, Enterprise Edition
  * J2ME - Java 2 Platform, Micro Edition

# Components
  * JDBC
  * JNDI
  * Regular Expressions
  * JDBC

#Java Tutorials

* [http://docs.oracle.com/javase/tutorial/index.html](http://docs.oracle.com/javase/tutorial/index.html)

* [http://docs.oracle.com/javase/tutorial/java/TOC.html](http://docs.oracle.com/javase/tutorial/java/TOC.html)

* [http://docs.oracle.com/javaee/6/firstcup/doc/gkhoy.html](http://docs.oracle.com/javaee/6/firstcup/doc/gkhoy.html)

* [http://docs.oracle.com/javase/tutorial/](http://docs.oracle.com/javase/tutorial/)

* [http://www.oracle.com/webfolder/technetwork/tutorials/obe/java/gc01/index.html](http://www.oracle.com/webfolder/technetwork/tutorials/obe/java/gc01/index.html)

* [JavaSE1.5 Annotations](http://docs.oracle.com/javase/1.5.0/docs/guide/language/annotations.html)

* [User Input (Scanner)](http://www.programmingsimplified.com/java/source-code/java-program-take-input-from-user)

* [jMockit](http://abhinandanmk.blogspot.com/2012/06/jmockit-tutoriallearn-it-today-with.html)

#Java Certifications

* [http://docs.oracle.com/javase/tutorial/extra/certification/javase-7-programmer1.html](http://docs.oracle.com/javase/tutorial/extra/certification/javase-7-programmer1.html)
* [http://docs.oracle.com/javase/tutorial/extra/certification/javase-7-programmer2.html](http://docs.oracle.com/javase/tutorial/extra/certification/javase-7-programmer2.html)

#JavaDB
* [Java DB in JDK 7](https://www.youtube.com/watch?v=Ua1y4RoBQUo)

#JUnit

* [http://junit.org/](http://junit.org/)
* [http://www.vogella.com/tutorials/JUnit/article.html](http://www.vogella.com/tutorials/JUnit/article.html)
* [Maven Repository: junit/junit](http://mvnrepository.com/artifact/junit/junit)
* 
#Maven
* mvn archetype:generate
* [Maven Archetype from Eclipse](http://www.avajava.com/tutorials/lessons/how-do-i-perform-an-archetype-create-from-eclipse.html)
* [Maven Project Import](http://www.avajava.com/tutorials/lessons/how-do-i-import-a-maven-project-into-eclipse.html)

#Spring

* [Dependency Injection](https://www.youtube.com/watch?v=GB8k2-Egfv0&list=PLC97BDEFDCDD169D7)

* [Aspect Oriented Programming](http://docs.spring.io/spring/docs/2.0.x/reference/aop.html) 

#Java Community
* [JCP](https://jcp.org/en/home/index)

#JSRs
* [Specifications for JavaSE/EE](https://jcp.org/en/jsr/platform?listBy=2&listByType=platform)

#Videos
* [Lean Parts](https://www.youtube.com/watch?v=vvtuFLz2prk)

#Regex
* [regex/Pattern.html](http://docs.oracle.com/javase/7/docs/api/java/util/regex/Pattern.html)
#EJB
* [Annotations](http://docs.oracle.com/cd/E15051_01/wls/docs103/ejb30/annotations.html)

#Tomcat
* [Install on OSX](http://wolfpaulus.com/jounal/mac/tomcat7/)

#FAQ
* ```JDK``` Java SE Development Kit
  * includes ```javac``` compiler
  * other tools ```javap```, ```jar```, debugging tools
  * and a ```JRE```...

* ```JRE``` Java Runtime Environment runs java applications
  * ```JVM``` plus ```javaw```, ```class files``` and ```libraries``` like util, math, lang

* ```JVM``` Java Virtual Machine runs byte code
  * ```java``` 
  * ```$ java -fullversion``` ->  ```java full version "1.7.0_60-b19"```
  * ```which java``` -> ```/usr/bin/java```
  * ```ls -la /usr/bin/java``` -> ```lrwxr-xr-x  1 root  wheel  74 Nov  9  2013 /usr/bin/java -> /System/Library/Frameworks/JavaVM.framework/Versions/Current/Commands/java```
  * ```java -version``` -> ```java version "1.7.0_60"
Java(TM) SE Runtime Environment (build 1.7.0_60-b19)
Java HotSpot(TM) 64-Bit Server VM (build 24.60-b09, mixed mode)```


* ```Java SE``` - Java Standard Edition
  * ```J2SE``` is an older name
  * Java SE is a set of  Specifications

* ```Java EE``` - Java Enterprise Edition
  * ```J2EE``` is an older name
  * Java EE is a set of  Specifications

* What is Glassfish?

* How do you run a java application?
* How does a java application access it's arguments?
* What is the ```CLASSPATH````?
* What is ```javac``?
* What is a ```jre``?
* What is a ```RIA``?
  * [http://docs.oracle.com/javase/7/docs/technotes/guides/jweb/index.html](http://docs.oracle.com/javase/7/docs/technotes/guides/jweb/index.html)
* What is an ```executable jar file```?
* What does the java compiler do?
* What is ```JAVA_HOME```?
  * ```$JAVA_HOME``` ->  ```/Library/Java/JavaVirtualMachines/jdk1.7.0_60.jdk/Contents/Home```
* What is a ```JSR```?
* What is ```JCP```?
* What is ```JME``` or ```Java Micro Edition```?
* What is ```Java Web Start```?
* What is the ```Byte-code Verifier```?
  * [http://docs.oracle.com/javase/specs/jvms/se7/html/jvms-4.html#jvms-4.10.2.2](http://docs.oracle.com/javase/specs/jvms/se7/html/jvms-4.html#jvms-4.10.2.2)





