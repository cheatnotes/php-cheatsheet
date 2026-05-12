

![Cheat Notes Banner]()


---

# PHP Cheatsheet
 
A comprehensive guide to modern PHP development covering PHP 8.x features, object-oriented programming, database integration, API development, testing, and deployment. Learn best practices, design patterns, security principles, and performance optimization through hands-on projects. Ideal for beginners transitioning to professional development and experienced developers upgrading to modern PHP standards. Includes coverage of Composer, PHPUnit, Laravel ecosystem, and cloud deployment strategies.

---

## Table of Contents

### **Part I: Foundations of PHP**
**Chapter 1: Introduction to PHP**  
1.1 History and Evolution of PHP  
1.2 The PHP 8 Revolution: JIT, Performance, and Syntax Improvements  
1.3 Setting Up the Development Environment (PHP-FPM, Docker, VS Code)  
1.4 Your First Script: Hello World and Server Configuration  
1.5 Embedding PHP in HTML and Understanding the Request Lifecycle  

**Chapter 2: Language Basics**  
2.1 Syntax, Semicolons, and Code Blocks  
2.2 Variables, Constants, and Variable Variables  
2.3 Data Types: Scalar, Compound, and Special Types  
2.4 Type Declarations and Strict Typing  
2.5 Operators: Arithmetic, Logical, Bitwise, Spaceship, and Null Coalescing  
2.6 Expressions, Statements, and Control Flow  

**Chapter 3: Control Structures**  
3.1 Conditional Statements: `if`, `else`, `elseif`, `switch`, and `match`  
3.2 Loops: `for`, `while`, `do-while`, `foreach`, and Iteration Techniques  
3.3 Break, Continue, and Goto  
3.4 Alternative Syntax for Templates  
3.5 Practical Flow Control Patterns  

**Chapter 4: Functions**  
4.1 Declaring and Invoking Functions  
4.2 Parameters: Positional, Named (PHP 8), Default, and Variadic  
4.3 Return Types and Multiple Return Values  
4.4 Variable Scope, Global Variables, and Static Variables  
4.5 Anonymous Functions, Closures, and the `use` Keyword  
4.6 Arrow Functions (fn) and First-Class Callable Syntax  
4.7 Recursion and Memoization  

**Chapter 5: Arrays and Strings**  
5.1 Indexed, Associative, and Multidimensional Arrays  
5.2 Array Manipulation: Sorting, Filtering, Mapping, and Reducing  
5.3 Spread Operator and Array Destructuring  
5.4 String Interpolation, Heredoc, and Nowdoc  
5.5 Multibyte Strings and UTF-8 Handling  
5.6 Regular Expressions (PCRE) and Pattern Matching  

**Chapter 6: File Handling and Streams**  
6.1 Reading, Writing, and Appending Files  
6.2 File Uploads and MIME Type Validation  
6.3 Working with Directories and File Information  
6.4 Streams, Stream Contexts, and Filters  
6.5 Temporary Files and Memory Streams  

---

### **Part II: Object-Oriented Programming**
**Chapter 7: OOP Fundamentals**  
7.1 Classes, Objects, Properties, and Methods  
7.2 Visibility Modifiers: Public, Private, and Protected  
7.3 Constructors, Destructors, and Constructor Property Promotion (PHP 8)  
7.4 `$this`, `self`, `static`, and Late Static Binding  
7.5 Magic Methods: `__get`, `__set`, `__call`, `__toString`, and Others  

**Chapter 8: Inheritance and Polymorphism**  
8.1 Extending Classes and Method Overriding  
8.2 Abstract Classes and Methods  
8.3 Final Classes and Methods  
8.4 Type Hinting and Polymorphic Behavior  

**Chapter 9: Interfaces, Traits, and Enums**  
9.1 Defining and Implementing Interfaces  
9.2 Multiple Interfaces and Interface Inheritance  
9.3 Traits: Solving Multiple Inheritance  
9.4 Trait Precedence, Conflicts, and Aliases  
9.5 Enumerations (PHP 8.1): Backed, Pure, and Methods in Enums  

**Chapter 10: Namespaces and Autoloading**  
10.1 Declaring and Importing Namespaces  
10.2 Sub-namespaces and Name Resolution  
10.3 PSR-4 Autoloading with Composer  
10.4 Class Aliases and Dynamic Class Loading  

**Chapter 11: Error and Exception Handling**  
11.1 Error Levels and Configuration  
11.2 Custom Error Handlers and Logging  
11.3 Exceptions, Try-Catch, and Finally Blocks  
11.4 Custom Exception Hierarchies  
11.5 Throwable Interface and Error Exceptions  

---

### **Part III: Modern PHP 8 Features**
**Chapter 12: PHP 8 Type System**  
12.1 Union Types and Mixed Types  
12.2 Nullable Types and Static Return Type  
12.3 `never` Return Type  
12.4 Type Inference and Variance  

**Chapter 13: Syntax and Developer Experience**  
13.1 Named Arguments and Reordering Parameters  
13.2 Match Expressions vs. Switch  
13.3 Nullsafe Operator (`?->`)  
13.4 Attributes (Annotations) and Reflection  
13.5 Fibers and Cooperative Multitasking  

**Chapter 14: Performance and JIT**  
14.1 Understanding the JIT Compiler  
14.2 Opcache Configuration and Tuning  
14.3 Preloading for Production  
14.4 Benchmarking and Profiling Tools  

