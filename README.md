 # Interview Backend Questions

## General Questions 
### Table of Contents
1. [Explain SOLID](#explain-solid)
2. [Explain Abstraction](#explain-abstraction)
3. [Explain Polymorphism concept in computer science](#explain-polymorphism-concept-in-computer-science)
4. [Explain Single Responsibility with examples](#explain-single-responsibility-with-examples)
5. [Explain Design Pattern](#explain-design-pattern)
6. [Design Pattern you know and used before](#design-pattern-you-know-and-used-before)
7. [Explain Async, Sync](#explain-async-sync)
8. [Proxy Servers](#proxy-servers)
9. [What are Multi-Tenant Servers](#what-are-multi-tenant-servers)
10. [Why we need Tokens for authentication](#why-we-need-tokens-for-authentication)
11. [Authentication vs Authorization](#authentication-vs-authorization)
12. [Monolith vs Microservices](#monolith-vs-microservices)
13. [What is a Load Balancer and its importance?](#what-is-a-load-balancer-and-its-importance)
14. [How Can I enhance the API and reduce API response time?](#how-can-i-enhance-the-api-and-reduce-api-response-time)

## Database Questions
### Table of Contents
1. [Explain ACID concept](#explain-acid-concept)
2. [What is an ORM and when/why to use it](#what-is-an-orm-and-whenwhy-to-use-it)
3. [Database indexing (explain/when to use/tradeoffs)](#database-indexing-explainwhen-to-usetradeoffs)
4. [What is a database view](#what-is-a-database-view)
5. [Explain Database transaction](#explain-database-transaction)
6. [SQL vs NoSQL](#sql-vs-nosql)
7. [Difference Between DELETE and TRUNCATE](#difference-between-delete-and-truncate)
8. [What is a lock and why is it useful?](#what-is-a-lock-and-why-is-it-useful)
9. [Explain Join in Database](#explain-join-in-database)
10. [Difference Between Cluster/Non-Cluster Index](#difference-between-clusternon-cluster-index)
11. [What is Elasticsearch and when to use it and explain its tradeoffs](#what-is-elasticsearch-and-when-to-use-it-and-explain-its-tradeoffs)
12. [How does Database Normalization improve design?](#how-does-database-normalization-improve-design)
13. [How can I enhancement the SQL query?](#how-can-i-enhancement-the-sql-query)
14. [What is the innodb?](#what-is-the-innodb)

## Git Questions
### Table of Contents
1. [What is `git fetch` vs. `git pull`](#what-is-git-fetch-vs-git-pull)
2. [What is a Git tag, and why is it used?](#what-is-a-git-tag-and-why-is-it-used)

## Django & Python Questions
### Table of Contents
1. [Explain Django's MVT architecture](#explain-djangos-mvt-architecture)
2. [How does Python's GIL (Global Interpreter Lock) work?](#how-does-pythons-gil-global-interpreter-lock-work)

## PHP Laravel Questions
### Table of Contents
1. [Explain the Eloquent ORM in Laravel](#explain-the-eloquent-orm-in-laravel)
2. [What are Middlewares in Laravel?](#what-are-middlewares-in-laravel)
3. [Explain Laravel lifecycle](#explain-laravel-lifecycle)
4. [Define N+1 Problem and How we can solve it](#define-n1-problem-and-how-we-can-solve-it)
5. [What is the service container?](#what-is-the-service-container)
6. [What is the service provider?](#what-is-the-service-provider)
7. [What is the composer?](#what-is-the-composer)
8. [What are jobs and when we use them?](#what-are-jobs-and-when-we-use-them)
9. [What is dependency injection?](#what-is-dependency-injection)

### Q&A

#### Explain SOLID <a name="explain-solid"></a>
**Q: Explain SOLID principles.**
A: SOLID is an acronym for five design principles intended to make software designs more understandable, flexible, and maintainable. The principles are Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, and Dependency Inversion.

#### Explain Abstraction <a name="explain-abstraction"></a>
**Q: Explain Abstraction.**
A: Abstraction in computer science is a method of reducing complexity and allowing efficient design and implementation in complex software systems by hiding the technical complexity and only showing the essential features of the object.

### Explain Polymorphism concept in computer science <a name="explain-polymorphism-concept-in-computer-science"></a>
**Q: What is polymorphism in computer science?**
**A:** Polymorphism is a fundamental concept in object-oriented programming that allows objects to be treated as instances of their parent class, enabling a single interface to handle different underlying data types. There are two main types: compile-time (or static), which includes method overloading, and run-time (or dynamic), which involves method overriding through inheritance.

### Explain Single Responsibility with examples <a name="explain-single-responsibility-with-examples"></a>
**Q: What does Single Responsibility Principle (SRP) mean and can you provide an example?**
**A:** The Single Responsibility Principle is one of the SOLID principles which states that a class should have only one reason to change, meaning it should perform a single kind of duty. For example, a class `InvoiceProcessor` should handle invoice processing, but not the invoice's persistence to a database; the latter should be handled by another class like `InvoiceRepository`.

### Explain Design Pattern <a name="explain-design-pattern"></a>
**Q: What is a design pattern in software engineering?**
**A:** Design patterns are typical solutions to common problems in software design. They serve as templates that can be applied to real-world programming issues. Patterns are categorized into Creational, Structural, and Behavioral types, each addressing different aspects of design challenges.

### Design Pattern you know and used before <a name="design-pattern-you-know-and-used-before"></a>
**Q: What design patterns have you used?**
**A:** I've frequently used the Singleton pattern for ensuring only one instance of a class is created, the Observer pattern to enable a subscription mechanism to notify multiple objects about any events that happen to the object they are observing, and the Factory Method pattern which provides an interface for creating objects but allows subclasses to alter the type of objects that will be created.

### Explain Async, Sync <a name="explain-async-sync"></a>
**Q: What is the difference between asynchronous and synchronous programming?**
**A:** In synchronous programming, tasks are performed one after another, each task starting only after the previous one has finished. Asynchronous programming allows a task to be initiated and then put aside until a later time while other tasks run in the meantime, improving the efficiency of application execution.

### Proxy Servers <a name="proxy-servers"></a>
**Q: What are proxy servers and how do they work?**
**A:** Proxy servers act as intermediaries between a client and a server, forwarding client requests to the server and then returning the server's response to the client. This provides increased privacy and security and can also be used to cache data to improve load times.

### Explain Polymorphism concept in computer science <a name="explain-polymorphism-concept-in-computer-science"></a>
**Q: What is polymorphism in computer science?**
**A:** Polymorphism is a fundamental concept in object-oriented programming that allows objects to be treated as instances of their parent class, enabling a single interface to handle different underlying data types. There are two main types: compile-time (or static), which includes method overloading, and run-time (or dynamic), which involves method overriding through inheritance.

### Explain Single Responsibility with examples <a name="explain-single-responsibility-with-examples"></a>
**Q: What does Single Responsibility Principle (SRP) mean and can you provide an example?**
**A:** The Single Responsibility Principle is one of the SOLID principles which states that a class should have only one reason to change, meaning it should perform a single kind of duty. For example, a class `InvoiceProcessor` should handle invoice processing, but not the invoice's persistence to a database; the latter should be handled by another class like `InvoiceRepository`.

### Explain Design Pattern <a name="explain-design-pattern"></a>
**Q: What is a design pattern in software engineering?**
**A:** Design patterns are typical solutions to common problems in software design. They serve as templates that can be applied to real-world programming issues. Patterns are categorized into Creational, Structural, and Behavioral types, each addressing different aspects of design challenges.

### Design Pattern you know and used before <a name="design-pattern-you-know-and-used-before"></a>
**Q: What design patterns have you used?**
**A:** I've frequently used the Singleton pattern for ensuring only one instance of a class is created, the Observer pattern to enable a subscription mechanism to notify multiple objects about any events that happen to the object they are observing, and the Factory Method pattern which provides an interface for creating objects but allows subclasses to alter the type of objects that will be created.

### Explain Async, Sync <a name="explain-async-sync"></a>
**Q: What is the difference between asynchronous and synchronous programming?**
**A:** In synchronous programming, tasks are performed one after another, each task starting only after the previous one has finished. Asynchronous programming allows a task to be initiated and then put aside until a later time while other tasks run in the meantime, improving the efficiency of application execution.

### Proxy Servers <a name="proxy-servers"></a>
**Q: What are proxy servers and how do they work?**
**A:** Proxy servers act as intermediaries between a client and a server, forwarding client requests to the server and then returning the server's response to the client. This provides increased privacy and security and can also be used to cache data to improve load times.

### What are Multi-Tenant Servers <a name="what-are-multi-tenant-servers"></a>
**Q: What are Multi-Tenant Servers?**  
A: Multi-tenant servers host multiple clients (tenants) on the same server infrastructure. Each tenant's data and applications are isolated but operate on shared resources like databases, compute resources, and storage systems. This architecture is cost-effective and efficient for managing large numbers of users, especially in cloud environments or SaaS (Software as a Service) applications, where scalability and resource optimization are crucial.

### Why we need Tokens for authentication <a name="why-we-need-tokens-for-authentication"></a>
**Q: Why do we need Tokens for authentication?**  
A: Tokens, such as JWTs (JSON Web Tokens), are used in authentication to securely transmit information between parties as a JSON object. They are crucial because they allow the server to verify the token's validity without storing session information, thus supporting stateless authentication. Tokens enhance security by ensuring that the authentication information is protected with encryption and signatures and provide a scalable way to handle authentication across distributed systems.

### Authentication vs Authorization <a name="authentication-vs-authorization"></a>
**Q: What is the difference between Authentication and Authorization?**  
A: Authentication is the process of verifying who a user is, while authorization is the process of verifying what they have access to. Authentication typically precedes authorization; once a user's identity is confirmed through login credentials, biometrics, or tokens, authorization then checks whether they have the rights to access certain resources or perform specific actions within the system.

### Monolith vs Microservices <a name="monolith-vs-microservices"></a>
**Q: What is the difference between Monolith and Microservices architectures?**  
A: Monolith architecture involves building a single unified software application where all components are interconnected and interdependent. In contrast, Microservices architecture breaks down the application into smaller, independent services that communicate over a network. Microservices allow for easier scaling and better fault isolation, making it easier to update and maintain parts of the application without affecting the whole system. However, they can introduce complexity in terms of network latency and the management of distributed systems.

### What is a Load Balancer and its importance? <a name="what-is-a-load-balancer-and-its-importance"></a>
**Q: What is a Load Balancer and why is it important?**  
A: A Load Balancer is a device that distributes network or application traffic across multiple servers to enhance the efficiency, reliability, and capacity of service handling. It ensures no single server bears too much demand. By spreading the load, it helps prevent server overload, minimizes response time, and ensures a smoother distribution of workloads. It is vital for maintaining system performance and availability, especially in environments with high traffic or in distributed systems like microservices.

### How Can I enhance the API and reduce API response time? <a name="how-can-i-enhance-the-api-and-reduce-api-response-time"></a>
**Q: How can I enhance the API and reduce API response time?**  
A: Enhancing API performance and reducing response times can be achieved through several strategies:
1. **Caching:** Store frequently accessed data in cache to avoid unnecessary database queries.
2. **Optimize Queries:** Ensure database queries are efficient and fetch only the necessary data.
3. **Use Content Delivery Networks (CDNs):** Serve content from locations closer to the user to reduce latency.
4. **Load Balancing:** Distribute incoming API requests across multiple servers to ensure no single server becomes a bottleneck.
5. **Asynchronous Processing:** Handle tasks that are resource-intensive or time-consuming in an asynchronous manner.
6. **Code Optimization:** Regularly profile and optimize your API’s codebase to remove bottlenecks.




### Contributing to Q&A
To add a question and answer to this section:
1. Add your question to the 'Table of Contents' with a link.
2. Write your question and answer in the Q&A section following the format above.
3. Make sure to test your changes to the README for proper formatting.
