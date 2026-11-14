# afiarena
AfiArena is a scalable gaming tournament management platform that enables player registration, tournament participation, real-time leaderboard tracking, notifications, and analytics using a microservices architecture.
CGI java fullstack interview questions segregate pani kodu. frquently asked questions, check panu glassdoors,linkedin la.angular ,java,spring,microservices,system design elameh serach pani consolodated questions kodu

Machi 🔥 CGI Java Full Stack Developer Interview – Consolidated Question Bank (2025–2026) ready!

Glassdoor, LinkedIn, GeeksforGeeks மற்றும் CGI interview experience reports search panni, Java, Angular, Spring Boot, Microservices, SQL, Coding, System Design, Scenario-Based Questions ellathayum segregate panniruken.

Important: Actual CGI interview-la candidates report panna questions-ku 🔴 mark panniruken. Adhe topic-la preparation-ku important questions-ku 🟡 mark panniruken.

Indha list mainly 2–6 years experienced Java Full Stack Developers target panni prepare panniruken. Exact questions project, experience, client, interviewer poruthu change aagalam.

🔥 CGI Interview – Research Findings
Glassdoor & LinkedIn-la enna kandupidichen?
1. CGI Bengaluru – May 2026 (Glassdoor)

Senior Java Developer interview-la ketta questions:

Externalization
final vs finally vs finalize
Method Overloading
Serialization
Thread Lifecycle
Marker Interface
Dependency Injection
Spring Boot Actuator
POST vs PUT
Monolithic vs Microservices
Reported interview process: 2 technical rounds + HR/managerial round. 

2. CGI – 4 Years Experience (LinkedIn)

Candidate share panna questions:

Java 8 features
Optional
Comparator vs Comparable
Abstract Class vs Interface
Immutable Class
HashMap vs Hashtable
ArrayList vs LinkedList
Spring Boot annotations
Global Exception Handling
Java Streams coding 
3. CGI – 3.4 Years Experience (LinkedIn, May 2025)

OOP concepts
AOP
Checked vs Unchecked Exception
Custom Exception
Object class
SQL second-highest salary 
4. CGI – March 2026 (Glassdoor)

Reported interview process:

Java, Spring, Kafka, Java 8 MCQ + coding
Core Java, Spring Boot, Microservices
Client round with coding
Scenario-based managerial round 
5. CGI – Senior Software Engineer (Glassdoor, July 2026)

System Design
SOLID Principles
Design Patterns
TDD
AWS
Java Collections
Spring
Multithreading 
Research conclusion: Java fundamentals, Collections, Java 8 Streams, Spring Boot and project-based scenarios recur across multiple reports. Angular-specific CGI reports are comparatively limited, so Angular section-la common full-stack interview questions-um include panniruken.

🟢 SECTION 1: CORE JAVA – 35 Questions
Priority: VERY HIGH ⭐⭐⭐⭐⭐

A. OOP Concepts
🔴 What are the four pillars of OOP?
🔴 What is the difference between Abstract Class and Interface?
🔴 What is Method Overloading vs Method Overriding?
🟡 Can we override a static method?
🟡 Can we overload the main method?
🟡 What is runtime polymorphism?
🟡 What is compile-time polymorphism?
🟡 What is constructor chaining?
🟡 What is the difference between this and super?
🟡 What is encapsulation? Explain with a real-time example.
B. String Handling
🔴 Difference between == and .equals()?
🟡 Difference between String, StringBuilder and StringBuffer?
🟡 Why is String immutable in Java?
🟡 What is String Constant Pool?
🟡 What happens when we create a String using new?
🟡 How does String interning work?
C. Exception Handling
🔴 Checked vs Unchecked Exceptions?
🔴 Difference between throw and throws?
🔴 Difference between final, finally, and finalize?
🔴 How do you create a custom exception?
🟡 Can we have multiple catch blocks?
🟡 What happens if an exception occurs inside a finally block?
🔴 What is try-with-resources?
D. Java Fundamentals
🔴 What is Serialization?
🔴 What is Externalization?
🔴 What is a Marker Interface?
🔴 What is the static keyword?
🔴 What is the Object class?
🟡 What is the difference between shallow copy and deep copy?
🔴 How do you create an immutable class?
🟡 What is the difference between final and static?
🟡 What is the purpose of transient?
🟡 What is the difference between JVM, JRE and JDK?
🔴 Explain Java 17 features.
🟡 Explain Java memory management.
Most important: Hashing, String immutability, Exception Handling, Serialization, OOP.