---

### **Part IV: Working with Data**
**Chapter 15: Database Programming with PDO**  
15.1 Connecting to MySQL, PostgreSQL, and SQLite  
15.2 Prepared Statements and Parameter Binding  
15.3 Transactions, Savepoints, and Rollbacks  
15.4 Fetch Modes and Data Mapping  
15.5 Connection Pooling and Persistent Connections  

**Chapter 16: Advanced Data Storage**  
16.1 Redis Integration for Caching and Sessions  
16.2 MongoDB and Document-Oriented Patterns  
16.3 Elasticsearch Basics for Search  
16.4 File-Based Storage: JSON, XML, YAML, and CSV  

---

### **Part V: Web Development**
**Chapter 17: HTTP and Web Fundamentals**  
17.1 Request/Response Lifecycle and Superglobals  
17.2 Sessions and Cookies: Security and Best Practices  
17.3 Headers, Status Codes, and Content Negotiation  
17.4 Handling GET, POST, PUT, DELETE, and PATCH  

**Chapter 18: Building APIs**  
18.1 RESTful Architecture and Resource Design  
18.2 JSON Serialization and Validation  
18.3 Authentication: API Keys, OAuth2, and JWT  
18.4 Rate Limiting and Versioning  
18.5 Introduction to GraphQL with PHP  

**Chapter 19: Templating and Frontend Integration**  
19.1 Separation of Concerns and MVC Basics  
19.2 Native PHP Templating  
19.3 Twig and Blade Engine Deep Dive  
19.4 CSRF Protection and Form Security  

---

### **Part VI: Security**
**Chapter 20: Application Security**  
20.1 XSS Prevention and Output Escaping  
20.2 SQL Injection Defense Strategies  
20.3 CSRF Tokens and SameSite Cookies  
20.4 Command Injection and Path Traversal  
20.5 File Upload Security and Validation  

**Chapter 21: Authentication and Cryptography**  
21.1 Password Hashing with `password_hash()`  
21.2 Encryption, Decryption, and SSL/TLS  
21.3 Role-Based Access Control (RBAC)  
21.4 Secure Randomness and Token Generation  

---

### **Part VII: Testing and Quality Assurance**
**Chapter 22: Unit Testing with PHPUnit**  
22.1 Installation, Configuration, and Test Structure  
22.2 Assertions, Data Providers, and Fixtures  
22.3 Mocking, Stubbing, and Test Doubles  
22.4 Code Coverage and Mutation Testing  

**Chapter 23: Quality Tools and CI/CD**  
23.1 Static Analysis with PHPStan and Psalm  
23.2 Code Style: PHP-CS-Fixer and PHPCS  
23.3 GitHub Actions and Automated Testing Pipelines  
23.4 Pre-commit Hooks and Linting  

---

### **Part VIII: The PHP Ecosystem**
**Chapter 24: Composer and Dependency Management**  
24.1 `composer.json` Schema and Version Constraints  
24.2 Autoloading, Scripts, and Plugins  
24.3 Semantic Versioning and Private Repositories  
24.4 Security Auditing with `composer audit`  

**Chapter 25: Frameworks**  
25.1 Laravel: Eloquent, Routing, and Blade  
25.2 Symfony Components and Flex  
25.3 Slim and Micro-Framework Architecture  
25.4 Choosing the Right Framework for Your Project  

---

### **Part IX: Performance and DevOps**
**Chapter 26: Optimization Strategies**  
26.1 Profiling with Xdebug and Blackfire  
26.2 Caching: OPcache, APCu, and Object Caching  
26.3 Database Query Optimization and Indexing  
26.4 Memory Management and Garbage Collection  

**Chapter 27: Deployment and Infrastructure**  
27.1 Docker and Docker Compose for PHP  
27.2 Nginx with PHP-FPM Configuration  
27.3 Horizontal Scaling and Load Balancing  
27.4 Logging with Monolog and Centralized Monitoring  

---

### **Part X: Advanced Topics**
**Chapter 28: Asynchronous and Parallel PHP**  
28.1 ReactPHP and Event-Driven Architecture  
28.2 Swoole and Coroutines  
28.3 The `parallel` Extension for Multithreading  
28.4 Message Queues: RabbitMQ and Redis Streams  

**Chapter 29: Extending PHP**  
29.1 FFI: Calling C Libraries from PHP  
29.2 Writing PHP Extensions in C  
29.3 Embedding PHP in Other Applications  

**Chapter 30: Design Patterns and Architecture**  
30.1 Creational, Structural, and Behavioral Patterns  
30.2 SOLID Principles in PHP  
30.3 Domain-Driven Design and Hexagonal Architecture  
30.4 Event Sourcing and CQRS  

---

### **Appendices**
**Appendix A:** Installing PHP on Linux, macOS, and Windows  
**Appendix B:** PSR Standards Reference  
**Appendix C:** Migrating from PHP 7.x to 8.x  
**Appendix D:** PHP.ini Configuration Directives  
**Appendix E:** ASCII Table of Escape Sequences and Operators  
**Appendix F:** Composer Package Recommendations by Category  
**Appendix G:** HTTP Status Codes Quick Reference  
**Appendix H:** Docker Compose Templates for Common Stacks
