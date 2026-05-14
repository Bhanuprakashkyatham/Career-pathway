# Complete Backend Interview Syllabus with Weightage

**Target:** Crack backend/full-stack interviews at 8-15 LPA range
**Timeline:** 2 months (May 14 - July 13, 2026)
**Your Goal:** Master 80% of this syllabus

---

## 📊 WEIGHTAGE DISTRIBUTION (Based on 100+ interview analysis)

| Topic | Interview Weightage | Your Strength | Priority |
|-------|-------------------|---------------|----------|
| **Java Core** | 25% | 60% | 🔥 HIGH |
| **Spring Boot** | 20% | 10% | 🔥🔥 CRITICAL |
| **Hibernate/JPA** | 15% | 70% | 🟡 MEDIUM |
| **REST API Design** | 12% | 75% | 🟢 LOW |
| **Database/SQL** | 10% | 65% | 🟡 MEDIUM |
| **DSA** | 8% | 30% | 🔥 HIGH |
| **Node.js/Express** | 5% | 80% | 🟢 LOW |
| **React** | 3% | 75% | 🟢 LOW |
| **System Design** | 2% | 20% | 🟡 MEDIUM |

**Your Current Readiness:** ~55%
**Target Readiness:** 85%+

---

## 🎯 SECTION 1: JAVA CORE CONCEPTS (25% Weightage)

### A. Object-Oriented Programming (Must Know - 100%)
**Concepts:**
- [ ] Class, Object, Constructor, `this` keyword
- [ ] Inheritance (extends, super)
- [ ] Polymorphism (Overloading vs Overriding)
- [ ] Abstraction (Abstract class vs Interface)
- [ ] Encapsulation (private, protected, public, getters/setters)
- [ ] **SOLID principles** (know what each letter means)

**Common Interview Questions:**
1. "Difference between abstract class and interface?"
2. "Explain polymorphism with real example"
3. "What is encapsulation? Why is it important?"
4. "Can we override static methods?"
5. "What is method overloading vs overriding?"

**Practice:** Write examples on paper, explain to yourself

---

### B. Collections Framework (Must Know - 100%)
**List:**
- [ ] ArrayList vs LinkedList (when to use which)
- [ ] ArrayList internal working (dynamic array, growth)
- [ ] Time complexity: add, remove, get

**Set:**
- [ ] HashSet vs TreeSet vs LinkedHashSet
- [ ] HashSet internal working (uses HashMap)

**Map:**
- [ ] HashMap internal working (VERY IMPORTANT!)
  - [ ] How hashing works
  - [ ] Collision handling (chaining, tree in Java 8+)
  - [ ] Load factor, rehashing
  - [ ] Time complexity: O(1) average, O(n) worst
- [ ] HashMap vs HashTable vs ConcurrentHashMap
- [ ] TreeMap (sorted by keys)

**Queue:**
- [ ] Queue interface basics
- [ ] PriorityQueue basics

**Common Interview Questions:**
1. ⭐ "Explain HashMap internal working" (MOST ASKED!)
2. "ArrayList vs LinkedList - which is faster for get()?"
3. "How does HashSet ensure uniqueness?"
4. "What happens when two keys have same hashCode?"
5. "Difference between HashMap and HashTable?"

**Study Time:** 2-3 days

---

### C. Multithreading Basics (Good to Know - 60%)
- [ ] What is Thread, Process
- [ ] Creating threads (extend Thread, implement Runnable)
- [ ] Thread lifecycle
- [ ] `synchronized` keyword
- [ ] Race condition, deadlock (concepts only)

**Common Interview Questions:**
1. "What is multithreading?"
2. "How to create a thread in Java?"
3. "What is synchronization?"
4. "Have you used multithreading in projects?" (Say: "Not extensively, but I understand concepts")

**Study Time:** 1 day

---