🟢 SECTION 2: COLLECTIONS FRAMEWORK – 25 Questions
Priority: VERY HIGH ⭐⭐⭐⭐⭐

List, Set and Map
🔴 Difference between ArrayList and LinkedList?
🔴 Difference between HashMap and Hashtable?
🔴 How does HashMap work internally?
🔴 Difference between HashMap and ConcurrentHashMap?
🟡 Difference between HashSet and TreeSet?
🟡 Does HashSet allow duplicate objects?
🟡 How does HashSet work internally?
🟡 Difference between List, Set and Map?
🟡 Difference between HashMap and LinkedHashMap?
🟡 Difference between HashMap and TreeMap?
Internal Working
🟡 What happens when two keys have the same hashCode?
🟡 How does HashMap handle collisions?
🟡 What is HashMap load factor?
🟡 When does HashMap resize?
🟡 Why must we override equals() and hashCode() together?
🟡 What happens if we override equals() but not hashCode()?
🟡 Can we use a custom object as a HashMap key?
🟡 What happens if a HashMap key is modified after insertion?
Scenario-Based Questions
🟡 How do you remove duplicates from an ArrayList?
🟡 How do you sort a list of Employee objects?
🔴 Comparable vs Comparator?
🟡 Fail-fast vs fail-safe iterators?
🟡 What is ConcurrentModificationException?
🟡 How do you make a collection thread-safe?
🟡 When would you choose ConcurrentHashMap over HashMap?
🔥 Important CGI-style Scenario
class Employee {
    int id;
    String name;

    Employee(int id, String name) {
        this.id = id;
        this.name = name;
    }
}
Set<Employee> employees = new HashSet<>();

employees.add(new Employee(1, "Arun"));
employees.add(new Employee(1, "Arun"));

System.out.println(employees.size());
Questions:

What will be the output?
Why does HashSet allow both objects?
How do you prevent duplicates?
What happens if we override only equals()?
How does HashSet use HashMap internally?
Indha type of internal-working questions-ku prepare aaganum.

🟢 SECTION 3: JAVA 8 / STREAM API – 25 Questions
Priority: VERY HIGH ⭐⭐⭐⭐⭐

Java 8 Concepts
🔴 What are the features of Java 8?
🔴 What is a Functional Interface?
🔴 What is Lambda Expression?
🔴 What is Optional?
🟡 What is Stream API?
🟡 Difference between Stream and Collection?
🟡 Difference between map() and flatMap()?
🟡 Difference between filter() and map()?
🟡 Difference between findFirst() and findAny()?
🟡 Difference between intermediate and terminal operations?
Stream Operations
🟡 Difference between reduce() and collect()?
🟡 What is Collectors.groupingBy()?
🟡 What is Collectors.partitioningBy()?
🟡 How does distinct() work?
🟡 Difference between sorted() and Comparator?
🟡 What is a parallel stream?
🟡 When should we avoid parallel streams?
🟡 What is method reference?
🟡 Difference between Predicate, Function, Consumer and Supplier?
🟡 What are default and static methods in interfaces?
Java 8 Coding Questions
🔴 Find the frequency of each character using Streams.
🔴 Find the sum of positive and negative numbers separately.
🟡 Find duplicate elements using Streams.
🟡 Find the second-highest salary from an Employee list.
🟡 Group employees by department using Streams.
Must practice: filter, map, flatMap, sorted, distinct, groupingBy, toMap, reduce.

