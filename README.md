# My Journey to Become a Software Engineer

In this repository I will keep the progress fo my career as a software engineer, I think it is very
important that we all have some record of our progress, when I started programming I wanted to have
a record to go in the future and see what decisions I have taken and this repository is the result
of that record.

### Programming Change My Life

##### Day 1201-1202 Concurrency and Testing in Python

Today I learn how to mock dependencies in Python testing, I have a class that use a database, for the unit testing I need to mock this database. The code to create the instance of the database is placed inside the class constructor, and I cannot mock the database. I need to add the database connection how dependency and learn how mock. I learn a great lesson today. I develop this code only thinking that is a little script and not required unit testing. Great error for my lucky, the code grows, and I have a lot of chaos with try to fix the issues that I discover. I need to learn that apply TDD always is the fastest way to create code.

##### Day 1200 Concurrency and Pandas

Well, in the morning I read one chapter about the Java concurrency book and I make some exercises with concurrency. I continue reading the pandas documentation, in the work we manage a lot of CSV files and python and pandas are great tools for this type of tasks. I have listened that Scala is great also for these types of works. When finish my book, I continue reading about Microservices and start to learn Scala or Clojure.

##### Day 1199 Problems Reading CSV Files

Today I have a lot of problems trying to read a CSV with Kotlin and tablesaw, then I have the same problems with Apache Spark I cannot find a easy way to skip the first line in a CSV file. With Kotlin, Tablesaw and Apache Spark I need to manually delete the line in the csv file before try to read it. I believe that this is bad, with python and pandas I can skip lines before read the CSV very easy. Maybe I need to check more Apache Spark, because Apache Spark I understand that is a great tool for this type of tasks. Well tomorrow is weekend I want to finish to read the Java Concurrency book this weekend.

##### Day 1198 Reading CSV with Concurrency

I try to read a CSV file with Java library tablesaw I need to do some data analysis with the CSV and well, this library like Pandas is good. I have a problem, my CSV have the first row with one parameter, and I cannot analyze the document. The idea is to start to extract the document information concurrently, and create a JSON file with the data filtered. It is a good exercise to do. 

##### Day 1197 Livelock

Today I learn some techniques to avoid Liveness Hazards in the concurrently programming. I learn about what is a deadlock and the different types that can exist. I remember a moment when I provoke a Livelock with Kafka in one application because I enqueue all messages with some error again and again in the origin queue, well you can imagine the eternal cycle that I create. 

##### Day 1196 ETL and Java Swing

Today I need to do some code with Java swing the Java Concurrency book have some examples with swing library is amazing how the GUI applications manage your lifecycle. I remember one time that I have a problem with Kotlin in Android development, the app needs to connect to a one Websocket built with Node.js. The concern is that the mobile app disconnect to the Websocket a lot of times, and we have don't idea about what is the issue. Well today I think that the problem it's about of threads, I think, but I am not sure. I need to check this in another time.

##### Day 1195 Continuous study of concurrence

Today I continue reading the Java Concurrency book, we have come to the part of the GUI frameworks like swing and JavaFX. Likewise, I continue to learn English and I am still looking for a way to better organize my activities and studies.

##### Day 1193-1194 Awaitility Library

This weekend, I continue learning about concurrency in Java. I learned to use the Awaitility library and I start to do TDD with concurrency, this is a great challenge, apply concurrency in the code is hard, but test concurrency is hardest yet. I am happy because I continue with my Java mastery and Object-Oriented programming, I have a lot of plans for this current year. 

##### Day 1192 Threads, Threads, and more threads

Really I dream with threads in the night, I think that it is normal because currently I continue to studying concurrency in Java. Now I can understand the reason that the concurrency is a topic for senior developers is hard, really is hard. So I hope that in January I can finish reading the Java Concurrency book and do some toy projects with this feature, I am thinking in a Microservices project.

##### Day 1191 Thread Interruption

Today I studied about how to interrupt a task running in another thread and how the client code needs to handle the interruption, I remember a time when I do this implementation with Java code. I had an asynchronous data flow and this code execute in a method. My mission is easy, for example a client will, can cancel this method execution in any moment, but the client cannot cancel directly. I used an implementation using Kafka to send an event and when this event arrives the flow is cancelled. I remember this because the Microservice always have three replicas and my Kafka event send it only a one replica. So, I had a big headache with this problem, but I learn a lot. 

##### Day 1190 Executors and Firewall Problems

Today I have a Firewall problem in the work is frustrated when you have a problem, and you cannot fix because it is out of your scope, this task not depend on you.
Also, I learn the about the Executor interface in Java and learn what utilities have the Java Language to work with concurrency. I write a basic WebServer with the tutorials in the book, and I understand a little more how works a WebServer, and how the asynchronous is a vital part of this technology. I continue to learning concurrency more slowly, they have a lot of concepts to learn.

##### Day 1189 Latches and FutureTask in Java

