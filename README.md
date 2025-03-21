# Dev Resources

This repository contains the resources I have used to get up to speed when working on different projects. I recommend that you follow the order of topics as outlined below. You will be able to find relevant resources in the directories. 

[Roadmap for backend developers](https://roadmap.sh/backend)

## 0. Primer/intro

Challenges of being a developer and how to handle some of them. Mostly about mindset.

1. You don't know what challenges you will face. Just start developing and discover them later. It is better to develop fast and discover fast than trying to plan and not do anything
2. 

## 1. JAVA OCP Developer books

Being very proficient in Java is great...

Read the book in its entirety and do all the tasks. 

### (OPTIONAL) 1.1 Kotlin mini course

It is one of two languages you are likely to be working with once in a project. Great to have som exposure to it as well.

Builds on the knowledge you have gained in the first module. Transitioning to Kotlin is no big task and much of the syntax is similar.

## 2. Working with containers

As a new developer, learning about containers is essential because you'll inevitably encounter them in your career. Containers are the foundation of many modern applications, and understanding them will make you more efficient and versatile as a developer. They allow you to package and run applications consistently across different environments, without the need for special access or complicated setup. This flexibility makes containers an invaluable tool, ensuring your code works seamlessly no matter where it’s deployed. So, whether you’re excited about it or not, mastering containers will help you stay ahead in the software development world.

1. Course on Podman in [pluralsight](https://app.pluralsight.com/library/courses/podman-getting-started/table-of-contents)

## 3. Quick intro to modern architecture

This is important as you will start developing the mental framework necessary to build well structured and functioning applications. It will also help you better understand why we do certain things in the following courses and make you better suited for communicating with architects and stakeholders.

DDD, Tactical DDD and strategic DDD.

Loose coupling in practice: what does it mean and how do we achieve it?

## 4. Spring boot + IntelliJ

Spring is important because...

You will learn these basic things about Spring:
* Beans beans beans (1. Java annotations, 2. How Spring Manages Beans, 3. Dependency Injection and config files)
* How to set up a simple REST controller, run it, test with intellij client, set up tests for the controller and what kinds of tests are nice for controllers
* A reminder on how to structure a web service (patterns best practices and so on)

Nice to know in intellij when working with Spring or in general:
* Git in IntelliJ
* The built in web client
* A note on testing (@SpringBootTest, mocks etc.)
* Test coverage plugin
* Copilot?
* Shortcuts you should know

## 5. CQRS Event sourcing

https://www.youtube.com/watch?v=8JKjvY4etTY 

## 6. Kafka
(Summary from chatGPT) Apache Kafka is a must-learn for new developers because it empowers you to handle real-time data streams efficiently, a crucial skill in today's data-driven world. Its scalable, distributed architecture and advanced stream processing capabilities make it ideal for building robust, high-performance applications. Learning Kafka opens doors to opportunities in top companies and equips you with the tools to manage and process data streams effectively, making you a valuable asset in any tech team.

Introduction to event-driven design (4 articles by [confluent](https://www.confluent.io/blog/journey-to-event-driven-part-1-why-event-first-thinking-changes-everything/))

Introduction to data mesh by [confluent](https://www.youtube.com/watch?v=nhgsgvELJ_E&list=PLa7VYi0yPIH0L8ahQYbyBFkGc6a949-Lj&index=1)

Kafka was originally developed at LinkedIn. As an introduciton, I recommend that you read [this](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)

The following are steps I took to start learning about Apache Kafka:
1. Check out "Kafka Certified Developer" by "A Cloud Guru" on Pluralsight. Go here to access the playground (formerly Linux academy): [playground](https://help.pluralsight.com/hc/en-us/articles/24564263824404-Hands-on-playground-overview#access) and choose "sign in with pluralsight credentials". You should probably view the tutorial from [here](https://learn.acloud.guru/), as they have updated links to the resources.

2. Now might be the time to do some reading. Check out this free ebook on kafka by Confluent: https://www.confluent.io/resources/ebook/kafka-the-definitive-guide/

3. After that, you might want to check out: [Apache Kafka Deep Dive](https://learn.acloud.guru/course/bf0aeafb-8bc4-4082-bd3a-00972349b6c0/overview)

4. Practice resources: https://quizlet.com/573725773/apache-kafka-ccdak-study-guide-combined-notes-flash-cards/, https://quizlet.com/fr/931742490/ccdak-apache-kafka-flash-cards/ og andre mock exams på UDEMY
5. https://github.com/danielsobrado/CCDAK-Exam-Questions 

## 7. Architetcture course

https://www.bouvet.no/kurs/kategorier/utvikling-for-web-og-mobil/implementing-modern-architecture