🟢 SECTION 4: MULTITHREADING – 20 Questions
Priority: HIGH ⭐⭐⭐⭐

🔴 What is the Thread Lifecycle?
🔴 How many ways can we create a Thread?
🔴 What is synchronization?
🔴 What is thread safety?
🔴 Difference between wait() and sleep()?
🔴 Difference between wait(), notify() and notifyAll()?
🟡 Difference between Runnable and Callable?
🟡 Difference between start() and run()?
🟡 What is deadlock?
🟡 How do you prevent deadlock?
🟡 What is volatile?
🟡 What is AtomicInteger?
🟡 What is ExecutorService?
🟡 What is ThreadPoolExecutor?
🟡 What is CompletableFuture?
🟡 Difference between synchronized and ReentrantLock?
🟡 What is ThreadLocal?
🟡 What is race condition?
🟡 How does ConcurrentHashMap support concurrency?
🟡 How do you handle multiple concurrent API requests?
🔵 SECTION 5: SPRING BOOT – 35 Questions
Priority: VERY HIGH ⭐⭐⭐⭐⭐

Spring Fundamentals
🔴 What is Spring Framework?
🔴 What is the difference between Spring and Spring Boot?
🔴 What is Dependency Injection?
🔴 What are the types of Dependency Injection?
🔴 What is IoC Container?
🔴 What is @SpringBootApplication?
🔴 Difference between @Component, @Service and @Repository?
🟡 Difference between @Controller and @RestController?
🟡 Difference between @Autowired and constructor injection?
🟡 What is Bean Scope?
Spring Boot Internals
🟡 How does Spring Boot Auto Configuration work?
🟡 What happens when a Spring Boot application starts?
🟡 What is the Spring Bean Lifecycle?
🟡 What is @Configuration?
🟡 What is @Bean?
🔴 What are Spring Profiles?
🔴 What is Spring Boot Actuator?
🟡 Difference between application.properties and application.yml?
🟡 What is @Primary?
🟡 What is @Qualifier?
REST API
🔴 Difference between POST and PUT?
🟡 Difference between PUT and PATCH?
🟡 Difference between @RequestParam and @PathVariable?
🟡 What is @RequestBody?
🟡 What is ResponseEntity?
🟡 How do you validate request payloads?
🔴 How do you implement Global Exception Handling?
🟡 What is @ControllerAdvice?
🟡 What is @ExceptionHandler?
🟡 How do you implement pagination and sorting?
Advanced Spring Boot
🟡 How does @Transactional work?
🟡 What are transaction propagation types?
🟡 How do you implement Spring Security with JWT?
🟡 How do you improve Spring Boot application performance?
🟡 How do you handle a slow REST API?
🔥 Real-Time Scenario
Interviewer:

Your Spring Boot API is taking 10 seconds to respond. How will you troubleshoot it?

Expected discussion:

Application logs and tracing
Database query performance
Missing indexes
N+1 query problem
External API latency
Thread pool saturation
Connection pool configuration
Caching
JVM memory and GC
Indha madhiri scenario-based questions-ku strong-ah prepare aagu.

🔵 SECTION 6: MICROSERVICES – 30 Questions
Priority: VERY HIGH ⭐⭐⭐⭐⭐

