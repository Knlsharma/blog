---
published: true
---
## Rise OF Java (jdk 9)

You may have heard about Java 9’s module system, but there's even more to this new version. Here are ten exciting new features that will ship with Java 9.

**1.** **Platform Module System (Project Jigsaw)**:*It is a new kind of Java programing component that can be used to collect Java code (classes and packages)*. The main **goal of this project is** to easily scale down application to small devices. **In Java 9, JDK** itself has divided into set of modules to make it more lightweight. It also allows us to **develop modular applications**.

**2.** **Interface Private Methods**:In Java 9, we **can create private methods inside an interface**. Interface allows us to declare private methods that help to _share common code between non-abstract methods._

Before Java 9, creating private methods inside an interface _cause a compile time error._

**3. Try-With Resources**:Java introduced try-with-resource feature in **Java 7 that helps to close resource** automatically after being used.

In other words, we can say that we don't need to **close resources (file, connection, network etc) explicitly**, try-with-resource close that automatically by using AutoClosable interface.

In Java 7, try-with-resources has a limitation that requires _resource to declare locally within its block._

**4. Anonymous Classes Improvement**:Java 9 introduced a new f**eature that allows us to use diamond operator with anonymous classes**. Using the diamond with anonymous classes was**not allowed in Java 7.**

In Java 9, as long as the inferred type is denotable, **we can use the diamond operator** when we create an _anonymous_ inner class.

**5. Java @SafeVarargs Annotation**:It is an_annotation which applies on a method or constructor_ that takes varargs parameters. It is used to ensure that the method does not perform _unsafe operations on its varargs parameters._

It was included in __**Java 7 and can only be applied on Final, methodsStatic, methodsConstructors**__.

**6. Java Collection Factory Methods**:_Factory methods are special type of static methods that are used to create unmodifiable instances of collections_. It means we can u**se these methods to create list**, set and map of small number of elements.

It is unmodifiable, so adding new element will throw **java.lang.UnsupportedOperationException**

**7. Java Process API Improvement**:Java has improved its **process API in Java 9 version** that helps to manage and control _operating system processes_.

In earlier versions, it was complex to manage and control operating system processes by **using Java programming. Now, new classes and interfaces are added to perform this task**.

**8. Java New Version-String Scheme**:Java version-string is a format that _contains version specific information. This version-string consists of major, minor, security and patch update release_s.

In Java 9, a new **version-string scheme is introduced**.

**9. JShell:** The Java Shell (REPL):*It is an interactive Java Shell tool, it allows us to execute Java code from the shell and shows output immediately. JShell is a REPL (Read Evaluate Print Loop) tool and run from the command line. It is benificial, if we want to test our business logic and get result immediately*.

**10. BeanInfo Annotations**:The _@beaninfo_ Javadoc tag is replaced with the annotation types _JavaBean, BeanProperty, and SwingContainer_.

We can use these attributed directly in the **Bean class**. It also allows auto *removal for automatically created classes and set the corresponding feature attributes during BeanInfo generation at runtime*.


These are many more features to try,So move on to [jdk 9](https://www.oracle.com/technetwork/java/javase/downloads/jdk9-downloads-3848520.html)

**More links**

  [java 9 Doc](https://www.oracle.com/technetwork/java/javase/documentation/index.html), 
  [Java SE at a Glance](https://www.oracle.com/technetwork/java/javase/overview/index.html), 
  [Java SE General FAQs](https://www.oracle.com/technetwork/java/javase/overview/faqs-jsp-136696.html).