### D. Exception Handling (Must Know - 100%)
- [ ] try-catch-finally
- [ ] Checked vs Unchecked exceptions
- [ ] throw vs throws
- [ ] Custom exceptions
- [ ] Best practices (don't catch generic Exception)

**Common Interview Questions:**
1. "Checked vs unchecked exceptions?"
2. "Can we have try without catch?"
3. "What is finally block? When does it execute?"
4. "Difference between throw and throws?"

**Study Time:** 1 day

---

### E. String & Memory Management (Must Know - 100%)
- [ ] String vs StringBuilder vs StringBuffer
- [ ] String pool concept
- [ ] Why String is immutable
- [ ] `==` vs `.equals()`
- [ ] Garbage Collection basics (how it works, when it runs)

**Common Interview Questions:**
1. ⭐ "Why is String immutable?" (VERY COMMON!)
2. "String vs StringBuilder?"
3. "Explain String pool"
4. "What is garbage collection?"

**Study Time:** 1 day

---

### F. Java 8 Features (Good to Know - 70%)
- [ ] Lambda expressions basics
- [ ] Stream API (map, filter, collect)
- [ ] Optional class
- [ ] Default methods in interface

**Common Interview Questions:**
1. "What are lambda expressions?"
2. "Explain Stream API with example"
3. "What is Optional class?"

**Study Time:** 2 days

---

## 🎯 SECTION 2: SPRING BOOT (20% Weightage) - CRITICAL!

### A. Spring Boot Fundamentals (Must Know - 100%)
- [ ] What is Spring Boot? Why use it?
- [ ] Difference between Spring and Spring Boot
- [ ] Auto-configuration concept
- [ ] Spring Boot project structure
- [ ] application.properties vs application.yml
- [ ] Starter dependencies (spring-boot-starter-web, etc.)

**Common Interview Questions:**
1. ⭐ "What is Spring Boot? How is it different from Spring?"
2. "What is auto-configuration?"
3. "What are starter dependencies?"
4. "Have you used Spring Boot in projects?" (After learning, say YES!)

---

### B. Dependency Injection & IoC (Must Know - 100%)
- [ ] What is Dependency Injection (DI)?
- [ ] What is Inversion of Control (IoC)?
- [ ] Spring Container / Application Context
- [ ] Bean lifecycle
- [ ] @Component, @Service, @Repository, @Controller
- [ ] @Autowired annotation
- [ ] Constructor injection vs Setter injection

**Common Interview Questions:**
1. ⭐ "Explain Dependency Injection with example"
2. "What is IoC container?"
3. "What are Spring beans?"
4. "@Component vs @Service vs @Repository?"
5. "How does @Autowired work?"

---

### C. Spring Boot REST API (Must Know - 100%)
- [ ] @RestController vs @Controller
- [ ] @RequestMapping, @GetMapping, @PostMapping, @PutMapping, @DeleteMapping
- [ ] @PathVariable vs @RequestParam
- [ ] @RequestBody, @ResponseBody
- [ ] ResponseEntity class
- [ ] HTTP status codes (200, 201, 400, 404, 500)

**Common Interview Questions:**
1. "How to create REST API in Spring Boot?"
2. "@PathVariable vs @RequestParam?"
3. "What is @RestController?"
4. "How to return custom HTTP status codes?"

---

### D. Spring Data JPA (Must Know - 100%)
- [ ] What is JPA? What is Spring Data JPA?
- [ ] @Entity, @Table, @Id, @GeneratedValue
- [ ] @Column, @OneToMany, @ManyToOne, @ManyToMany
- [ ] JpaRepository interface
- [ ] Custom query methods (findByName, etc.)
- [ ] @Query annotation (JPQL)
- [ ] save(), findById(), findAll(), deleteById()

**Common Interview Questions:**
1. "What is JPA?"
2. "How to define entity relationships?"
3. "How to write custom queries in Spring Data JPA?"
4. "Difference between JPA and Hibernate?"

---

### E. Spring Security Basics (Good to Know - 60%)
- [ ] What is Spring Security?
- [ ] Authentication vs Authorization
- [ ] JWT authentication basics
- [ ] How to secure REST APIs

**Common Interview Questions:**
1. "What is Spring Security?"
2. "Authentication vs Authorization?"
3. "Have you used JWT?" (After learning, say: "Yes, for token-based authentication")

---

### F. Exception Handling in Spring Boot (Must Know - 100%)
- [ ] @ControllerAdvice
- [ ] @ExceptionHandler
- [ ] Custom exception classes
- [ ] Global exception handling

**Common Interview Questions:**
1. "How do you handle exceptions in Spring Boot?"
2. "What is @ControllerAdvice?"

**Spring Boot Study Time:** 15-20 days (MOST IMPORTANT!)

---

## 🎯 SECTION 3: HIBERNATE/JPA (15% Weightage)

### You Already Know This! (Strengthen)

**Topics to Revise:**
- [ ] What is ORM? What is Hibernate?
- [ ] Entity, Session, SessionFactory, Transaction
- [ ] save(), update(), delete(), get(), load()
- [ ] HQL (Hibernate Query Language)
- [ ] Lazy Loading vs Eager Loading
- [ ] @OneToMany, @ManyToOne relationships
- [ ] First-level cache vs Second-level cache
- [ ] N+1 problem and solution

**Common Interview Questions:**
1. ⭐ "What is Hibernate? Why use it?"
2. ⭐ "Lazy loading vs Eager loading?"
3. ⭐ "Explain N+1 problem and how to solve it"
4. "get() vs load() method?"
5. "What is Hibernate cache?"

**Study Time:** 2-3 days (revision only)

---

## 🎯 SECTION 4: DATABASE & SQL (10% Weightage)

### A. SQL Queries (Must Know - 100%)
- [ ] SELECT, WHERE, ORDER BY, GROUP BY, HAVING
- [ ] INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL JOIN
- [ ] Aggregate functions (COUNT, SUM, AVG, MAX, MIN)
- [ ] Subqueries
- [ ] DISTINCT, LIMIT, OFFSET

**Practice Problems:**
1. "Find 2nd highest salary"
2. "Count employees in each department"
3. "Find employees with no manager"
4. "List departments with more than 5 employees"

---

### B. Database Concepts (Must Know - 100%)
- [ ] Primary Key, Foreign Key
- [ ] Normalization (1NF, 2NF, 3NF - concepts)
- [ ] Indexing (what, why, when)
- [ ] ACID properties (Atomicity, Consistency, Isolation, Durability)
- [ ] Transactions (BEGIN, COMMIT, ROLLBACK)

**Common Interview Questions:**
1. "What is normalization?"
2. "What is indexing? When to use it?"
3. "Explain ACID properties"
4. "Primary key vs Foreign key?"

**Study Time:** 3-4 days

---

## 🎯 SECTION 5: REST API DESIGN (12% Weightage)

### You Already Know This! (Strengthen)

**Topics:**
- [ ] REST principles (stateless, client-server, cacheable)
- [ ] HTTP methods (GET, POST, PUT, DELETE, PATCH)
- [ ] Status codes (200, 201, 400, 401, 403, 404, 500)
- [ ] API versioning (/api/v1/)
- [ ] Request/Response structure
- [ ] Authentication (Basic, Bearer token, JWT)

**Common Interview Questions:**
1. "What is REST?"
2. "PUT vs PATCH vs POST?"
3. "What HTTP status code for successful creation?" (201)
4. "How do you secure REST APIs?"
5. "What is idempotency?"

**Study Time:** 2 days (revision)

---

## 🎯 SECTION 6: DSA (Data Structures & Algorithms) (8% Weightage)

### A. Must-Know Topics for Backend Interviews
**Arrays:**
- [ ] Reverse array
- [ ] Find max/min
- [ ] Two sum problem
- [ ] Remove duplicates

**Strings:**
- [ ] Reverse string
- [ ] Check palindrome
- [ ] Anagram check
- [ ] Count vowels/consonants

**LinkedList:**
- [ ] Reverse linked list
- [ ] Detect cycle
- [ ] Find middle element

**Recursion:**
- [ ] Factorial
- [ ] Fibonacci
- [ ] Sum of digits

**Searching:**
- [ ] Linear search
- [ ] Binary search

**Sorting:**
- [ ] Bubble sort (concept)
- [ ] Merge sort (concept)
- [ ] Quick sort (concept)

**Time Complexity:**
- [ ] Big O notation (O(1), O(n), O(log n), O(n²))

**Study Time:** Daily 30-45 min for 2 months

---

## 🎯 SECTION 7: NODE.JS / EXPRESS (5% Weightage)

### You Already Know This! (Maintain)

**Topics to Revise:**
- [ ] What is Node.js? Event loop, non-blocking I/O
- [ ] Express.js basics (routes, middleware)
- [ ] Middleware concept & examples
- [ ] Error handling
- [ ] async/await, Promises
- [ ] REST API development

**Study Time:** 1 day (revision)

---

## 🎯 SECTION 8: REACT (3% Weightage)

### You Already Know This! (Maintain)

**Topics to Revise:**
- [ ] Components, Props, State
- [ ] useState, useEffect hooks
- [ ] Virtual DOM
- [ ] Conditional rendering
- [ ] Event handling

**Study Time:** 1 day (revision)

---

## 🎯 SECTION 9: SYSTEM DESIGN BASICS (2% Weightage)

### Basic Concepts (Good to Know)
- [ ] Monolith vs Microservices
- [ ] Load Balancing concept
- [ ] Caching (Redis basics)
- [ ] Database replication
- [ ] Horizontal vs Vertical scaling
- [ ] API Gateway concept

**Common Interview Questions:**
1. "Monolith vs Microservices?"
2. "What is load balancing?"
3. "What is caching? Why use it?"

**Study Time:** 3-4 days (basic understanding)

---

## 🎯 SECTION 10: DEVOPS & DEPLOYMENT (Bonus)

### Docker (Must Learn)
- [ ] What is Docker? Containers vs VMs
- [ ] Dockerfile basics
- [ ] docker build, docker run, docker ps
- [ ] Docker Compose basics

### Kubernetes (Good to Know - Concepts Only)
- [ ] What is Kubernetes?
- [ ] Pods, Services, Deployments (concepts)

### AWS Basics (Good to Know - Concepts Only)
- [ ] What is EC2, S3, RDS (concepts)
- [ ] Cloud deployment basics

**Study Time:** 5-7 days

---

## 📚 STUDY PRIORITY RANKING

### 🔥🔥🔥 CRITICAL (Must Complete in First 30 Days)
1. **Spring Boot** (15 days) - 0% → 85%
2. **Java Collections** (3 days) - 60% → 95%
3. **DSA** (Daily 45 min) - 30% → 70%

### 🔥🔥 HIGH PRIORITY (Complete in 45 Days)
4. **Docker** (5 days) - 0% → 70%
5. **SQL** (3 days) - 65% → 90%
6. **Java OOP** (2 days) - 60% → 90%

### 🔥 MEDIUM PRIORITY (Complete in 60 Days)
7. **Hibernate** (2 days revision) - 70% → 90%
8. **System Design Basics** (3 days) - 20% → 60%
9. **Spring Security** (3 days) - 0% → 60%

### 🟢 MAINTAIN (1-2 Days Revision)
10. **Node.js/Express** - 80% → 85%
11. **React** - 75% → 85%
12. **REST API** - 75% → 90%

---

## 🎯 RECOMMENDED RESOURCES

### Spring Boot
- **Best Course:** "Spring Boot Complete Course" by Telusko on YouTube (FREE)
- **Backup:** "Spring Boot Tutorial" by Java Brains (FREE)
- **Practice:** Build 2-3 projects (TODO app, Blog API, E-commerce API)

### Java
- **Revision:** "Java Interview Questions" by Durga Sir on YouTube
- **Practice:** GeeksForGeeks Java articles

### DSA
- **Platform:** LeetCode Easy problems (50 problems)
- **Backup:** GeeksForGeeks "Must Do Coding Questions"
- **Daily:** 2 problems (1 easy + 1 medium)

### SQL
- **Practice:** SQLZoo, HackerRank SQL
- **Time:** 1 hour daily for 3 days

### Docker
- **Course:** "Docker Tutorial for Beginners" by TechWorld with Nana (FREE)
- **Practice:** Dockerize your Spring Boot app

---

## ✅ COMPLETION CHECKLIST (Track Progress)

### Week 1-2: Spring Boot Foundation
- [ ] Day 1-2: Spring Boot intro, auto-configuration
- [ ] Day 3-4: Dependency Injection, IoC
- [ ] Day 5-7: REST API development
- [ ] Day 8-10: Spring Data JPA
- [ ] Day 11-14: Build TODO API project

### Week 3-4: Spring Boot Advanced + Docker
- [ ] Day 15-17: Exception handling, validation
- [ ] Day 18-20: Spring Security + JWT
- [ ] Day 21-23: Build Blog API project
- [ ] Day 24-28: Docker basics + Dockerize your app

### Week 5-6: Java Strengthening + System Design
- [ ] Day 29-31: Java Collections revision
- [ ] Day 32-34: Java OOP concepts
- [ ] Day 35-37: Hibernate revision
- [ ] Day 38-40: SQL practice
- [ ] Day 41-42: System Design basics

### Week 7-8: Final Prep + Mock Interviews
- [ ] Day 43-49: Interview questions practice
- [ ] Day 50-56: Mock interviews daily
- [ ] Day 57-60: Revision + confidence building

---

## 🎯 SUCCESS METRICS

| Topic | Current | Target | Status |
|-------|---------|--------|--------|
| Java Core | 60% | 90% | 🔄 |
| Spring Boot | 10% | 85% | 🔄 |
| Hibernate | 70% | 90% | 🔄 |
| DSA | 30% | 70% | 🔄 |
| SQL | 65% | 90% | 🔄 |
| Docker | 0% | 70% | 🔄 |
| **Overall** | **55%** | **85%+** | 🎯 |

---

**Next:** 2-Month Daily Learning Roadmap →