Architecture
🔴 Monolithic vs Microservices?
🟡 What are the advantages of Microservices?
🟡 What are the disadvantages of Microservices?
🟡 How do Microservices communicate?
🟡 Synchronous vs Asynchronous Communication?
🟡 REST vs Kafka?
🟡 What is Service Discovery?
🟡 What is API Gateway?
🟡 What is Load Balancing?
🟡 What is Config Server?
Resilience
🟡 What is Circuit Breaker?
🟡 What is Resilience4j?
🟡 What is Retry Pattern?
🟡 What is Timeout Pattern?
🟡 What is Bulkhead Pattern?
🟡 How do you handle service failure?
🟡 How do you prevent cascading failures?
🟡 What is distributed tracing?
🟡 What is correlation ID?
🟡 How do you monitor Microservices?
Transactions and Data
🟡 What is Saga Pattern?
🟡 Choreography vs Orchestration?
🟡 What is Eventual Consistency?
🟡 How do you manage distributed transactions?
🟡 Database per Service vs Shared Database?
Scenario-Based Questions
🟡 Payment Service is down. How will Order Service behave?
🟡 How do you handle duplicate Kafka messages?
🟡 How do you secure communication between Microservices?
🟡 How do you deploy Microservices without downtime?
🟡 How do you debug an issue across five Microservices?
🟣 SECTION 7: ANGULAR – 35 Questions
Priority: VERY HIGH ⭐⭐⭐⭐⭐

Note: CGI-specific Angular question reports kammiya irukku. Below questions are consolidated Angular full-stack preparation topics, not all verified as asked at CGI.

Angular Basics
What is Angular?
Angular vs AngularJS?
What are Angular Components?
What are Directives?
What are the types of Directives?
What is Data Binding?
Explain One-way vs Two-way Data Binding.
What is Dependency Injection in Angular?
What are Angular Services?
What are Standalone Components?
Components and Lifecycle
Explain Angular Component Lifecycle Hooks.
Difference between constructor and ngOnInit?
What is ngOnChanges?
What is ngOnDestroy?
What is Change Detection?
What is OnPush Change Detection?
What are Signals in Angular?
RxJS and Observables
Observable vs Promise?
Subject vs BehaviorSubject?
What is RxJS?
Difference between switchMap, mergeMap and concatMap?
What is debounceTime?
How do you prevent memory leaks from subscriptions?
Routing and Forms
What is Angular Routing?
What are Route Guards?
What is Lazy Loading?
Reactive Forms vs Template-driven Forms?
How do you implement Custom Validators?
HTTP and API Integration
What is HttpClient?
What is an HTTP Interceptor?
How do you attach a JWT token to API requests?
How do you handle HTTP errors globally?
How do you handle CORS issues with Spring Boot?
How do you share data between unrelated components?
How do you improve Angular application performance?
🔥 Angular Scenario-Based Questions
Scenario 1: Angular page-la API response varathuku 8 seconds aaguthu. How will you troubleshoot?

Scenario 2: User search box-la type pannumbodhu every keystroke-ku API call poguthu. How will you optimize?

Scenario 3: JWT token expire aagiduchu. Angular-la refresh token flow eppadi implement pannuva?

Scenario 4: Parent and child components-ku data share panna enna approaches use pannuva?

Scenario 5: Angular application-la 10,000 records display pannanum. Performance eppadi improve pannuva?

🟡 SECTION 8: SQL + JPA + HIBERNATE – 25 Questions
Priority: VERY HIGH ⭐⭐⭐⭐⭐

SQL
🔴 Write a query to find the second-highest salary.
🔴 Find the third-highest salary without a subquery.
🟡 Difference between INNER JOIN and LEFT JOIN?
🟡 Difference between WHERE and HAVING?
🟡 Difference between DELETE, TRUNCATE and DROP?
🟡 What is an Index?
🟡 Clustered vs Non-clustered Index?
🟡 What is Database Normalization?
🟡 What are ACID properties?
🟡 How do you optimize a slow SQL query?
Hibernate / JPA
🟡 What is JPA?
🟡 Difference between JPA and Hibernate?
🟡 What is EntityManager?
🟡 Difference between save() and saveAndFlush()?
🟡 What is Lazy Loading?
🟡 What is Eager Loading?
🟡 What is N+1 Query Problem?
🟡 How do you solve N+1 queries?
🟡 Difference between OneToMany and ManyToOne?
🟡 What is CascadeType?
🟡 What is orphanRemoval?
🟡 What is Optimistic Locking?
🟡 What is Pessimistic Locking?
🟡 What is Hibernate First-Level Cache?
🟡 How do you implement pagination using Spring Data JPA?
🟠 SECTION 9: JAVA CODING QUESTIONS – 25 Problems
Priority: VERY HIGH ⭐⭐⭐⭐⭐

