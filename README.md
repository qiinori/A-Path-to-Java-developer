# Study-Java-

![Java Developer RoadMap](C:\Users\qiino\Desktop\Git\Java\Study-Java-\images\Java Developer RoadMap.jpg)

## Learn the basics
- [x] ##### Git & Github
- [x] ##### Linux 
- [x] ##### Data Structures and Algorithms
## General Programming skills
### IDE
- [x] - #### Eclipse
- [x] - #### IDEA
- [x] - #### NetBeans
## Tools
- ##### [status: Learning] Maven
- ##### [status: Learning]  Junit
## JDK
- ##### [status: Learning] Collections
- ##### [status: Learning] IO
- ##### [status: Learning] JAVA 8

##### Git & Github
I read the book " Pro Git book", written by Scott Chacon and Ben Straub and published by Apress.
Link: https://git-scm.com/book/en/v2

##### Linux
##### Data Structures and Algorithms
##### HTTP / HTTPS
##### Computer Science Fundamentals
##### Design Patterns
 [books ](https://www.java67.com/2016/10/top-5-object-oriented-analysis-and-design-patterns-book-java.html)
 [courses ](https://javarevisited.blogspot.com/2018/02/top-5-java-design-pattern-courses-for-developers.html)
[![best courses to learn Design Pattern in Java](https://1.bp.blogspot.com/-j58vxQ8Snyo/XZ8sEJebc2I/AAAAAAAAbAE/KaZSnwCCXyYK836r64fUjhlPNwJbZ16XgCLcBGAsYHQ/s400/design%2Bpattern%2Blibrary%2Bin%2BJava%2Bpluralsight%2Bcourse.png)](https://javarevisited.blogspot.com/2018/08/5-object-oriented-programming-and-design-courses-for-Java-programmers.html)





## Topics
### 1. Tools
The tools section is divided into different sections. First, your IDE, which is your primary tool and can do almost everything you asked for like compile, run, debug, profile, test, compare files and code, refactoring, and much more.

The second part is the build tool, which you need to build and deploy your projects like [Maven](https://medium.com/javarevisited/top-10-free-courses-to-learn-maven-jenkins-and-docker-for-java-developers-51fa7a1e66f6) and [Gradle](https://www.java67.com/2018/04/10-tools-java-developers-should-learn.html). Anyone of this would be enough. I have just listed ANT, but that's for legacy projects. For all new Java projects, prefer Maven or Gradle.

And, the third and most crucial part includes containers like [**Docker and Kubernetes**](https://click.linksynergy.com/deeplink?id=JVFxdTr9V80&mid=39197&murl=https%3A%2F%2Fwww.udemy.com%2Fcourse%2Fdocker-and-kubernetes-the-complete-guide), CI/CD tools like Jenkins and TeamCity, and Infrastructure automation tools like Ansible.

If you are interested in learning about these tools, here are some useful courses to learn build tools and IDEs

- [5 courses to learn Apache Maven for Java developers ](https://javarevisited.blogspot.com/2019/03/top-5-course-to-learn-apache-maven-for.html)
- [5 Courses to learn IntelliJIDEA](https://itnext.io/top-5-intellijidea-and-android-studio-courses-for-java-and-android-programmers-afcc27309b60)
- [5 Free Courses to learn Eclipse IDE](https://medium.com/javarevisited/top-10-courses-to-learn-eclipse-junit-and-mockito-for-java-developers-4de1e8d62b96)
- [Top 5 Courses to learn Docker and Kubernetes](https://javarevisited.blogspot.com/2019/05/top-5-courses-to-learn-docker-and-kubernetes-for-devops.html)
- [Top 5 Courses to learn Jenkins for CI/CD](https://javarevisited.blogspot.com/2018/09/top-5-jenkins-courses-for-java-and-DevOps-Programmers.html)
- [Top 5 Courses to learn Ansible for Server Automation](https://javarevisited.blogspot.com/2019/11/top-5-course-to-learn-ansible-for-devops.html)

### 2. JDK APIs

The next important thing to learn is JDK APIs, which is very, very important for any Java developer. This is quite a big section, and that's why it's divided into core areas like Java Collections framework, Java Concurrency, Java IO, and Java 8 APIs, let's explore each of them



### 2.1 Java Collections Framework

This is one of the most essential Java API every Java developer should learn. This API provides implementations of standard data structure in Java-like linked list, set, stack, queue, hash table, priority queue, and others.

At least you should know about all everyday objects like ArrayList, HashMap, HashSet, LinkedHashSet, TreeSet, etc. Each of them has their different property like ArrayList is a dynamic array which can grow, HashMap is a standard implementation of the hash table and can be used to store key-value pairs.

Similarly, HashSet is a set implementation that doesn't allow duplicate elements. I strongly suggest you check [**Java Fundamentals: Collections** ](https://pluralsight.pxf.io/c/1193463/424552/7490?u=https%3A%2F%2Fwww.pluralsight.com%2Fcourses%2Fjava-fundamentals-collections)course by Richard Warburton on Pluralsight to learn Java Collection Framework in depth.



[![best course to learn Java Collections](https://1.bp.blogspot.com/-51YQ1ykKDi8/XZ8qE5pTrnI/AAAAAAAAa_o/WARKXteTbqE0bgH5kwktcsjDPs7Rvjd2wCLcBGAsYHQ/s400/collection-interface-hierarchy-java.png)](https://medium.com/javarevisited/top-5-java-online-courses-for-beginners-best-of-lot-1e1e240a758)





### 2.2 Java Concurrency

After Java Collections, the next, most crucial API in Java is about multithreading and concurrency, and I firmly believe that if you want to be a competent Java developer, you must have a solid understanding and command on Java Concurrency API.

You should not only have an in-depth understanding of fundamental concepts like Thread, Runnable, Object locking, and Synchronization, but you should also be familiar with concepts like deadlock, livelock, race conditions, and how to deal with them.

You should also learn about advanced Java concepts like synchronizers added on Java 5 and subsequent version, I mean CyclicBarrier, CountDownLatch, Phaser, and CompleteableFuture, etc., along with Futures and how to perform the async operation in Java.

I know, it's a lot of stuff, and that's why I suggest you join an in-depth course like [**Java Concurrency in Practice bundle**](https://learning.javaspecialists.eu/courses/concurrency-in-practice-bundle?affcode=92815_johrd7r8) from Heinz Kabutz, a Java Champion, and authority when it comes to concurrency and design patterns. This course is a bit expensive, but you will learn a lot more concepts in-depth, which makes it completely worth your time and money.



[![best course to learn Java Concurrency](https://1.bp.blogspot.com/-tdhD0MmQzeg/XZ8onrTdYQI/AAAAAAAAa_M/LSePerq2UKQSo4umnqaq4x-TGRCOolbTACLcBGAsYHQ/s320/CPU%2Bcache%2Bvolatile%2Bconcurrency%2Bin%2BJava.png)](https://javarevisited.blogspot.com/2018/06/top-5-java-multithreading-and-concurrency-courses-experienced-programmers.html)



On the other hand, if the price is an issue, you can also check this Udemy course to [**Efficient Java Multithreading with Executors**](https://click.linksynergy.com/fs-bin/click?id=JVFxdTr9V80&subid=0&offerid=323058.1&type=10&tmpid=14538&RD_PARM1=https%3A%2F%2Fwww.udemy.com%2Fefficient-java-multithreading-with-executors%2F), which won't cost you more than $10 if you get it on Udemy flash sales which happens every month. This is also an excellent course to learn Java concurrency and multithreading in Java.



### 2.3 Java IO

I have interviewed more than 100+ Java programmers, and I have noticed one pattern; they all have very little knowledge of Java IO and NIO APIs as compared to Java Collections and Java Multithreading API. I can understand that many people spend a lot of time learning those two APIs, but you cannot leave behind this critical APIs.

If you have to code a real-world, core Java application, you will need to use classes like File, InputStream, OutputStream, Reader, Writer from java.io package, which is the core of the Java IO API. Similarly, you also need to know about ByteBuffer, FileChannel, Selector, and other critical classes from the java.nio API, if you want to write a socket-based application.

Unfortunately, there are not many dedicated resources on teaching Java IO and Java NIO API, but [**The Complete Java Masterclass** ](https://click.linksynergy.com/fs-bin/click?id=JVFxdTr9V80&subid=0&offerid=323058.1&type=10&tmpid=14538&RD_PARM1=https%3A%2F%2Fwww.udemy.com%2Fjava-the-complete-java-developer-course%2F)is a great resource to master this API. You will find a lot of essential concepts from this API in this course.



[![best course to learn Java File API](https://1.bp.blogspot.com/-ub8CRTC3yXo/XZ8ru78p7QI/AAAAAAAAa_8/wDn4g4t5NaI95TB-iG7SAg_uhLfTTrmqwCLcBGAsYHQ/s400/FileReader%2Bvs%2BFileInputStream%2Bin%2BJava.png)](https://javarevisited.blogspot.com/2018/05/top-5-java-courses-for-beginners-to-learn-online.html)





### 2.4 Java 8 Features

Now, the next and another necessary API, a Java programmer, should learn is the Java 8 features, which has completely changed the way Java is coded and programmed nowadays. To become a Java developer in 2020, you must know how to use a Lambda expression, Stream API, Optional classes, and new Date and Time API.

Without knowing these APIs, it would be very tough to write a Java application in 2020. Most of the library also now stop supporting version lower than Java 8, which means you have to learn Java 8 features now than later. It's already 5 years since Java 8 was released, so you literally have no excuse left.

When it comes to learning Java 8 features, there are a lot of excellent resources available in the market. Still, if you already know Java, I suggest you choose the resource which only focuses on Java 8 features like **[What's New in Java 8](https://pluralsight.pxf.io/c/1193463/424552/7490?u=https%3A%2F%2Fwww.pluralsight.com%2Fcourses%2Fjava-8-whats-new)** course on Pluralsight. This way, you can learn Java 8 in no time.



[![best course to learn Java 8](https://1.bp.blogspot.com/-xf_jet_Y3nA/XZ8rZmcXF5I/AAAAAAAAa_0/1Lj-mGz-VxYct3JD8ZTD8oCG6N2I9kl9gCLcBGAsYHQ/s400/Java%2B8%2BComparator%2Bexample.png)](https://www.freecodecamp.org/news/these-are-the-best-free-courses-to-help-you-learn-java-8-and-java-9-a7615c8644ab/)

While Java 8 features are essential for Core Java developers, if you can, please learn all other new features introduced from Java 9 to Java 13 like Modules, var for local variables, static factory methods for collections, Text Block, String in Switch and many more. If you need a resource, you can check out this list of courses to [learn all new Java features ](https://medium.com/javarevisited/top-5-courses-to-learn-new-features-of-java-8-to-java-13-107eb51d2a13)in 2020.



## 3. Frameworks

The best thing about Java is that it has a vibrant eco-system, which means there are a lot of frameworks and libraries to almost anything. Usually, I don't suggest a Java developer learn a framework until he needs to use it in his project. Still, there are some frameworks and libraries, which I believe every Java developer should know like Spring, Spring Boot, Hibernate, Log4j, JUnit, etc.



### 3. 1 Spring Framework

If you want to become a Java developer in 2020, I strongly recommend you to learn Spring Framework first. This is one of the most popular Java frameworks, and literally, almost every single Java application I have worked in the last 5 years, uses this framework.

Spring Framework encourages writing clean code, which is easier to test and maintain by providing you features like Dependency Injection and Inversion of Control. It also has a rich API for most of the day-to-day tasks, and that's why every Java developer should learn Spring framework.

And, if you want to learn Spring framework, there is no better course than **[Spring Framework 5: Beginner to Guru](https://click.linksynergy.com/fs-bin/click?id=JVFxdTr9V80&subid=0&offerid=323058.1&type=10&tmpid=14538&RD_PARM1=https%3A%2F%2Fwww.udemy.com%2Fspring-framework-5-beginner-to-guru%2F)**. It covers Spring 5, the latest version of spring 5, and teaches Spring in a more hands-on way than any other course.



[![best course to learn Spring 5](https://1.bp.blogspot.com/-AQRpoBo_VAA/XZ8og0nesCI/AAAAAAAAa_I/VQ-eO3Z9M2ARXQncDTeJcananwpZLUOzwCLcBGAsYHQ/s400/Spring%2BFramework%2B5%2BBeginner%2Bto%2BGuru%2BUdemy%2Bcourse.jpg)](https://javarevisited.blogspot.com/2018/06/top-6-spring-framework-online-courses-Java-programmers.html)





### 3.2 Hibernate

The second framework which I recommend every Java developer to learn is the Hibernate, which is based upon JPA (Java Persistence API). To be accurate, Hibernate came before JPA, but because [JPA](https://javarevisited.blogspot.com/2018/01/top-5-hibernate-and-jpa-courses-for-java-programmers-learn-online.html) is standard API to implement the persistence layer in Java, Hibernate implements it.

Now, why should you learn Hibernate? Well, because most of the Java applications you will work with will interact with Database, and it's excruciating to deal with Database in Java using[ JDBC](http://www.java67.com/2018/03/top-5-free-jdbc-courses-for-java.html) and without a proper framework like Hibernate.

It provides some of the essential features like Caching and Transaction out-of-the-box, which means you have more time to focus on your application logic, then implementing caching in your application. This seriously improves the performance of Java application, and so far, my most significant reason to use Hibernate.

Now, when it comes to learning Hibernate there are many great resources available in the market, but the **[Spring & Hibernate for Beginners](https://click.linksynergy.com/link?id=JVFxdTr9V80&offerid=323058.647428&type=2&murl=https%3A%2F%2Fwww.udemy.com%2Fspring-hibernate-tutorial%2F)** course is my preferred one because you can kill two birds from one stone, you can learn both Spring and Hibernate in one class rather than joining separate courses for them.



### 3.3 Spring Boot

This is another framework I recommend every Java developer to learn in 2020 and going forward. Spring Boot took Spring's philosophy of simplification and made it easy to work with Spring itself. Just like Spring makes it easier to create a Java application, Spring Boot makes it easier to create a spring-based Java application.

Features like auto-configuration take away most of the pain associated with configuring Spring application. Similarly, starter POM features grouped commonly used dependency into simple reusable POMs.

Now, if you want to learn Spring Boot, I strongly suggest you go through [**Learn Spring Boot in 100 Steps**](https://click.linksynergy.com/fs-bin/click?id=JVFxdTr9V80&subid=0&offerid=323058.1&type=10&tmpid=14538&RD_PARM1=https%3A%2F%2Fwww.udemy.com%2Fspring-boot-tutorial-for-beginners%2F) course; it's one of the best and most up-to-date and also provide step-by-step guides for everyday things a Spring Boot developer needs to know.



[![img](https://1.bp.blogspot.com/-w3X3JcxbiXo/XZ8peoFAi_I/AAAAAAAAa_g/fGDiOkQIneEprjqFUNpP96-tHd4BlAykACLcBGAsYHQ/s400/Creating%2BYour%2BFirst%2BSpring%2BBoot%2BApplication%2BPluralsight%2Bcourse.png)](https://hackernoon.com/top-5-online-courses-to-learn-spring-boot-in-2019-c2fd7a0282c2)





### 3.4 MicroProfile, Micronaut, and Quarkus

While learning Spring Boot and Spring Cloud is sufficient for developing Microservices in Java, there is a couple of more advanced frameworks you can explore, like Eclipse Microprofile, Micronaut, and Quarkus.

**3.4.1 [Eclipse Microprofile](https://microprofile.io/)**
It's an initiative that aims to optimize Enterprise Java for Microservice Architecture. It's driven by Eclipse, one of the leading organizations of Java and the company behind popular Eclipse IDE. The goal Eclipse of MicroProfile is to define standard APIs for building microservices and deliver portable applications across multiple MicroProfile runtimes. The current version of Eclipse Microprofile in 3.2, and it's a useful Java framework to learn in 2020.

**3.4.3 [Micronaut](https://micronaut.io/)**
This is another Java framework you can learn in 2020. Micronaut is a modern, JVM-based, full-stack framework for building modular, easily testable microservice and serverless applications. It's a polyglot framework and allows you to create an application using Java, Kotlin, or Groovy. Some of the key talking points of Micronaut is reduced startup time, blazing-fast throughput, and minimal memory footprint.

**3.4.3 [Quarkus](https://quarkus.io/)**
Quarkus is a Kubernetes Native Java stack tailored for OpenJDK HotSpot and GraalVM, crafted from the best of breed Java libraries and standards. Quarkus tailors your application for GraalVM and HotSpot to get Amazingly fast boot time and incredibly low RSS memory (not just heap size!).

It also provides instant scalability and high-density memory utilization in container orchestration platforms like Kubernetes using a technique called compile-time boot. You can also use both the familiar imperative code and the non-blocking reactive style when developing applications for Quarkus.

In short, one of the best platforms for Java developers to create an application and something worth learning in 2020.



[![Top frameworks to learn in Java 2020](https://1.bp.blogspot.com/-fY1gzOrbL7Y/Xgw2l4FnRyI/AAAAAAAAcL8/OSjDvepQFcsslSx6D-UJfYSluqIqm86WwCLcBGAsYHQ/s320/Quarkus.png)](https://1.bp.blogspot.com/-fY1gzOrbL7Y/Xgw2l4FnRyI/AAAAAAAAcL8/OSjDvepQFcsslSx6D-UJfYSluqIqm86WwCLcBGAsYHQ/s1600/Quarkus.png)





## 4. Testing

Testing is an essential skill for any Java developer, particularly unit testing, integration testing, and automation testing. At the bare minimum, every Java developer should be familiar with [JUnit](https://dzone.com/articles/top-5-junit-and-unit-testing-courses-for-java-prog) and [Mockito](https://medium.com/javarevisited/5-courses-to-learn-junit-and-mockito-in-2019-best-of-lot-f217d8b93688), two of the most popular Unit testing and Mock library.

If you know these two and know how to use them to effectively create a unit test, you will be a much better Java developer than without them.

There are more advanced libraries also exists like Cucumber for Business-driven testing, Robot Framework for integration testing, but there is no substitute for JUnit, you will always need that.

When it comes to a mocking library, you have a couple of choices like PowerMock, Mockito, and EasyMock. Still, I strongly suggest you learn Mockito because it's a vast library, and also many Java developers and companies are doing that. It is slowly becoming the standard library for creating mock objects in Java.

If you want to learn JUnit and Mockito, I have already shared a lot of resources like [books](https://javarevisited.blogspot.com/2014/08/top-5-books-to-learn-unit-testing-junit-tdd-Java-programmers.html#axzz5E2uHdG3w) and [courses](https://hackernoon.com/5-courses-java-programmers-can-join-to-learn-junit-and-mockito-in-2019-h74t38r4), you can check those to learn more.



## 5. Utility Libraries

The real power of Java lies in its vibrant ecosystem of open source libraries. You will find libraries to do almost anything in Java from logging to machine learning, from sending an HTTP request to parsing JSON and much more.

Apart from that, Java is also lucky to have utility libraries like Apache Commons and Google Guava, these two libraries effectively complement JDK libraries. I have also shared a list of [20 Java APIs and libraries](https://javarevisited.blogspot.com/2018/01/top-20-libraries-and-apis-for-java-programmers.html) for Java developers.

I suggest you go through that list, chances are that you already half of them but if you don't learn them they are very, very useful and help you to write better Java programs and deliver faster.

## Reference:
https://javarevisited.blogspot.com/2019/10/the-java-developer-roadmap.html