Today I was learned about latches and FutureTask in Java. The Java Concurrency book it's hard to understand, remember when I started to learn about concurrency I can't understand why reason my code that execute in a separate thread don't executed. I understand a little today what is the reason for this behavior imagine that you have three process A, B and C. Process A execute in 1 second, process B in 5 seconds and process C in 2 seconds. If you do your process B asynchronous, you need a way to say it to the application, hey you need to wait 5 seconds before you finish. In this scenario, a latch save your life because your program wait to the latch finish your work. I think that I will write a tutorial with an example about this topic.

##### Day 1188 Taking the Way Again

I lost in the weekend in some familiar situations how programmers we like to write code all day I believe, but in some times you can't do it. Currently, I continue to study Concurrency in Java and in general. The Java Concurrency Book is my guide, and Baeldung blog and Stack Overflow are my best friends in this trip. Concurrency is hard, I think that is a next level in my career how Software Developer.

##### Day 1184 My First Certification

Today I complete my first course and achieve my first certification in the year. The course is about Zero Trust Security Framework, the zero trust framework is a great tool to do our systems more secure. I believe that any developer needs to know these principles because all developers work with data, and know how to handle this data is an important thing in the work.

##### Day 1183 Learning about Concurrency

Today I continue reading the book Java Concurrency in Practice. I am learning about how to build good objects for concurrency programs and multiple threads. The book is a little old and some examples in the book not have the same behavior in my Java 17 version. The knowledge acquired at this moment is great. Definitely, I will to buy this book in physic form. 

##### Day 1182 Started to Write Articles with Medium

Today I write my first programming tutorial in Medium blog, I have a lot of nervous but well I hope that help programming community. Write tutorials, I think that is a great way to learn some topic in a more deep and practice my English. For January, I have the goal to write two tutorials and finish the Java Concurrency book reading. In my work, the things go fine.

##### Day 1181 Start with Go

Today I continue to improve my English and start to learn go. When I start to write code in Go, my first reaction is, why I don't do this with Kotlin?. Kotlin and Java are different programming languages, but have a lot of similarities. I need to learn a language that go out my comfort zone. Go or Rust is my decision.

##### Day 1179-1180 Happy New Year Programers

Today I write my years goals about my career how Software Craftsmanship yeah I want to be a Software Craftsmanship. Some examples are Java Developer Certification, Red Hat certification, improve my English, learn new programming language and some more. This is a good exercise thank Own Your Teach Career book.

##### Day 1178 Concurrency 

Today I start to learn about concurrency in Java, I notice that I have a lot of lacks in this topic in the programming world. The next year I want to be a Java Developer Certificate by Oracle, I think that this topic is necessary.

##### Day 1177 Create a Facade

I remember in the microservice world for example if service A needs new functionality for example work with microservice C but microservice C do not have the same communication protocol. You need to modify the microservice A to work with this protocol. Maybe you do not want to add this new protocol to microservice A at this moment, a Facade microservice can save your life. One new microservice only designed to permit the communication between A ↔ B. I don't remember in which book I read about this. But today I use this for doing some work.

##### Day 1175-1176 Sick

Yesterday I was sick, I don't work and don't do any code. Today I was learning about Java 17 and Tablesaw I am playing with some CSV files to read the data and create Java objects with them. I want to continue playing with these things this week and well in 2023 I will start to read some book. Java Concurrency maybe.

##### Day 1174 The importance of the correct refactor

Today, when I am writing some lines of code with Java, I start to refactor my Strings to Enums. My objective is added more type-safe to my code, but when I to do this, little refactors I think. So I refactor this, maybe I can apply X design pattern, or maybe we can skip this if statement, if I apply this type of technique. Finally, I only refactor with the type-safety, but I spend about 20 minutes thinking in unnecessary refactors at this moment. I am not said that refactor is unnecessary, only I said that premature refactor is bad, if you apply for example TDD your code is awesome from the first time. Refactor is only necessary when the code starts to growth, well always think in small pieces of code.

##### Day 1171-1172-1173 Christmastime

I take a free time about the coding, with the arrival of the Christmas and new year I need to think about all my achieves in this year and start to think about my next achieves for the 2023 year. Merry Christmas programmers.

##### Day 1170 CSV files and Pandas

Well today I learn more about Pandas and CSV files, pandas can parse your CSV files into JSON format, but you need to be sure about the JSON format is the correct. I learn this important lesson today. I have a lot of desire to work with CSV with Java/Kotlin/Scala and Apache Spark. So, I think that in the weekend I practice this.

##### Day 1169 Managing Stress Situations and Finish my Book

Today I have a very stress situation in my work, and this is because about my lack in English. I think that I have improved my English a lot but at this moment is not very good to have a conversation with USA people. Definitely English is my main goal the next year, though Java Developer certification is important too. Also I finish the Software Craftsmanship book really I enjoy reading this book.

##### Day 1168 Python and CSV

Today, I learn more about pandas library, In the work we use a lot of information storage in CSV files. I want to be more Agile for example, I need to check all the elements in this CSV that have this ID. Tomorrow I want to explore another library for this purpose in Java called Tableu.

##### Day 1167 Study More English

I decide that in the end of the year I need a relax about study computer science things, and for this reason I will focus to improve my English. In my work in these moments, I have some meetings with native English speakers, and it is frustrating don't understand them very well. Also, I start to write Java tutorials one each week, I hope that in the next year I feel more comfortable with the English language. 