Directly Reported CGI Coding Questions
No.	Coding Problem	Source
1	Check whether a number is prime and optimize the solution	LinkedIn
2	Move all zeros to the end of an array	LinkedIn
3	Calculate positive and negative sums using Streams	LinkedIn
4	Find character frequency using Streams	LinkedIn
5	Find second-highest salary using SQL	LinkedIn
6	Find third-highest salary without subquery	LinkedIn
7	Print star patterns	Glassdoor
Sources: 

Additional Important Coding Questions
Reverse a String without built-in methods.
Check whether a String is palindrome.
Find duplicate characters in a String.
Find the first non-repeating character.
Find duplicate numbers in an array.
Find the missing number in an array.
Find the second-largest number.
Find the maximum occurring character.
Sort an Employee list by salary.
Find the highest-paid employee using Streams.
Group employees by department.
Count word frequency using HashMap.
Check whether two Strings are anagrams.
Find common elements between two arrays.
Find the longest substring without repeating characters.
Implement Two Sum using HashMap.
Merge two sorted arrays.
Find the maximum number of concurrent users from login/logout timestamps.
Important: Problems 23 and 25 appear in a third-party CGI full-stack interview narrative, but that report is not independently verified. 

🔴 SECTION 10: SYSTEM DESIGN – 20 Questions
Priority: HIGH ⭐⭐⭐⭐

High-Level System Design
Design an E-commerce Application.
Design an Order Management System.
Design a URL Shortener.
Design a Notification Service.
Design a Ticket Management System.
Design an Employee Management System.
Design a Payment Processing System.
Design an API Rate Limiter.
Design a File Upload Service.
Design a Logging and Monitoring System.
Architecture Discussion
How do you design a system for 10,000 concurrent users?
How do you scale a Spring Boot application?
How do you design a highly available REST API?
How do you implement caching using Redis?
How do you handle database bottlenecks?
How do you ensure data consistency across services?
How do you design authentication for a distributed system?
How do you implement fault tolerance?
How do you handle high-volume Kafka events?
How do you design a system that supports zero-downtime deployment?
🔥 System Design Scenario
Design an Order Management System using Angular + Spring Boot + Microservices.

Interviewer follow-up questions:

Which Microservices will you create?
How will Angular communicate with the backend?
How will Order Service communicate with Payment Service?
What happens if payment succeeds but inventory update fails?
How will you handle duplicate orders?
Where will you use Kafka?
Where will you use Redis?
How will you implement authentication?
How will you handle 10,000 concurrent requests?
How will you monitor production failures?
Indha one system design prepare pannale multiple architecture concepts cover pannalam.

🔴 SECTION 11: REAL-TIME SCENARIO QUESTIONS – 20 Questions
Priority: VERY HIGH ⭐⭐⭐⭐⭐

Experience irukkura candidates-ku indha section romba important.

Spring Boot Scenarios
🔴 Your Spring Boot application is running slowly. How will you investigate?
🔴 REST API response time suddenly increases. What will you check?
🔴 Your application throws OutOfMemoryError. How will you troubleshoot?
🟡 Database connection pool is exhausted. What will you do?
🟡 API returns 500 errors intermittently. How will you debug?
Microservices Scenarios
🟡 One Microservice is down. How will other services handle it?
🟡 Kafka consumer processes the same message twice. How will you handle it?
🟡 Two services update related data, but one fails. How will you maintain consistency?
🟡 API Gateway becomes a bottleneck. What will you do?
🟡 One Microservice is consuming excessive memory. How will you investigate?
Angular Scenarios
🟡 Angular application becomes slow after navigation. How will you debug?
🟡 API gets called multiple times unexpectedly. How will you prevent it?
🟡 How will you handle an expired access token?
🟡 How will you prevent unnecessary component re-rendering?
🟡 How will you handle multiple dependent API calls?
Database / Production Scenarios
🔴 How will you optimize a slow SQL query?
🔴 How will you handle 5,000 concurrent users?
🟡 Two users update the same record simultaneously. How will you handle it?
🟡 Database CPU utilization reaches 95%. What will you investigate?
🟡 Production application works locally but fails after deployment. How will you troubleshoot?
Questions 1, 2, 3, 16 and 17 are supported by a CGI candidate's LinkedIn interview report. 