##### Day 1165-1166 New certificate and Other Java Tutorial.

Saturday I complete my course about Containers and Kubernetes, I do the test and approve it. Sunday I make a new Java tutorial about the static imports my second tutorial in the year I progress little, but I start to try to help others developers.

##### Day 1164 Start in Action

I think that today I start to growth my career in another level. Well the first time that I try to share my knowledge is not the better but is the start. The most difficult part to try new things is only to start to do it. Yeah, definitively the next year I start my own tech blog. My next goal is this writes tech articles and tutorials, and learn more English.

##### Day 1163 Nervous

Tomorrow I have my first skill share session, this is the first time that I do this. The first time that try to share my knowledge with another persons in a meeting, and is in English more difficult for me, but I think that is the moment to start growth my career.

##### Day 1162 Continue with my RedHat Course

Today I continue advance in my RedHat course about Container Platform Application Deployment, this course is hard to do, but the labs are amazing.

##### Day 1161 Java Logging System

In one application, I need to create a log system using the own Java library, this library is good, but have some lacks. I start to think and design a good solution for this problem. I imagine a simple but powerful solution. Well, I am excited about this.

##### Day 1159-1160 Kubernetes Services

Today I learn how works the Kubernetes services, it is amazing how the Kubernetes architecture is structured to not create coupled between applications. I am learning a lot about this, and obviously I can apply all of this knowledge in my next coding.

##### Day 1158 Reading and Red Hat Certification

Today I continue reading my current book, and advance in my Red Hat certification. Also I need to refresh my mind about Polymorphism tomorrow I need to write a tutorial in which I need to explain what is Polymorphism.

##### Day 1157 Goals

Today I continue reading my book, practice TDD, and I establish some goals related to my Software Engineer career, these goals are related to Java and Microservices.

##### Day 1156 Software Craftsmanship

Today I continue with the reading of my book, and some YouTube videos about TDD, I want to compromise to do this technique of coding in my daily work. Definitely, I think that practice TDD is a good choice.

##### Day 1155 Mockito Library

Today I study Mockito library, I try to understand in a good way how to mock dependencies, I try to apply TDD in my day work. Tomorrow I continue to study Java.

##### Day 1154 I Learned New Things About Containers

Today I study about how to build your own Containers, you need to take a basic image and apply the necessary changes to this image with a file called Dockerfile or Container file. I always thought that Docker is the unique way to build containers, but this is not true, you can build containers with many shapes, it is interesting how the community advance in these topics fast. Well, the change is the unique thing that never changes.

##### Day 1153 Study

Today I advance in my Red Hat certification about containers and OpenShift, I review some topics and learn new. I need to start to read a new book, I am bored without read.

##### Day 1151-1152 How Do You Explain a Computer Science Topic?

Today I need to write a tutorial in which I need to explain a Java characteristic. I like to write tutorials because in this part I discover my gaps and lacks. Is complicated, try to teach any topic in which you do not have the necessary acknowledge, and this is a good signal that you need to be better in this topic.


**Day 1 - 50 HTML - CSS - Javascript**  [here](./day0-50.md)</br>
**Day 51 - 100 Javascript** [here](./day51-100.md)</br>
**Day 101 - 150 Javascript** [here](./day101-150.md)</br>
**Day 151 - 200 Javascript** [here](./day151-200.md)</br>
**Day 201 - 250 Javascript and start React JS** [here](day201-250.md)</br>
**Day 251 - 300 Javascript - React JS** [here](day251-300.md)</br>
**Day 301 - 350 Javascript - React JS and start Node JS** [here](day301-350.md)</br>
**Day 351 - 400 Start learn MERN stack** [here](day351-400.md)</br>
**Day 401 - 450 MERN stack - Docker - Typescript - TDD** [here](day401-450.md)</br>
**Day 451 - 500 Object Oriented Programming** [here](day451-500.md)</br>
**Day 501 - 550 Data Structures and Algorithms** [here](day501-550.md)</br>
**Day 551 - 600 Java**</br>
**Day 601 - 650 Java** [here](day601-650.md)</br>
**Day 651 - 700 Java and Spring Boot** [here](day651-700.md)</br>
**Day 701 - 750 Java | Spring Boot | MySQL** [here](day701-750.md)</br>
**Day 751 - 800 Java | Spring Boot | MySQL** [here](day751-800.markdown)</br>
**Day 801 - 850 Java | Spring Boot | OCI** [here](day801-850.md)</br>
**Day 851 - 900 Java | Design Patterns** [here](day851-900.md)</br>
**Day 901 - 950 Java | Design Patterns** [here](day901-950.md)</br>
**Day 951 - 1000 Java | Design Patterns** [here](day951-1000.md)</br>
**Day 1001 - 1050 Java | New Job** [here](day1001-1050.md)</br>
**Day 1051 - 1100 Java | Python | Cloud Computing** [here](day1051-1100.md)</br>
**Day 1101 - 1150 Java | Containers | Cloud Native Development | OpenShift** [here](day1101-1150.md)</br>