🟤 SECTION 12: DESIGN PATTERNS + SOLID – 15 Questions
What are SOLID Principles?
Explain Single Responsibility Principle.
Explain Open/Closed Principle.
Explain Dependency Inversion Principle.
What is Singleton Design Pattern?
How do you implement a thread-safe Singleton?
How can Singleton be broken?
What is Factory Design Pattern?
Factory vs Abstract Factory?
What is Builder Design Pattern?
What is Strategy Design Pattern?
What is Observer Design Pattern?
What is Circuit Breaker Pattern?
What is Repository Pattern?
Which design patterns have you used in your project?
🟤 SECTION 13: KAFKA + DEVOPS + CLOUD – 20 Questions
Kafka
What is Apache Kafka?
What is a Topic?
What is a Partition?
What is a Consumer Group?
How does Kafka maintain message ordering?
What is an Offset?
How do you handle failed Kafka messages?
How do you prevent duplicate message processing?
DevOps
What is Docker?
What is the difference between Docker Image and Container?
What is Kubernetes?
What is CI/CD?
How do you deploy a Spring Boot application?
What is the difference between Git merge and rebase?
Cloud / Monitoring
What is AWS EC2?
What is AWS S3?
What is a Load Balancer?
What is Horizontal vs Vertical Scaling?
What is Prometheus?
How do you monitor Microservices in production?
CGI interview reports mention Kafka, Azure, AWS, Git, cloud fundamentals and deployment-related topics. 

🟢 SECTION 14: PROJECT-BASED QUESTIONS – 20 Questions
Priority: EXTREMELY HIGH ⭐⭐⭐⭐⭐

CGI-la project experience based questions-um prepare pannanum.

Explain your current project architecture.
What is your role in the project?
Explain the end-to-end request flow from Angular to Database.
How many Microservices are there in your project?
How do your Microservices communicate?
Which Java version are you using?
Which Angular version are you using?
Which Spring Boot version are you using?
How do you implement authentication?
How do you handle exceptions?
How do you manage transactions?
How do you handle production issues?
Explain one challenging bug you fixed.
How do you optimize application performance?
What is your deployment process?
How do you write unit tests?
How do you handle code reviews?
What is your Git branching strategy?
Have you worked on performance optimization?
Explain one feature you developed end-to-end.
Preparation tip: Project explanation-la architecture diagram, one feature flow, one production issue, one performance improvement, one challenging bug ready-ah vechiko.

🟣 SECTION 15: HR + MANAGERIAL ROUND – 15 Questions
Tell me about yourself.
Explain your current project.
Why are you looking for a job change?
Why do you want to join CGI?
What are your current responsibilities?
What is your biggest technical challenge?
How do you handle production incidents?
How do you handle conflicts within your team?
Have you worked directly with clients?
How do you handle tight deadlines?
Are you comfortable working with different technologies?
What is your current CTC?
What is your expected CTC?
What is your notice period?
Do you have any questions for us?
📊 CGI Java Full Stack – Preparation Priority
Research reports and common interview coverage base panni naan suggest panra priority:

Technology	Priority	Preparation
Core Java	⭐⭐⭐⭐⭐	Must prepare
Collections	⭐⭐⭐⭐⭐	Must prepare
Java 8 Streams	⭐⭐⭐⭐⭐	Must prepare
Spring Boot	⭐⭐⭐⭐⭐	Must prepare
Microservices	⭐⭐⭐⭐⭐	Must prepare
Project Explanation	⭐⭐⭐⭐⭐	Must prepare
Coding	⭐⭐⭐⭐⭐	Must practice
SQL + JPA	⭐⭐⭐⭐⭐	Must prepare
Angular	⭐⭐⭐⭐⭐	Full-stack role-ku essential
Scenario-Based	⭐⭐⭐⭐⭐	Experienced candidates
Multithreading	⭐⭐⭐⭐	High priority
System Design	⭐⭐⭐⭐	Mid/senior roles
Design Patterns	⭐⭐⭐⭐	High priority
Kafka	⭐⭐⭐	Project-dependent
Docker / Cloud	⭐⭐⭐	Project-dependent
Indha priority ratings en preparation recommendations; CGI official interview weightage illa.

📅 7-Day CGI Interview Preparation Plan
Day	Topics	Practice
Day 1	Core Java + OOP + String + Exceptions	5 coding problems
Day 2	Collections + Java 8 Streams	10 Stream programs
Day 3	Spring Boot + REST + JPA	Build/explain CRUD API
Day 4	Microservices + Kafka + Security	5 real-time scenarios
Day 5	Angular + RxJS + Routing + Forms	Angular coding scenarios
Day 6	SQL + Multithreading + Design Patterns	SQL queries + coding
Day 7	System Design + Project + HR	Mock interview
🎯 TOP 25 – FIRST PREPARE THESE
Time kammiya irundha indha 25 questions first complete pannu.

No.	Question
1	How does HashMap work internally?
2	HashMap vs ConcurrentHashMap?
3	How does HashSet handle duplicate objects?
4	equals() vs hashCode()?
5	Abstract Class vs Interface?
6	Checked vs Unchecked Exception?
7	Java 8 features and Stream API?
8	map() vs flatMap()?
9	Find duplicates using Java Streams.
10	Find second-highest salary using SQL.
11	What is Dependency Injection?
12	How does @SpringBootApplication work?
13	@Component vs @Service vs @Repository?
14	How does @Transactional work?
15	How do you implement Global Exception Handling?
16	Monolithic vs Microservices?
17	How do Microservices communicate?
18	What is Circuit Breaker?
19	How do you handle distributed transactions?
20	Angular Lifecycle Hooks?
21	Observable vs Promise?
22	switchMap vs mergeMap?
23	How does Angular HTTP Interceptor work?
24	Explain your project architecture.
25	How do you troubleshoot a slow Spring Boot API?
🔗 Research Sources
Actual candidate experiences paakka:

Glassdoor

CGI Senior Java Developer Interview Experiences
CGI Java Developer Interview Questions
CGI Senior Software Engineer Interviews
LinkedIn

CGI Java Backend – 4 YOE Interview Experience
CGI Java Developer – 3.4 YOE Questions
CGI Java Developer – 2.8 YOE Interview
CGI Production Scenario Interview Questions
Other

GeeksforGeeks – CGI Java Interview Experience
Note: Glassdoor/LinkedIn experiences are self-reported. Some may not be independently verifiable, and not every question will appear in every CGI interview.

🔥 Machi, rendu details sollu:
1. Unakku ethana years of experience?

2–3 YOE
3–4 YOE
4–6 YOE
6+ YOE
2. CGI-la endha role-ku interview?

Java Full Stack Developer
Senior Java Full Stack Developer
Software Engineer
Senior Software Engineer
Idha sonna, un experience-ku match aagura CGI most-important 100 questions shortlist panni, Java + Angular + Spring Boot + Microservices + Coding + Real-time Scenarios ellathukkum interview-la sollura madhiri English answers + easy Thanglish explanation + code examples oda prepare pannalam.






