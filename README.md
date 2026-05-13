

![PHP cheatsheet](https://github.com/cheatnotes/php-cheatsheet/blob/main/php-cheat-cover.png)


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

---

## Part I: Foundations of PHP

---

### Chapter 1: Introduction to PHP

#### 1.1 History and Evolution of PHP

PHP stands as one of the most enduring and widely-adopted server-side programming languages in the history of the web. Its journey from a simple set of Common Gateway Interface scripts to a sophisticated, high-performance language powering enterprise applications represents a remarkable evolution spanning more than a quarter-century.

The story begins in 1993 when Rasmus Lerdorf, a Danish-Canadian programmer, created a set of Perl scripts to track visitors to his online resume. He initially called these scripts "Personal Home Page Tools," a name that would later be transformed into the recursive acronym we know today: PHP: Hypertext Preprocessor. What began as a personal project quickly gained attention from other developers who recognized the utility of server-side scripting for web development.

In 1995, Lerdorf released PHP 1.0 to the public, providing basic functionality for handling form data and working with databases. The early versions were rudimentary by modern standards, but they addressed a genuine need in the nascent web development community. Developers were struggling with complex CGI scripts written in C or Perl, and PHP offered a simpler alternative that could be embedded directly within HTML.

The release of PHP 2.0 in 1997 marked the first significant step toward a more robust language. This version introduced support for Microsoft SQL Server and included a more sophisticated parsing engine. However, the true transformation came with PHP 3.0 in 1998, which represented a complete rewrite of the core engine. Andi Gutmans and Zeev Suraski joined the project and created the foundation that would support PHP's growth for years to come. PHP 3.0 introduced object-oriented programming capabilities, database abstraction layers, and a modular extension system that allowed developers to add functionality without modifying the core.

The year 2000 brought PHP 4.0, powered by the Zend Engine 1.0, named after its creators Zeev and Andi. This version delivered substantial performance improvements, session management, output buffering, and enhanced security features. PHP 4.0 became the dominant version for web development during the early 2000s, powering everything from personal blogs to major corporate websites. The LAMP stack—Linux, Apache, MySQL, and PHP—emerged as the standard architecture for web applications, democratizing web development and enabling the creation of platforms like WordPress, Drupal, and Joomla.

PHP 5.0 arrived in 2004, bringing a completely revamped object model inspired by Java. The Zend Engine 2.0 provided true object-oriented programming support with visibility modifiers, abstract classes, interfaces, constructors and destructors, and exception handling. This release also introduced the PHP Data Objects (PDO) extension, offering a consistent interface for database access. PHP 5.3, released in 2009, added namespaces, closures, and late static binding, further modernizing the language. Subsequent releases in the 5.x series brought generators, traits, and the password hashing API that would become essential for secure application development.

The planned PHP 6.0 release, which aimed to implement native Unicode support, was ultimately abandoned due to technical challenges. Instead, the community channeled its efforts into PHP 7.0, released in December 2015. This version represented a quantum leap in performance, delivering up to three times faster execution through the new Zend Engine 3.0. PHP 7.0 introduced scalar type declarations, return type declarations, the spaceship and null coalescing operators, and anonymous classes. The performance gains were so significant that PHP 7 quickly became the new standard, with most major frameworks and content management systems requiring or recommending it.

The PHP 7.x series continued to evolve with regular releases. PHP 7.1 added nullable types, void return types, symmetric array destructuring, and class constant visibility. PHP 7.2 introduced the Sodium cryptographic library, object type hints, and parameter type widening. PHP 7.3 brought flexible heredoc and nowdoc syntaxes, trailing commas in function calls, and the `is_countable()` function. PHP 7.4, released in November 2019, was the final 7.x release and introduced typed properties, arrow functions, the null coalescing assignment operator, and spread operators in array expressions.

#### 1.2 The PHP 8 Revolution: JIT, Performance, and Syntax Improvements

PHP 8.0, released on November 26, 2020, represented the most significant update to the language since PHP 7.0 and arguably the most transformative since PHP 5.0. This release introduced features that fundamentally changed how developers write PHP code while delivering performance improvements that continued pushing the language toward parity with compiled alternatives.

**Just-In-Time Compilation**

The most anticipated feature of PHP 8.0 was the JIT compiler, representing years of research and development. Traditional PHP execution involves parsing source code into an abstract syntax tree, compiling it into opcodes, and then interpreting those opcodes through the Zend Virtual Machine. The opcode cache, introduced in earlier versions, stored compiled opcodes in memory to avoid recompilation on subsequent requests, dramatically improving performance.

The JIT compiler takes this optimization further by compiling frequently executed opcode sequences directly into machine code. When the JIT identifies a hot code path—a section of code executed repeatedly—it translates the opcodes into native machine instructions that the CPU can execute directly, bypassing the virtual machine's interpretation overhead.

The PHP 8.0 JIT implementation uses a tracing approach, where it monitors execution and identifies loops and frequently called functions as candidates for compilation. The compiled code resides in shared memory, making it available across requests. This approach particularly benefits CPU-intensive workloads such as image processing, cryptographic operations, and mathematical computations. For typical web applications that are primarily I/O-bound, the performance gains from JIT may be less dramatic than the improvements delivered by the Zend Engine 3.0 optimization in PHP 7.0, but for specific use cases, the difference can be substantial.

The JIT configuration offers four levels of optimization through the `opcache.jit` directive:

- `tracing` (default): The most aggressive optimization, identifying hot traces and compiling them
- `function`: Compiles entire functions when they become hot
- `disable`: Completely disables JIT compilation
- `off`: Not available

Additional configuration options allow fine-tuning the JIT behavior, including the memory buffer size for compiled code, the threshold for triggering compilation, and profiling granularity.

**Named Arguments**

Named arguments fundamentally changed how developers call functions and methods in PHP. Before PHP 8.0, function arguments were strictly positional, requiring developers to pass values in the exact order defined by the function signature. This created several pain points: functions with many parameters became difficult to read, optional parameters required passing default values for preceding parameters, and function signatures couldn't easily evolve without breaking backward compatibility.

Named arguments solve these problems by allowing developers to specify parameter names when passing values:

```php
function createUser(string $name, string $email, bool $isAdmin = false, ?string $phone = null) {
    // Implementation
}

// Before PHP 8.0: Unclear which boolean represents what
createUser('John Doe', 'john@example.com', true, null);

// With PHP 8.0 named arguments: Self-documenting code
createUser(
    name: 'John Doe',
    email: 'john@example.com',
    isAdmin: true
);
```

Named arguments can be combined with positional arguments, though positional arguments must precede named arguments in the call. This feature dramatically improves code readability, especially when working with frameworks and libraries that define methods with many parameters.

The implications for backward compatibility are equally significant. Library maintainers can now add new optional parameters without breaking existing code, as long as existing parameters retain their names. Parameter renaming becomes a breaking change when callers use named arguments, creating a new consideration for API design.

**Attributes (Annotations)**

Attributes provide native syntax for adding structured metadata to classes, methods, functions, parameters, properties, and constants. Before PHP 8.0, developers relied on docblock annotations parsed by external libraries like Doctrine Annotations. This approach suffered from several limitations: annotations were just comments with no language-level validation, parsing was error-prone and slow, and there was no standardization across libraries.

PHP 8.0 introduces attributes as first-class language constructs defined using the `#[...]` syntax:

```php
#[Route('/api/users', methods: ['GET'])]
#[Middleware('auth')]
class UserController
{
    #[Inject]
    private UserRepository $repository;
    
    #[Cache(ttl: 3600)]
    public function index(): array
    {
        return $this->repository->findAll();
    }
}
```

Attributes are validated at compile time, ensuring they reference actual classes and receive correct argument types. They can be retrieved at runtime through the Reflection API, enabling frameworks to inspect and act upon metadata without docblock parsing.

The attribute system is extensible, allowing developers to define custom attributes by creating classes annotated with the `#[Attribute]` attribute. Attribute classes can specify their valid targets (class, method, property, etc.) and whether they can be repeated on the same target.

**Union Types**

Union types extend PHP's type system by allowing parameters and return values to accept multiple types. Before PHP 8.0, nullable types provided limited support for accepting either a specific type or null, but there was no way to express "string or int" or "array or ArrayAccess."

```php
// PHP 8.0 union types
function processId(int|string $id): User|null
{
    if (is_string($id)) {
        return $this->findBySlug($id);
    }
    return $this->findById($id);
}
```

Union types make code more expressive and enable better static analysis. The `mixed` type, introduced in PHP 8.0, serves as a shorthand for `array|bool|callable|int|float|null|object|string|resource` and indicates that a value can be of any type. PHP 8.1 added the `never` return type for functions that never return (either by throwing an exception or calling `exit()`) and the `true` type for use in union types.

**Match Expression**

The match expression provides a more powerful alternative to the switch statement, addressing several long-standing complaints. Match expressions are exhaustive, requiring coverage of all possible cases or a default case. They use strict comparison instead of loose comparison, eliminating the type-coercion surprises that plague switch statements. Match expressions also return a value, making them usable in assignments and expressions.

```php
// Traditional switch with loose comparison
switch ($statusCode) {
    case 200:
    case 201:
        $message = 'Success';
        break;
    case 404:
        $message = 'Not Found';
        break;
    default:
        $message = 'Unknown';
        break;
}

// Match expression with strict comparison
$message = match ($statusCode) {
    200, 201 => 'Success',
    404 => 'Not Found',
    default => 'Unknown',
};
```

The match expression supports complex conditions on the left side and any expression on the right side, including function calls and closures. This makes it particularly useful for mapping values, routing decisions, and state machine implementations.

**Nullsafe Operator**

Navigating object graphs with potential null values has always been a source of boilerplate code and potential errors. The traditional approach involved chains of null checks:

```php
// Without nullsafe operator
$country = null;
if ($user !== null) {
    $address = $user->getAddress();
    if ($address !== null) {
        $country = $address->getCountry();
    }
}

// With nullsafe operator
$country = $user?->getAddress()?->getCountry();
```

The nullsafe operator (`?->`) short-circuits to null when the left side evaluates to null, eliminating the need for explicit null checks in property and method chains. This feature significantly reduces boilerplate code while maintaining safety.

**Constructor Property Promotion**

Constructor property promotion reduces the verbosity of defining and initializing class properties. Before PHP 8.0, creating a class with typed properties required declaring properties, defining constructor parameters, and manually assigning parameters to properties. This pattern was so common that it became one of the most requested language features.

```php
// Before PHP 8.0
class User
{
    private string $name;
    private string $email;
    private ?string $phone;
    
    public function __construct(
        string $name,
        string $email,
        ?string $phone = null
    ) {
        $this->name = $name;
        $this->email = $email;
        $this->phone = $phone;
    }
}

// With PHP 8.0 constructor property promotion
class User
{
    public function __construct(
        private string $name,
        private string $email,
        private ?string $phone = null,
    ) {}
}
```

Promoted properties can include visibility modifiers, type declarations, and default values. They can be combined with regular constructor parameters and can use any visibility level. This feature alone eliminates a substantial amount of boilerplate code in typical PHP applications.

**Additional PHP 8.0 Improvements**

The `str_contains()`, `str_starts_with()`, and `str_ends_with()` functions finally provide native implementations for common string operations that previously required `strpos()` checks. The `Stringable` interface allows type hints for objects that implement `__toString()`. The `ValueError` exception class handles type errors for internal functions. Weak maps enable garbage collection-friendly storage of object references.

**PHP 8.1 Enhancements**

Released in November 2021, PHP 8.1 built upon the 8.0 foundation with enumerations, fibers, readonly properties, intersection types, and the `never` return type. Enumerations brought native support for enumerated values with methods and backed values, eliminating the need for constant-based workarounds. Fibers introduced cooperative multitasking, enabling lightweight concurrency without the complexity of full multithreading. Readonly properties prevented modification after initialization, improving immutability support. Intersection types allowed combining multiple interfaces in type declarations.

**PHP 8.2 and 8.3 Features**

PHP 8.2, released in December 2022, introduced readonly classes, allowing all properties of a class to be declared readonly with a single keyword. Disjunctive Normal Form types provided greater flexibility in type declarations. The `true` type became a standalone type. Sensitive parameter values could be marked to prevent inclusion in stack traces. PHP 8.3, released in November 2023, added typed class constants, the `json_validate()` function for validating JSON without decoding, the `mb_str_pad()` function for multibyte string padding, and improvements to the random extension.

The PHP 8.x series represents a fundamentally different language from PHP 5.x and even PHP 7.x. The combination of a stronger type system, more expressive syntax, native attributes, enumerations, and fibers positions PHP as a modern, competitive language suitable for enterprise application development. The performance improvements, while not always the headline feature, continue to make PHP applications faster and more efficient.

#### 1.3 Setting Up the Development Environment (PHP-FPM, Docker, VS Code)

A professional development environment is the foundation of productive PHP development. Modern PHP applications require careful configuration of web servers, PHP runtimes, databases, caching systems, and debugging tools. The traditional approach of installing each component directly on the development machine has largely given way to containerized environments that ensure consistency across development, staging, and production.

**Understanding PHP-FPM**

PHP FastCGI Process Manager (PHP-FPM) is the modern standard for serving PHP applications. Unlike the older `mod_php` approach for Apache, which embedded PHP within the web server process, PHP-FPM operates as a separate service that communicates with the web server through the FastCGI protocol. This separation provides several advantages: resource isolation, allowing the web server and PHP to scale independently; graceful process management with configurable pools, worker counts, and restart policies; and compatibility with any web server supporting FastCGI.

The PHP-FPM process manager maintains a pool of worker processes that handle PHP execution. When a request arrives, the web server forwards it to an available worker, which executes the script and returns the response. After processing, the worker returns to the pool, ready for the next request. This model avoids the overhead of starting a new PHP process for each request while providing isolation between requests.

PHP-FPM configuration centers on pool definitions, typically located in `/etc/php/8.3/fpm/pool.d/` on Linux systems. Each pool represents a group of workers with specific settings:

```ini
[app]
user = www-data
group = www-data
listen = /run/php/php8.3-fpm.sock
listen.owner = www-data
listen.group = www-data

pm = dynamic
pm.max_children = 50
pm.start_servers = 5
pm.min_spare_servers = 5
pm.max_spare_servers = 35

pm.status_path = /status
ping.path = /ping
slowlog = /var/log/php8.3-fpm-slow.log
request_slowlog_timeout = 10s
```

The process manager mode (`pm`) controls how worker processes are created and maintained. Static mode maintains a fixed number of workers. Dynamic mode adjusts the worker count based on demand within configured minimum and maximum boundaries. Ondemand mode creates workers only when requests arrive and terminates them after idle periods.

**Docker for PHP Development**

Docker has transformed PHP development by enabling reproducible environments that mirror production configurations. Rather than installing PHP, MySQL, Redis, and other services directly on development machines, developers define these services in declarative configuration files and run them in isolated containers.

A typical PHP development setup uses Docker Compose to orchestrate multiple containers. The `docker-compose.yml` file defines the services, networks, and volumes:

```yaml
version: '3.8'

services:
  app:
    build:
      context: .
      dockerfile: Dockerfile
    container_name: php_app
    restart: unless-stopped
    working_dir: /var/www
    volumes:
      - ./:/var/www
      - ./docker/php/php.ini:/usr/local/etc/php/conf.d/custom.ini
    networks:
      - app_network
    depends_on:
      - mysql
      - redis

  nginx:
    image: nginx:alpine
    container_name: nginx_server
    restart: unless-stopped
    ports:
      - "8080:80"
    volumes:
      - ./:/var/www
      - ./docker/nginx/default.conf:/etc/nginx/conf.d/default.conf
    networks:
      - app_network
    depends_on:
      - app

  mysql:
    image: mysql:8.0
    container_name: mysql_db
    restart: unless-stopped
    environment:
      MYSQL_ROOT_PASSWORD: root_password
      MYSQL_DATABASE: app_database
      MYSQL_USER: app_user
      MYSQL_PASSWORD: user_password
    ports:
      - "3306:3306"
    volumes:
      - mysql_data:/var/lib/mysql
    networks:
      - app_network

  redis:
    image: redis:alpine
    container_name: redis_cache
    restart: unless-stopped
    ports:
      - "6379:6379"
    networks:
      - app_network

  mailhog:
    image: mailhog/mailhog
    container_name: mailhog
    ports:
      - "1025:1025"
      - "8025:8025"
    networks:
      - app_network

networks:
  app_network:
    driver: bridge

volumes:
  mysql_data:
```

The Dockerfile for the PHP container customizes the official PHP image with necessary extensions, Composer, and configuration:

```dockerfile
FROM php:8.3-fpm

# Install system dependencies
RUN apt-get update && apt-get install -y \
    git \
    curl \
    libpng-dev \
    libonig-dev \
    libxml2-dev \
    libzip-dev \
    zip \
    unzip \
    libpq-dev \
    libicu-dev \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

# Install PHP extensions
RUN docker-php-ext-install \
    pdo_mysql \
    pdo_pgsql \
    mbstring \
    exif \
    pcntl \
    bcmath \
    gd \
    intl \
    zip \
    opcache

# Install Redis extension
RUN pecl install redis \
    && docker-php-ext-enable redis

# Install Xdebug for debugging
RUN pecl install xdebug \
    && docker-php-ext-enable xdebug

# Copy custom PHP configuration
COPY docker/php/php.ini /usr/local/etc/php/conf.d/custom.ini

# Install Composer
COPY --from=composer:latest /usr/bin/composer /usr/bin/composer

# Set working directory
WORKDIR /var/www

# Create system user to match host user
ARG USER_ID=1000
ARG GROUP_ID=1000
RUN groupadd -g ${GROUP_ID} appuser \
    && useradd -u ${USER_ID} -g appuser -m appuser \
    && chown -R appuser:appuser /var/www

USER appuser
```

This setup creates a complete development environment: PHP-FPM for processing requests, Nginx as the web server, MySQL for relational data, Redis for caching, and Mailhog for capturing outgoing emails. The entire stack starts with a single `docker-compose up` command and stops with `docker-compose down`.

**Visual Studio Code Configuration**

Visual Studio Code has emerged as the preferred editor for PHP development, offering excellent integration with PHP tools through extensions. A well-configured VS Code setup includes extensions for language support, debugging, formatting, and static analysis.

Essential PHP extensions for VS Code include:

- **PHP Intelephense**: Provides intelligent code completion, parameter hints, navigation, and refactoring support. It's superior to the basic PHP language support and offers features comparable to full IDEs.

- **PHP Debug**: Integrates Xdebug with VS Code's debugging interface, enabling breakpoints, variable inspection, stack traces, and step-through debugging directly in the editor.

- **PHP CS Fixer** or **phpcs**: Applies coding standards automatically or provides real-time feedback on style violations.

- **PHPStan** or **Psalm**: Integrates static analysis results directly into the editor, highlighting type errors and potential issues.

- **Composer**: Provides Composer integration for dependency management within VS Code.

The `.vscode/launch.json` configuration connects VS Code to the Xdebug instance running in the Docker container:

```json
{
    "version": "0.2.0",
    "configurations": [
        {
            "name": "Listen for Xdebug",
            "type": "php",
            "request": "launch",
            "port": 9003,
            "pathMappings": {
                "/var/www": "${workspaceFolder}"
            },
            "hostname": "0.0.0.0",
            "xdebugSettings": {
                "max_depth": 3
            }
        }
    ]
}
```

The `pathMappings` configuration translates file paths between the Docker container and the local filesystem, enabling accurate breakpoint placement and step-through debugging.

**Development Tools Installation**

Beyond the core environment, modern PHP development relies on ecosystem tools that should be globally available:

Composer is the dependency manager for PHP, responsible for installing and managing libraries. Installation is straightforward:

```bash
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('sha384', 'composer-setup.php') === file_get_contents('https://composer.github.io/installer.sig')) { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
php composer-setup.php
php -r "unlink('composer-setup.php');"
sudo mv composer.phar /usr/local/bin/composer
```

PHP CS Fixer and PHP CodeSniffer enforce coding standards consistently across teams:

```bash
composer global require friendsofphp/php-cs-fixer
composer global require squizlabs/php_codesniffer
```

Laravel Valet (for macOS) or Laragon (for Windows) provide simplified local development environments for those who prefer not to use Docker. These tools configure Nginx, PHP, and DNS automatically, allowing developers to access projects through `.test` domains.

**Environment Configuration Management**

Managing configuration differences between development, staging, and production environments requires careful planning. The twelve-factor app methodology recommends storing configuration in environment variables, which keeps sensitive information out of code and enables easy changes between environments.

PHP applications commonly use `.env` files for local development, loaded by libraries like `vlucas/phpdotenv`. These files should never be committed to version control; instead, a `.env.example` file documents the required variables with placeholder values.

```bash
# .env.example
APP_NAME="My Application"
APP_ENV=local
APP_DEBUG=true
APP_URL=http://localhost:8080

DB_CONNECTION=mysql
DB_HOST=mysql
DB_PORT=3306
DB_DATABASE=app_database
DB_USERNAME=app_user
DB_PASSWORD=user_password

REDIS_HOST=redis
REDIS_PASSWORD=null
REDIS_PORT=6379

MAIL_MAILER=smtp
MAIL_HOST=mailhog
MAIL_PORT=1025
```

Docker Compose can pass environment variables directly to containers, either through the `environment` section or by referencing an env file. Kubernetes and other orchestration platforms provide their own mechanisms for managing configuration and secrets.

#### 1.4 Your First Script: Hello World and Server Configuration

The traditional "Hello World" program serves as more than a tradition—it validates that every component of the development environment functions correctly. For PHP, this means verifying that the web server forwards requests to PHP-FPM, that PHP processes the script, and that the response reaches the browser.

Create a file named `index.php` in the project's web root directory:

```php
<?php

declare(strict_types=1);

echo "Hello, World!";

phpinfo();
```

The `declare(strict_types=1)` enables strict type checking for this file, a practice recommended for all new PHP code. The `echo` statement outputs the greeting. `phpinfo()` generates a comprehensive report of PHP's configuration, loaded extensions, and environment settings—invaluable for verifying the development environment.

Accessing `http://localhost:8080/` (or the configured URL) should display the greeting followed by the PHP information page. If errors appear instead, the troubleshooting process begins: checking that Docker containers are running, verifying port mappings, confirming file permissions, and examining Nginx configuration.

**Understanding Nginx Configuration**

The Nginx configuration for serving PHP applications requires specific directives to forward requests to PHP-FPM:

```nginx
server {
    listen 80;
    server_name localhost;
    root /var/www/public;
    index index.php;

    location / {
        try_files $uri $uri/ /index.php?$query_string;
    }

    location ~ \.php$ {
        fastcgi_pass app:9000;
        fastcgi_param SCRIPT_FILENAME $document_root$fastcgi_script_name;
        fastcgi_param QUERY_STRING $query_string;
        fastcgi_param REQUEST_METHOD $request_method;
        fastcgi_param CONTENT_TYPE $content_type;
        fastcgi_param CONTENT_LENGTH $content_length;
        include fastcgi_params;
        fastcgi_buffers 16 16k;
        fastcgi_buffer_size 32k;
    }

    location ~ /\.ht {
        deny all;
    }
}
```

The `location ~ \.php$` block matches requests for PHP files and forwards them to the PHP-FPM service (named `app` in Docker Compose) on port 9000. The `fastcgi_param` directives pass request information that PHP accesses through superglobals like `$_SERVER` and `$_GET`. The `try_files` directive in the root location implements front-controller routing, directing all non-file requests to `index.php` for framework processing.

**Apache Configuration Alternative**

For developers using Apache instead of Nginx, the configuration uses `mod_proxy_fcgi` or the older `mod_php`:

```apache
<VirtualHost *:80>
    DocumentRoot /var/www/public
    ServerName localhost

    <Directory /var/www/public>
        Options Indexes FollowSymLinks
        AllowOverride All
        Require all granted
        
        <FilesMatch \.php$>
            SetHandler "proxy:fcgi://app:9000"
        </FilesMatch>
    </Directory>
</VirtualHost>
```

**The Request Lifecycle**

Understanding what happens between entering a URL and seeing the response is fundamental to PHP development. When a request arrives:

1. The web server (Nginx) receives the HTTP request and determines how to handle it based on its configuration.

2. For static files (CSS, JavaScript, images), Nginx serves them directly without invoking PHP, providing significantly faster responses.

3. For PHP files, Nginx constructs a FastCGI request and sends it to the PHP-FPM service. The request includes the script path, HTTP method, headers, query string, and body content.

4. PHP-FPM assigns the request to an available worker process from its pool. If no workers are available and the maximum hasn't been reached, it spawns a new worker (depending on the process manager configuration).

5. The worker initializes the PHP runtime, loading the `php.ini` configuration and any enabled extensions. If opcache is enabled, it checks for a cached version of the compiled opcodes.

6. The script is parsed, compiled to opcodes (or retrieved from opcache), and executed. During execution, the script accesses databases, caches, and other services as needed.

7. The worker returns the response (typically HTML, JSON, or other content) and any HTTP headers through FastCGI to Nginx.

8. Nginx sends the HTTP response to the client and closes the connection (or keeps it alive for subsequent requests).

9. The PHP worker returns to the pool, ready for the next request. PHP automatically cleans up resources, closes database connections, and releases memory.

This lifecycle repeats for every request, which is why opcode caching is critical for performance—it eliminates the parsing and compilation steps for unchanged scripts.

**Troubleshooting Common Issues**

Several issues commonly arise during environment setup:

"502 Bad Gateway" errors typically indicate that Nginx cannot communicate with PHP-FPM. Verify that the PHP container is running (`docker ps`), that the service name in the Nginx configuration matches the Docker Compose service name, and that PHP-FPM is listening on the expected port.

"Permission denied" errors suggest file permission mismatches between the host and container. The container's PHP-FPM process runs as a specific user (often `www-data`), which must have read access to the PHP files. The Dockerfile earlier addressed this by creating a user matching the host's user ID.

"File not found" errors occur when the `SCRIPT_FILENAME` parameter doesn't match the actual file location. Verify the `root` directive in Nginx configuration and ensure the `fastcgi_param SCRIPT_FILENAME` correctly combines the document root and script name.

Xdebug connection issues usually involve network configuration between the container and host. Xdebug 3 uses port 9003 by default, and the `xdebug.client_host` setting must point to the host machine's IP address from the container's perspective (typically `host.docker.internal` on Docker Desktop for Mac and Windows, or the Docker bridge gateway address on Linux).

#### 1.5 Embedding PHP in HTML and Understanding the Request Lifecycle

PHP's original design purpose was embedding dynamic content within HTML, and this capability remains central to the language despite its evolution into a general-purpose programming language. Understanding the relationship between PHP and HTML, and how the server processes combined files, is essential for effective web development.

**PHP Tags and Escaping**

PHP code blocks begin with `<?php` and end with `?>`. The short echo tag `<?=` is equivalent to `<?php echo` and is commonly used in templates:

```php
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title><?= $pageTitle ?? 'Default Title' ?></title>
</head>
<body>
    <h1>Welcome, <?= htmlspecialchars($username, ENT_QUOTES, 'UTF-8') ?></h1>
    
    <?php if ($isAuthenticated): ?>
        <nav>
            <a href="/dashboard">Dashboard</a>
            <a href="/logout">Logout</a>
        </nav>
    <?php else: ?>
        <nav>
            <a href="/login">Login</a>
            <a href="/register">Register</a>
        </nav>
    <?php endif; ?>
    
    <main>
        <?php foreach ($articles as $article): ?>
            <article>
                <h2><?= htmlspecialchars($article['title'], ENT_QUOTES, 'UTF-8') ?></h2>
                <p><?= nl2br(htmlspecialchars($article['excerpt'], ENT_QUOTES, 'UTF-8')) ?></p>
            </article>
        <?php endforeach; ?>
    </main>
</body>
</html>
```

Notice the use of `htmlspecialchars()` when outputting user-generated content. This function converts special HTML characters to their entity equivalents, preventing cross-site scripting (XSS) attacks. Every piece of data that originates from users or external sources must be escaped appropriately for its context before output.

The closing `?>` tag is optional at the end of PHP files, and many style guides recommend omitting it to prevent accidental whitespace output that could interfere with HTTP headers. Files containing only PHP code should omit the closing tag entirely.

**Alternative Syntax for Control Structures**

PHP provides alternative syntax for control structures specifically designed for template use. Rather than using curly braces, these structures use colons and `endif`, `endwhile`, `endforeach`, etc.:

```php
<?php if ($user->isPremium()): ?>
    <div class="premium-badge">Premium Member</div>
<?php elseif ($user->isTrial()): ?>
    <div class="trial-badge">Trial Member</div>
<?php else: ?>
    <div class="free-badge">Free Member</div>
<?php endif; ?>

<?php foreach ($products as $product): ?>
    <?= $this->render('product-card', ['product' => $product]) ?>
<?php endforeach; ?>
```

This syntax improves readability when PHP is interspersed with HTML, making the structure clearer than matching curly braces across template sections.

**Separation of Concerns**

While embedding PHP in HTML is convenient for simple pages, applications of any complexity benefit from separating business logic from presentation. The Model-View-Controller (MVC) pattern addresses this by placing data handling in models, presentation logic in views, and request handling in controllers.

A basic MVC structure keeps PHP logic out of templates as much as possible:

```php
// Controller
class ArticleController
{
    public function index(ArticleRepository $repository): Response
    {
        $articles = $repository->findPublished();
        $totalCount = $repository->countTotal();
        
        return new Response(
            $this->render('articles/index', [
                'articles' => $articles,
                'totalCount' => $totalCount,
                'currentPage' => 1,
            ])
        );
    }
}

// View (articles/index.php)
<?php $this->layout('main') ?>

<h1>Articles (<?= $totalCount ?> total)</h1>

<?php if (empty($articles)): ?>
    <p>No articles found.</p>
<?php else: ?>
    <div class="article-list">
        <?php foreach ($articles as $article): ?>
            <div class="article-card">
                <h2><?= htmlspecialchars($article->title) ?></h2>
                <time><?= $article->publishedAt->format('Y-m-d') ?></time>
            </div>
        <?php endforeach; ?>
    </div>
<?php endif; ?>
```

The controller prepares all data needed by the view, which focuses solely on presentation with minimal logic—conditionals and loops but no database queries or complex calculations.

**The Complete Request Lifecycle in Detail**

Building on the earlier overview, an in-depth understanding of the request lifecycle enables better debugging and optimization. Let's trace a complete request through a modern PHP application using Nginx, PHP-FPM, and a framework:

**Phase 1: Connection Establishment**

A user's browser initiates a TCP connection to the server on port 443 (HTTPS) or 80 (HTTP). For HTTPS connections, TLS handshake occurs, negotiating encryption parameters and validating certificates. The entire PHP application has no involvement in this phase—it's handled by Nginx or a load balancer.

**Phase 2: Request Parsing**

Nginx receives the HTTP request and parses the request line (method, path, HTTP version), headers, and body. It determines which virtual server configuration matches the request based on the `Host` header and `server_name` directives.

**Phase 3: Static File Check**

Nginx checks if the requested path corresponds to a static file. If the request is for `/css/style.css` and the file exists, Nginx serves it directly with appropriate caching headers. This shortcut avoids invoking PHP entirely, which is why frameworks typically store static assets in dedicated directories.

**Phase 4: Routing to PHP**

For dynamic requests, Nginx applies the location blocks in its configuration. The most common pattern uses `try_files` to implement front-controller routing:

```nginx
location / {
    try_files $uri $uri/ /index.php?$query_string;
}
```

This directive attempts to serve the exact file requested. If it doesn't exist, it tries the path as a directory. If neither exists, it forwards the request to `/index.php`, passing the original query string. This enables clean URLs like `/users/123` to be handled by a single entry point.

**Phase 5: FastCGI Communication**

Nginx constructs a FastCGI request containing all the information PHP needs:

- `SCRIPT_FILENAME`: The absolute path to the PHP file
- `REQUEST_METHOD`: GET, POST, PUT, DELETE, etc.
- `QUERY_STRING`: The URL query string
- `REQUEST_URI`: The full request URI
- `DOCUMENT_URI`: The URI used to determine the script
- `SERVER_PROTOCOL`: HTTP/1.1 or HTTP/2
- `CONTENT_TYPE`: The request Content-Type header
- `CONTENT_LENGTH`: The request body length
- All HTTP headers with names prefixed by `HTTP_`

**Phase 6: PHP Initialization**

The PHP-FPM worker receiving the request initializes the PHP runtime. This includes loading the `php.ini` configuration, enabling extensions, and setting up memory limits. If opcache is enabled, it checks for a cached version of the requested script's opcodes. On the first request after deployment or cache clear, the script must be parsed and compiled.

**Phase 7: Framework Bootstrapping**

The entry point (typically `index.php`) loads the Composer autoloader, then bootstraps the framework. This involves:

```php
<?php
// public/index.php
declare(strict_types=1);

require_once __DIR__ . '/../vendor/autoload.php';

$app = require_once __DIR__ . '/../bootstrap/app.php';

$request = App\Http\Request::capture();
$response = $app->handle($request);
$response->send();
```

The autoloader registers itself with PHP's autoloading system, enabling classes to be loaded on demand. The framework container is created with configuration loaded from environment variables and config files. Service providers register routes, event listeners, and middleware.

**Phase 8: Middleware Execution**

Before reaching the application's core logic, the request passes through middleware layers. Middleware can authenticate users, validate CSRF tokens, compress responses, add CORS headers, and perform countless other functions. Each middleware can modify the request, pass it to the next handler, or return a response directly (for example, redirecting unauthenticated users).

**Phase 9: Routing**

The router matches the request method and URI against registered routes. Modern framework routers support parameter binding, pattern matching, and grouping:

```php
Route::get('/users/{user}', [UserController::class, 'show'])
    ->whereNumber('user')
    ->middleware('auth');

Route::post('/api/articles', [ArticleController::class, 'store'])
    ->middleware(['auth', 'throttle:60']);
```

When a route matches, the router extracts parameters and resolves the controller. Dependency injection containers automatically instantiate the controller and inject its dependencies.

**Phase 10: Controller Execution**

The controller method executes the application's business logic. It interacts with models, validates input, and prepares data for the response:

```php
public function show(int $userId, UserRepository $repository): View|JsonResponse
{
    $user = $repository->findOrFail($userId);
    
    if (request()->wantsJson()) {
        return new JsonResponse($user);
    }
    
    return view('users.show', ['user' => $user]);
}
```

**Phase 11: Response Generation**

The controller returns a response object, which may contain HTML from a rendered template, JSON from serialized data, or a file download. The framework processes the response through outgoing middleware, which may add headers, modify content, or log the request.

**Phase 12: Output to FastCGI**

The response is sent back through FastCGI to Nginx. PHP-FPM flushes output buffers and closes the connection. The worker process is returned to the pool.

**Phase 13: Nginx Response**

Nginx receives the FastCGI response, adds configured headers, applies compression if enabled, and sends the complete HTTP response to the client. For keep-alive connections, Nginx waits for subsequent requests on the same TCP connection.

**Phase 14: Browser Rendering**

The browser receives the HTTP response, parses the HTML, and begins rendering. It discovers references to CSS, JavaScript, images, and other resources, initiating new requests for each. These subsidiary requests follow the same lifecycle, though static resources bypass PHP entirely.

**Understanding State Management**

HTTP is a stateless protocol—each request is independent, with no inherent memory of previous requests. PHP provides several mechanisms for maintaining state across requests:

Superglobals like `$_GET`, `$_POST`, and `$_COOKIE` carry data from request to request. `$_GET` contains URL parameters, visible in the address bar and bookmarks. `$_POST` carries form submission data. `$_COOKIE` stores small pieces of data on the client that are sent with every request.

Sessions provide server-side state storage with a client-side identifier. PHP's session handling generates a unique session ID, stores it in a cookie, and associates server-side data with that ID. Sessions are critical for authentication, shopping carts, and user preferences:

```php
session_start();

// Store data
$_SESSION['user_id'] = $user->id;
$_SESSION['last_activity'] = time();

// Retrieve data
$userId = $_SESSION['user_id'] ?? null;
```

Session configuration in `php.ini` controls session lifetime, storage mechanism, and security settings. For production applications, sessions should use secure storage like Redis rather than the default file-based handler:

```php
ini_set('session.save_handler', 'redis');
ini_set('session.save_path', 'tcp://redis:6379');
ini_set('session.gc_maxlifetime', 86400);
ini_set('session.cookie_secure', '1');
ini_set('session.cookie_httponly', '1');
ini_set('session.cookie_samesite', 'Lax');
```

---

### Chapter 2: Language Basics

#### 2.1 Syntax, Semicolons, and Code Blocks

PHP syntax draws from C, Perl, and Java, making it familiar to developers with experience in those languages. However, PHP's dynamic nature and web-focused origins create subtle differences that merit careful attention.

**Statement Termination**

PHP requires semicolons to terminate statements. Unlike JavaScript, where semicolons are often optional due to automatic semicolon insertion, PHP enforces explicit termination. Omitting a semicolon produces a parse error:

```php
// Correct
$name = 'John';
echo $name;

// Parse error
$name = 'John'
echo $name; // Parse error: syntax error, unexpected 'echo'
```

The only exception is when a statement is immediately followed by a closing PHP tag, where the semicolon is implied:

```php
<?php if ($condition): ?>
    <p>Condition is true</p>
<?php endif; // Semicolon optional before closing tag ?>
```

**Whitespace and Formatting**

PHP is whitespace-insensitive, treating spaces, tabs, and newlines equally. This allows developers to format code for readability without affecting execution:

```php
// These are identical
echo 'Hello'; echo 'World';

echo 'Hello';
echo 'World';
```

PHP coding standards like PSR-12 provide detailed formatting guidelines: four-space indentation (no tabs), one blank line between methods, no trailing whitespace, and specific brace placement. Consistent formatting improves code review and collaboration.

**Comments**

PHP supports three comment styles. Single-line comments use `//` or `#`. Multi-line comments use `/* */`:

```php
// This is a single-line comment
# This is also a single-line comment (less common)

/*
 * This is a multi-line comment
 * suitable for documentation blocks
 */

/**
 * DocBlock comment for documenting functions and classes
 * 
 * @param string $name The user's name
 * @return string A greeting message
 */
function greet(string $name): string
{
    return "Hello, {$name}!";
}
```

DocBlock comments, while not part of PHP itself, are a de facto standard for documenting code. They use PHPDocumentor syntax with annotations like `@param`, `@return`, `@throws`, and `@var`. Many IDEs parse DocBlocks to provide tooltips and type information.

**Code Blocks and Scope**

Curly braces (`{}`) define code blocks for control structures, functions, and classes. They create lexical scope for variables (with exceptions for certain language constructs):

```php
if ($condition) {
    $x = 10; // $x is available after this block
    $y = 20;
}

echo $x; // Works: 10
echo $y; // Works: 20

// PHP does not have block-level scope for variables
// Variables defined inside blocks are accessible outside
```

Unlike many languages, PHP does not have block-level variable scope. Variables defined inside `if` blocks, loops, or bare `{}` blocks remain accessible after the block ends. Only functions and classes create new variable scopes.

#### 2.2 Variables, Constants, and Variable Variables

**Variables**

PHP variables are prefixed with `$`, followed by a name starting with a letter or underscore. Variable names are case-sensitive and can contain letters, numbers, and underscores:

```php
$name = 'Alice';
$user_2 = 'Bob';
$_internal = 'private';
$café = 'Works with UTF-8'; // PHP 8 allows extended characters
```

Variables are loosely typed by default, meaning they can hold values of different types throughout their lifetime. Assigning a new value changes both the value and the type:

```php
$value = 42;        // integer
$value = 'forty-two'; // now a string
$value = [4, 2];    // now an array
```

This flexibility is both a strength and a source of bugs. Type declarations (covered later) provide a way to constrain types when needed.

**Variable Assignment and References**

Assignment copies values by default for scalar types and arrays. Objects are assigned by reference (technically, the object identifier is copied, not the object itself):

```php
$a = 10;
$b = $a;    // $b gets a copy of 10
$b = 20;    // $a is still 10

$obj1 = new stdClass();
$obj1->value = 42;
$obj2 = $obj1;     // $obj2 references the same object
$obj2->value = 99; // $obj1->value is also 99
```

Explicit references use the `&` operator to create aliases:

```php
$a = 10;
$b = &$a;   // $b is a reference to $a
$b = 20;    // $a is now also 20
```

References are most commonly used in function parameters to modify variables passed by callers:

```php
function addSuffix(string &$name): void
{
    $name .= ' Jr.';
}

$fullName = 'Robert';
addSuffix($fullName);
echo $fullName; // 'Robert Jr.'
```

**Constants**

Constants store values that cannot change during script execution. PHP supports two constant declaration styles:

```php
// Traditional define() function
define('APP_NAME', 'My Application');
define('DEBUG_MODE', true);

// const keyword (compile-time constants)
const MAX_USERS = 100;
const GREETING = 'Hello, World!';
```

The `const` keyword has several advantages: it's parsed at compile time, supports arrays and expressions with constant values, and respects namespaces. The `define()` function runs at runtime and can use expressions:

```php
define('TIMESTAMP', time()); // Runtime evaluation

const ARR = [1, 2, 3];       // Array constant (PHP 7+)
// const TIME = time();      // Error: not a constant expression
```

PHP 8.3 introduced typed class constants:

```php
class Configuration
{
    const string APP_NAME = 'My App';
    const int MAX_CONNECTIONS = 100;
    const bool DEBUG = false;
}
```

Constants are global by default but can be namespace-scoped. The `defined()` function checks if a constant exists:

```php
if (!defined('API_KEY')) {
    define('API_KEY', 'sk-123456');
}
```

**Magic Constants**

PHP provides predefined constants that change depending on context:

- `__LINE__`: Current line number in the file
- `__FILE__`: Full path and filename of the file
- `__DIR__`: Directory of the file (without trailing slash, equivalent to `dirname(__FILE__)`)
- `__FUNCTION__`: Current function name
- `__CLASS__`: Current class name including namespace
- `__TRAIT__`: Current trait name
- `__METHOD__`: Current method name including class
- `__NAMESPACE__`: Current namespace name

These are particularly useful for logging, debugging, and path resolution:

```php
spl_autoload_register(function(string $class): void {
    $path = __DIR__ . '/' . str_replace('\\', '/', $class) . '.php';
    if (file_exists($path)) {
        require_once $path;
    }
});
```

**Variable Variables**

PHP supports variable variables, where a variable's name is determined by another variable's value:

```php
$field = 'email';
$$field = 'user@example.com'; // Creates variable $email

echo $email; // 'user@example.com'
```

Variable variables can be chained and used with array elements:

```php
$a = 'b';
$b = 'c';
$c = 'Hello';
echo $$$a; // 'Hello' — evaluates $a to 'b', then $b to 'c', then $c to 'Hello'
```

While powerful, variable variables can make code difficult to understand, debug, and statically analyze. They should be used sparingly and with caution, typically only in meta-programming scenarios where alternatives like arrays or objects are impractical.

#### 2.3 Data Types: Scalar, Compound, and Special Types

PHP's type system comprises scalar types (single values), compound types (collections of values), and special types. Understanding how PHP handles types, including implicit and explicit conversion, is fundamental to writing correct and predictable code.

**Scalar Types**

**Integers** represent whole numbers without decimal points. On 64-bit systems, integers range from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 (64-bit signed). PHP automatically converts integers to floats when they exceed the integer range:

```php
$population = 8_000_000_000; // Numeric literal separator (PHP 7.4+)
$hex = 0xFF;      // 255
$octal = 0o755;   // 493 (PHP 8.1+)
$binary = 0b1010; // 10
```

Integer literals support underscores for readability, hexadecimal (`0x`), octal (`0o`), and binary (`0b`) notation.

**Floats** (double-precision floating-point numbers) represent numbers with fractional parts. PHP uses IEEE 754 64-bit format, which provides approximately 15-16 significant digits of precision:

```php
$pi = 3.14159;
$scientific = 1.5e3; // 1500
$tiny = 1.5e-3;      // 0.0015
```

The limited precision of floats is a common source of bugs in financial calculations. Use the `BCMath` or `Decimal` extensions for precise decimal arithmetic when accuracy matters:

```php
// Problematic
$result = 0.1 + 0.2; // 0.30000000000000004
$equal = $result === 0.3; // false

// Accurate
$result = bcadd('0.1', '0.2', 2); // '0.30'
```

**Strings** represent sequences of characters. PHP strings can be single-quoted, double-quoted, heredoc, or nowdoc:

```php
$name = 'Alice';

// Single-quoted: minimal parsing, only \\ and \'
$literal = 'Hello, $name'; // 'Hello, $name'

// Double-quoted: interpolates variables and escape sequences
$interpolated = "Hello, $name"; // 'Hello, Alice'
$complex = "Hello, {$name}s";   // 'Hello, Alices'

// Heredoc: multi-line with interpolation
$heredoc = <<<EOT
Hello, $name
This is a multi-line string
EOT;

// Nowdoc: multi-line without interpolation
$nowdoc = <<<'EOT'
Hello, $name
Variables are not parsed
EOT;
```

String indexing accesses individual bytes (not characters) using bracket notation:

```php
$str = 'Hello';
echo $str[0]; // 'H'
$str[1] = 'a'; // 'Hallo'
```

For multibyte strings containing UTF-8 characters, use the `mb_*` functions for correct character-level operations.

**Booleans** represent truth values: `true` or `false` (case-insensitive, though lowercase is standard). Boolean conversion follows specific rules:

- `false`: `0`, `0.0`, `''`, `'0'`, `[]`, `null`, and uninitialized variables
- `true`: Everything else, including negative numbers, non-empty strings, and objects

```php
$isActive = true;
$isEmpty = false;

// Boolean conversion gotchas
(bool) '';        // false
(bool) '0';       // false — surprising!
(bool) 'false';   // true — non-empty string
(bool) -1;        // true — non-zero number
```

**Compound Types**

**Arrays** are ordered collections of key-value pairs. PHP arrays are incredibly flexible, supporting sequential integer keys, string keys, mixed keys, and nesting:

```php
// Indexed array (sequential integer keys)
$colors = ['red', 'green', 'blue'];

// Associative array (string keys)
$user = [
    'name' => 'Alice',
    'email' => 'alice@example.com',
    'age' => 30,
];

// Mixed keys
$data = [
    0 => 'first',
    'key' => 'value',
    1 => 'second',
];

// Multi-dimensional
$matrix = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9],
];
```

The spread operator (`...`) unpacks arrays:

```php
$defaults = ['limit' => 10, 'offset' => 0];
$userSettings = ['limit' => 50];
$settings = [...$defaults, ...$userSettings]; // ['limit' => 50, 'offset' => 0]
```

Array destructuring extracts values into variables:

```php
// Indexed destructuring
[$red, $green, $blue] = $colors;

// Associative destructuring (PHP 7.1+)
['name' => $name, 'email' => $email] = $user;

// Skipping elements
[, $second, , $fourth] = [1, 2, 3, 4];
```

**Objects** are instances of classes. PHP objects are accessed by handle (similar to references), meaning assignments and function calls pass the object identity rather than copying:

```php
class User
{
    public function __construct(
        public string $name,
        public string $email,
    ) {}
}

$user1 = new User('Alice', 'alice@example.com');
$user2 = $user1;         // Both reference the same object
$user2->name = 'Bob';    // $user1->name is also 'Bob'

$clone = clone $user1;   // Creates a shallow copy
$clone->name = 'Charlie'; // $user1->name remains 'Bob'
```

**Special Types**

**Null** represents a variable with no value. A variable is null if it has been assigned the constant `null`, hasn't been set to any value yet, or has been unset:

```php
$var = null;
$uninitialized; // Undefined variable warning in PHP 8, but evaluates to null if accessed
unset($var);    // $var is now undefined
```

Use the null coalescing operator (`??`) and null coalescing assignment operator (`??=`) for concise null checks:

```php
$name = $_GET['name'] ?? 'Guest';
$config['debug'] ??= false; // Sets default if not set
```

**Resources** hold references to external resources like database connections, file handles, and curl instances. Most resource types are being replaced by opaque objects in modern PHP:

```php
// Traditional resource
$file = fopen('data.txt', 'r');
// ... use file operations ...
fclose($file);

// Modern object-based approach (GD extension in PHP 8.0+)
$image = imagecreatetruecolor(100, 100);
```

**Callback/Callable** represents callable values: function names, closures, object methods, and static methods. This pseudo-type is used for type hints:

```php
function processItems(array $items, callable $callback): array
{
    $result = [];
    foreach ($items as $item) {
        $result[] = $callback($item);
    }
    return $result;
}

// Calling with different callable types
$result1 = processItems([1, 2, 3], 'strval');
$result2 = processItems([1, 2, 3], fn($n) => $n * 2);
$result3 = processItems([1, 2, 3], [$object, 'method']);
```

#### 2.4 Type Declarations and Strict Typing

Type declarations have transformed PHP from a dynamically typed language with unpredictable behavior to one where types can be explicitly specified and enforced. Modern PHP development embraces type declarations as a best practice for catching errors early and improving code clarity.

**Argument Type Declarations**

Function and method parameters can specify expected types:

```php
function calculateTotal(float $price, int $quantity, ?string $currency = null): float
{
    $total = $price * $quantity;
    if ($currency) {
        // Apply currency conversion
    }
    return $total;
}

calculateTotal(19.99, 3);           // Works
calculateTotal('19.99', '3');       // Works with coercive mode
calculateTotal(true, 3);            // TypeError in strict mode
```

The nullable type prefix (`?`) allows the value to be null in addition to the specified type. Union types (PHP 8.0+) accept multiple types:

```php
function process(int|string $id): void
{
    if (is_int($id)) {
        // Handle numeric ID
    } else {
        // Handle string slug
    }
}
```

**Return Type Declarations**

Return types follow the parameter list, preceded by a colon:

```php
function getUser(int $id): ?User
{
    return User::find($id); // Returns User or null
}

function redirect(string $url): never
{
    header("Location: {$url}");
    exit();
}
```

The `void` return type indicates no return value. The `never` return type (PHP 8.1+) declares that the function never returns (it throws an exception or terminates the script).

**Property Type Declarations**

PHP 7.4 introduced typed properties, allowing class properties to declare their types:

```php
class Product
{
    public string $name;
    public float $price;
    public ?string $description = null;
    private array $tags = [];
    
    // PHP 8.1 readonly properties
    public readonly string $sku;
    
    // PHP 8.2 readonly classes
    // All properties are readonly
}

readonly class ValueObject
{
    public string $id;
    public DateTimeImmutable $createdAt;
}
```

Typed properties must be initialized before access, either with a default value or during construction. Uninitialized properties trigger a `TypeError` when accessed.

**Coercive vs. Strict Typing**

PHP operates in two typing modes. Coercive mode (default) attempts to convert values to the declared type when possible. Strict mode rejects any value that doesn't exactly match the declared type:

```php
declare(strict_types=1); // Enable strict typing for this file

function add(int $a, int $b): int
{
    return $a + $b;
}

// Coercive mode (without strict_types)
add('5', '10');  // Returns 15 (strings coerced to ints)

// Strict mode (with strict_types=1)
add('5', '10');  // TypeError: must be of type int, string given
```

The `declare(strict_types=1)` directive affects only the file that calls the function, not the file that defines it. This enables library authors to add type declarations without breaking existing code that relies on coercion.

**The `mixed` Type**

The `mixed` type (PHP 8.0+) represents any value: `array|bool|callable|int|float|null|object|resource|string`. It's the implicit type for parameters without type declarations:

```php
function log(mixed $value): void
{
    var_dump($value);
}

log('string');
log(42);
log(['array']);
log(null);
```

**Type Variance**

PHP supports covariant return types and contravariant parameter types in inheritance:

```php
interface Animal {}
class Dog implements Animal {}
class Puppy extends Dog {}

interface AnimalFactory
{
    public function create(): Animal;
}

class DogFactory implements AnimalFactory
{
    // Covariant return type: Animal -> Dog (narrower)
    public function create(): Dog
    {
        return new Dog();
    }
}

class Consumer
{
    public function consume(Dog $dog): void {}
}

class PuppyConsumer extends Consumer
{
    // Contravariant parameter type: Dog -> Animal (wider)
    public function consume(Animal $animal): void {}
}
```

This aligns PHP with the Liskov substitution principle, ensuring that subtypes can be used wherever their parent types are expected.

#### 2.5 Operators: Arithmetic, Logical, Bitwise, Spaceship, and Null Coalescing

PHP provides a rich set of operators that cover everything from basic arithmetic to sophisticated comparisons and null-safe access patterns.

**Arithmetic Operators**

Standard arithmetic operations work as expected, with automatic type conversion for numeric strings:

```php
$sum = 10 + 5;         // 15
$difference = 10 - 5;  // 5
$product = 10 * 5;     // 50
$quotient = 10 / 5;    // 2.0 (always returns float)
$remainder = 10 % 3;   // 1
$power = 10 ** 3;      // 1000

// Compound assignment
$count = 0;
$count += 5;  // Same as: $count = $count + 5;
$count++;     // Increment: 6
$count--;     // Decrement: 5
```

The division operator always returns a float, even when the result is a whole number.

**String Operators**

PHP uses the dot (`.`) for string concatenation:

```php
$firstName = 'John';
$lastName = 'Doe';
$fullName = $firstName . ' ' . $lastName; // 'John Doe'

// Compound concatenation
$message = 'Hello';
$message .= ', World!'; // 'Hello, World!'
```

**Comparison Operators**

PHP provides both loose and strict comparison:

```php
// Loose comparison (type coercion)
5 == '5';        // true
5 != '5';        // false

// Strict comparison (same type and value)
5 === '5';       // false (different types)
5 !== '5';       // true

// Numeric comparison
5 < 10;          // true
5 <= 5;          // true
10 > 5;          // true
10 >= 10;        // true
```

The spaceship operator (`<=>`) returns -1, 0, or 1 for less than, equal, or greater than:

```php
1 <=> 2;   // -1
2 <=> 2;   // 0
3 <=> 2;   // 1

// Useful for sorting
usort($items, fn($a, $b) => $a['priority'] <=> $b['priority']);
```

**Null Coalescing Operators**

The null coalescing operator (`??`) checks if a value is set and not null:

```php
// Traditional
$username = isset($_GET['username']) ? $_GET['username'] : 'Guest';

// Null coalescing
$username = $_GET['username'] ?? 'Guest';

// Chaining
$displayName = $_POST['name'] ?? $_SESSION['name'] ?? 'Anonymous';

// Null coalescing assignment (PHP 7.4+)
$config['debug'] ??= false; // Sets only if not set
```

**Logical Operators**

Logical operators work with boolean values and are commonly used in conditions:

```php
// AND: true if both operands are truthy
if ($isAuthenticated && $hasPermission) { }

// OR: true if either operand is truthy
if ($isAdmin || $isModerator) { }

// NOT: negates the value
if (! $isDeleted) { }

// Short-circuit evaluation
$user = getUser() && $user->isActive(); // Only calls getUser() if needed
```

The alternative `and` and `or` operators have lower precedence than `&&` and `||`:

```php
// These are different!
$result = true || false;   // Assignment happens first, results in true
$result = true or false;   // Equivalent to: ($result = true) or false
```

**Ternary Operator**

The ternary operator provides a concise conditional expression:

```php
$status = $age >= 18 ? 'adult' : 'minor';

// Nested ternary (use sparingly for readability)
$category = $score >= 90 ? 'A' : ($score >= 80 ? 'B' : 'C');

// Elvis operator (PHP 5.3+): returns first value if truthy
$display = $userInput ?: 'Default'; // Equivalent to: $userInput ? $userInput : 'Default'
```

**Bitwise Operators**

Bitwise operators manipulate individual bits within integers:

```php
$flags = 0b0000;
$flags |= 0b0001;  // Set bit 0
$flags |= 0b0010;  // Set bit 1

$hasBit1 = ($flags & 0b0001) !== 0; // true

// Bitwise NOT, XOR, left shift, right shift
$inverse = ~$flags;     // Flip all bits
$toggle = $flags ^ 0b0011; // Toggle bits
$doubled = $flags << 1;    // Multiply by 2
$halved = $flags >> 1;     // Divide by 2
```

**Error Control Operator**

The `@` operator suppresses error messages for a single expression. Its use is strongly discouraged in modern PHP because it degrades performance and hides genuine issues:

```php
$content = @file_get_contents('may-not-exist.txt');
// Better:
$content = file_get_contents('may-not-exist.txt');
if ($content === false) {
    // Handle the error properly
}
```

**Execution Operator**

Backticks execute shell commands and return the output:

```php
$files = `ls -la`; // Unix/Linux command
```

This operator should be avoided for security reasons; use `exec()`, `shell_exec()`, or Symfony's Process component instead with proper input sanitization.

#### 2.6 Expressions, Statements, and Control Flow

**Expressions**

In PHP, almost everything is an expression that evaluates to a value. Assignments are expressions that return the assigned value, enabling chaining:

```php
$a = ($b = 5) + 3; // $b is 5, $a is 8

// Function calls in expressions
$result = strtoupper(trim($input));

// Conditional expressions
$value = $condition ? doSomething() : doOtherThing();
```

The fact that assignments are expressions enables compact patterns but can also produce confusing code when not used carefully.

**Statements**

Statements perform actions but don't produce values. Common statement types include:

- Expression statements: An expression followed by a semicolon
- Compound statements: Blocks enclosed in braces
- Selection statements: `if`, `switch`, `match`
- Iteration statements: `while`, `do-while`, `for`, `foreach`
- Jump statements: `break`, `continue`, `return`, `goto`
- Declaration statements: Function, class, and namespace declarations

**Expression vs. Statement Distinction**

The distinction matters for certain language constructs:

```php
// echo is a statement, not an expression
$result = echo 'Hello'; // Parse error!

// print is an expression that always returns 1
$result = print 'Hello'; // Prints 'Hello', $result is 1

// Variable assignment is an expression
while ($row = fetchNext()) {
    // Process $row
}
```

**Control Flow Patterns**

Beyond basic conditional and loop structures, PHP offers several patterns for managing program flow:

Early returns reduce nesting and improve readability:

```php
function processOrder(?Order $order): array
{
    if ($order === null) {
        return ['error' => 'Order not found'];
    }
    
    if ($order->isCancelled()) {
        return ['error' => 'Order is cancelled'];
    }
    
    if (!$order->isPaid()) {
        return ['error' => 'Payment required'];
    }
    
    // Main processing logic
    $result = $order->ship();
    return ['success' => $result];
}
```

Guard clauses validate preconditions at the beginning of functions, eliminating invalid states early:

```php
function divide(int $numerator, int $denominator): float
{
    if ($denominator === 0) {
        throw new DivisionByZeroError('Cannot divide by zero');
    }
    
    return $numerator / $denominator;
}
```

---

### Chapter 3: Control Structures

#### 3.1 Conditional Statements: `if`, `else`, `elseif`, `switch`, and `match`

Conditional execution is the foundation of program logic, enabling different code paths based on dynamic conditions.

**The `if` Statement**

The basic `if` statement executes a block when a condition evaluates to `true`:

```php
if ($temperature > 30) {
    echo "It's hot outside!";
}
```

The condition can be any expression that evaluates to a boolean. PHP's loose typing means non-boolean values are automatically converted: `0`, `''`, `[]`, `null` become `false`; everything else becomes `true`.

**The `else` and `elseif` Clauses**

`else` provides an alternative path when the condition is false. `elseif` chains multiple conditions:

```php
if ($score >= 90) {
    $grade = 'A';
} elseif ($score >= 80) {
    $grade = 'B';
} elseif ($score >= 70) {
    $grade = 'C';
} elseif ($score >= 60) {
    $grade = 'D';
} else {
    $grade = 'F';
}
```

Beware of dangling else ambiguity and always use braces for clarity, even when the block contains a single statement. The PSR-12 coding standard requires braces for all control structures.

**The `switch` Statement**

`switch` compares a value against multiple cases using loose comparison:

```php
switch ($method) {
    case 'GET':
        handleGet();
        break;
    case 'POST':
        handlePost();
        break;
    case 'PUT':
    case 'PATCH':
        handleUpdate();
        break;
    default:
        throw new InvalidArgumentException("Unknown method: {$method}");
}
```

The `break` statement prevents fall-through to subsequent cases. Omitting `break` intentionally requires a comment explaining why:

```php
switch ($status) {
    case 'pending':
        logAudit('Status set to pending');
        // Intentional fall-through
    case 'draft':
        sendNotification();
        break;
}
```

`switch` uses loose comparison, which can produce surprising results with mixed types:

```php
switch (0) {
    case 'zero':    // 'zero' loosely equals 0? No, so this doesn't match
        break;
    case null:      // null loosely equals 0? Yes!
        echo 'Matches null'; // This executes!
        break;
}
```

**The `match` Expression (PHP 8.0+)**

The `match` expression addresses `switch`'s shortcomings with strict comparison, return values, and exhaustiveness checking:

```php
$result = match ($statusCode) {
    200, 201, 204 => 'Success',
    301, 302 => 'Redirect',
    400, 404 => 'Client Error',
    500, 502, 503 => 'Server Error',
    default => 'Unknown',
};

// Using match for complex mappings
$handler = match (true) {
    $age < 13 => new ChildHandler(),
    $age < 18 => new TeenHandler(),
    $age < 65 => new AdultHandler(),
    default => new SeniorHandler(),
};
```

#### 3.2 Loops: `for`, `while`, `do-while`, `foreach`, and Iteration Techniques

Loops enable repetitive execution of code blocks, essential for processing collections, generating sequences, and implementing algorithms. PHP provides four primary loop constructs, each suited to different scenarios.

**The `while` Loop**

The `while` loop evaluates a condition before each iteration, executing the body only while the condition remains true:

```php
$count = 1;
while ($count <= 10) {
    echo "Iteration {$count}\n";
    $count++;
}
```

`while` loops are ideal when the number of iterations is unknown beforehand, such as processing database result sets or reading files:

```php
$file = fopen('data.csv', 'r');
while (($row = fgetcsv($file)) !== false) {
    processRow($row);
}
fclose($file);
```

The condition is checked before each iteration, meaning the body may never execute if the condition is initially false.

**The `do-while` Loop**

The `do-while` loop guarantees at least one execution by checking the condition after the body:

```php
do {
    $input = readline('Enter a number between 1 and 10: ');
    $number = (int) $input;
} while ($number < 1 || $number > 10);

echo "You entered: {$number}";
```

This construct is less common but useful when the loop body must execute before the termination condition can be evaluated, such as input validation, menu systems, and game loops.

**The `for` Loop**

The `for` loop combines initialization, condition, and increment in a single statement:

```php
for ($i = 0; $i < 10; $i++) {
    echo "Square of {$i} is " . ($i * $i) . "\n";
}
```

Each of the three expressions is optional. Omitting the condition creates an infinite loop:

```php
for (;;) {
    // Infinite loop - use break to exit
    $data = fetchData();
    if ($data === null) {
        break;
    }
    process($data);
}
```

Multiple expressions can be included using the comma operator:

```php
for ($i = 0, $j = 10; $i < 10; $i++, $j--) {
    echo "i={$i}, j={$j}\n";
}
```

The `for` loop excels with numeric iteration where the start, end, and step are known. For iterating over collections, `foreach` is more appropriate.

**The `foreach` Loop**

The `foreach` loop iterates over arrays and Traversable objects, providing the cleanest syntax for collection traversal:

```php
$users = [
    ['name' => 'Alice', 'email' => 'alice@example.com'],
    ['name' => 'Bob', 'email' => 'bob@example.com'],
    ['name' => 'Charlie', 'email' => 'charlie@example.com'],
];

foreach ($users as $user) {
    echo "{$user['name']} <{$user['email']}>\n";
}
```

Accessing both keys and values:

```php
foreach ($users as $index => $user) {
    echo "#{$index}: {$user['name']}\n";
}
```

A common pitfall involves modifying arrays during iteration. PHP operates on a copy of the array by default. To modify the original array, use a reference:

```php
// Modifying values via reference
foreach ($prices as &$price) {
    $price *= 1.1; // Apply 10% increase
}
unset($price); // Important: break the reference after the loop

// Without reference, modifications don't persist
foreach ($prices as $price) {
    $price *= 1.1; // This changes the copy, not the original
}
```

Always call `unset()` on the reference variable after the loop to prevent accidental modifications later in the code.

**Iteration Techniques and Patterns**

**Array destructuring in foreach** (PHP 7.1+):

```php
$coordinates = [
    ['x' => 10, 'y' => 20],
    ['x' => 30, 'y' => 40],
];

foreach ($coordinates as ['x' => $x, 'y' => $y]) {
    echo "Point at ({$x}, {$y})\n";
}
```

**Iterating with index tracking**:

```php
$items = ['a', 'b', 'c', 'd'];
$total = count($items);

foreach ($items as $index => $item) {
    $isFirst = $index === 0;
    $isLast = $index === $total - 1;
    
    if ($isFirst) {
        echo "<first>";
    }
    echo $item;
    if ($isLast) {
        echo "</last>";
    } else {
        echo ", ";
    }
}
```

**Lazy iteration with generators** for memory efficiency with large datasets:

```php
function readLargeFile(string $path): Generator
{
    $file = fopen($path, 'r');
    while (($line = fgets($file)) !== false) {
        yield trim($line);
    }
    fclose($file);
}

// Only one line in memory at a time
foreach (readLargeFile('massive-log.txt') as $line) {
    processLine($line);
}
```

**Chunking iterations** for batch processing:

```php
$records = range(1, 1000);
$chunkSize = 100;

foreach (array_chunk($records, $chunkSize) as $chunk) {
    processBatch($chunk);
    clearCache();
}
```

**Nested loop optimization** by avoiding repeated computations:

```php
// Inefficient
foreach ($categories as $category) {
    $products = getProductsByCategory($category['id']); // Query per category
    foreach ($products as $product) {
        renderProduct($product, $category);
    }
}

// Efficient: load all data first
$allProducts = getAllProductsGroupedByCategory();
foreach ($categories as $category) {
    $products = $allProducts[$category['id']] ?? [];
    foreach ($products as $product) {
        renderProduct($product, $category);
    }
}
```

#### 3.3 Break, Continue, and Goto

**The `break` Statement**

`break` immediately terminates the current loop or switch statement:

```php
$target = 42;
$found = false;

foreach ($data as $item) {
    if ($item['id'] === $target) {
        $found = true;
        break; // Exit loop immediately
    }
    processItem($item);
}
```

`break` accepts an optional integer argument to break out of nested structures:

```php
foreach ($matrix as $row) {
    foreach ($row as $cell) {
        if ($cell < 0) {
            break 2; // Exit both loops
        }
        process($cell);
    }
}
```

**The `continue` Statement**

`continue` skips the rest of the current iteration and moves to the next:

```php
foreach ($users as $user) {
    if (!$user->isActive()) {
        continue; // Skip inactive users
    }
    
    if ($user->isBounced()) {
        continue; // Skip users with bounced emails
    }
    
    sendNewsletter($user);
}
```

Like `break`, `continue` accepts a numeric argument for nested loops:

```php
foreach ($departments as $dept) {
    foreach ($dept->getEmployees() as $employee) {
        if ($employee->isOnLeave()) {
            continue 2; // Skip to next department
        }
        calculatePayroll($employee);
    }
}
```

**The `goto` Statement**

`goto` jumps to a labeled point in the same file and scope. While often discouraged for creating spaghetti code, it has legitimate uses for breaking out of deeply nested structures or implementing cleanup logic:

```php
function processFile(string $path): ?array
{
    $file = @fopen($path, 'r');
    if ($file === false) {
        return null;
    }
    
    $lockAcquired = flock($file, LOCK_SH);
    if (!$lockAcquired) {
        goto cleanup_file;
    }
    
    $data = [];
    while (($row = fgetcsv($file)) !== false) {
        if (!validateRow($row)) {
            goto cleanup_lock;
        }
        $data[] = $row;
    }
    
    cleanup_lock:
    flock($file, LOCK_UN);
    
    cleanup_file:
    fclose($file);
    
    return $data ?? null;
}
```

This pattern ensures cleanup code always runs, regardless of early exits. Modern PHP often achieves the same result with `try-finally`, but `goto` remains available for specific cases.

#### 3.4 Alternative Syntax for Templates

PHP provides alternative syntax for control structures specifically designed for embedding in HTML templates. These use colons and explicit closing keywords instead of braces:

**if/elseif/else**:

```php
<?php if ($user->isAuthenticated()): ?>
    <div class="dashboard">
        <h2>Welcome, <?= htmlspecialchars($user->name) ?></h2>
        <p>Your last login was <?= $user->lastLogin->format('Y-m-d') ?></p>
    </div>
<?php elseif ($showLoginForm): ?>
    <form method="post" action="/login">
        <input type="email" name="email" placeholder="Email">
        <input type="password" name="password" placeholder="Password">
        <button type="submit">Login</button>
    </form>
<?php else: ?>
    <p>Login is currently disabled for maintenance.</p>
<?php endif; ?>
```

**foreach**:

```php
<table>
    <thead>
        <tr>
            <th>Name</th>
            <th>Email</th>
            <th>Status</th>
        </tr>
    </thead>
    <tbody>
        <?php foreach ($users as $user): ?>
            <tr class="<?= $user->isActive() ? 'active' : 'inactive' ?>">
                <td><?= htmlspecialchars($user->name) ?></td>
                <td><?= htmlspecialchars($user->email) ?></td>
                <td><?= $user->isActive() ? 'Active' : 'Inactive' ?></td>
            </tr>
        <?php endforeach; ?>
    </tbody>
</table>
```

**for and while**:

```php
<?php for ($i = 1; $i <= 5; $i++): ?>
    <h<?= $i ?>>Heading Level <?= $i ?></h<?= $i ?>>
<?php endfor; ?>

<?php while ($post = $posts->fetch()): ?>
    <article>
        <h3><?= htmlspecialchars($post['title']) ?></h3>
    </article>
<?php endwhile; ?>
```

**switch**:

```php
<?php switch ($notificationType): ?>
    <?php case 'success': ?>
        <div class="alert alert-success"><?= $message ?></div>
        <?php break; ?>
    <?php case 'error': ?>
        <div class="alert alert-error"><?= $message ?></div>
        <?php break; ?>
    <?php case 'warning': ?>
        <div class="alert alert-warning"><?= $message ?></div>
        <?php break; ?>
    <?php default: ?>
        <div class="alert alert-info"><?= $message ?></div>
<?php endswitch; ?>
```

The alternative syntax integrates more naturally with HTML than brace syntax. Most PHP templating engines (Blade, Twig) build on these concepts with additional features.

#### 3.5 Practical Flow Control Patterns

**State Machine Implementation**

State machines model processes with distinct states and transitions. The match expression from PHP 8.0 provides elegant state machine logic:

```php
enum OrderState: string
{
    case Pending = 'pending';
    case Confirmed = 'confirmed';
    case Shipped = 'shipped';
    case Delivered = 'delivered';
    case Cancelled = 'cancelled';
}

class OrderStateMachine
{
    private const array TRANSITIONS = [
        'pending' => ['confirmed', 'cancelled'],
        'confirmed' => ['shipped', 'cancelled'],
        'shipped' => ['delivered'],
        'delivered' => [],
        'cancelled' => [],
    ];
    
    public function transition(Order $order, OrderState $newState): void
    {
        $current = $order->getState()->value;
        $target = $newState->value;
        
        $allowed = self::TRANSITIONS[$current] ?? [];
        
        if (!in_array($target, $allowed, true)) {
            throw new InvalidStateTransitionException(
                "Cannot transition from {$current} to {$target}"
            );
        }
        
        $order->setState($newState);
        
        // Side effects based on transition
        match (true) {
            $target === 'confirmed' => $this->sendOrderConfirmation($order),
            $target === 'shipped' => $this->sendShippingNotification($order),
            $target === 'cancelled' => $this->processRefund($order),
            default => null,
        };
    }
}
```

**Retry Logic with Exponential Backoff**

Network operations and external API calls benefit from retry logic:

```php
function callExternalApi(string $url, int $maxRetries = 3): array
{
    $attempt = 0;
    $baseDelay = 100; // milliseconds
    
    while ($attempt < $maxRetries) {
        try {
            $response = makeHttpRequest($url);
            if ($response->getStatusCode() === 200) {
                return json_decode($response->getBody(), true);
            }
            
            if ($response->getStatusCode() >= 500) {
                throw new ServerErrorException("Server error");
            }
            
            // Client error - don't retry
            throw new ClientErrorException("Client error");
            
        } catch (ServerErrorException $e) {
            $attempt++;
            if ($attempt === $maxRetries) {
                throw new MaxRetriesExceededException(
                    "Failed after {$maxRetries} attempts",
                    0,
                    $e
                );
            }
            
            // Exponential backoff with jitter
            $delay = $baseDelay * (2 ** ($attempt - 1));
            $jitter = random_int(0, $delay);
            usleep(($delay + $jitter) * 1000);
        }
    }
    
    throw new LogicException('Unreachable');
}
```

**Pagination Logic**

Pagination requires careful boundary handling:

```php
function paginate(int $totalItems, int $currentPage, int $perPage = 20): array
{
    $totalPages = max(1, (int) ceil($totalItems / $perPage));
    $currentPage = max(1, min($currentPage, $totalPages));
    $offset = ($currentPage - 1) * $perPage;
    
    $pages = [];
    $maxVisible = 7;
    
    if ($totalPages <= $maxVisible) {
        $pages = range(1, $totalPages);
    } else {
        // Always show first page
        $pages[] = 1;
        
        $start = max(2, $currentPage - 2);
        $end = min($totalPages - 1, $currentPage + 2);
        
        if ($start > 2) {
            $pages[] = '...';
        }
        
        for ($i = $start; $i <= $end; $i++) {
            $pages[] = $i;
        }
        
        if ($end < $totalPages - 1) {
            $pages[] = '...';
        }
        
        // Always show last page
        $pages[] = $totalPages;
    }
    
    return [
        'current_page' => $currentPage,
        'total_pages' => $totalPages,
        'per_page' => $perPage,
        'total_items' => $totalItems,
        'offset' => $offset,
        'pages' => $pages,
        'has_previous' => $currentPage > 1,
        'has_next' => $currentPage < $totalPages,
        'previous_page' => $currentPage > 1 ? $currentPage - 1 : null,
        'next_page' => $currentPage < $totalPages ? $currentPage + 1 : null,
    ];
}
```

---

### Chapter 4: Functions

#### 4.1 Declaring and Invoking Functions

Functions are the primary unit of code organization in PHP, encapsulating logic into reusable, testable units. PHP supports user-defined functions, anonymous functions, arrow functions, and first-class callable syntax.

**Basic Function Declaration**

```php
function greet(string $name): string
{
    return "Hello, {$name}!";
}

// Invocation
$message = greet('Alice');
echo $message; // "Hello, Alice!"
```

Function names follow the same rules as variable names but without the `$` prefix. They are case-insensitive (though consistent casing should be used), can contain letters, numbers, and underscores, and must start with a letter or underscore.

**Conditional Function Definitions**

Functions can be defined conditionally, though this pattern is unusual and can harm readability:

```php
if (!function_exists('array_key_first')) {
    function array_key_first(array $array): mixed
    {
        foreach ($array as $key => $unused) {
            return $key;
        }
        return null;
    }
}
```

This polyfill pattern provides backward compatibility for functions introduced in newer PHP versions. The `function_exists()` check prevents redeclaration errors.

**Functions Within Functions**

PHP allows nested function declarations, but the inner function only becomes available after the outer function executes:

```php
function outer(): void
{
    function inner(): void
    {
        echo "Inner function called\n";
    }
    echo "Outer function called\n";
}

outer(); // "Outer function called"
inner(); // "Inner function called" - available now

// inner() would cause error if called before outer()
```

This pattern has limited practical use and can create unexpected behavior. Most developers should avoid it in favor of classes or closures.

**Returning Values**

Functions return values using the `return` statement. If no `return` is executed, the function returns `null`:

```php
function mayReturnNull(bool $condition): ?string
{
    if ($condition) {
        return 'Something';
    }
    // Implicitly returns null
}

// void functions must not return anything
function logMessage(string $message): void
{
    echo $message . "\n";
    // No return statement
}
```

Multiple return values can be simulated with arrays or objects:

```php
function getMinMax(array $numbers): array
{
    return ['min' => min($numbers), 'max' => max($numbers)];
}

['min' => $min, 'max' => $max] = getMinMax([3, 1, 4, 1, 5, 9]);

// Or using a value object
readonly class MinMaxResult
{
    public function __construct(
        public int $min,
        public int $max,
    ) {}
}

function getMinMaxObject(array $numbers): MinMaxResult
{
    return new MinMaxResult(min($numbers), max($numbers));
}
```

#### 4.2 Parameters: Positional, Named (PHP 8), Default, and Variadic

**Positional Parameters**

The traditional parameter passing method requires arguments in the exact order of the function definition:

```php
function createUser(string $name, string $email, int $age): User
{
    return new User($name, $email, $age);
}

// Arguments must match parameter order
createUser('Alice', 'alice@example.com', 30);
```

**Default Parameters**

Parameters can specify default values, making them optional at call sites:

```php
function generatePassword(int $length = 12, bool $includeSymbols = true): string
{
    $chars = 'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789';
    if ($includeSymbols) {
        $chars .= '!@#$%^&*()_+-=[]{}|;:,.<>?';
    }
    
    $password = '';
    for ($i = 0; $i < $length; $i++) {
        $password .= $chars[random_int(0, strlen($chars) - 1)];
    }
    return $password;
}

$pass1 = generatePassword();           // 12 chars, with symbols
$pass2 = generatePassword(16);         // 16 chars, with symbols
$pass3 = generatePassword(8, false);   // 8 chars, no symbols
```

Default values must be constant expressions (literals, constants, arrays). They cannot be function calls except in limited cases with `new` in PHP 8.1+:

```php
// Invalid
function setTimer(int $duration = time()): void {} // Error

// Valid (PHP 8.1+)
function createLogger(?LoggerInterface $logger = new NullLogger()): LoggerInterface
{
    return $logger;
}
```

**Named Arguments (PHP 8.0+)**

Named arguments allow passing values by parameter name, enabling skipping optional parameters and improving readability:

```php
function sendEmail(
    string $to,
    string $subject,
    string $body,
    ?string $cc = null,
    ?string $bcc = null,
    bool $isHtml = false,
    int $priority = 0,
): void {
    // Implementation
}

// With named arguments: clear and order-independent
sendEmail(
    to: 'user@example.com',
    subject: 'Welcome!',
    body: '<h1>Welcome</h1>',
    isHtml: true,
    priority: 1,
);

// Mixing positional and named (positional must come first)
sendEmail(
    'user@example.com',
    'Welcome!',
    'Welcome to the platform',
    isHtml: true,
);
```

Named arguments significantly improve code readability for functions with many optional parameters. They also enable library authors to add new optional parameters without breaking existing calls.

**Variadic Parameters**

Variadic parameters accept a variable number of arguments, collected into an array:

```php
function sum(int ...$numbers): int
{
    return array_sum($numbers);
}

sum(1, 2, 3, 4, 5); // 15
sum();               // 0

// Combining with other parameters
function logWithContext(string $level, string $message, mixed ...$context): void
{
    $contextStr = json_encode($context);
    echo "[{$level}] {$message} {$contextStr}\n";
}

logWithContext('error', 'Database connection failed', 
    'host' => 'db.example.com',
    'error' => 'Connection refused'
);
```

The spread operator unpacks arrays into argument lists:

```php
$numbers = [1, 2, 3, 4, 5];
sum(...$numbers); // Equivalent to sum(1, 2, 3, 4, 5)

$params = [
    'to' => 'user@example.com',
    'subject' => 'Test',
    'body' => 'Testing',
];
sendEmail(...$params); // Spreads associative array as named arguments
```

#### 4.3 Return Types and Multiple Return Values

**Return Type Declarations**

Return types ensure functions return the expected type, catching mismatches during development:

```php
function divide(int $a, int $b): float
{
    return $a / $b; // Automatically returns float
}

function findUser(int $id): ?User // Nullable return type
{
    return User::find($id); // Returns User or null
}

function getStatus(): string|int // Union return type
{
    if (rand(0, 1)) {
        return 'active';
    }
    return 200;
}
```

**Void and Never Return Types**

`void` indicates a function that performs an action without returning a meaningful value:

```php
function redirect(string $url): void
{
    header("Location: {$url}");
    exit();
}
```

`never` (PHP 8.1+) declares that the function never returns normally—it either throws an exception or terminates the script:

```php
function abort(int $code, string $message = ''): never
{
    http_response_code($code);
    echo $message ?: getStatusMessage($code);
    exit();
}

function throwNotFoundException(string $entity, int $id): never
{
    throw new NotFoundException("{$entity} with id {$id} not found");
}
```

**Static Return Type**

The `static` return type (PHP 8.0+) preserves the called class in inheritance chains:

```php
class Model
{
    public static function find(int $id): static
    {
        // Returns instance of the called class, not necessarily Model
        return new static(['id' => $id]);
    }
}

class User extends Model
{
    public function posts(): array
    {
        return Post::findByUser($this->id);
    }
}

// Type is User, not Model
$user = User::find(1);
$user->posts(); // Available because static returns User
```

**Multiple Return Values**

PHP functions return a single value, but arrays and objects simulate multiple returns:

```php
// Using array destructuring
function getUserData(int $id): array
{
    $user = getUserFromDatabase($id);
    return [
        'name' => $user->name,
        'email' => $user->email,
        'registeredAt' => $user->created_at,
    ];
}

['name' => $name, 'email' => $email] = getUserData(1);

// Using value objects for type safety
readonly class Coordinates
{
    public function __construct(
        public float $latitude,
        public float $longitude,
    ) {}
}

function geocode(string $address): Coordinates
{
    // ... geocoding logic ...
    return new Coordinates(37.7749, -122.4194);
}

$coords = geocode('San Francisco');
echo $coords->latitude; // 37.7749
```

Value objects provide type safety and autocompletion benefits that arrays cannot match.

#### 4.4 Variable Scope, Global Variables, and Static Variables

**Function Scope**

Functions create their own variable scope. Variables defined inside a function are not accessible outside, and variables defined outside are not accessible inside unless explicitly imported:

```php
$external = 'outside';

function test(): void
{
    $internal = 'inside';
    echo $internal; // Works
    
    // echo $external; // Warning: Undefined variable
    global $external; // Import global variable
    echo $external; // Works: 'outside'
}

test();
// echo $internal; // Warning: Undefined variable
```

**Global Variables**

The `global` keyword imports a global variable into function scope:

```php
$config = ['debug' => true, 'cache' => false];

function isDebugEnabled(): bool
{
    global $config;
    return $config['debug'] ?? false;
}
```

The `$GLOBALS` superglobal array provides an alternative:

```php
function setDebug(bool $value): void
{
    $GLOBALS['config']['debug'] = $value;
}
```

Global variables are generally discouraged in favor of dependency injection and configuration objects. They make code difficult to test, reason about, and refactor.

**Static Variables**

Static variables retain their value between function calls:

```php
function getNextId(): int
{
    static $counter = 0;
    return ++$counter;
}

echo getNextId(); // 1
echo getNextId(); // 2
echo getNextId(); // 3
```

Static variables are useful for caching expensive computations:

```php
function getExpensiveData(int $id): array
{
    static $cache = [];
    
    if (!isset($cache[$id])) {
        $cache[$id] = fetchFromDatabase($id);
    }
    
    return $cache[$id];
}
```

The cache persists across calls within the same request but resets on each new request. For cross-request caching, use APCu, Redis, or file-based caching.

**Closures and the `use` Keyword**

Closures (anonymous functions) capture variables from their parent scope using the `use` keyword:

```php
function createMultiplier(int $factor): Closure
{
    return function (int $number) use ($factor): int {
        return $number * $factor;
    };
}

$doubler = createMultiplier(2);
$tripler = createMultiplier(3);

echo $doubler(5); // 10
echo $tripler(5); // 15
```

Variables captured by `use` are copied by default. To modify the original variable, pass it by reference:

```php
$total = 0;

$addToTotal = function (int $amount) use (&$total): void {
    $total += $amount;
};

$addToTotal(10);
$addToTotal(25);
echo $total; // 35
```

#### 4.5 Anonymous Functions, Closures, and the `use` Keyword

**Anonymous Functions**

Anonymous functions (lambdas) are functions without a name, useful for callbacks and short-lived logic:

```php
// As a callback
$sorted = array_filter($numbers, function (int $number): bool {
    return $number % 2 === 0;
});

// Assigned to a variable
$greet = function (string $name): string {
    return "Hello, {$name}!";
};
echo $greet('Alice');

// Immediately invoked
$result = (function (int $x, int $y): int {
    return $x + $y;
})(5, 10); // $result is 15
```

**Closures and Variable Capture**

Closures are anonymous functions that capture variables from their enclosing scope. Without `use`, closures cannot access variables from the parent scope:

```php
$multiplier = 10;

// Error: $multiplier is not defined in closure scope
$bad = function (int $x): int {
    return $x * $multiplier; // Undefined variable
};

// Correct: capture $multiplier
$good = function (int $x) use ($multiplier): int {
    return $x * $multiplier;
};
```

**Capture by Value vs. Reference**

Variables captured with `use` are captured by value at the time the closure is defined, not when it's executed:

```php
$count = 0;

$increment = function () use ($count): int {
    $count++;
    return $count;
};

echo $increment(); // 1
echo $increment(); // 2 (closure's $count is independent)
echo $count;       // 0 (original unchanged)
```

Capture by reference keeps the variables linked:

```php
$count = 0;

$increment = function () use (&$count): int {
    $count++;
    return $count;
};

echo $increment(); // 1
echo $count;       // 1 (original modified)
```

**Binding Closures to Objects**

The `Closure::bind()` and `Closure::bindTo()` methods allow closures to access private and protected members of objects:

```php
class BankAccount
{
    private float $balance;
    
    public function __construct(float $initialBalance)
    {
        $this->balance = $initialBalance;
    }
}

$account = new BankAccount(1000);

// Access private property through bound closure
$getBalance = function (): float {
    return $this->balance;
};

$boundGetBalance = $getBalance->bindTo($account, BankAccount::class);
echo $boundGetBalance(); // 1000

// One-step binding
$readBalance = \Closure::bind(
    function (): float { return $this->balance; },
    $account,
    BankAccount::class
);
echo $readBalance(); // 1000
```

This technique is powerful for testing and metaprogramming but should be used judiciously, as it breaks encapsulation.

**Callable Type Hints**

Functions, closures, object methods, and static methods can all be used as callables:

```php
function executeWithLogging(callable $operation, string $operationName): mixed
{
    $start = microtime(true);
    $result = $operation();
    $duration = microtime(true) - $start;
    
    logOperation($operationName, $duration);
    
    return $result;
}

// With closure
$result = executeWithLogging(
    fn() => fetchUsers(),
    'fetch_users'
);

// With object method
$result = executeWithLogging(
    [$userService, 'findAll'],
    'find_all_users'
);

// With static method
$result = executeWithLogging(
    [UserService::class, 'findAll'],
    'user_service_find_all'
);
```

#### 4.6 Arrow Functions (fn) and First-Class Callable Syntax

**Arrow Functions (PHP 7.4+)**

Arrow functions provide a concise syntax for simple closures that return a single expression:

```php
// Traditional closure
$doubled = array_map(function (int $n): int {
    return $n * 2;
}, $numbers);

// Arrow function
$doubled = array_map(fn(int $n): int => $n * 2, $numbers);

// Arrow functions with multiple parameters
$sums = array_map(
    fn(int $x, int $y): int => $x + $y,
    $array1,
    $array2
);
```

Arrow functions capture variables from the parent scope automatically by value, without requiring `use`:

```php
$multiplier = 10;
$factor = 2;

// Variables are captured automatically
$calculate = fn(int $x): int => $x * $multiplier + $factor;

echo $calculate(5); // 52
```

Arrow functions have limitations: they can only contain a single expression (no statements), cannot modify captured variables, and cannot be bound to objects with `bindTo()`. They excel as concise callbacks for mapping, filtering, and reducing operations.

**First-Class Callable Syntax (PHP 8.1+)**

The first-class callable syntax provides a cleaner way to create closures from existing functions and methods:

```php
// Traditional syntax
$uppercase = function (string $s): string {
    return strtoupper($s);
};

// First-class callable syntax
$uppercase = strtoupper(...);

// Works with namespaced functions
$encode = json_encode(...);

// Works with object methods
$calculate = $calculator->add(...);

// Works with static methods
$parse = DateTimeImmutable::createFromFormat(...);
```

The `...` syntax creates a closure that forwards all arguments to the specified callable:

```php
$strings = ['hello', 'world'];
$uppercased = array_map(strtoupper(...), $strings);
// Equivalent to: array_map(fn($s) => strtoupper($s), $strings)
```

First-class callable syntax is particularly useful with higher-order functions that accept callbacks:

```php
// Define a pipeline of transformations
$pipeline = [
    trim(...),
    strtolower(...),
    fn(string $s): string => preg_replace('/\s+/', '-', $s),
];

$result = array_reduce(
    $pipeline,
    fn(string $carry, callable $fn): string => $fn($carry),
    '  Hello World  '
);
// $result is 'hello-world'
```

#### 4.7 Recursion and Memoization

**Recursion**

Recursive functions call themselves to solve problems that can be broken into smaller, similar sub-problems:

```php
function factorial(int $n): int
{
    if ($n < 0) {
        throw new InvalidArgumentException('Negative numbers not allowed');
    }
    
    // Base case
    if ($n <= 1) {
        return 1;
    }
    
    // Recursive case
    return $n * factorial($n - 1);
}

echo factorial(5); // 120
```

Tree traversal naturally suits recursion:

```php
class TreeNode
{
    public function __construct(
        public readonly string $value,
        public readonly array $children = [],
    ) {}
}

function traverseTree(TreeNode $node, int $depth = 0): void
{
    echo str_repeat('  ', $depth) . $node->value . "\n";
    
    foreach ($node->children as $child) {
        traverseTree($child, $depth + 1);
    }
}
```

**Tail Recursion**

Tail recursion occurs when the recursive call is the last operation in the function. PHP does not optimize tail recursion (unlike some functional languages), so deep recursion can exhaust the call stack:

```php
// This will cause a stack overflow for large $n
function sumTo(int $n): int
{
    if ($n <= 0) return 0;
    return $n + sumTo($n - 1); // Not tail-recursive: addition happens after call
}

// Tail-recursive version (still limited in PHP)
function sumToTail(int $n, int $accumulator = 0): int
{
    if ($n <= 0) return $accumulator;
    return sumToTail($n - 1, $accumulator + $n); // Tail call
}
```

For deep recursion in PHP, convert to iteration:

```php
function sumToIterative(int $n): int
{
    $sum = 0;
    for ($i = 1; $i <= $n; $i++) {
        $sum += $i;
    }
    return $sum;
}
```

**Memoization**

Memoization caches function results for repeated inputs, trading memory for speed:

```php
function fibonacci(int $n): int
{
    static $cache = [];
    
    if ($n < 0) {
        throw new InvalidArgumentException('Negative numbers not allowed');
    }
    
    if ($n <= 1) {
        return $n;
    }
    
    if (!isset($cache[$n])) {
        $cache[$n] = fibonacci($n - 1) + $n - 2;
    }
    
    return $cache[$n];
}

echo fibonacci(50); // Near-instant despite recursive algorithm
```

Generic memoization wrapper for closures:

```php
function memoize(callable $fn): callable
{
    return function (mixed ...$args) use ($fn): mixed {
        static $cache = [];
        
        $key = serialize($args);
        
        if (!array_key_exists($key, $cache)) {
            $cache[$key] = $fn(...$args);
        }
        
        return $cache[$key];
    };
}

$slowFunction = function (int $n): int {
    // Simulate expensive computation
    usleep(100000);
    return $n * $n;
};

$fastFunction = memoize($slowFunction);

echo $fastFunction(42); // Slow
echo $fastFunction(42); // Instant (cached)
echo $fastFunction(100); // Slow (new input)
```

---

### Chapter 5: Arrays and Strings

#### 5.1 Indexed, Associative, and Multidimensional Arrays

Arrays are PHP's most versatile data structure, functioning as lists, dictionaries, stacks, queues, and more.

**Indexed Arrays**

Indexed arrays use sequential integer keys starting from 0:

```php
$fruits = ['apple', 'banana', 'cherry'];
// Equivalent to:
$fruits = [0 => 'apple', 1 => 'banana', 2 => 'cherry'];

// Appending elements
$fruits[] = 'date';  // Automatically gets key 3
array_push($fruits, 'elderberry', 'fig');
```

Array keys are automatically assigned incrementally. Removing elements doesn't reindex the array, which can create gaps:

```php
unset($fruits[1]); // Removes 'banana'
// $fruits is now [0 => 'apple', 2 => 'cherry', 3 => 'date']

// Reindex with array_values
$fruits = array_values($fruits); // [0 => 'apple', 1 => 'cherry', 2 => 'date']
```

**Associative Arrays**

Associative arrays use string or mixed keys:

```php
$user = [
    'name' => 'Alice Johnson',
    'email' => 'alice@example.com',
    'age' => 30,
    'preferences' => [
        'theme' => 'dark',
        'notifications' => true,
    ],
];

// Accessing values
echo $user['name']; // 'Alice Johnson'

// Adding/updating values
$user['phone'] = '+1-555-0100';
$user['age'] = 31;
```

String keys are case-sensitive. Numeric strings used as keys are automatically converted to integers:

```php
$array = ['1' => 'one', 1 => 'also one'];
// Only one element remains with key 1 and value 'also one'
```

**Multidimensional Arrays**

Arrays can contain other arrays to arbitrary depth:

```php
$matrix = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9],
];

echo $matrix[1][2]; // 6

$users = [
    [
        'name' => 'Alice',
        'roles' => ['admin', 'editor'],
    ],
    [
        'name' => 'Bob',
        'roles' => ['viewer'],
    ],
];

echo $users[0]['roles'][1]; // 'editor'
```

**Array Access with Bracket Notation**

PHP 7.1+ supports array destructuring for extracting values:

```php
// Indexed destructuring
[$first, $second, $third] = $fruits;

// Skipping elements
[, , $third] = $fruits;

// Nested destructuring with keys
[0 => ['name' => $firstName], 1 => ['name' => $secondName]] = $users;
```

**Arrays as Stacks and Queues**

Arrays can function as stacks (LIFO) with `array_push()` and `array_pop()`:

```php
$stack = [];
array_push($stack, 'a', 'b', 'c');
$top = array_pop($stack); // 'c', $stack is ['a', 'b']
```

Queues (FIFO) use `array_push()` with `array_shift()`:

```php
$queue = [];
array_push($queue, 'first', 'second');
$first = array_shift($queue); // 'first', $queue is ['second']
```

For large queues, `array_shift()` is O(n) because it reindexes the array. Consider using `SplQueue` or a deque implementation for performance-sensitive queue operations.

#### 5.2 Array Manipulation: Sorting, Filtering, Mapping, and Reducing

**Mapping**

`array_map()` transforms each element through a callback:

```php
$numbers = [1, 2, 3, 4, 5];

$squared = array_map(fn(int $n): int => $n * $n, $numbers);
// [1, 4, 9, 16, 25]

// Multiple arrays
$firstNames = ['Alice', 'Bob', 'Charlie'];
$lastNames = ['Smith', 'Jones', 'Brown'];

$fullNames = array_map(
    fn(string $first, string $last): string => "{$first} {$last}",
    $firstNames,
    $lastNames
);
// ['Alice Smith', 'Bob Jones', 'Charlie Brown']

// Preserving keys
$associative = ['a' => 1, 'b' => 2, 'c' => 3];
$doubled = array_map(fn(int $n): int => $n * 2, $associative);
// ['a' => 2, 'b' => 4, 'c' => 6]
```

**Filtering**

`array_filter()` returns elements that pass a truth test:

```php
$numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

$even = array_filter($numbers, fn(int $n): bool => $n % 2 === 0);
// [1 => 2, 3 => 4, 5 => 6, 7 => 8, 9 => 10] - original keys preserved

$positive = array_filter($numbers); // Without callback, removes falsy values
```

Filtering with value and key:

```php
$users = [
    'admin' => ['name' => 'Alice', 'active' => true],
    'editor' => ['name' => 'Bob', 'active' => false],
    'viewer' => ['name' => 'Charlie', 'active' => true],
];

$activeUsers = array_filter(
    $users,
    fn(array $user, string $role): bool => $user['active'] && $role !== 'viewer',
    ARRAY_FILTER_USE_BOTH
);
```

**Reducing**

`array_reduce()` collapses an array into a single value:

```php
$numbers = [1, 2, 3, 4, 5];

$sum = array_reduce(
    $numbers,
    fn(int $carry, int $number): int => $carry + $number,
    0
); // 15

$product = array_reduce(
    $numbers,
    fn(int $carry, int $number): int => $carry * $number,
    1
); // 120

// Building complex structures
$frequency = array_reduce(
    ['apple', 'banana', 'apple', 'cherry', 'banana', 'apple'],
    fn(array $counts, string $fruit): array => [...$counts, $fruit => ($counts[$fruit] ?? 0) + 1],
    []
);
// ['apple' => 3, 'banana' => 2, 'cherry' => 1]
```

**Sorting**

PHP provides numerous sorting functions with different behaviors:

```php
$fruits = ['banana', 'apple', 'cherry', 'date'];

// Sort by value, reindexed
sort($fruits); // ['apple', 'banana', 'cherry', 'date']

// Sort by value, preserve keys
asort($fruits);

// Sort by key
ksort($fruits);

// Reverse sorting
rsort($fruits); // Reverse sort by value, reindexed
arsort($fruits); // Reverse sort by value, preserve keys
krsort($fruits); // Reverse sort by key

// User-defined sorting
usort($users, fn(array $a, array $b): int => $a['age'] <=> $b['age']);
```

**Array Utility Functions**

```php
// Searching
$key = array_search('apple', $fruits); // Returns key or false
$exists = in_array('apple', $fruits); // true or false
$filtered = array_unique([1, 2, 2, 3, 1]); // [1, 2, 3]

// Merging
$merged = array_merge([1, 2], [3, 4]); // [1, 2, 3, 4]
$replaced = array_replace(
    ['color' => 'blue', 'size' => 'M'],
    ['color' => 'red']
); // ['color' => 'red', 'size' => 'M']

// Slicing and combining
$slice = array_slice([1, 2, 3, 4, 5], 1, 3); // [2, 3, 4]
$combined = array_combine(['a', 'b'], [1, 2]); // ['a' => 1, 'b' => 2]

// Column extraction
$names = array_column($users, 'name');
$byRole = array_column($users, null, 'id');

// Diff and intersect
$diff = array_diff([1, 2, 3], [2, 3, 4]); // [1]
$intersect = array_intersect([1, 2, 3], [2, 3, 4]); // [2, 3]
```

#### 5.3 Spread Operator and Array Destructuring

**Spread Operator (PHP 7.4+)**

The spread operator unpacks arrays within array expressions:

```php
$defaults = ['theme' => 'light', 'language' => 'en'];
$userSettings = ['theme' => 'dark', 'fontSize' => 14];

$settings = [...$defaults, ...$userSettings];
// ['theme' => 'dark', 'language' => 'en', 'fontSize' => 14]
// Later spreads overwrite earlier ones

// Combining multiple arrays
$part1 = [1, 2];
$part2 = [3, 4];
$part3 = [5, 6];
$combined = [...$part1, ...$part2, ...$part3]; // [1, 2, 3, 4, 5, 6]

// Using with function return values
$merged = [...getSettings(), ...getOverrides()];
```

The spread operator creates a new array; it does not modify the originals.

**Array Destructuring**

Destructuring extracts array values into variables:

```php
// Simple destructuring
$coordinates = [37.7749, -122.4194];
[$lat, $long] = $coordinates;
echo $lat; // 37.7749

// With keys
$user = ['name' => 'Alice', 'email' => 'alice@example.com', 'age' => 30];
['name' => $name, 'email' => $email] = $user;

// Skipping elements
[,,$third] = [1, 2, 3, 4]; // $third is 3

// Nested destructuring
$data = [
    'user' => ['id' => 1, 'name' => 'Alice'],
    'meta' => ['page' => 1],
];
[
    'user' => ['id' => $userId, 'name' => $userName],
    'meta' => ['page' => $page],
] = $data;

// Destructuring with foreach
$users = [
    ['id' => 1, 'name' => 'Alice', 'email' => 'alice@example.com'],
    ['id' => 2, 'name' => 'Bob', 'email' => 'bob@example.com'],
];

foreach ($users as ['id' => $id, 'name' => $name]) {
    echo "#{$id}: {$name}\n";
}
```

**Value Swapping**

Destructuring enables elegant value swapping without temporary variables:

```php
$a = 10;
$b = 20;
[$a, $b] = [$b, $a];
echo "a={$a}, b={$b}"; // a=20, b=10
```

#### 5.4 String Interpolation, Heredoc, and Nowdoc

**Double-Quoted String Interpolation**

Double-quoted strings parse variables and escape sequences:

```php
$name = 'Alice';
$age = 30;

// Simple variable interpolation
echo "Hello, $name"; // "Hello, Alice"

// Curly brace syntax for complex expressions
echo "Next year, {$name} will be " . ($age + 1); // Method call
echo "The value is: {$object->property}";
echo "Array element: {$array['key']}";
echo "First character: {$name[0]}";
```

Escape sequences in double-quoted strings:

```php
echo "Line 1\nLine 2";
echo "Tab\tseparated";
echo "Quote: \"text\"";
echo "Dollar sign: \$name";
echo "Backslash: \\";
```

**Single-Quoted Strings**

Single-quoted strings perform minimal parsing—only `\\` and `\'` are recognized:

```php
echo 'Hello, $name'; // Literally: Hello, $name
echo 'It\'s a beautiful day'; // Escaped single quote
echo 'C:\\Windows\\System32'; // Escaped backslash
```

Single-quoted strings are slightly faster when no interpolation is needed, though the difference is negligible in most applications.

**Heredoc Syntax**

Heredoc provides multi-line strings with interpolation:

```php
$name = 'Alice';
$count = 42;

$text = <<<EOT
Hello, {$name}!

You have {$count} new messages.

Thank you,
The Team
EOT;

// Flexible indentation (PHP 7.3+)
function getEmail(): string
{
    $user = 'Bob';
    
    return <<<HTML
        <div class="email">
            <h1>Welcome, {$user}!</h1>
            <p>Thank you for registering.</p>
        </div>
        HTML;
}
```

The closing marker must appear at the beginning of a line, though it can be preceded by spaces or tabs (not other characters) in PHP 7.3+.

**Nowdoc Syntax**

Nowdoc provides multi-line strings without interpolation, similar to single-quoted strings:

```php
$code = <<<'CODE'
    function example(): void {
        echo "This is not parsed\n";
        $variable = 'not interpolated';
    }
CODE;
```

Nowdoc is ideal for embedding code examples, SQL queries with dollar signs, or any text containing characters that would be interpreted in heredoc.

#### 5.5 Multibyte Strings and UTF-8 Handling

PHP's native string functions operate on bytes, not characters. This works correctly for single-byte encodings like ASCII but fails for multibyte encodings like UTF-8.

**The Problem with Byte-Only Functions**

```php
$japanese = '日本語'; // 3 characters, 9 bytes in UTF-8

strlen($japanese);           // 9 (bytes, not characters)
mb_strlen($japanese);        // 3 (characters)

substr($japanese, 0, 1);     // Broken: returns partial character
mb_substr($japanese, 0, 1);  // '日' (correct)
```

Functions like `strlen()`, `substr()`, `strpos()`, and `strtoupper()` must be replaced with their `mb_*` equivalents when working with multibyte strings.

**Essential MBString Functions**

```php
$text = 'Café résumé';

// Length
mb_strlen($text); // 12 characters

// Position
mb_strpos($text, 'é'); // 3 (first occurrence)
mb_strrpos($text, 'é'); // 11 (last occurrence)

// Substring
mb_substr($text, 0, 3); // 'Caf'

// Case conversion
mb_strtoupper($text);  // 'CAFÉ RÉSUMÉ'
mb_strtolower($text);  // 'café résumé'
mb_convert_case($text, MB_CASE_TITLE); // 'Café Résumé'

// Splitting
mb_str_split($text); // ['C', 'a', 'f', 'é', ' ', 'r', 'é', 's', 'u', 'm', 'é']
```

**Character Encoding Configuration**

Set the internal encoding for all `mb_*` functions:

```php
mb_internal_encoding('UTF-8');
mb_http_output('UTF-8');
mb_regex_encoding('UTF-8');
```

Or configure in `php.ini`:

```ini
mbstring.internal_encoding = UTF-8
mbstring.http_output = UTF-8
mbstring.language = Neutral
```

**Unicode Normalization**

Different byte sequences can represent the same character in Unicode (composed vs. decomposed forms). The Normalizer class ensures consistent representation:

```php
$normalizer = new Normalizer();

$composed = 'é'; // U+00E9 (single code point)
$decomposed = 'é'; // U+0065 + U+0301 (e + combining accent)

$composed === $decomposed; // false (different byte sequences)

Normalizer::normalize($composed) === Normalizer::normalize($decomposed); // true
// Default normalization is NFC (Normalization Form Composed)
```

Normalization is essential before string comparison, search, and storage to prevent duplicate entries and failed lookups.

**Encoding Detection and Conversion**

```php
// Detect encoding
$encoding = mb_detect_encoding($text, ['UTF-8', 'ISO-8859-1', 'Windows-1252']);

// Convert between encodings
$utf8text = mb_convert_encoding($latin1text, 'UTF-8', 'ISO-8859-1');

// Alternative using iconv
$utf8text = iconv('ISO-8859-1', 'UTF-8', $latin1text);
```

Always store and process text as UTF-8. Convert from other encodings only at system boundaries (file imports, legacy database reads).

**Grapheme Functions for Display Length**

Some characters are composed of multiple code points but display as a single grapheme:

```php
$emoji = '👨‍👩‍👧‍👦'; // Family emoji: 7 characters, multiple code points

mb_strlen($emoji); // 7 (code points)
grapheme_strlen($emoji); // 1 (visual grapheme)
```

Use `grapheme_*` functions for user-facing operations where display length matters.

#### 5.6 Regular Expressions (PCRE) and Pattern Matching

PHP uses Perl-Compatible Regular Expressions (PCRE) through the `preg_*` functions.

**Pattern Matching**

```php
$pattern = '/\d{3}-\d{2}-\d{4}/'; // Social security number pattern

$ssn = '123-45-6789';
$match = preg_match($pattern, $ssn); // 1 (match found)

// Extracting matches with capture groups
$pattern = '/(\d{3})-(\d{2})-(\d{4})/';
preg_match($pattern, $ssn, $matches);
// $matches = ['123-45-6789', '123', '45', '6789']

// Named capture groups
$pattern = '/(?P<area>\d{3})-(?P<group>\d{2})-(?P<serial>\d{4})/';
preg_match($pattern, $ssn, $matches);
echo $matches['area']; // '123'
```

**Finding All Matches**

```php
$text = 'Contact alice@example.com or bob@example.org for details.';
$pattern = '/[\w.-]+@[\w.-]+\.\w+/';

preg_match_all($pattern, $text, $emails);
// $emails[0] = ['alice@example.com', 'bob@example.org']
```

**Search and Replace**

```php
// Simple replacement
$text = 'The quick brown fox jumps over the lazy dog';
$result = preg_replace('/quick|lazy/', '***', $text);
// 'The *** brown fox jumps over the *** dog'

// Using capture groups in replacement
$date = '2023-12-25';
$reformatted = preg_replace('/(\d{4})-(\d{2})-(\d{2})/', '$2/$3/$1', $date);
// '12/25/2023'

// Callback replacement
$text = 'Temperature: 25°C, Distance: 100km';
$converted = preg_replace_callback(
    '/(\d+)°C/',
    fn(array $matches): string => round($matches[1] * 9/5 + 32) . '°F',
    $text
);
// 'Temperature: 77°F, Distance: 100km'
```

**Pattern Modifiers**

Common modifiers appended after the closing delimiter:

```php
'/pattern/i'   // Case-insensitive
'/pattern/m'   // Multiline: ^ and $ match line boundaries
'/pattern/s'   // Dot matches newlines
'/pattern/u'   // UTF-8 mode (always use for multibyte strings)
'/pattern/x'   // Extended: ignore whitespace and allow comments
'/pattern/U'   // Ungreedy: quantifiers are lazy by default
```

Combining modifiers:

```php
$pattern = '/<div\b[^>]*>(.*?)<\/div>/siu';
// s: dot matches newlines (div content may span lines)
// i: case-insensitive (<div>, <DIV>)
// u: UTF-8 encoding
```

**Common Patterns**

```php
// Email validation
$emailPattern = '/^[\w.%+-]+@[\w.-]+\.[a-zA-Z]{2,}$/';

// URL validation
$urlPattern = '~^(https?|ftp)://[^\s/$.?#].[^\s]*$~i';

// Extract query parameters
$url = 'https://example.com/page?name=John&age=30';
parse_str(parse_url($url, PHP_URL_QUERY), $params);
// $params = ['name' => 'John', 'age' => '30']

// Phone number (US format)
$phonePattern = '/^\(?\d{3}\)?[-.\s]?\d{3}[-.\s]?\d{4}$/';

// IPv4 address
$ipPattern = '/^(?:(?:25[0-5]|2[0-4]\d|[01]?\d\d?)\.){3}(?:25[0-5]|2[0-4]\d|[01]?\d\d?)$/';
```

**Splitting Strings**

```php
$csv = 'apple,banana,"cherry, with comma",date';
$fields = preg_split('/,(?=(?:[^"]*"[^"]*")*[^"]*$)/', $csv);
// Better: use str_getcsv for actual CSV parsing
$fields = str_getcsv($csv);
```

**Performance Considerations**

Regular expressions are powerful but can be expensive. Cache compiled patterns when used repeatedly:

```php
// PHP automatically caches compiled regex internally, but complex patterns
// or large inputs still require care

// Use str_contains() instead of preg_match for simple substring checks
if (str_contains($text, 'needle')) { /* ... */ }

// Use str_starts_with() and str_ends_with() for prefix/suffix checks
if (str_starts_with($url, 'https://')) { /* ... */ }
```

---

### Chapter 6: File Handling and Streams

#### 6.1 Reading, Writing, and Appending Files

PHP provides multiple approaches to file operations, from simple functions to streaming interfaces.

**Simple File Operations**

```php
// Reading entire file
$content = file_get_contents('/path/to/file.txt');
$lines = file('/path/to/file.txt', FILE_IGNORE_NEW_LINES | FILE_SKIP_EMPTY_LINES);

// Writing entire file (overwrites)
file_put_contents('/path/to/file.txt', 'New content', LOCK_EX);

// Appending
file_put_contents('/path/to/file.txt', "New line\n", FILE_APPEND | LOCK_EX);
```

These functions are convenient for small to medium files but load the entire file into memory, which can be problematic for large files.

**Streaming File Operations**

Stream-based access processes files incrementally with lower memory overhead:

```php
// Reading with a file handle
$handle = fopen('/path/to/large-file.csv', 'r');

if ($handle === false) {
    throw new RuntimeException('Could not open file');
}

while (($line = fgets($handle)) !== false) {
    // Process each line
    processCsvRow(str_getcsv($line));
}

fclose($handle);

// Writing with a file handle
$handle = fopen('/path/to/output.txt', 'w');
fwrite($handle, "First line\n");
fwrite($handle, "Second line\n");
fclose($handle);

// Binary-safe reading of exact bytes
$handle = fopen('binary.dat', 'rb');
$header = fread($handle, 16); // Read exactly 16 bytes
$remaining = stream_get_contents($handle); // Read the rest
fclose($handle);
```

**File Modes**

The file open mode determines the operation and behavior:

| Mode | Description |
|------|-------------|
| `'r'` | Read only, pointer at beginning |
| `'r+'` | Read and write, pointer at beginning |
| `'w'` | Write only, truncate or create |
| `'w+'` | Read and write, truncate or create |
| `'a'` | Write only, pointer at end, create if needed |
| `'a+'` | Read and write, pointer at end, create if needed |
| `'x'` | Write only, create new file, fail if exists |
| `'x+'` | Read and write, create new file, fail if exists |

Add `'b'` for binary mode (recommended for portability across platforms):

```php
$handle = fopen('file.bin', 'rb'); // Binary read
$handle = fopen('file.txt', 'wb'); // Binary write
```

**File Locking**

Locking prevents race conditions when multiple processes access the same file:

```php
$handle = fopen('counter.txt', 'c+');

if (flock($handle, LOCK_EX)) { // Exclusive lock
    $count = (int) fgets($handle);
    $count++;
    rewind($handle);
    ftruncate($handle, 0);
    fwrite($handle, (string) $count);
    fflush($handle);
    flock($handle, LOCK_UN); // Release lock
}

fclose($handle);
```

Lock types: `LOCK_SH` (shared/read), `LOCK_EX` (exclusive/write), `LOCK_UN` (unlock), `LOCK_NB` (non-blocking, combined with SH or EX).

**File Pointers and Seeking**

```php
$handle = fopen('data.txt', 'r');

// Get current position
$position = ftell($handle);

// Move to specific position
fseek($handle, 100, SEEK_SET); // From beginning
fseek($handle, 50, SEEK_CUR);  // From current
fseek($handle, -20, SEEK_END); // From end

// Reset to beginning
rewind($handle);

// Read by chunks
$chunk = fread($handle, 4096);
```

#### 6.2 File Uploads and MIME Type Validation

**Handling Uploaded Files**

File uploads arrive through the `$_FILES` superglobal:

```php
// HTML form
// <form method="post" enctype="multipart/form-data">
//     <input type="file" name="avatar">
// </form>

// PHP handling
$upload = $_FILES['avatar'];

if ($upload['error'] !== UPLOAD_ERR_OK) {
    throw new UploadException(
        match ($upload['error']) {
            UPLOAD_ERR_INI_SIZE => 'File exceeds upload_max_filesize',
            UPLOAD_ERR_FORM_SIZE => 'File exceeds MAX_FILE_SIZE',
            UPLOAD_ERR_PARTIAL => 'File was only partially uploaded',
            UPLOAD_ERR_NO_FILE => 'No file was uploaded',
            UPLOAD_ERR_NO_TMP_DIR => 'Missing temporary folder',
            UPLOAD_ERR_CANT_WRITE => 'Failed to write file to disk',
            default => 'Unknown upload error',
        }
    );
}
```

**Secure Upload Handling**

```php
class FileUploadHandler
{
    private const ALLOWED_TYPES = [
        'image/jpeg' => 'jpg',
        'image/png' => 'png',
        'image/gif' => 'gif',
        'image/webp' => 'webp',
    ];
    
    private const MAX_FILE_SIZE = 5 * 1024 * 1024; // 5MB
    
    public function handle(array $upload, string $destinationDir): string
    {
        // Validate upload
        if ($upload['error'] !== UPLOAD_ERR_OK) {
            throw new UploadException('Upload failed');
        }
        
        // Validate size
        if ($upload['size'] > self::MAX_FILE_SIZE) {
            throw new UploadException('File too large');
        }
        
        // Validate MIME type using fileinfo (not client-supplied)
        $finfo = new finfo(FILEINFO_MIME_TYPE);
        $mimeType = $finfo->file($upload['tmp_name']);
        
        if (!isset(self::ALLOWED_TYPES[$mimeType])) {
            throw new UploadException("Invalid file type: {$mimeType}");
        }
        
        // Generate unique filename
        $extension = self::ALLOWED_TYPES[$mimeType];
        $filename = bin2hex(random_bytes(16)) . '.' . $extension;
        $destination = rtrim($destinationDir, '/') . '/' . $filename;
        
        // Ensure directory exists
        if (!is_dir($destinationDir)) {
            mkdir($destinationDir, 0755, true);
        }
        
        // Move uploaded file
        if (!move_uploaded_file($upload['tmp_name'], $destination)) {
            throw new UploadException('Failed to move uploaded file');
        }
        
        return $filename;
    }
}
```

Important security practices: never trust the client-supplied MIME type (`$upload['type']`); use `finfo` for server-side detection. Always store uploaded files outside the web root or with proper access controls. Validate file contents, not just extensions.

#### 6.3 Working with Directories and File Information

**Directory Operations**

```php
// Create directory
mkdir('/path/to/new/dir', 0755, true); // Recursive creation

// Remove directory (must be empty)
rmdir('/path/to/empty/dir');

// Scan directory contents
$files = scandir('/path/to/dir'); // Includes '.' and '..'
$files = array_diff(scandir('/path/to/dir'), ['.', '..']);

// Iterate with DirectoryIterator
$iterator = new DirectoryIterator('/path/to/dir');
foreach ($iterator as $item) {
    if ($item->isDot()) continue;
    
    if ($item->isFile()) {
        echo "File: {$item->getFilename()} ({$item->getSize()} bytes)\n";
    } elseif ($item->isDir()) {
        echo "Directory: {$item->getFilename()}\n";
    }
}

// Recursive iteration
$iterator = new RecursiveIteratorIterator(
    new RecursiveDirectoryIterator('/path/to/dir')
);

foreach ($iterator as $item) {
    echo $item->getPathname() . "\n";
}
```

**File Information**

```php
$path = '/path/to/file.txt';

// File metadata
$size = filesize($path);
$modified = filemtime($path); // Unix timestamp
$accessed = fileatime($path);
$created = filectime($path); // Actually "change time" on Unix
$owner = fileowner($path);
$perms = fileperms($path);  // Permissions as integer

// File type checks
is_file($path);
is_dir($path);
is_link($path);
is_readable($path);
is_writable($path);
is_executable($path);

// Path information
$info = pathinfo('/var/www/images/photo.jpg');
// [
//     'dirname' => '/var/www/images',
//     'basename' => 'photo.jpg',
//     'extension' => 'jpg',
//     'filename' => 'photo',
// ]

$realPath = realpath($path); // Absolute path with symlinks resolved
$basename = basename($path); // 'file.txt'
$dirname = dirname($path);  // '/path/to'
```

**File System Traversal Security**

Always validate and sanitize user-supplied paths to prevent directory traversal attacks:

```php
function getSafeFile(string $userFilename, string $baseDir): ?string
{
    // Resolve the full path
    $fullPath = realpath($baseDir . '/' . $userFilename);
    
    // Verify path is within allowed base directory
    $baseDir = realpath($baseDir);
    
    if ($fullPath === false || !str_starts_with($fullPath, $baseDir)) {
        return null; // Path traversal attempt or nonexistent file
    }
    
    return $fullPath;
}
```

#### 6.4 Streams, Stream Contexts, and Filters

**Stream Concept**

Streams provide a unified interface for reading and writing to various resources: files, network connections, compressed archives, and more. PHP's stream abstraction allows the same functions to work with different backends:

```php
// These all use the same stream functions:
// file:// stream
$content = file_get_contents('/path/to/file.txt');

// http:// stream (with allow_url_fopen enabled)
$content = file_get_contents('https://api.example.com/data');

// php:// streams for special resources
$input = file_get_contents('php://input');    // Request body
$output = fopen('php://output', 'w');         // Response body
$memory = fopen('php://memory', 'r+');        // In-memory file
$temp = fopen('php://temp', 'r+');            // Temp file (memory then disk)
```

**Stream Contexts**

Stream contexts provide options and parameters for stream operations:

```php
// HTTP context with custom headers
$context = stream_context_create([
    'http' => [
        'method' => 'POST',
        'header' => [
            'Content-Type: application/json',
            'Authorization: Bearer ' . $apiToken,
        ],
        'content' => json_encode($data),
        'timeout' => 30,
        'ignore_errors' => true, // Return body even on HTTP errors
    ],
]);

$response = file_get_contents('https://api.example.com/endpoint', false, $context);

// Check response headers
$headers = $http_response_header; // Magic variable set by stream functions
```

**Stream Filters**

Filters transform data as it passes through a stream:

```php
// Applying filters to file operations
$handle = fopen('data.txt', 'r');

// Add decompression filter
stream_filter_append($handle, 'zlib.inflate');

// Add from base64 encoding
stream_filter_append($handle, 'convert.base64-decode');

$content = stream_get_contents($handle);
fclose($handle);

// Writing with compression
$handle = fopen('compressed.gz', 'w');
stream_filter_append($handle, 'zlib.deflate', STREAM_FILTER_WRITE);
fwrite($handle, 'Data to compress');
fclose($handle);
```

Common built-in filters: `string.toupper`, `string.tolower`, `string.rot13`, `convert.base64-encode`, `convert.base64-decode`, `zlib.deflate`, `zlib.inflate`, `mcrypt.*`, `mdecrypt.*`.

**Custom Stream Filters**

Creating custom filters by extending `php_user_filter`:

```php
class CensorFilter extends php_user_filter
{
    public function filter($in, $out, &$consumed, bool $closing): int
    {
        while ($bucket = stream_bucket_make_writeable($in)) {
            $bucket->data = str_replace(
                ['badword1', 'badword2'],
                '****',
                $bucket->data
            );
            $consumed += $bucket->datalen;
            stream_bucket_append($out, $bucket);
        }
        return PSFS_PASS_ON;
    }
}

// Register the filter
stream_filter_register('censor', CensorFilter::class);

// Use it
$handle = fopen('input.txt', 'r');
stream_filter_append($handle, 'censor');
$clean = stream_get_contents($handle);
```

#### 6.5 Temporary Files and Memory Streams

**PHP Memory and Temp Streams**

```php
// php://memory - entirely in RAM
$memory = fopen('php://memory', 'r+');
fwrite($memory, 'Data stored in memory');
rewind($memory);
echo fgets($memory); // 'Data stored in memory'
fclose($memory);

// php://temp - in memory up to limit, then to disk
$temp = fopen('php://temp/maxmemory:1048576', 'r+');
// Stores up to 1MB in memory, then spills to temp file
```

**System Temporary Files**

```php
// Create a temporary file (returns file handle)
$tempHandle = tmpfile();
fwrite($tempHandle, 'Temporary data');
// File automatically deleted when closed or script ends
fclose($tempHandle);

// Create a named temporary file
$tempPath = tempnam(sys_get_temp_dir(), 'myapp_');
file_put_contents($tempPath, 'Temporary data');
// File must be manually deleted
register_shutdown_function(function () use ($tempPath): void {
    if (file_exists($tempPath)) {
        unlink($tempPath);
    }
});
```

## Part II: Object-Oriented Programming

---

### Chapter 7: OOP Fundamentals

#### 7.1 Classes, Objects, Properties, and Methods

Object-Oriented Programming in PHP has matured dramatically since its introduction. Modern PHP OOP is robust, expressive, and comparable to other enterprise languages. Understanding its fundamentals is essential for professional PHP development.

**Defining Classes**

A class serves as a blueprint for creating objects, encapsulating data (properties) and behavior (methods):

```php
class User
{
    // Properties
    private int $id;
    private string $name;
    private string $email;
    private DateTimeImmutable $createdAt;
    
    // Methods
    public function __construct(string $name, string $email)
    {
        $this->name = $name;
        $this->email = $email;
        $this->createdAt = new DateTimeImmutable();
    }
    
    public function getName(): string
    {
        return $this->name;
    }
    
    public function getEmail(): string
    {
        return $this->email;
    }
    
    public function updateEmail(string $newEmail): void
    {
        if (!filter_var($newEmail, FILTER_VALIDATE_EMAIL)) {
            throw new InvalidArgumentException('Invalid email address');
        }
        $this->email = $newEmail;
    }
}
```

**Instantiating Objects**

Objects are created using the `new` keyword:

```php
$user = new User('Alice Johnson', 'alice@example.com');
echo $user->getName(); // 'Alice Johnson'

// Creating multiple instances
$user1 = new User('Bob', 'bob@example.com');
$user2 = new User('Charlie', 'charlie@example.com');
// Each instance maintains its own property values
```

**Properties**

Properties store an object's state. Modern PHP supports typed properties, readonly properties, and property promotion:

```php
class Product
{
    // Typed properties (PHP 7.4+)
    private string $name;
    private float $price;
    private ?string $description = null;
    private array $tags = [];
    private bool $isAvailable = true;
    
    // Readonly properties (PHP 8.1+)
    public readonly string $sku;
    
    // Static property
    private static int $count = 0;
    
    public function __construct(string $name, float $price, string $sku)
    {
        $this->name = $name;
        $this->price = $price;
        $this->sku = $sku;
        self::$count++;
    }
    
    // Property with custom getter logic
    public function getPriceWithTax(float $taxRate = 0.2): float
    {
        return $this->price * (1 + $taxRate);
    }
}
```

Uninitialized typed properties must be assigned before access. PHP throws a `TypeError` if a typed property is accessed before initialization:

```php
class Incomplete
{
    private string $name; // Must be initialized in constructor
    
    public function getName(): string
    {
        return $this->name; // Error if constructor never set it
    }
}
```

**Methods**

Methods define object behavior. They can have visibility modifiers, type declarations, and return types:

```php
class Order
{
    private array $items = [];
    private float $total = 0.0;
    private OrderStatus $status = OrderStatus::Pending;
    
    // Public method - accessible everywhere
    public function addItem(OrderItem $item): void
    {
        $this->items[] = $item;
        $this->recalculateTotal();
    }
    
    // Private method - internal use only
    private function recalculateTotal(): void
    {
        $this->total = array_reduce(
            $this->items,
            fn(float $sum, OrderItem $item): float => $sum + $item->getSubtotal(),
            0.0
        );
    }
    
    // Protected method - accessible in subclasses
    protected function validateStatusTransition(OrderStatus $newStatus): bool
    {
        return $this->status->canTransitionTo($newStatus);
    }
    
    // Static method - called on class, not instance
    public static function fromArray(array $data): self
    {
        $order = new self();
        foreach ($data['items'] as $itemData) {
            $order->addItem(OrderItem::fromArray($itemData));
        }
        return $order;
    }
}
```

#### 7.2 Visibility Modifiers: Public, Private, and Protected

Visibility modifiers enforce encapsulation by controlling access to class members.

**Public**

Public members are accessible from anywhere—inside the class, from derived classes, and from external code:

```php
class Configuration
{
    public string $applicationName = 'My App';
    
    public function getVersion(): string
    {
        return '1.0.0';
    }
}

$config = new Configuration();
echo $config->applicationName; // Accessible
echo $config->getVersion();    // Accessible
```

Public properties expose implementation details and make future changes difficult. Most properties should be private or protected, accessed through methods (getters/setters) that can add validation, logging, or transformation logic.

**Private**

Private members are accessible only within the defining class:

```php
class BankAccount
{
    private float $balance;
    private array $transactions = [];
    
    public function __construct(float $initialBalance)
    {
        $this->balance = $initialBalance;
    }
    
    public function deposit(float $amount): void
    {
        if ($amount <= 0) {
            throw new InvalidArgumentException('Deposit must be positive');
        }
        
        $this->balance += $amount;
        $this->recordTransaction('deposit', $amount);
    }
    
    public function withdraw(float $amount): void
    {
        if ($amount <= 0) {
            throw new InvalidArgumentException('Withdrawal must be positive');
        }
        
        if ($amount > $this->balance) {
            throw new InsufficientFundsException();
        }
        
        $this->balance -= $amount;
        $this->recordTransaction('withdrawal', $amount);
    }
    
    public function getBalance(): float
    {
        return $this->balance;
    }
    
    private function recordTransaction(string $type, float $amount): void
    {
        $this->transactions[] = [
            'type' => $type,
            'amount' => $amount,
            'timestamp' => new DateTimeImmutable(),
            'balance' => $this->balance,
        ];
    }
}

$account = new BankAccount(1000);
$account->deposit(500);
// $account->balance = 1000000; // Error: private property
// $account->recordTransaction('hack', 1000000); // Error: private method
```

Private members are not accessible in child classes. This is intentional—it allows parent classes to change private implementation details without affecting subclasses.

**Protected**

Protected members are accessible within the defining class and its subclasses:

```php
abstract class Entity
{
    protected int $id;
    protected DateTimeImmutable $createdAt;
    protected ?DateTimeImmutable $updatedAt = null;
    
    public function __construct()
    {
        $this->createdAt = new DateTimeImmutable();
    }
    
    public function getId(): int
    {
        return $this->id;
    }
    
    protected function markUpdated(): void
    {
        $this->updatedAt = new DateTimeImmutable();
    }
}

class Article extends Entity
{
    private string $title;
    private string $content;
    
    public function update(string $title, string $content): void
    {
        $this->title = $title;
        $this->content = $content;
        $this->markUpdated(); // Accessible in child class
    }
}

$article = new Article();
// $article->markUpdated(); // Error: protected method, not accessible externally
```

Protected members are part of the class's extension API but not its public interface. They represent a commitment to subclasses—changes to protected members can break child classes.

**Visibility Best Practices**

- **Properties**: Start with `private`. Promote to `protected` only when subclasses genuinely need direct access.
- **Methods**: Use `public` for the class's external API. Use `private` for implementation details. Use `protected` for extension points designed for subclass overriding.
- **Immutability**: Prefer `public readonly` for value objects where external access without modification is desired.
- **Information Hiding**: Expose the minimum surface area. Every public member is a commitment that constrains future changes.

#### 7.3 Constructors, Destructors, and Constructor Property Promotion (PHP 8)

**Constructors**

The constructor method `__construct()` initializes new objects. PHP calls it automatically when an object is created:

```php
class User
{
    private string $email;
    private string $username;
    private DateTimeImmutable $registeredAt;
    
    public function __construct(string $email, string $username)
    {
        $this->email = $email;
        $this->username = $username;
        $this->registeredAt = new DateTimeImmutable();
    }
}

$user = new User('alice@example.com', 'alice');
```

**Constructor Promotion (PHP 8.0+)**

Constructor property promotion reduces boilerplate by combining property declaration with constructor parameters:

```php
// Traditional (PHP 7.4)
class User
{
    private string $name;
    private string $email;
    private ?string $phone;
    private DateTimeImmutable $createdAt;
    
    public function __construct(
        string $name,
        string $email,
        ?string $phone = null
    ) {
        $this->name = $name;
        $this->email = $email;
        $this->phone = $phone;
        $this->createdAt = new DateTimeImmutable();
    }
}

// With constructor promotion (PHP 8.0)
class User
{
    private DateTimeImmutable $createdAt;
    
    public function __construct(
        private string $name,
        private string $email,
        private ?string $phone = null,
    ) {
        $this->createdAt = new DateTimeImmutable();
    }
}
```

Promoted properties can use all visibility modifiers, include default values, and be combined with regular constructor parameters:

```php
class Product
{
    public function __construct(
        public readonly string $sku,
        private string $name,
        private float $price,
        private ?string $description = null,
        private DateTimeImmutable $createdAt = new DateTimeImmutable(),
    ) {}
}
```

**Constructor Overloading**

PHP doesn't support multiple constructors directly. Instead, use static factory methods:

```php
class Money
{
    private function __construct(
        private int $amountInCents,
        private string $currency,
    ) {}
    
    public static function fromCents(int $cents, string $currency = 'USD'): self
    {
        return new self($cents, $currency);
    }
    
    public static function fromDecimal(float $amount, string $currency = 'USD'): self
    {
        return new self((int) round($amount * 100), $currency);
    }
    
    public static function zero(string $currency = 'USD'): self
    {
        return new self(0, $currency);
    }
}

$price = Money::fromDecimal(19.99);
$free = Money::zero();
```

Static factory methods provide named constructors, can return cached instances, throw specific exceptions, and return subclasses—flexibility that single constructors cannot match.

**Destructors**

The `__destruct()` method is called when an object is destroyed (no more references exist) or during script shutdown:

```php
class FileHandler
{
    private $handle;
    
    public function __construct(private string $path)
    {
        $this->handle = fopen($path, 'r');
    }
    
    public function readLine(): ?string
    {
        $line = fgets($this->handle);
        return $line !== false ? $line : null;
    }
    
    public function __destruct()
    {
        if ($this->handle) {
            fclose($this->handle);
        }
    }
}

// Destructor called automatically when $handler goes out of scope
// or when script ends
function processFile(): void
{
    $handler = new FileHandler('data.txt');
    // ... use handler ...
} // Destructor called here
```

Destructors have limitations: they cannot throw exceptions (PHP fatal error), cannot rely on other objects still existing during shutdown, and execution order is not guaranteed. For resource management, prefer explicit `close()` or `dispose()` methods, or implement `__destruct()` as a safety net only.

#### 7.4 `$this`, `self`, `static`, and Late Static Binding

**$this**

`$this` refers to the current object instance and is available in non-static methods:

```php
class Person
{
    private string $name;
    
    public function setName(string $name): self
    {
        $this->name = $name;
        return $this; // Fluent interface
    }
    
    public function introduce(): string
    {
        return "Hi, I'm {$this->name}";
    }
}
```

`$this` always refers to the object on which the method was called, even in inherited methods.

**self**

`self` refers to the class where it's written, not where it's called:

```php
class ParentClass
{
    public static function whoAmI(): string
    {
        return self::class; // Always returns 'ParentClass'
    }
}

class ChildClass extends ParentClass
{
    // Inherits whoAmI()
}

echo ChildClass::whoAmI(); // 'ParentClass' — uses self from parent
```

Use `self` for constants, static properties, and methods where the defining class's implementation should always be used.

**static (Late Static Binding)**

`static` resolves to the class that was actually called at runtime, enabling polymorphic behavior in static contexts:

```php
class Model
{
    protected static string $table;
    
    public static function getTable(): string
    {
        return static::$table; // Resolves at runtime
    }
    
    public static function find(int $id): ?static
    {
        $table = static::getTable();
        // Query database...
        $data = fetchFromDatabase($table, $id);
        return $data ? new static($data) : null;
    }
}

class User extends Model
{
    protected static string $table = 'users';
}

class Post extends Model
{
    protected static string $table = 'posts';
}

echo User::getTable(); // 'users'
echo Post::getTable(); // 'posts'

$user = User::find(1); // Returns User instance
$post = Post::find(1); // Returns Post instance
```

Key differences:

| Context | `self` | `static` |
|---------|--------|----------|
| In `ParentClass` | Refers to `ParentClass` | Refers to the called class |
| Method call | Calls ParentClass method | Calls called class method (if overridden) |
| Property access | Access ParentClass property | Access called class property |
| Instance creation | Creates ParentClass instance | Creates called class instance |

**Forwarding Static Calls**

Late static binding requires that the called method is defined or inherited. Forwarding calls explicitly can be necessary:

```php
class Base
{
    public static function create(): static
    {
        return new static();
    }
    
    public static function process(): void
    {
        static::doProcess(); // Forward to runtime class
    }
    
    protected static function doProcess(): void
    {
        echo "Base processing\n";
    }
}

class Derived extends Base
{
    protected static function doProcess(): void
    {
        echo "Derived processing\n";
    }
}

Derived::process(); // "Derived processing"
```

#### 7.5 Magic Methods: `__get`, `__set`, `__call`, `__toString`, and Others

Magic methods are special methods PHP calls automatically in response to specific actions. They enable dynamic behavior but should be used judiciously—they can hide complexity and degrade performance.

**__get and __set**

Called when accessing undefined or inaccessible properties:

```php
class DynamicAttributes
{
    private array $data = [];
    
    public function __get(string $name): mixed
    {
        return $this->data[$name] ?? null;
    }
    
    public function __set(string $name, mixed $value): void
    {
        $this->data[$name] = $value;
    }
    
    public function __isset(string $name): bool
    {
        return isset($this->data[$name]);
    }
    
    public function __unset(string $name): void
    {
        unset($this->data[$name]);
    }
}

$obj = new DynamicAttributes();
$obj->name = 'Alice';      // Calls __set
$obj->email = 'alice@example.com';
echo $obj->name;            // Calls __get: 'Alice'
echo isset($obj->email);    // true (via __isset)
unset($obj->email);         // Calls __unset
```

**__call and __callStatic**

Called when invoking undefined or inaccessible methods:

```php
class QueryBuilder
{
    private array $conditions = [];
    private array $orders = [];
    
    public function __call(string $name, array $arguments): self
    {
        // Handle whereXxx methods dynamically
        if (str_starts_with($name, 'whereBy')) {
            $field = lcfirst(substr($name, 7));
            return $this->where($field, $arguments[0] ?? null);
        }
        
        throw new BadMethodCallException("Method {$name} does not exist");
    }
    
    public function where(string $field, mixed $value): self
    {
        $this->conditions[] = [$field, '=', $value];
        return $this;
    }
    
    public static function __callStatic(string $name, array $arguments): self
    {
        return (new self())->__call($name, $arguments);
    }
}

$query = new QueryBuilder();
$query->whereByName('Alice')
      ->whereByAge(30);
```

**__toString**

Called when an object is used as a string:

```php
class EmailAddress
{
    public function __construct(
        private string $local,
        private string $domain,
    ) {}
    
    public function __toString(): string
    {
        return "{$this->local}@{$this->domain}";
    }
}

$email = new EmailAddress('alice', 'example.com');
echo $email; // 'alice@example.com'
$formatted = "Contact: {$email}"; // String interpolation triggers __toString
```

PHP 8.0 introduced the `Stringable` interface, automatically implemented by classes with `__toString()`, allowing `string|Stringable` type hints.

**__invoke**

Called when an object is used as a function:

```php
class Multiplier
{
    public function __construct(private int $factor) {}
    
    public function __invoke(int $number): int
    {
        return $number * $this->factor;
    }
}

$doubler = new Multiplier(2);
echo $doubler(5); // 10

// Useful for single-method objects (strategy pattern)
$operations = [
    'double' => new Multiplier(2),
    'triple' => new Multiplier(3),
];

$result = array_map($operations['double'], [1, 2, 3]); // [2, 4, 6]
```

**__clone**

Called when an object is cloned. Use it to implement deep copies or reset state:

```php
class Invoice
{
    private DateTimeImmutable $createdAt;
    private ?string $invoiceNumber = null;
    
    public function __construct()
    {
        $this->createdAt = new DateTimeImmutable();
    }
    
    public function setInvoiceNumber(string $number): void
    {
        $this->invoiceNumber = $number;
    }
    
    public function __clone(): void
    {
        // Reset state for the clone
        $this->createdAt = new DateTimeImmutable();
        $this->invoiceNumber = null;
    }
}

$original = new Invoice();
$original->setInvoiceNumber('INV-001');

$duplicate = clone $original;
// $duplicate has fresh createdAt and null invoiceNumber
```

**__sleep and __wakeup**

Control serialization behavior:

```php
class UserSession
{
    private string $token;
    private $databaseConnection; // Resource, cannot be serialized
    private DateTimeImmutable $lastActivity;
    
    public function __sleep(): array
    {
        // Only serialize these properties
        return ['token', 'lastActivity'];
    }
    
    public function __wakeup(): void
    {
        // Re-establish database connection after unserialization
        $this->databaseConnection = Database::getConnection();
    }
}
```

PHP 7.4+ added `__serialize()` and `__unserialize()` as a cleaner alternative:

```php
public function __serialize(): array
{
    return [
        'token' => $this->token,
        'lastActivity' => $this->lastActivity->format('c'),
    ];
}

public function __unserialize(array $data): void
{
    $this->token = $data['token'];
    $this->lastActivity = new DateTimeImmutable($data['lastActivity']);
}
```

**__debugInfo**

Controls what `var_dump()` displays:

```php
class User
{
    private string $password;
    
    public function __construct(
        private string $name,
        #[\SensitiveParameter]
        string $password,
    ) {
        $this->password = password_hash($password, PASSWORD_BCRYPT);
    }
    
    public function __debugInfo(): array
    {
        return [
            'name' => $this->name,
            'password' => '[REDACTED]',
        ];
    }
}
```

**Performance Considerations**

Magic methods are slower than direct property/method access because PHP must check for their existence. For performance-critical code or classes with many instances, prefer explicit implementations:

```php
// Slower due to magic methods
class MagicUser
{
    private array $data = [];
    public function __get(string $name): mixed { return $this->data[$name] ?? null; }
    public function __set(string $name, mixed $value): void { $this->data[$name] = $value; }
}

// Faster with explicit properties
class ExplicitUser
{
    public string $name;
    public string $email;
}
```

---

### Chapter 8: Inheritance and Polymorphism

#### 8.1 Extending Classes and Method Overriding

Inheritance allows a class to inherit properties and methods from a parent class, promoting code reuse and establishing type hierarchies.

**Basic Inheritance**

```php
class Vehicle
{
    public function __construct(
        protected string $make,
        protected string $model,
        protected int $year,
    ) {}
    
    public function getDescription(): string
    {
        return "{$this->year} {$this->make} {$this->model}";
    }
    
    public function startEngine(): string
    {
        return "Engine started";
    }
}

class Car extends Vehicle
{
    private int $doors;
    
    public function __construct(
        string $make,
        string $model,
        int $year,
        int $doors,
    ) {
        parent::__construct($make, $model, $year);
        $this->doors = $doors;
    }
    
    public function getDescription(): string
    {
        return parent::getDescription() . " ({$this->doors}-door)";
    }
}

$car = new Car('Toyota', 'Camry', 2023, 4);
echo $car->getDescription(); // "2023 Toyota Camry (4-door)"
echo $car->startEngine();    // "Engine started" (inherited)
```

**Method Overriding**

Child classes can override parent methods to provide specialized behavior:

```php
class Logger
{
    public function log(string $message, string $level = 'info'): void
    {
        echo "[{$level}] {$message}\n";
    }
}

class FileLogger extends Logger
{
    private $handle;
    
    public function __construct(string $path)
    {
        $this->handle = fopen($path, 'a');
    }
    
    public function log(string $message, string $level = 'info'): void
    {
        $formatted = "[{$level}] {$message}\n";
        fwrite($this->handle, $formatted);
    }
    
    public function __destruct()
    {
        if ($this->handle) {
            fclose($this->handle);
        }
    }
}
```

When overriding, the child method must maintain compatibility with the parent signature. PHP enforces:
- Same or more permissive visibility (can make protected → public, not public → protected)
- Same or narrower return type (covariance)
- Same or wider parameter types (contravariance) for PHP 8.0+
- Same number of required parameters (optional parameters can differ)

**Calling Parent Methods**

Use `parent::` to call the overridden parent method:

```php
class AuditedLogger extends Logger
{
    private int $logCount = 0;
    
    public function log(string $message, string $level = 'info'): void
    {
        $this->logCount++;
        parent::log($message, $level);
    }
    
    public function getLogCount(): int
    {
        return $this->logCount;
    }
}
```

**The `final` Keyword on Methods**

`final` methods cannot be overridden, protecting critical behavior:

```php
class PaymentProcessor
{
    final public function processPayment(float $amount, string $currency): PaymentResult
    {
        $this->validateAmount($amount);
        $this->validateCurrency($currency);
        return $this->doProcess($amount, $currency);
    }
    
    // Subclasses can customize this part
    protected function doProcess(float $amount, string $currency): PaymentResult
    {
        // Default implementation
        return new PaymentResult(true);
    }
    
    private function validateAmount(float $amount): void
    {
        if ($amount <= 0) {
            throw new InvalidArgumentException('Amount must be positive');
        }
    }
}
```

#### 8.2 Abstract Classes and Methods

Abstract classes define partial implementations that subclasses must complete.

**Defining Abstract Classes**

```php
abstract class Repository
{
    abstract protected function getTableName(): string;
    abstract protected function mapRow(array $row): object;
    
    protected function getConnection(): PDO
    {
        return Database::getConnection();
    }
    
    public function findById(int $id): ?object
    {
        $stmt = $this->getConnection()->prepare(
            "SELECT * FROM {$this->getTableName()} WHERE id = ?"
        );
        $stmt->execute([$id]);
        $row = $stmt->fetch();
        
        return $row ? $this->mapRow($row) : null;
    }
    
    public function findAll(): array
    {
        $stmt = $this->getConnection()->query(
            "SELECT * FROM {$this->getTableName()}"
        );
        
        return array_map(
            fn(array $row): object => $this->mapRow($row),
            $stmt->fetchAll()
        );
    }
}

class UserRepository extends Repository
{
    protected function getTableName(): string
    {
        return 'users';
    }
    
    protected function mapRow(array $row): object
    {
        return new User(
            id: $row['id'],
            name: $row['name'],
            email: $row['email'],
        );
    }
    
    // Add User-specific methods
    public function findByEmail(string $email): ?User
    {
        $stmt = $this->getConnection()->prepare(
            "SELECT * FROM users WHERE email = ?"
        );
        $stmt->execute([$email]);
        $row = $stmt->fetch();
        
        return $row ? $this->mapRow($row) : null;
    }
}
```

**Template Method Pattern**

Abstract classes excel at implementing the Template Method pattern, where the parent defines an algorithm structure and subclasses fill in specific steps:

```php
abstract class ImportProcessor
{
    final public function process(string $filename): ImportResult
    {
        $rawData = $this->readFile($filename);
        $validatedData = $this->validate($rawData);
        $transformedData = $this->transform($validatedData);
        $savedCount = $this->save($transformedData);
        
        return new ImportResult($savedCount, count($validatedData));
    }
    
    protected function readFile(string $filename): array
    {
        $content = file_get_contents($filename);
        return $this->parse($content);
    }
    
    abstract protected function parse(string $content): array;
    abstract protected function validate(array $data): array;
    abstract protected function transform(array $data): array;
    abstract protected function save(array $data): int;
}

class CsvImportProcessor extends ImportProcessor
{
    protected function parse(string $content): array
    {
        $rows = [];
        $lines = explode("\n", $content);
        foreach ($lines as $line) {
            $rows[] = str_getcsv($line);
        }
        return $rows;
    }
    
    protected function validate(array $data): array
    {
        return array_filter($data, fn(array $row): bool => count($row) === 3);
    }
    
    protected function transform(array $data): array
    {
        return array_map(fn(array $row): array => [
            'name' => trim($row[0]),
            'email' => strtolower(trim($row[1])),
            'age' => (int) $row[2],
        ], $data);
    }
    
    protected function save(array $data): int
    {
        $count = 0;
        foreach ($data as $row) {
            // Save to database
            $count++;
        }
        return $count;
    }
}
```

#### 8.3 Final Classes and Methods

The `final` keyword prevents further inheritance or overriding.

**Final Classes**

A final class cannot be extended:

```php
final class StringUtils
{
    public static function truncate(string $text, int $maxLength): string
    {
        if (mb_strlen($text) <= $maxLength) {
            return $text;
        }
        return mb_substr($text, 0, $maxLength - 3) . '...';
    }
}

// Error: Class may not inherit from final class
// class ExtendedStringUtils extends StringUtils {}
```

Use final classes when:
- The class represents a complete concept with no valid extensions
- Security constraints require preventing subclass modification
- Performance-critical code where inheritance indirection is undesirable

**Final Methods**

Final methods cannot be overridden in child classes:

```php
class SecurityHandler
{
    final public function sanitize(string $input): string
    {
        return htmlspecialchars(strip_tags(trim($input)), ENT_QUOTES, 'UTF-8');
    }
    
    public function process(string $input): string
    {
        $clean = $this->sanitize($input);
        return $this->format($clean);
    }
    
    protected function format(string $input): string
    {
        return $input;
    }
}
```

**Composition Over Inheritance**

Final classes encourage composition—building complex objects by combining simpler ones rather than extending them:

```php
// Instead of inheritance
final class OrderEmailService
{
    public function __construct(
        private readonly OrderRepository $orders,
        private readonly TemplateRenderer $renderer,
        private readonly MailTransport $mailer,
    ) {}
    
    public function sendConfirmation(int $orderId): void
    {
        $order = $this->orders->findOrFail($orderId);
        $html = $this->renderer->render('emails/confirmation', ['order' => $order]);
        $this->mailer->send($order->email, 'Order Confirmation', $html);
    }
}
```

#### 8.4 Type Hinting and Polymorphic Behavior

**Polymorphism Through Interfaces and Inheritance**

Polymorphism allows different classes to be treated through a common interface:

```php
interface Notifiable
{
    public function getNotificationEmail(): string;
    public function getNotificationPreference(): string;
}

class User implements Notifiable
{
    public function __construct(
        private string $name,
        private string $email,
    ) {}
    
    public function getNotificationEmail(): string
    {
        return $this->email;
    }
    
    public function getNotificationPreference(): string
    {
        return 'html';
    }
}

class Admin extends User
{
    public function getNotificationPreference(): string
    {
        return 'text'; // Admins prefer plain text
    }
}

// Polymorphic function
function sendNotification(Notifiable $recipient, string $message): void
{
    $email = $recipient->getNotificationEmail();
    $format = $recipient->getNotificationPreference();
    
    if ($format === 'html') {
        sendHtmlEmail($email, $message);
    } else {
        sendTextEmail($email, $message);
    }
}

$user = new User('Alice', 'alice@example.com');
$admin = new Admin('Bob', 'bob@admin.com');

sendNotification($user, 'Welcome!');
sendNotification($admin, 'System update');
```

**Type Checking at Runtime**

```php
function processEntity(object $entity): void
{
    // Check exact class
    if ($entity instanceof User) {
        handleUser($entity);
    }
    
    // Check interface implementation
    if ($entity instanceof Notifiable) {
        notify($entity);
    }
    
    // Check parent class
    if (is_subclass_of($entity, Model::class)) {
        logModelAccess($entity);
    }
}
```

**Dependency Injection and Polymorphism**

Polymorphism enables flexible dependency injection:

```php
class ReportGenerator
{
    public function __construct(
        private ReportFormatter $formatter, // Interface
        private ReportRepository $repository,
    ) {}
    
    public function generate(): string
    {
        $data = $this->repository->getData();
        return $this->formatter->format($data);
    }
}

// Different formatters can be injected
$pdfReport = new ReportGenerator(new PdfFormatter(), $repo);
$csvReport = new ReportGenerator(new CsvFormatter(), $repo);
$jsonReport = new ReportGenerator(new JsonFormatter(), $repo);
```

---

### Chapter 9: Interfaces, Traits, and Enums

#### 9.1 Defining and Implementing Interfaces

Interfaces define contracts that implementing classes must fulfill. They specify method signatures without implementation details.

**Basic Interface Definition**

```php
interface CacheInterface
{
    public function get(string $key, mixed $default = null): mixed;
    public function set(string $key, mixed $value, ?int $ttl = null): bool;
    public function delete(string $key): bool;
    public function clear(): bool;
    public function has(string $key): bool;
}
```

Classes implement interfaces using the `implements` keyword:

```php
class RedisCache implements CacheInterface
{
    public function __construct(private \Redis $redis) {}
    
    public function get(string $key, mixed $default = null): mixed
    {
        $value = $this->redis->get($key);
        return $value !== false ? unserialize($value) : $default;
    }
    
    public function set(string $key, mixed $value, ?int $ttl = null): bool
    {
        $serialized = serialize($value);
        if ($ttl !== null) {
            return $this->redis->setex($key, $ttl, $serialized);
        }
        return $this->redis->set($key, $serialized);
    }
    
    public function delete(string $key): bool
    {
        return (bool) $this->redis->del($key);
    }
    
    public function clear(): bool
    {
        return $this->redis->flushDB();
    }
    
    public function has(string $key): bool
    {
        return (bool) $this->redis->exists($key);
    }
}

class ArrayCache implements CacheInterface
{
    private array $storage = [];
    private array $expiration = [];
    
    public function get(string $key, mixed $default = null): mixed
    {
        if (!$this->has($key)) {
            return $default;
        }
        return $this->storage[$key];
    }
    
    public function set(string $key, mixed $value, ?int $ttl = null): bool
    {
        $this->storage[$key] = $value;
        if ($ttl !== null) {
            $this->expiration[$key] = time() + $ttl;
        }
        return true;
    }
    
    public function delete(string $key): bool
    {
        unset($this->storage[$key], $this->expiration[$key]);
        return true;
    }
    
    public function clear(): bool
    {
        $this->storage = [];
        $this->expiration = [];
        return true;
    }
    
    public function has(string $key): bool
    {
        if (!array_key_exists($key, $this->storage)) {
            return false;
        }
        if (isset($this->expiration[$key]) && $this->expiration[$key] < time()) {
            $this->delete($key);
            return false;
        }
        return true;
    }
}
```

**Interface Constants**

Interfaces can define constants accessible by implementing classes:

```php
interface HttpStatus
{
    const OK = 200;
    const CREATED = 201;
    const BAD_REQUEST = 400;
    const UNAUTHORIZED = 401;
    const NOT_FOUND = 404;
    const SERVER_ERROR = 500;
}

class ApiResponse implements HttpStatus
{
    public static function success(mixed $data): array
    {
        return [
            'status' => self::OK,
            'data' => $data,
        ];
    }
    
    public static function notFound(): array
    {
        return [
            'status' => self::NOT_FOUND,
            'message' => 'Resource not found',
        ];
    }
}
```

**Interface Inheritance**

Interfaces can extend other interfaces, creating richer contracts:

```php
interface Readable
{
    public function read(int $bytes): string;
}

interface Writable
{
    public function write(string $data): int;
}

interface Seekable
{
    public function seek(int $position): void;
}

interface FileLike extends Readable, Writable, Seekable
{
    public function close(): void;
    public function isOpen(): bool;
}
```

#### 9.2 Multiple Interfaces and Interface Inheritance

PHP doesn't support multiple inheritance for classes, but a class can implement multiple interfaces, achieving a form of multiple inheritance of type:

```php
class FileHandler implements Writable, Readable, Seekable
{
    private $handle;
    
    public function __construct(string $path, string $mode)
    {
        $this->handle = fopen($path, $mode);
    }
    
    public function read(int $bytes): string
    {
        return fread($this->handle, $bytes);
    }
    
    public function write(string $data): int
    {
        return fwrite($this->handle, $data);
    }
    
    public function seek(int $position): void
    {
        fseek($this->handle, $position);
    }
}
```

**Duck Typing with Interfaces**

Interfaces enable duck typing—if an object implements the required interface, it can be used regardless of its class hierarchy:

```php
interface Jsonable
{
    public function toJson(): string;
}

class User implements Jsonable
{
    public function toJson(): string
    {
        return json_encode([
            'type' => 'user',
            'name' => $this->name,
            'email' => $this->email,
        ]);
    }
}

class Order implements Jsonable
{
    public function toJson(): string
    {
        return json_encode([
            'type' => 'order',
            'id' => $this->id,
            'total' => $this->total,
        ]);
    }
}

function apiResponse(Jsonable $entity): void
{
    header('Content-Type: application/json');
    echo $entity->toJson();
}
```

**Interface Segregation Principle**

Prefer small, focused interfaces over large, monolithic ones:

```php
// Bad: One large interface
interface Worker
{
    public function work(): void;
    public function eat(): void;
    public function sleep(): void;
}

// Good: Segregated interfaces
interface Workable
{
    public function work(): void;
}

interface Eatable
{
    public function eat(): void;
}

interface Sleepable
{
    public function sleep(): void;
}

class Human implements Workable, Eatable, Sleepable
{
    public function work(): void { /* ... */ }
    public function eat(): void { /* ... */ }
    public function sleep(): void { /* ... */ }
}

class Robot implements Workable
{
    public function work(): void { /* ... */ }
    // No need to implement eat() or sleep()
}
```

#### 9.3 Traits: Solving Multiple Inheritance

Traits provide horizontal code reuse, allowing methods to be shared across unrelated classes.

**Defining Traits**

```php
trait Timestampable
{
    private DateTimeImmutable $createdAt;
    private ?DateTimeImmutable $updatedAt = null;
    
    public function initializeTimestamps(): void
    {
        $this->createdAt = new DateTimeImmutable();
    }
    
    public function markUpdated(): void
    {
        $this->updatedAt = new DateTimeImmutable();
    }
    
    public function getCreatedAt(): DateTimeImmutable
    {
        return $this->createdAt;
    }
    
    public function getUpdatedAt(): ?DateTimeImmutable
    {
        return $this->updatedAt;
    }
}

trait SoftDeletable
{
    private ?DateTimeImmutable $deletedAt = null;
    
    public function softDelete(): void
    {
        $this->deletedAt = new DateTimeImmutable();
    }
    
    public function restore(): void
    {
        $this->deletedAt = null;
    }
    
    public function isDeleted(): bool
    {
        return $this->deletedAt !== null;
    }
}

class Article
{
    use Timestampable;
    use SoftDeletable;
    
    public function __construct(
        private string $title,
        private string $content,
    ) {
        $this->initializeTimestamps();
    }
    
    public function update(string $title, string $content): void
    {
        $this->title = $title;
        $this->content = $content;
        $this->markUpdated();
    }
}
```

**Abstract Methods in Traits**

Traits can declare abstract methods that using classes must implement:

```php
trait Identifiable
{
    abstract public function getId(): int;
    
    public function isEqualTo(self $other): bool
    {
        return $this->getId() === $other->getId();
    }
}

class User
{
    use Identifiable;
    
    public function __construct(private int $id)
    {
        // ...
    }
    
    public function getId(): int
    {
        return $this->id;
    }
}
```

**Property Definitions in Traits (PHP 8.2+)**

PHP 8.2 allows traits to define constants and PHP 8.2+ improved property handling:

```php
trait HasDefaultSettings
{
    private array $settings = [];
    
    public function getSetting(string $key, mixed $default = null): mixed
    {
        return $this->settings[$key] ?? $default;
    }
    
    public function setSetting(string $key, mixed $value): void
    {
        $this->settings[$key] = $value;
    }
}
```

**Composing Traits from Traits**

Traits can use other traits:

```php
trait Loggable
{
    private function log(string $message): void
    {
        echo "[LOG] {$message}\n";
    }
}

trait Auditable
{
    use Loggable;
    
    protected function audit(string $action): void
    {
        $this->log("Audit: {$action}");
    }
}
```

#### 9.4 Trait Precedence, Conflicts, and Aliases

When multiple traits provide methods with the same name, conflicts must be resolved explicitly.

**Conflict Resolution with `insteadof`**

```php
trait LoggerA
{
    public function log(string $message): void
    {
        echo "[A] {$message}\n";
    }
}

trait LoggerB
{
    public function log(string $message): void
    {
        echo "[B] {$message}\n";
    }
}

class Service
{
    use LoggerA, LoggerB {
        LoggerA::log insteadof LoggerB; // Use LoggerA's log method
    }
}
```

**Method Aliasing with `as`**

```php
class Service
{
    use LoggerA, LoggerB {
        LoggerA::log insteadof LoggerB;
        LoggerB::log as logB; // Make LoggerB's log available as logB
    }
    
    public function doSomething(): void
    {
        $this->log('From LoggerA');
        $this->logB('From LoggerB');
    }
}
```

**Changing Visibility**

The `as` keyword can also modify visibility:

```php
trait InternalLogger
{
    private function writeLog(string $message): void
    {
        // Write to log file
    }
}

class PublicService
{
    use InternalLogger {
        writeLog as public log; // Make private method public with new name
    }
}

$service = new PublicService();
$service->log('This is now accessible');
```

**Override Precedence**

Class methods always take precedence over trait methods, which take precedence over inherited methods:

```php
class BaseClass
{
    public function greet(): string
    {
        return 'Hello from BaseClass';
    }
}

trait GreetingTrait
{
    public function greet(): string
    {
        return 'Hello from Trait';
    }
}

class ChildClass extends BaseClass
{
    use GreetingTrait;
    // Trait's greet takes precedence over parent's greet
    
    public function greet(): string
    {
        return 'Hello from ChildClass'; // Overrides both
    }
}
```

#### 9.5 Enumerations (PHP 8.1): Backed, Pure, and Methods in Enums

PHP 8.1 introduced native enumerations, providing type-safe enum values.

**Pure Enumerations**

Pure enums have no scalar equivalent:

```php
enum Status
{
    case Draft;
    case Published;
    case Archived;
}

class Article
{
    private Status $status = Status::Draft;
    
    public function publish(): void
    {
        if ($this->status !== Status::Draft) {
            throw new RuntimeException('Only draft articles can be published');
        }
        $this->status = Status::Published;
    }
    
    public function getStatus(): Status
    {
        return $this->status;
    }
}
```

**Backed Enumerations**

Backed enums have scalar (int or string) values:

```php
enum OrderStatus: string
{
    case Pending = 'pending';
    case Processing = 'processing';
    case Shipped = 'shipped';
    case Delivered = 'delivered';
    case Cancelled = 'cancelled';
    
    public function label(): string
    {
        return match ($this) {
            self::Pending => 'Pending',
            self::Processing => 'Processing',
            self::Shipped => 'Shipped',
            self::Delivered => 'Delivered',
            self::Cancelled => 'Cancelled',
        };
    }
    
    public function canTransitionTo(self $newStatus): bool
    {
        return match ($this) {
            self::Pending => in_array($newStatus, [self::Processing, self::Cancelled]),
            self::Processing => in_array($newStatus, [self::Shipped, self::Cancelled]),
            self::Shipped => $newStatus === self::Delivered,
            self::Delivered => false,
            self::Cancelled => false,
        };
    }
}

// Creating from scalar value
$status = OrderStatus::from('pending'); // OrderStatus::Pending
$status = OrderStatus::tryFrom('invalid'); // null

// Accessing value
echo OrderStatus::Processing->value; // 'processing'
echo OrderStatus::Processing->name;  // 'Processing'
```

**Enum Methods and Static Methods**

Enums support methods and static methods, making them powerful value objects:

```php
enum Currency: string
{
    case USD = 'USD';
    case EUR = 'EUR';
    case GBP = 'GBP';
    case JPY = 'JPY';
    
    public function symbol(): string
    {
        return match ($this) {
            self::USD => '$',
            self::EUR => '€',
            self::GBP => '£',
            self::JPY => '¥',
        };
    }
    
    public function decimalPlaces(): int
    {
        return match ($this) {
            self::JPY => 0,
            default => 2,
        };
    }
    
    public function format(int $amountInCents): string
    {
        $decimal = $amountInCents / (10 ** $this->decimalPlaces());
        return $this->symbol() . number_format($decimal, $this->decimalPlaces());
    }
    
    public static function fromCountryCode(string $code): self
    {
        return match ($code) {
            'US' => self::USD,
            'GB' => self::GBP,
            'JP' => self::JPY,
            default => self::EUR,
        };
    }
}

echo Currency::USD->format(1999); // '$19.99'
echo Currency::JPY->format(5000); // '¥5000'
```

**Enums Implementing Interfaces**

Enums can implement interfaces:

```php
interface Filterable
{
    public function filter(array $data): array;
}

enum StatusFilter: int implements Filterable
{
    case Active = 1;
    case Inactive = 0;
    case All = -1;
    
    public function filter(array $data): array
    {
        if ($this === self::All) {
            return $data;
        }
        
        return array_filter(
            $data,
            fn(array $row): bool => ($row['active'] ?? 0) === $this->value
        );
    }
}
```

---

### Chapter 10: Namespaces and Autoloading

#### 10.1 Declaring and Importing Namespaces

Namespaces prevent naming collisions and organize code into logical groups. They are fundamental to modern PHP development.

**Declaring Namespaces**

```php
<?php

namespace App\Models;

class User
{
    public function __construct(
        private string $name,
        private string $email,
    ) {}
}

class Order
{
    // ...
}
```

A file can have only one namespace declaration, and it must be the first statement after `<?php` (with the exception of `declare`).

**Sub-namespaces**

Define hierarchies with backslash separators:

```php
namespace App\Models\Ecommerce;

class Product {}
class Category {}

namespace App\Models\Content;

class Article {}
class Page {}
```

**Importing with `use`**

The `use` keyword imports names from other namespaces:

```php
<?php

namespace App\Controllers;

use App\Models\User;
use App\Models\Order;
use App\Services\{PaymentService, NotificationService};
use App\Exceptions\{NotFoundException, ValidationException};

class OrderController
{
    public function create(
        User $user,
        PaymentService $payment,
        NotificationService $notifications,
    ): Order {
        // Implementation
    }
}
```

**Importing Functions and Constants (PHP 5.6+)**

```php
use function App\Helpers\formatCurrency;
use const App\Config\API_BASE_URL;

$formatted = formatCurrency(1999);
echo API_BASE_URL;
```

**Aliasing**

Use `as` to resolve naming conflicts:

```php
use App\Models\User as UserModel;
use App\Entities\User as UserEntity;
use Illuminate\Support\Facades\Log as LaravelLog;
use Monolog\Logger as MonologLogger;
```

#### 10.2 Sub-namespaces and Name Resolution

**Relative vs. Fully Qualified Names**

Within a namespace, PHP resolves names relative to the current namespace:

```php
namespace App\Services;

use App\Models\User; // Absolute

class UserService
{
    public function create(User $user): void  // Uses imported User
    {
        $validator = new Validation\EmailValidator(); // Relative: App\Services\Validation\EmailValidator
        $logger = new \Monolog\Logger('user');        // Fully qualified
    }
}
```

For names starting with a backslash, PHP uses the fully qualified name. For names without a leading backslash that aren't imported, PHP prepends the current namespace.

**The Global Namespace**

Functions and classes without a namespace are in the global namespace. Access them with a leading backslash from within a namespace:

```php
namespace App\Utils;

$array = [1, 2, 3];
$count = \count($array); // Global count function
$json = \json_encode($array); // Global json_encode
```

PHP falls back to the global namespace for functions and constants (but not classes) if the namespaced version isn't found:

```php
namespace App\Utils;

// These work without leading backslash due to fallback
$count = count($array);
var_dump($array);

// Classes require explicit import or leading backslash
$date = new \DateTime();
```

**Namespace Best Practices**

- Mirror the directory structure: `App\Models\User` → `src/Models/User.php`
- One class per file (exceptions for closely related helper classes)
- Keep namespace depth reasonable (3-5 levels)
- Group imports by type: classes first, then functions, then constants
- Avoid using global namespace functions that have OOP alternatives

#### 10.3 PSR-4 Autoloading with Composer

PSR-4 is the standard for autoloading PHP classes from file paths. Composer implements it automatically.

**Directory Structure**

```
project/
├── composer.json
├── src/
│   ├── Models/
│   │   ├── User.php          (namespace App\Models;)
│   │   └── Order.php         (namespace App\Models;)
│   ├── Services/
│   │   └── PaymentService.php (namespace App\Services;)
│   └── Controllers/
│       └── UserController.php (namespace App\Controllers;)
├── tests/
│   └── Unit/
│       └── UserTest.php
└── vendor/
```

**Composer Configuration**

```json
{
    "autoload": {
        "psr-4": {
            "App\\": "src/",
            "App\\Tests\\": "tests/"
        }
    }
}
```

After adding the configuration, generate the autoloader:

```bash
composer dump-autoload
```

**The Entry Point**

```php
<?php
// public/index.php
require __DIR__ . '/../vendor/autoload.php';

use App\Controllers\UserController;

$controller = new UserController();
$controller->index();
```

**Classmap and Files Autoloading**

Beyond PSR-4, Composer supports other autoloading strategies:

```json
{
    "autoload": {
        "classmap": [
            "src/Legacy/",
            "lib/"
        ],
        "files": [
            "src/helpers.php",
            "src/constants.php"
        ],
        "psr-4": {
            "App\\": "src/"
        }
    }
}
```

- **classmap**: Scans directories and builds a map of all classes found. Good for legacy code not following PSR-4.
- **files**: Includes the specified files on every request. Suitable for functions and constants.

**Autoloader Optimization**

```bash
# Development: optimized for new classes
composer dump-autoload

# Production: optimized for speed, requires dump when classes change
composer dump-autoload --optimize --no-dev
```

#### 10.4 Class Aliases and Dynamic Class Loading

**Creating Aliases**

`class_alias()` creates runtime aliases for classes:

```php
class_alias(\App\Models\User::class, 'User');

$user = new User(); // Works even without use statement
```

This is useful for backward compatibility or providing short names for deeply nested classes.

**Dynamic Class Loading**

Use variables and strings for dynamic class instantiation:

```php
$type = 'User';
$className = "\\App\\Models\\{$type}";

if (class_exists($className)) {
    $instance = new $className();
}
```

`::class` syntax provides compile-time checked class name resolution:

```php
use App\Models\User;

echo User::class; // 'App\Models\User'

// Works with interfaces and traits too
echo CacheInterface::class; // 'App\Contracts\CacheInterface'
```

---

### Chapter 11: Error and Exception Handling

#### 11.1 Error Levels and Configuration

PHP errors range from notices to fatal errors. Understanding error levels enables proper handling and logging.

**Error Level Constants**

| Level | Description |
|-------|-------------|
| `E_ERROR` | Fatal runtime errors |
| `E_WARNING` | Runtime warnings (non-fatal) |
| `E_PARSE` | Compile-time parse errors |
| `E_NOTICE` | Runtime notices (potential bugs) |
| `E_CORE_ERROR` | Fatal errors during PHP startup |
| `E_CORE_WARNING` | Warnings during PHP startup |
| `E_COMPILE_ERROR` | Fatal compile-time errors |
| `E_COMPILE_WARNING` | Compile-time warnings |
| `E_USER_ERROR` | User-generated error |
| `E_USER_WARNING` | User-generated warning |
| `E_USER_NOTICE` | User-generated notice |
| `E_STRICT` | PHP suggestions for code changes |
| `E_RECOVERABLE_ERROR` | Catchable fatal errors |
| `E_DEPRECATED` | Deprecation notices |
| `E_USER_DEPRECATED` | User-generated deprecation notices |
| `E_ALL` | All errors and warnings |

**Configuring Error Reporting**

```php
// Development: show all errors
error_reporting(E_ALL);
ini_set('display_errors', '1');
ini_set('display_startup_errors', '1');

// Production: log errors, hide from users
error_reporting(E_ALL);
ini_set('display_errors', '0');
ini_set('log_errors', '1');
ini_set('error_log', '/var/log/php/error.log');
```

**Triggering Errors**

```php
trigger_error('This is a notice', E_USER_NOTICE);
trigger_error('This is a warning', E_USER_WARNING);
trigger_error('This is an error', E_USER_ERROR); // Fatal
```

#### 11.2 Custom Error Handlers and Logging

**Custom Error Handler**

```php
set_error_handler(function (
    int $errno,
    string $errstr,
    string $errfile,
    int $errline,
): bool {
    $error = "[{$errno}] {$errstr} in {$errfile}:{$errline}";
    
    // Log all errors
    error_log($error);
    
    // Convert certain errors to exceptions
    if (in_array($errno, [E_ERROR, E_CORE_ERROR, E_COMPILE_ERROR, E_USER_ERROR])) {
        throw new \ErrorException($errstr, 0, $errno, $errfile, $errline);
    }
    
    // Return true to prevent PHP's default error handler
    return true;
});
```

**Exception Handler**

Set a global exception handler for uncaught exceptions:

```php
set_exception_handler(function (\Throwable $exception): void {
    // Log the exception
    error_log((string) $exception);
    
    // Return a user-friendly error response
    http_response_code(500);
    
    if (ini_get('display_errors') === '1') {
        echo "<h1>Error</h1>";
        echo "<pre>{$exception}</pre>";
    } else {
        echo "<h1>An error occurred</h1>";
        echo "<p>Please try again later.</p>";
    }
});
```

**Shutdown Handler for Fatal Errors**

```php
register_shutdown_function(function (): void {
    $error = error_get_last();
    
    if ($error !== null && in_array($error['type'], [E_ERROR, E_PARSE, E_CORE_ERROR, E_COMPILE_ERROR])) {
        // Handle fatal error
        error_log("Fatal error: {$error['message']} in {$error['file']}:{$error['line']}");
        
        while (ob_get_level()) {
            ob_end_clean();
        }
        
        http_response_code(500);
        echo json_encode(['error' => 'Internal server error']);
    }
});
```

#### 11.3 Exceptions, Try-Catch, and Finally Blocks

**Throwing Exceptions**

```php
class InsufficientFundsException extends \RuntimeException
{
    public function __construct(
        private float $balance,
        private float $requested,
    ) {
        $shortfall = $this->requested - $this->balance;
        parent::__construct(
            "Insufficient funds. Balance: {$this->balance}, requested: {$this->requested}, shortfall: {$shortfall}"
        );
    }
    
    public function getBalance(): float
    {
        return $this->balance;
    }
    
    public function getRequested(): float
    {
        return $this->requested;
    }
}

function withdraw(float $amount): void
{
    $balance = getCurrentBalance();
    
    if ($amount > $balance) {
        throw new InsufficientFundsException($balance, $amount);
    }
    
    // Process withdrawal
}
```

**Catching Exceptions**

```php
try {
    withdraw(500);
    echo "Withdrawal successful";
} catch (InsufficientFundsException $e) {
    echo "Cannot withdraw: {$e->getMessage()}";
    echo "Your balance: {$e->getBalance()}";
} catch (\Throwable $e) {
    echo "An unexpected error occurred";
    error_log((string) $e);
}
```

**Catching Multiple Exception Types**

```php
try {
    processOrder($orderId);
} catch (NotFoundException | ValidationException $e) {
    // Handle known user-facing errors
    return response()->error($e->getMessage(), 400);
} catch (PaymentFailedException $e) {
    // Handle payment-specific errors
    return response()->error('Payment failed, please try again', 402);
} catch (\Throwable $e) {
    // Handle unexpected errors
    report($e);
    return response()->error('Internal server error', 500);
}
```

**The `finally` Block**

`finally` executes regardless of whether an exception was thrown:

```php
function processFile(string $path): array
{
    $handle = null;
    
    try {
        $handle = fopen($path, 'r');
        if ($handle === false) {
            throw new \RuntimeException("Could not open file: {$path}");
        }
        
        $data = [];
        while (($row = fgetcsv($handle)) !== false) {
            $data[] = $row;
        }
        
        return $data;
        
    } finally {
        // Always close the file handle
        if ($handle !== null) {
            fclose($handle);
        }
    }
}
```

**Rethrowing Exceptions**

Catch an exception, perform an action, then rethrow:

```php
try {
    sendEmail($recipient, $subject, $body);
} catch (MailException $e) {
    $this->logger->error('Failed to send email', [
        'recipient' => $recipient,
        'error' => $e->getMessage(),
    ]);
    
    if ($this->shouldRetry($e)) {
        $this->queueForRetry($recipient, $subject, $body);
    }
    
    throw $e; // Rethrow for caller to handle
}
```

#### 11.4 Custom Exception Hierarchies

Well-designed exception hierarchies aid in error handling granularity:

```php
// Base application exception
abstract class ApplicationException extends \RuntimeException
{
    abstract public function getHttpStatusCode(): int;
    abstract public function getUserMessage(): string;
}

// Domain-specific exceptions
class UserNotFoundException extends ApplicationException
{
    public function __construct(private int $userId)
    {
        parent::__construct("User {$this->userId} not found");
    }
    
    public function getHttpStatusCode(): int
    {
        return 404;
    }
    
    public function getUserMessage(): string
    {
        return 'The requested user could not be found.';
    }
}

class ValidationException extends ApplicationException
{
    private array $errors;
    
    public function __construct(array $errors)
    {
        $this->errors = $errors;
        parent::__construct('Validation failed: ' . implode(', ', $errors));
    }
    
    public function getHttpStatusCode(): int
    {
        return 422;
    }
    
    public function getUserMessage(): string
    {
        return 'Please correct the following errors.';
    }
    
    public function getErrors(): array
    {
        return $this->errors;
    }
}

class PaymentProcessingException extends ApplicationException
{
    public function __construct(
        string $message,
        private ?string $paymentGatewayError = null,
    ) {
        parent::__construct($message);
    }
    
    public function getHttpStatusCode(): int
    {
        return 402;
    }
    
    public function getUserMessage(): string
    {
        return 'Payment processing failed. Please try again.';
    }
}

// Unified exception handler
function handleApplicationException(ApplicationException $e): void
{
    http_response_code($e->getHttpStatusCode());
    
    echo json_encode([
        'error' => $e->getUserMessage(),
        'details' => $e instanceof ValidationException ? $e->getErrors() : null,
    ]);
}
```

#### 11.5 Throwable Interface and Error Exceptions

**The Throwable Hierarchy**

PHP 7 introduced the `Throwable` interface, unifying exceptions and errors:

```
Throwable
├── Exception
│   ├── RuntimeException
│   ├── LogicException
│   └── ... (user exceptions)
└── Error
    ├── TypeError
    ├── ParseError
    ├── ArithmeticError
    │   └── DivisionByZeroError
    ├── AssertionError
    ├── ValueError (PHP 8.0+)
    └── ... (engine errors)
```

**Catching Throwable**

Catch `Throwable` to handle both exceptions and errors:

```php
try {
    $result = 100 / 0; // DivisionByZeroError
} catch (\Throwable $e) {
    echo get_class($e) . ': ' . $e->getMessage();
    // DivisionByZeroError: Division by zero
}
```

**Converting Errors to Exceptions**

Modern PHP automatically converts many errors to `Error` exceptions. Custom error handlers can convert remaining errors:

```php
set_error_handler(function (int $severity, string $message, string $file, int $line): bool {
    if (!(error_reporting() & $severity)) {
        return true;
    }
    
    throw new \ErrorException($message, 0, $severity, $file, $line);
});
```

**Assertions as Exceptions**

Configure assertions to throw exceptions:

```php
ini_set('assert.exception', '1');
ini_set('zend.assertions', '1'); // Enable in development

try {
    assert($user !== null, 'User must be logged in');
    assert($amount > 0, 'Amount must be positive');
} catch (\AssertionError $e) {
    // Handle assertion failure
}
```

**Best Practices for Exception Handling**

- Throw specific exception types, not generic `\Exception`
- Include contextual data in exceptions (IDs, values, relevant state)
- Never suppress exceptions with empty catch blocks
- Log exceptions at appropriate levels (warning, error, critical)
- Let exceptions propagate to a global handler for consistent formatting
- Use exceptions for exceptional situations, not control flow
- Validate input early and throw before work begins
- Document thrown exceptions in PHPDoc blocks

---

## Part III: Modern PHP 8 Features


### Chapter 12: PHP 8 Type System

#### 12.1 Union Types and Mixed Types

PHP 8.0 revolutionized the type system with union types, allowing parameters and return values to accept multiple types natively. This feature eliminates the need for PHPDoc annotations to express type multiplicity.

**Union Type Syntax**

Union types list multiple types separated by vertical bars (`|`):

```php
class Request
{
    public function getParam(string|int $key, string|int $default = null): string|int|null
    {
        return $this->params[$key] ?? $default;
    }
}

function formatValue(string|int|float|bool $value): string
{
    return match (true) {
        is_bool($value) => $value ? 'yes' : 'no',
        is_int($value) => number_format($value),
        is_float($value) => number_format($value, 2),
        is_string($value) => $value,
    };
}

// Union types in action
$request = new Request();
$id = $request->getParam('id', 0);       // string|int
$slug = $request->getParam('slug', '');   // string|int (despite both being strings)

echo formatValue(42);          // "42"
echo formatValue(3.14159);     // "3.14"
echo formatValue(true);        // "yes"
echo formatValue('PHP 8');     // "PHP 8"
```

**Restrictions on Union Types**

Union types have several constraints that prevent ambiguity and maintain type system soundness:

```php
// Cannot include void
function bad(): void|string {} // Error: void can only be used as a return type

// Cannot include nullable combination
function bad(int|?string $value): void {} // Error: ?string is string|null, duplicating null

// Correct nullable form
function good(int|string|null $value): void {}

// Cannot include false without true in some contexts (PHP 8.2+)
// false can appear on its own or with other types
function find(string $needle): string|false {} // Valid

// Cannot include true without false
// true|string is valid in PHP 8.2+
function isValid(): true|false {} // Valid: equivalent to bool
```

**The `false` Pseudo-Type (PHP 8.2+)**

PHP 8.2 elevated `false` to a standalone type, useful for functions that return `false` on failure:

```php
function strpos(string $haystack, string $needle): int|false
{
    // Returns position or false
}

// Before PHP 8.2, this was expressed as:
// @return int|false
// Now it's enforced by the engine
```

**The `true` Type (PHP 8.2+)**

`true` can appear in union types, though it's most commonly used with `false` to represent booleans:

```php
function validateEmail(string $email): true|string
{
    if (filter_var($email, FILTER_VALIDATE_EMAIL)) {
        return true;
    }
    return 'Invalid email format';
}

$result = validateEmail('alice@example.com');
if ($result === true) {
    echo "Valid!";
} else {
    echo "Error: {$result}";
}
```

**The `mixed` Type**

`mixed` represents every possible type: `array|bool|callable|int|float|null|object|resource|string`. It's the implicit type for untyped parameters:

```php
function logDebug(mixed $value): void
{
    var_dump($value);
}

logDebug('Hello');
logDebug(42);
logDebug(['key' => 'value']);
logDebug(null);
logDebug(new stdClass());
```

Use `mixed` when:
- A function truly accepts any type
- Implementing a generic container or proxy
- Passing through values without inspection
- Interfacing with legacy code that lacks type information

Avoid `mixed` where more specific types apply. It's the entry point to stronger typing, not a substitute for it.

**Null and Union Types**

When `null` appears in a union type, the type becomes nullable. The `?Type` syntax is syntactic sugar for `Type|null`:

```php
// These are equivalent
function findUser(int $id): ?User {}
function findUser(int $id): User|null {}

// Nullable union types
function process(string|int|null $input): array|int|null {}
```

**Type Narrowing with Union Types**

Union types require runtime type checking before using type-specific operations:

```php
function processValue(string|int|array $value): string
{
    if (is_string($value)) {
        return strtoupper($value); // PHP knows $value is string here
    }
    
    if (is_int($value)) {
        return number_format($value); // $value is int
    }
    
    // $value is array
    return implode(', ', $value);
}

// Match expression with type narrowing
function handle(mixed $data): string
{
    return match (true) {
        is_string($data) => "String: {$data}",
        is_int($data) => 'Integer: ' . $data,
        is_array($data) => 'Array with ' . count($data) . ' items',
        $data instanceof Stringable => (string) $data,
        default => 'Unknown type: ' . gettype($data),
    };
}
```

**Union Types in Interfaces and Inheritance**

Union types must maintain compatibility with parent type declarations:

```php
interface Repository
{
    public function find(int|string $id): object|null;
}

class UserRepository implements Repository
{
    // Valid: narrower return type
    public function find(int|string $id): User|null
    {
        return User::find($id);
    }
}

class StrictRepository implements Repository
{
    // Valid: parameter type can be wider (int only)
    public function find(int|string $id): User|null
    {
        return User::find((int) $id);
    }
}
```

#### 12.2 Nullable Types and Static Return Type

**Nullable Types in Depth**

Nullable types explicitly permit null values alongside a primary type:

```php
class UserProfile
{
    private ?string $bio = null;
    private ?DateTimeImmutable $birthday = null;
    private ?Address $address = null;
    
    public function getBio(): ?string
    {
        return $this->bio;
    }
    
    public function setBirthday(string|DateTimeInterface|null $birthday): void
    {
        if ($birthday === null) {
            $this->birthday = null;
        } elseif (is_string($birthday)) {
            $this->birthday = new DateTimeImmutable($birthday);
        } else {
            $this->birthday = DateTimeImmutable::createFromInterface($birthday);
        }
    }
}
```

Nullable types express optionality semantically—a null bio means "no bio provided," which is different from an empty string bio.

**The Static Return Type**

The `static` return type preserves the calling class in inheritance chains, enabling fluent interfaces and correct type inference:

```php
class Model
{
    protected static string $table;
    
    public static function query(): static
    {
        return new static();
    }
    
    public static function find(int $id): ?static
    {
        // Returns instance of the class that called find(), not necessarily Model
        $data = fetchById(static::$table, $id);
        return $data ? new static($data) : null;
    }
    
    public function save(): static
    {
        // Save to database...
        return $this;
    }
}

class User extends Model
{
    protected static string $table = 'users';
    
    public function roles(): array
    {
        // User-specific method
        return Role::findByUser($this->id);
    }
}

class Post extends Model
{
    protected static string $table = 'posts';
}

$user = User::find(1); // Type is ?User, not ?Model
$user?->roles();        // Available without type casting

$post = Post::find(1);  // Type is ?Post
// $post->roles();      // Error: Post doesn't have roles()

// Fluent interface with static return
$user = (new User())
    ->fill(['name' => 'Alice'])
    ->save();
```

**Static vs. Self Return Types**

```php
abstract class Entity
{
    // self always returns Entity instances
    public static function createSelf(): self
    {
        return new self(); // Error if class is abstract
    }
    
    // static returns the called class instances
    public static function createStatic(): static
    {
        return new static(); // Returns User for User::createStatic()
    }
}

class User extends Entity {}

$user = User::createStatic(); // Type: User (correct)
// $user = User::createSelf(); // Would return Entity, but Entity is abstract
```

The distinction becomes crucial when extending classes and expecting calls to return the extended type.

#### 12.3 `never` Return Type

The `never` return type, introduced in PHP 8.1, declares that a function never returns normally. It either throws an exception or terminates script execution.

**Declaring `never` Functions**

```php
function redirect(string $url, int $code = 302): never
{
    header("Location: {$url}", true, $code);
    exit();
}

function abort(int $code, string $message = ''): never
{
    http_response_code($code);
    if ($message) {
        echo $message;
    }
    exit();
}

function throwNotFound(string $entity, int|string $id): never
{
    throw new NotFoundException("{$entity} with ID {$id} not found");
}

function unreachable(): never
{
    throw new \LogicException('This code should never be reached');
}
```

**`never` in Control Flow**

The type system understands that `never` functions terminate the current branch:

```php
function getUser(int $id): User
{
    $user = User::find($id);
    
    if ($user === null) {
        abort(404, 'User not found');
        // PHP understands execution never continues past here
    }
    
    // Type system knows $user is User (not User|null)
    return $user;
}

function processValue(string|int $value): string
{
    if (is_string($value)) {
        return $value;
    }
    
    if (is_int($value)) {
        return (string) $value;
    }
    
    // Type system knows this is unreachable
    throw new \RuntimeException('Unexpected type');
}
```

**`never` vs. `void`**

| Aspect | `void` | `never` |
|--------|--------|---------|
| Execution | Function returns | Function never returns |
| Return statement | `return;` allowed | No return statement allowed |
| After function call | Execution continues | Execution stops at call |
| Use case | Side-effect functions | Termination functions |
| Example | `setName(): void` | `throwError(): never` |

```php
// void: function completes normally
function logMessage(string $message): void
{
    file_put_contents('/var/log/app.log', $message . "\n");
    // Implicitly returns null
}

// never: function terminates the script
function fatalError(string $message): never
{
    error_log("FATAL: {$message}");
    exit(1);
}

// Usage difference
function process(mixed $data): string
{
    if ($data === null) {
        logMessage('Null data received');     // Execution continues
        return '';                             // Must still return
    }
    
    if (!is_string($data)) {
        fatalError('Invalid data type');      // Execution stops here
        // No need to return — the type system understands
    }
    
    return $data;
}
```

#### 12.4 Type Inference and Variance

**Type Inference in PHP**

PHP's type inference is limited compared to fully statically typed languages, but the engine infers types in several contexts:

```php
// Arrow functions infer return types
$add = fn(int $a, int $b) => $a + $b; // Return type inferred as int

// Closure inference
$filter = fn(array $items, callable $callback) => array_filter($items, $callback);

// Property inference with constructor promotion
class User
{
    public function __construct(
        private string $name,     // Type declared
        private \DateTimeImmutable $createdAt = new \DateTimeImmutable(), // Type declared
    ) {}
}

// PHP 8.3 improved inference in match expressions
$result = match ($status) {
    Status::Active => 1,
    Status::Inactive => 0,
    default => -1,
}; // Type inferred as int
```

**Covariance (Return Types)**

Covariance allows overriding methods to return more specific types than their parent:

```php
interface Factory
{
    public function create(): object;
}

class UserFactory implements Factory
{
    // Covariant: User is more specific than object
    public function create(): User
    {
        return new User();
    }
}

class AdminUserFactory extends UserFactory
{
    // Further covariant: AdminUser is more specific than User
    public function create(): AdminUser
    {
        return new AdminUser();
    }
}

// Union type covariance (contravariant narrowing)
interface Repository
{
    public function find(int $id): User|null|false;
}

class CachedUserRepository implements Repository
{
    public function find(int $id): User|null
    {
        // Cached version never returns false
        return $this->cache->get("user:{$id}");
    }
}
```

**Contravariance (Parameter Types)**

Contravariance allows overriding methods to accept wider parameter types:

```php
interface Consumer
{
    public function consume(User $user): void;
}

class GenericConsumer implements Consumer
{
    // Contravariant: object is wider than User
    public function consume(object $user): void
    {
        if ($user instanceof User) {
            // Handle User specifically
        } else {
            // Handle other objects
        }
    }
}

// Contravariance in callable types
class EventDispatcher
{
    private array $listeners = [];
    
    public function addListener(string $event, callable $listener): void
    {
        $this->listeners[$event][] = $listener;
    }
}
```

**Type Variance Rules Summary**

| Aspect | Covariance | Contravariance | Invariance |
|--------|------------|----------------|------------|
| Return types | ✓ Allowed | ✗ Not allowed | Child must match parent |
| Parameter types | ✗ Not allowed | ✓ Allowed (narrower→wider) | Child must match parent |
| Property types | ✗ Invariant | ✗ Invariant | Must match |

**Practical Variance Examples**

```php
// Example 1: Collection type safety
class Collection
{
    public function filter(callable $callback): self
    {
        return new static(array_filter($this->items, $callback));
    }
}

class UserCollection extends Collection
{
    // Can return UserCollection instead of Collection
    public function filter(callable $callback): self
    {
        return parent::filter($callback); // static returns UserCollection
    }
}

// Example 2: Event handling with variance
abstract class Event {}
class UserRegisteredEvent extends Event {}
class OrderPlacedEvent extends Event {}

interface EventHandler
{
    public function handle(Event $event): void;
}

class UserHandler implements EventHandler
{
    public function handle(Event $event): void
    {
        if ($event instanceof UserRegisteredEvent) {
            $this->sendWelcomeEmail($event);
        }
    }
}
```

---

### Chapter 13: Syntax and Developer Experience

#### 13.1 Named Arguments and Reordering Parameters

Named arguments are one of PHP 8.0's most impactful features, transforming how developers call functions and methods.

**Basic Named Arguments**

```php
function sendEmail(
    string $to,
    string $subject,
    string $body,
    string $cc = '',
    string $bcc = '',
    bool $isHtml = false,
    int $priority = 3,
    array $attachments = [],
): void {
    // Implementation
}

// Traditional: must maintain order, harder to read
sendEmail(
    'alice@example.com',
    'Welcome!',
    'Thank you for registering',
    '',
    '',
    true,
    1,
    []
);

// Named arguments: order-independent, self-documenting
sendEmail(
    to: 'alice@example.com',
    subject: 'Welcome!',
    body: '<h1>Welcome!</h1><p>Thank you for registering.</p>',
    isHtml: true,
    priority: 1,
);
```

**Mixing Positional and Named Arguments**

Positional arguments must precede named arguments:

```php
// Valid: positional then named
sendEmail(
    'alice@example.com',           // $to (positional)
    'Welcome!',                      // $subject (positional)
    body: 'Welcome to our platform', // $body (named)
    isHtml: false,
);

// Invalid: named before positional
sendEmail(
    to: 'alice@example.com',
    'Welcome!',                     // Error: positional after named
    body: 'Welcome!',
);
```

**Skipping Optional Parameters**

Named arguments eliminate the need to pass default values for intermediate optional parameters:

```php
function createUser(
    string $name,
    string $email,
    ?string $phone = null,
    ?string $address = null,
    ?string $city = null,
    ?string $country = null,
    bool $newsletter = false,
): User {
    // Implementation
}

// Skip directly to the parameter we care about
$user = createUser(
    name: 'Alice',
    email: 'alice@example.com',
    newsletter: true,
    // phone, address, city, country all use defaults
);
```

**Named Arguments and Inheritance**

Renaming parameters becomes a breaking change when callers use named arguments:

```php
class BaseController
{
    public function respond(array $data, int $statusCode = 200): Response
    {
        return new Response($data, $statusCode);
    }
}

// Caller using named argument
$controller->respond(data: ['ok' => true], statusCode: 201);

// If the author renames $statusCode to $code:
// public function respond(array $data, int $code = 200): Response
// All callers using statusCode: would break!
```

This creates a new semantic versioning consideration. Library authors should treat parameter names as part of their public API when releasing versions that might be used with named arguments.

**Spread Operator with Named Arguments**

The spread operator works with named arguments to forward calls:

```php
function proxy(string $message, ...$args): void
{
    doSomethingElse(message: $message, ...$args);
}

proxy(message: 'Test', priority: 1, source: 'cli');
// Equivalent to: doSomethingElse(message: 'Test', priority: 1, source: 'cli')
```

**Named Arguments in Frameworks**

Frameworks have embraced named arguments for improved controller and service method signatures:

```php
// Laravel controller
class OrderController
{
    public function index(
        #[Inject] OrderRepository $orders,
        int $page = 1,
        int $perPage = 20,
        string $sort = 'created_at',
        string $direction = 'desc',
        ?string $status = null,
    ): View {
        return view('orders.index', [
            'orders' => $orders->paginate(
                page: $page,
                perPage: $perPage,
                sort: $sort,
                direction: $direction,
                status: $status,
            ),
        ]);
    }
}
```

#### 13.2 Match Expressions vs. Switch

The match expression addresses decades of criticism about the `switch` statement while providing a more powerful and safer alternative.

**Strict Comparison**

`switch` uses loose comparison (`==`), while `match` uses strict comparison (`===`):

```php
$value = 0;

// Switch: loose comparison — surprising results
switch ($value) {
    case 'zero':
        $result = 'zero'; break;    // 'zero' == 0? No
    case false:
        $result = 'false'; break;   // false == 0? Yes! $result = 'false'
    case null:
        $result = 'null'; break;    // null == 0? Yes!
    default:
        $result = 'default';
}
echo $result; // 'false' — unexpected for $value = 0

// Match: strict comparison — predictable
$result = match ($value) {
    'zero' => 'zero',  // 'zero' !== 0, no match
    false => 'false',  // false !== 0, no match
    null => 'null',    // null !== 0, no match
    0 => 'zero',       // 0 === 0, match!
    default => 'default',
};
echo $result; // 'zero'
```

**Return Value**

`match` is an expression that returns a value, eliminating the need for temporary variables and `break`:

```php
// Switch requires assignment in each case
$grade = '';
switch (true) {
    case $score >= 90:
        $grade = 'A';
        break;
    case $score >= 80:
        $grade = 'B';
        break;
    case $score >= 70:
        $grade = 'C';
        break;
    default:
        $grade = 'F';
}

// Match returns directly
$grade = match (true) {
    $score >= 90 => 'A',
    $score >= 80 => 'B',
    $score >= 70 => 'C',
    default => 'F',
};
```

**No Fallthrough by Default**

`match` arms are single expressions, eliminating fallthrough bugs:

```php
// Switch fallthrough bug
switch ($status) {
    case 'pending':
        sendNotification(); // Forgot break! Falls through to draft
    case 'draft':
        save();
        break;
}

// Match arms are independent — no fallthrough
match ($status) {
    'pending' => sendNotification(),  // Only executes for pending
    'draft' => save(),                // Only executes for draft
};
```

**Exhaustiveness Checking**

`match` throws `UnhandledMatchError` if no case matches and there's no default. This catches unhandled cases early:

```php
enum Status
{
    case Active;
    case Inactive;
    case Suspended;
}

function getLabel(Status $status): string
{
    return match ($status) {
        Status::Active => 'Active',
        Status::Inactive => 'Inactive',
        // Forgot Status::Suspended — but PHP will catch it!
    };
}

// If Status::Suspended is passed, UnhandledMatchError is thrown
```

This is particularly powerful with enums, ensuring all cases are handled.

**Conditions in Match Arms**

Match arms can use complex conditions when matching on `true`:

```php
$message = match (true) {
    $age < 13 => 'Child',
    $age >= 13 && $age < 18 => 'Teenager',
    $age >= 18 && $age < 65 => 'Adult',
    $age >= 65 => 'Senior',
};

$tax = match (true) {
    $income <= 11000 => $income * 0.10,
    $income <= 44725 => $income * 0.12,
    $income <= 95375 => $income * 0.22,
    default => $income * 0.24,
};
```

**Multiple Values per Arm**

Combine multiple conditions in a single arm:

```php
$category = match ($statusCode) {
    200, 201, 204 => 'Success',
    301, 302, 307, 308 => 'Redirect',
    400, 401, 403, 404 => 'Client Error',
    500, 502, 503, 504 => 'Server Error',
    default => 'Unknown',
};

$weekend = match ($day) {
    'Saturday', 'Sunday' => true,
    default => false,
};
```

**Complex Right-Hand Expressions**

Match arms can contain any expression, including closures and function calls:

```php
$action = match ($command) {
    'create' => fn(array $data) => $this->create($data),
    'update' => fn(array $data) => $this->update($data['id'], $data),
    'delete' => fn(array $data) => $this->delete($data['id']),
    default => throw new InvalidArgumentException("Unknown command: {$command}"),
};

$result = $action($inputData);

// Match for routing
$handler = match ($request->getMethod()) {
    'GET' => $this->getHandler,
    'POST' => function () use ($request) {
        $this->validateCsrf($request);
        return $this->postHandler($request);
    },
    'PUT', 'PATCH' => function () use ($request) {
        $this->validateCsrf($request);
        return $this->putHandler($request);
    },
    'DELETE' => function () use ($request) {
        $this->validateCsrf($request);
        return $this->deleteHandler($request);
    },
};
```

#### 13.3 Nullsafe Operator (`?->`)

The nullsafe operator eliminates null-check boilerplate when navigating object hierarchies.

**The Problem: Null Check Pyramids**

```php
// Without nullsafe operator — the pyramid of doom
function getCustomerCity(?Order $order): ?string
{
    if ($order !== null) {
        $customer = $order->getCustomer();
        if ($customer !== null) {
            $address = $customer->getAddress();
            if ($address !== null) {
                return $address->getCity();
            }
        }
    }
    return null;
}

// Ternary nightmare (hard to read)
function getCustomerCity(?Order $order): ?string
{
    return $order ?
        ($order->getCustomer() ?
            ($order->getCustomer()->getAddress() ?
                $order->getCustomer()->getAddress()->getCity() :
                null) :
            null) :
        null;
}
```

**The Solution: Nullsafe Operator**

```php
function getCustomerCity(?Order $order): ?string
{
    return $order?->getCustomer()?->getAddress()?->getCity();
}

// Short-circuits to null if any link is null
// If $order is null, returns null immediately
// If getCustomer() returns null, returns null immediately
// If getAddress() returns null, returns null immediately
```

**How It Works**

The nullsafe operator short-circuits property access and method calls. When the left side evaluates to `null`, the entire chain evaluates to `null`:

```php
$result = $user?->getProfile()?->getSettings()?->get('theme');
// Equivalent to:
if ($user === null) {
    $result = null;
} else {
    $profile = $user->getProfile();
    if ($profile === null) {
        $result = null;
    } else {
        $settings = $profile->getSettings();
        if ($settings === null) {
            $result = null;
        } else {
            $result = $settings->get('theme');
        }
    }
}
```

**Nullsafe in Various Contexts**

```php
// Method calls
$length = $user?->getName()?->length();

// Property access
$color = $theme?->colors?->primary;

// Array access combined with nullsafe
$first = $user?->getTags()[0] ?? null; // Array access after nullsafe

// Method calls with arguments
$formatted = $user?->formatName(style: 'full');

// Writing (left side of assignment)
// $user?->name = 'Alice'; // NOT supported — nullsafe only for reading

// Nested with regular method chains
$result = $repository?->findById(1)?->getRelated()?->first();
```

**Combining Nullsafe with Null Coalescing**

```php
// Nullsafe chain with default value
$city = $order?->getCustomer()?->getAddress()?->getCity() ?? 'Unknown City';

// The ?? catches null from the nullsafe operator
// If any link returns null, 'Unknown City' is used

// Partial nullsafe with explicit boundaries
$country = $order?->getCustomer()?->getCountry();
$address = $order?->getCustomer()?->getAddress();

if ($address !== null) {
    // After null check, regular methods are fine
    $street = $address->getStreet();
    $zip = $address->getZipCode();
}
```

**Best Practices**

```php
// Good: Clear chain with obvious null propagation
$timezone = $request->getUser()?->getPreferences()?->getTimezone() ?? 'UTC';

// Bad: Overly long chains that hide complexity
$result = $a?->b()?->c()?->d()?->e()?->f(); // Too many things could be null

// Better: Break into meaningful intermediate steps
$user = $request->getUser();
$prefs = $user?->getPreferences();
$timezone = $prefs?->getTimezone() ?? 'UTC';

// Good: Nullsafe for optional relationships
$company = $employee?->getDepartment()?->getCompany();

// Bad: Nullsafe masking a code smell (Law of Demeter violation)
// Consider adding a convenience method instead
class Employee
{
    public function getCompanyName(): ?string
    {
        return $this->getDepartment()?->getCompany()?->getName();
    }
}
```

**Performance Characteristics**

The nullsafe operator has minimal overhead:

```php
// These have essentially identical performance
$result = $obj?->method();
$result = $obj !== null ? $obj->method() : null;

// The nullsafe operator is purely syntactic sugar
// compiled to equivalent null-check jumps
```

#### 13.4 Attributes (Annotations) and Reflection

Attributes provide native, structured metadata for PHP code, replacing PHPDoc annotations.

**Defining Attributes**

Create an attribute by marking a class with the `#[Attribute]` attribute:

```php
#[Attribute(Attribute::TARGET_CLASS | Attribute::TARGET_METHOD)]
class Route
{
    public function __construct(
        public string $path,
        public string $name = '',
        public array $methods = ['GET'],
        public array $middleware = [],
    ) {}
}

#[Attribute(Attribute::TARGET_PROPERTY)]
class Column
{
    public function __construct(
        public string $name,
        public string $type = 'string',
        public bool $nullable = false,
        public ?int $length = null,
    ) {}
}

#[Attribute(Attribute::TARGET_METHOD | Attribute::TARGET_FUNCTION)]
class RequireAuth
{
    public function __construct(
        public array $roles = [],
        public string $permission = '',
    ) {}
}
```

**Applying Attributes**

Attributes use the `#[...]` syntax:

```php
#[Route('/api/users', name: 'users.index', methods: ['GET'])]
class UserController
{
    #[Route('/api/users/{id}', name: 'users.show', methods: ['GET'])]
    #[RequireAuth(roles: ['admin', 'user'])]
    public function show(int $id): array
    {
        return User::findOrFail($id)->toArray();
    }
    
    #[Route('/api/users', name: 'users.store', methods: ['POST'])]
    #[RequireAuth(permission: 'create_users')]
    public function store(#[Body] CreateUserRequest $request): array
    {
        $user = User::create($request->validated());
        return $user->toArray();
    }
}
```

**Reading Attributes with Reflection**

```php
class RouteCollector
{
    public function collectRoutes(object $controller): array
    {
        $reflection = new ReflectionClass($controller);
        $routes = [];
        
        // Read class-level attributes
        $classAttributes = $reflection->getAttributes(Route::class);
        foreach ($classAttributes as $attribute) {
            $classRoute = $attribute->newInstance();
            // Use classRoute->path, classRoute->middleware, etc.
        }
        
        // Read method-level attributes
        foreach ($reflection->getMethods() as $method) {
            $methodAttributes = $method->getAttributes(Route::class);
            
            foreach ($methodAttributes as $attribute) {
                $route = $attribute->newInstance();
                $routes[] = [
                    'path' => $route->path,
                    'method' => $method->getName(),
                    'http_methods' => $route->methods,
                    'middleware' => $route->middleware,
                ];
            }
        }
        
        return $routes;
    }
}

// Using the collector
$collector = new RouteCollector();
$routes = $collector->collectRoutes(new UserController());
```

**Attribute Inheritance and REPEATABLE**

```php
#[Attribute(Attribute::TARGET_CLASS | Attribute::IS_REPEATABLE)]
class Tag
{
    public function __construct(public string $name) {}
}

#[Tag('important')]
#[Tag('documented')]
#[Tag('version-2.0')]
class ImportantService {}

// Read repeated attributes
$reflection = new ReflectionClass(ImportantService::class);
$tags = $reflection->getAttributes(Tag::class);

foreach ($tags as $tagAttribute) {
    $tag = $tagAttribute->newInstance();
    echo $tag->name . "\n"; // 'important', 'documented', 'version-2.0'
}
```

**Parameter Attributes**

Attributes can be applied to function parameters:

```php
#[Attribute(Attribute::TARGET_PARAMETER)]
class Inject
{
    public function __construct(public string $service = '') {}
}

#[Attribute(Attribute::TARGET_PARAMETER)]
class FromHeader
{
    public function __construct(public string $name) {}
}

class ApiController
{
    public function updateUser(
        #[FromHeader('X-User-Id')] int $userId,
        #[Inject] UserService $userService,
        array $data,
    ): Response {
        // $userId extracted from X-User-Id header
        // $userService injected automatically
        // $data from request body
    }
}

// Reading parameter attributes
$method = new ReflectionMethod(ApiController::class, 'updateUser');
foreach ($method->getParameters() as $parameter) {
    $injectAttributes = $parameter->getAttributes(Inject::class);
    if (count($injectAttributes) > 0) {
        $service = $injectAttributes[0]->newInstance()->service;
        // Resolve and inject the service
    }
}
```

**Conditional Attribute Checking**

```php
function isAuthenticated(ReflectionMethod $method): bool
{
    return count($method->getAttributes(RequireAuth::class)) > 0;
}

function getRequiredRole(ReflectionMethod $method): ?string
{
    $attrs = $method->getAttributes(RequireAuth::class);
    if (count($attrs) === 0) {
        return null;
    }
    return $attrs[0]->newInstance()->roles[0] ?? null;
}

// Checking multiple attribute types
$attributes = $method->getAttributes();
foreach ($attributes as $attribute) {
    match ($attribute->getName()) {
        RequireAuth::class => handleAuth($attribute->newInstance()),
        Throttle::class => applyThrottle($attribute->newInstance()),
        Cache::class => configureCaching($attribute->newInstance()),
        default => null,
    };
}
```

#### 13.5 Fibers and Cooperative Multitasking

Fibers, introduced in PHP 8.1, provide low-level cooperative multitasking, enabling asynchronous-style code without extensions like Swoole.

**Understanding Fibers**

A Fiber is a code block that can be suspended and resumed, similar to a generator but for general computation:

```php
$fiber = new Fiber(function (): void {
    echo "Fiber started\n";
    
    Fiber::suspend('Suspension point 1');
    
    echo "Fiber resumed\n";
    
    Fiber::suspend('Suspension point 2');
    
    echo "Fiber completed\n";
});

echo "Starting fiber\n";
$value = $fiber->start('Start value');
echo "Suspended with: {$value}\n";

$value = $fiber->resume('Resume value 1');
echo "Suspended with: {$value}\n";

$value = $fiber->resume('Resume value 2');
echo "Returned: {$value}\n";
```

**Fiber States**

A Fiber can be in one of several states:

```php
$fiber = new Fiber(function (): void {
    Fiber::suspend();
});

echo "Before start: ";
echo $fiber->isStarted() ? 'started' : 'not started'; // not started
echo $fiber->isSuspended() ? 'suspended' : 'not suspended'; // not suspended

$fiber->start();

echo "After suspend: ";
echo $fiber->isStarted() ? 'started' : 'not started'; // started
echo $fiber->isSuspended() ? 'suspended' : 'not suspended'; // suspended

$fiber->resume();

echo "After completion: ";
echo $fiber->isTerminated() ? 'terminated' : 'not terminated'; // terminated
```

**Practical Fiber Example: Non-Blocking HTTP**

```php
class AsyncHttpClient
{
    private array $handles = [];
    private array $fibers = [];
    
    public function request(string $url, array $options = []): mixed
    {
        $fiber = Fiber::getCurrent();
        
        if ($fiber === null) {
            throw new \RuntimeException('Must be called within a Fiber');
        }
        
        $ch = curl_init($url);
        curl_setopt_array($ch, $options + [
            CURLOPT_RETURNTRANSFER => true,
            CURLOPT_HEADER => false,
        ]);
        
        $multiHandle = $this->getMultiHandle();
        curl_multi_add_handle($multiHandle, $ch);
        
        $this->handles[(int) $ch] = $ch;
        $this->fibers[(int) $ch] = $fiber;
        
        Fiber::suspend();
        
        // Resumed after curl completes
        $result = curl_multi_getcontent($ch);
        curl_multi_remove_handle($multiHandle, $ch);
        curl_close($ch);
        
        return $result;
    }
    
    public function run(): void
    {
        $multiHandle = curl_multi_init();
        
        do {
            $status = curl_multi_exec($multiHandle, $active);
            
            if ($active) {
                curl_multi_select($multiHandle);
            }
            
            // Check for completed transfers
            while ($info = curl_multi_info_read($multiHandle)) {
                $handleId = (int) $info['handle'];
                
                if (isset($this->fibers[$handleId])) {
                    $fiber = $this->fibers[$handleId];
                    unset($this->fibers[$handleId], $this->handles[$handleId]);
                    
                    if ($fiber->isSuspended()) {
                        $fiber->resume();
                    }
                }
            }
        } while ($active);
        
        curl_multi_close($multiHandle);
    }
}

// Usage
$client = new AsyncHttpClient();

$results = [];

$fiber1 = new Fiber(function () use ($client, &$results): void {
    $results['api1'] = $client->request('https://api.example.com/endpoint1');
});

$fiber2 = new Fiber(function () use ($client, &$results): void {
    $results['api2'] = $client->request('https://api.example.com/endpoint2');
});

$fiber1->start();
$fiber2->start();
$client->run(); // Both requests complete concurrently

print_r($results);
```

**Fiber Error Handling**

Exceptions can cross Fiber boundaries:

```php
$fiber = new Fiber(function (): void {
    try {
        Fiber::suspend();
    } catch (\Exception $e) {
        echo "Caught in fiber: {$e->getMessage()}\n";
    }
});

$fiber->start();

try {
    $fiber->throw(new \Exception('Test exception'));
} catch (\Exception $e) {
    // Not caught here — handled inside the fiber
}

// If the fiber itself throws
$fiber2 = new Fiber(function (): never {
    throw new \RuntimeException('Fiber error');
});

try {
    $fiber2->start();
} catch (\RuntimeException $e) {
    echo "Caught outside: {$e->getMessage()}\n";
}
```

**Fibers vs. Generators**

| Feature | Generators | Fibers |
|---------|-----------|--------|
| Purpose | Data iteration | General suspension |
| Yield values | Iterable sequence | Arbitrary values |
| Receive values | Via `send()` | Via `resume()` |
| Call stack | Paused at yield | Paused anywhere |
| Use case | Lazy collections | Cooperative multitasking |
| Reusability | Forward-only | Can suspend/resume multiple times |

**Limitations and Best Practices**

Fibers cannot be used from the main thread — they must be started from a Fiber context for nested fiber suspension:

```php
// This works
$fiber = new Fiber(function (): void {
    echo "In fiber\n";
    Fiber::suspend();
    echo "After suspend\n";
});
$fiber->start();
$fiber->resume();

// This doesn't work — cannot suspend main script
// Fiber::suspend(); // Error: Cannot suspend outside of a fiber
```

Best practices:
- Use Fibers for I/O-bound operations, not CPU-bound work
- Consider higher-level libraries like ReactPHP or AMPHP instead of raw Fibers
- Ensure proper error handling — exceptions can cross fiber boundaries
- Avoid shared mutable state between fibers without synchronization
- Use Fibers for framework internals rather than application code

---

### Chapter 14: Performance and JIT

#### 14.1 Understanding the JIT Compiler

The Just-In-Time compiler transforms PHP opcodes into native machine code at runtime, potentially delivering significant performance improvements for CPU-intensive workloads.

**How PHP Execution Works**

Traditional PHP execution follows a multi-stage pipeline:

```
Source Code → Lexing → Parsing → AST → Opcodes → VM Interpretation
```

1. **Lexing**: Converts PHP source into tokens
2. **Parsing**: Converts tokens into an Abstract Syntax Tree
3. **Compilation**: Converts AST into opcodes (instructions for the Zend VM)
4. **Opcode Cache (Opcache)**: Stores compiled opcodes across requests
5. **VM Execution**: The Zend Virtual Machine executes opcodes sequentially

The JIT adds a sixth optional stage:

```
... → Opcodes → JIT Tracing → Native Machine Code → CPU Execution
```

**How the PHP 8 JIT Works**

The JIT uses a tracing approach rather than compiling entire functions or methods upfront:

1. **Profiling**: The JIT monitors execution through opcache, identifying hot code paths
2. **Trace Selection**: When a loop or frequently called function reaches a threshold, the JIT selects the sequence of opcodes as a trace
3. **Compilation**: The trace is compiled to native machine code using the DynASM library
4. **Optimization**: The compiled trace is optimized through constant folding, dead code elimination, and register allocation
5. **Execution**: Subsequent executions of the same code path use the native code instead of VM interpretation
6. **Side Exits**: If runtime conditions change (type changes, branches not taken), execution falls back to the VM

**What JIT Excels At**

JIT provides the most benefit for:

```php
// CPU-intensive numerical computation
function mandelbrot(float $cx, float $cy, int $maxIterations = 100): int
{
    $x = 0.0;
    $y = 0.0;
    $iteration = 0;
    
    while ($x * $x + $y * $y <= 4 && $iteration < $maxIterations) {
        $xtemp = $x * $x - $y * $y + $cx;
        $y = 2 * $x * $y + $cy;
        $x = $xtemp;
        $iteration++;
    }
    
    return $iteration;
}

// Image processing
function applyFilter(GdImage $image, array $matrix): GdImage
{
    $width = imagesx($image);
    $height = imagesy($image);
    $result = imagecreatetruecolor($width, $height);
    
    for ($x = 0; $x < $width; $x++) {
        for ($y = 0; $y < $height; $y++) {
            $pixel = convolve($image, $x, $y, $matrix);
            imagesetpixel($result, $x, $y, $pixel);
        }
    }
    
    return $result;
}

// Data processing with repeated operations
function calculateStatistics(array $samples): array
{
    $sum = 0;
    $sumSquared = 0;
    $count = 0;
    
    foreach ($samples as $value) {
        $sum += $value;
        $sumSquared += $value * $value;
        $count++;
    }
    
    $mean = $sum / $count;
    $variance = ($sumSquared / $count) - ($mean * $mean);
    
    return [
        'mean' => $mean,
        'stddev' => sqrt($variance),
        'count' => $count,
    ];
}
```

**What JIT Doesn't Help Much**

Typical web applications are primarily I/O-bound:

```php
// Database query — I/O bound, JIT has minimal impact
function getUsers(): array
{
    $stmt = Database::query('SELECT * FROM users');
    return $stmt->fetchAll();
}

// HTTP request — I/O bound
function fetchFromApi(string $url): array
{
    return json_decode(file_get_contents($url), true);
}

// Template rendering — mostly string operations, not CPU-intensive
function renderTemplate(string $template, array $data): string
{
    extract($data);
    ob_start();
    include $template;
    return ob_get_clean();
}
```

#### 14.2 Opcache Configuration and Tuning

Opcache provides the most significant performance improvement for PHP applications, with or without JIT.

**Understanding Opcache**

Opcache stores compiled opcodes in shared memory, eliminating parsing and compilation overhead:

```php
// Without Opcache (simplified):
// 1. Read PHP file from disk
// 2. Parse PHP source to tokens
// 3. Build Abstract Syntax Tree
// 4. Compile to opcodes
// 5. Execute opcodes
//
// With Opcache:
// 1. Check shared memory for cached opcodes
// 2. Execute cached opcodes (steps 1-4 skipped)
```

**Essential Opcache Configuration**

```ini
; /etc/php/8.3/fpm/conf.d/opcache.ini

; Enable opcache
opcache.enable=1

; Enable for CLI (development/debugging)
opcache.enable_cli=0

; Shared memory storage size (in megabytes)
; Increase for large applications with many files
opcache.memory_consumption=256

; Maximum number of cached scripts
; PHP 8 recommends at least 10000 for medium applications
opcache.max_accelerated_files=20000

; Percentage of wasted memory before restart
opcache.max_wasted_percentage=10

; Validate timestamps — check for file changes
; Enable in development, disable in production
opcache.validate_timestamps=1

; How often to check for file changes (in seconds)
; 0 means check on every request (development)
opcache.revalidate_freq=2

; Enable file-based cache fallback
opcache.file_cache=/var/cache/opcache

; Don't verify file paths when loading from cache
opcache.file_cache_only=0

; Interned strings buffer (in megabytes)
; PHP 8 benefits from larger values
opcache.interned_strings_buffer=32

; Use current working directory for cache key prefix
; Useful for hosting multiple applications
opcache.use_cwd=1

; Enable fast shutdown
opcache.fast_shutdown=1
```

**Production Opcache Configuration**

```ini
; Production — maximum performance
opcache.enable=1
opcache.memory_consumption=512
opcache.max_accelerated_files=50000
opcache.max_wasted_percentage=5
opcache.validate_timestamps=0        ; Never check timestamps
opcache.revalidate_freq=0
opcache.interned_strings_buffer=64
opcache.fast_shutdown=1
opcache.enable_file_override=1
opcache.huge_code_pages=1            ; Linux only, requires configuration
opcache.file_cache=/dev/shm/opcache  ; RAM disk if available
```

**Watch Command for Opcache Status**

```bash
# Monitor opcache status
watch -n 1 'php -r "print_r(opcache_get_status());"'

# Key metrics:
# - memory_usage: used_memory / free_memory
# - oom_restarts: should be 0
# - hash_restarts: should be 0
# - cache_full: should be false
# - num_cached_scripts vs num_cached_keys
# - hits vs misses ratio
```

**Opcache Reset Without Restarting**

```php
// Reset opcache programmatically
opcache_reset();

// Clear specific file
opcache_invalidate('/path/to/file.php', true);

// Via PHP-FPM (needs opcache status page)
// GET /opcache-status?reset=1
```

**Opcache Optimization Tips**

1. **Monitor hit rate**: Aim for >99% hit rate. Low hit rate means cache is too small or scripts change too often.

2. **Stagger deployments**: When deploying to multiple servers, stagger file updates to allow opcache to warm up.

3. **Preload critical files**: Use opcache.preload to cache essential classes on startup.

4. **Separate pools**: Use different opcache configurations for different application pools.

5. **Interned strings**: Increase `interned_strings_buffer` for applications with many string constants and class names.

```php
// Example: Checking opcache hit rate
$status = opcache_get_status();
$hitRate = $status['opcache_statistics']['opcache_hit_rate'] ?? 0;
error_log("Opcache hit rate: " . round($hitRate, 2) . "%");
```

#### 14.3 Preloading for Production

Preloading loads PHP files into memory when the server starts, keeping them available across all requests.

**How Preloading Works**

PHP-FPM loads a preload script once when starting. The script includes files that should remain in shared memory:

```php
<?php
// preload.php
// Executed once when PHP-FPM starts

// Load all framework classes
opcache_compile_file(__DIR__ . '/vendor/autoload.php');

// Preload commonly used application classes
$classes = [
    'src/Models/User.php',
    'src/Models/Order.php',
    'src/Services/PaymentService.php',
    'src/Controllers/BaseController.php',
];

foreach ($classes as $class) {
    opcache_compile_file(__DIR__ . '/' . $class);
}

// Preload entire directories
$iterator = new RecursiveIteratorIterator(
    new RecursiveDirectoryIterator(__DIR__ . '/src/Entities')
);

foreach ($iterator as $file) {
    if ($file->isFile() && $file->getExtension() === 'php') {
        opcache_compile_file($file->getPathname());
    }
}
```

**Preloading Configuration**

```ini
; php.ini
opcache.preload=/var/www/preload.php
opcache.preload_user=www-data
opcache.memory_consumption=512  ; Increased for preloaded files
```

**Preloading Best Practices**

```php
<?php
// preload.php — Production-ready example

// 1. Load the autoloader
opcache_compile_file(__DIR__ . '/vendor/autoload.php');

// 2. Load classmap from Composer autoloader
$composer = require __DIR__ . '/vendor/autoload.php';
if (method_exists($composer, 'getClassMap')) {
    $classMap = $composer->getClassMap();
    
    foreach (array_keys($classMap) as $class) {
        $file = $classMap[$class];
        if (file_exists($file) && str_starts_with($file, __DIR__ . '/vendor/')) {
            opcache_compile_file($file);
        }
    }
}

// 3. Load application classes
$appDirs = [
    __DIR__ . '/src/',
];

foreach ($appDirs as $dir) {
    $iterator = new RecursiveIteratorIterator(
        new RecursiveDirectoryIterator($dir)
    );
    
    foreach ($iterator as $file) {
        if ($file->isFile() && $file->getExtension() === 'php') {
            $path = $file->getPathname();
            
            // Skip test files
            if (str_contains($path, '/Tests/') || str_contains($path, '/tests/')) {
                continue;
            }
            
            opcache_compile_file($path);
        }
    }
}

// 4. Log preload completion
error_log('Preloading completed: ' . opcache_get_status()['preload_statistics']['scripts'] . ' scripts loaded');
```

**Preloading Limitations**

- Changes to preloaded files require server restart
- Cannot preload files with side effects (unless carefully controlled)
- May increase memory usage significantly
- Files loaded in preload cannot be unloaded
- Preloading errors prevent server startup

```php
// Avoid preloading files that:
// - Instantiate objects at file level
// - Contain dynamic includes
// - Depend on environment-specific constants not yet defined

// Example of problematic preload:
// This runs on preload, connecting to potentially unavailable database
// $db = new PDO('mysql:host=localhost', 'user', 'pass');
```

---

## Part IV: Working with Data


### Chapter 15: Database Programming with PDO

#### 15.1 Connecting to MySQL, PostgreSQL, and SQLite

PHP Data Objects (PDO) provide a consistent interface for accessing various database systems. Understanding PDO is fundamental to professional PHP development.

**The PDO Abstraction Layer**

PDO abstracts database access behind a common API while allowing database-specific features through driver-specific functions. This means the same PHP code can work with MySQL, PostgreSQL, SQLite, and other databases with minimal changes.

**Connecting to MySQL**

```php
// MySQL connection with PDO
$dsn = 'mysql:host=127.0.0.1;port=3306;dbname=myapp;charset=utf8mb4';
$username = 'app_user';
$password = 'secure_password';

$options = [
    PDO::ATTR_ERRMODE => PDO::ERRMODE_EXCEPTION,
    PDO::ATTR_DEFAULT_FETCH_MODE => PDO::FETCH_ASSOC,
    PDO::ATTR_EMULATE_PREPARES => false,
    PDO::MYSQL_ATTR_INIT_COMMAND => "SET NAMES 'utf8mb4' COLLATE 'utf8mb4_unicode_ci'",
    PDO::MYSQL_ATTR_USE_BUFFERED_QUERY => true,
    PDO::ATTR_PERSISTENT => false,
];

try {
    $pdo = new PDO($dsn, $username, $password, $options);
    echo "Connected to MySQL successfully\n";
} catch (PDOException $e) {
    error_log("Database connection failed: {$e->getMessage()}");
    throw new RuntimeException('Database connection failed', 0, $e);
}
```

The `charset=utf8mb4` parameter ensures full Unicode support including emojis. Never use `utf8` (three-byte), which cannot store all Unicode characters.

**Connecting to PostgreSQL**

```php
$dsn = 'pgsql:host=127.0.0.1;port=5432;dbname=myapp;options=\'--client_encoding=UTF8\'';

$options = [
    PDO::ATTR_ERRMODE => PDO::ERRMODE_EXCEPTION,
    PDO::ATTR_DEFAULT_FETCH_MODE => PDO::FETCH_ASSOC,
    PDO::ATTR_EMULATE_PREPARES => false,
    PDO::ATTR_PERSISTENT => false,
];

try {
    $pdo = new PDO($dsn, 'app_user', 'secure_password', $options);
    
    // Set search path for schemas
    $pdo->exec("SET search_path TO public, audit");
    
    echo "Connected to PostgreSQL successfully\n";
} catch (PDOException $e) {
    throw new RuntimeException('Database connection failed', 0, $e);
}
```

PostgreSQL-specific features can be accessed through driver-specific methods or by setting attributes before connection:

```php
// SSL connection for PostgreSQL
$dsn = 'pgsql:host=db.example.com;port=5432;dbname=myapp;sslmode=require;sslcert=/etc/ssl/client.crt;sslkey=/etc/ssl/client.key;sslrootcert=/etc/ssl/ca.crt';
```

**Connecting to SQLite**

SQLite requires no separate server—the database is a single file:

```php
// File-based SQLite
$dsn = 'sqlite:/var/data/myapp.db';

// In-memory SQLite (development/testing)
$dsn = 'sqlite::memory:';

$options = [
    PDO::ATTR_ERRMODE => PDO::ERRMODE_EXCEPTION,
    PDO::ATTR_DEFAULT_FETCH_MODE => PDO::FETCH_ASSOC,
    PDO::ATTR_EMULATE_PREPARES => false,
];

try {
    $pdo = new PDO($dsn, null, null, $options);
    
    // Enable foreign keys (disabled by default in SQLite)
    $pdo->exec('PRAGMA foreign_keys = ON');
    
    // Enable WAL mode for better concurrent read performance
    $pdo->exec('PRAGMA journal_mode = WAL');
    
    echo "Connected to SQLite successfully\n";
} catch (PDOException $e) {
    throw new RuntimeException('Database connection failed', 0, $e);
}
```

**Connection Management Pattern**

A robust application needs proper connection management:

```php
class DatabaseConnection
{
    private static ?self $instance = null;
    private PDO $pdo;
    
    private function __construct(
        private readonly array $config,
    ) {
        $this->connect();
    }
    
    public static function getInstance(array $config = []): self
    {
        if (self::$instance === null) {
            $defaultConfig = self::loadConfig();
            self::$instance = new self(array_merge($defaultConfig, $config));
        }
        return self::$instance;
    }
    
    private function connect(): void
    {
        $dsn = sprintf(
            '%s:host=%s;port=%s;dbname=%s;charset=%s',
            $this->config['driver'],
            $this->config['host'],
            $this->config['port'],
            $this->config['database'],
            $this->config['charset'] ?? 'utf8mb4',
        );
        
        $this->pdo = new PDO(
            $dsn,
            $this->config['username'],
            $this->config['password'],
            [
                PDO::ATTR_ERRMODE => PDO::ERRMODE_EXCEPTION,
                PDO::ATTR_DEFAULT_FETCH_MODE => PDO::FETCH_ASSOC,
                PDO::ATTR_EMULATE_PREPARES => false,
                PDO::ATTR_PERSISTENT => $this->config['persistent'] ?? false,
            ]
        );
    }
    
    public function getPdo(): PDO
    {
        // Verify connection is still alive
        try {
            $this->pdo->query('SELECT 1');
        } catch (PDOException $e) {
            $this->connect(); // Reconnect if connection lost
        }
        
        return $this->pdo;
    }
    
    private static function loadConfig(): array
    {
        return [
            'driver' => $_ENV['DB_DRIVER'] ?? 'mysql',
            'host' => $_ENV['DB_HOST'] ?? '127.0.0.1',
            'port' => $_ENV['DB_PORT'] ?? '3306',
            'database' => $_ENV['DB_DATABASE'] ?? 'myapp',
            'username' => $_ENV['DB_USERNAME'] ?? 'root',
            'password' => $_ENV['DB_PASSWORD'] ?? '',
            'charset' => $_ENV['DB_CHARSET'] ?? 'utf8mb4',
            'persistent' => (bool) ($_ENV['DB_PERSISTENT'] ?? false),
        ];
    }
}
```

**Connection Pooling Considerations**

PHP doesn't have built-in connection pooling like Java. Each PHP-FPM worker maintains its own set of connections. For high-traffic applications, consider:

```php
// Persistent connections (use with caution)
$options = [
    PDO::ATTR_PERSISTENT => true, // Reuses connections across requests
];

// With persistent connections, always set a connection-specific state
$pdo = new PDO($dsn, $user, $pass, $options);

// Reset connection state on each request
$pdo->exec("SET time_zone = '+00:00'");
$pdo->exec("SET NAMES 'utf8mb4'");
$pdo->exec("SET sql_mode = 'STRICT_TRANS_TABLES,NO_ZERO_DATE,NO_ZERO_IN_DATE'");
```

#### 15.2 Prepared Statements and Parameter Binding

Prepared statements are the primary defense against SQL injection and improve performance for repeated queries.

**Basic Prepared Statements**

```php
// Without prepared statements — dangerous!
$id = $_GET['id'];
$stmt = $pdo->query("SELECT * FROM users WHERE id = {$id}"); // SQL injection!

// With prepared statements — safe!
$stmt = $pdo->prepare('SELECT * FROM users WHERE id = ?');
$stmt->execute([$id]);
$user = $stmt->fetch();
```

**Parameter Binding Methods**

PDO supports several parameter binding approaches:

```php
// 1. Positional parameters (?)
$stmt = $pdo->prepare('INSERT INTO users (name, email, created_at) VALUES (?, ?, ?)');
$stmt->execute(['Alice', 'alice@example.com', date('Y-m-d H:i:s')]);

// 2. Named parameters (:name)
$stmt = $pdo->prepare('INSERT INTO users (name, email, created_at) VALUES (:name, :email, :now)');
$stmt->execute([
    'name' => 'Alice',
    'email' => 'alice@example.com',
    'now' => date('Y-m-d H:i:s'),
]);

// 3. Explicit binding with value
$stmt = $pdo->prepare('SELECT * FROM users WHERE email = :email AND status = :status');
$stmt->bindValue(':email', 'alice@example.com', PDO::PARAM_STR);
$stmt->bindValue(':status', 'active', PDO::PARAM_STR);
$stmt->execute();

// 4. Explicit binding by reference
$email = 'alice@example.com';
$status = 'active';
$stmt = $pdo->prepare('SELECT * FROM users WHERE email = :email AND status = :status');
$stmt->bindParam(':email', $email, PDO::PARAM_STR);
$stmt->bindParam(':status', $status, PDO::PARAM_STR);

// Changing variables after binding affects the query
$status = 'inactive';
$stmt->execute(); // Now queries inactive users
```

**Data Type Constants**

PDO provides type constants for precise data handling:

```php
$stmt->bindValue(':id', $id, PDO::PARAM_INT);
$stmt->bindValue(':name', $name, PDO::PARAM_STR);
$stmt->bindValue(':price', 19.99, PDO::PARAM_STR); // Use string for DECIMAL
$stmt->bindValue(':is_active', $active, PDO::PARAM_BOOL);
$stmt->bindValue(':data', null, PDO::PARAM_NULL);
$stmt->bindValue(':binary', $blob, PDO::PARAM_LOB);
```

**Working with NULL Values**

```php
// Handling optional parameters
$phone = $_POST['phone'] ?? null;

$stmt = $pdo->prepare('INSERT INTO users (name, phone) VALUES (:name, :phone)');

if ($phone === null) {
    $stmt->bindValue(':phone', null, PDO::PARAM_NULL);
} else {
    $stmt->bindValue(':phone', $phone, PDO::PARAM_STR);
}

// Or simply:
$stmt->execute([
    'name' => $name,
    'phone' => $phone, // null works directly with execute()
]);
```

**Batch Insert with Prepared Statements**

```php
$users = [
    ['name' => 'Alice', 'email' => 'alice@example.com'],
    ['name' => 'Bob', 'email' => 'bob@example.com'],
    ['name' => 'Charlie', 'email' => 'charlie@example.com'],
];

$stmt = $pdo->prepare('INSERT INTO users (name, email) VALUES (:name, :email)');

$pdo->beginTransaction();
try {
    foreach ($users as $user) {
        $stmt->execute($user);
    }
    $pdo->commit();
    echo "Inserted " . count($users) . " users\n";
} catch (Exception $e) {
    $pdo->rollBack();
    throw $e;
}
```

**Dynamic IN Clauses**

Handling variable-length IN clauses requires careful parameter generation:

```php
function findUsersByIds(array $ids): array
{
    $pdo = getConnection();
    
    // Generate placeholders: :id0, :id1, :id2, ...
    $placeholders = [];
    $params = [];
    foreach ($ids as $index => $id) {
        $key = ":id{$index}";
        $placeholders[] = $key;
        $params[$key] = (int) $id;
    }
    
    $placeholdersStr = implode(', ', $placeholders);
    $stmt = $pdo->prepare("SELECT * FROM users WHERE id IN ({$placeholdersStr})");
    $stmt->execute($params);
    
    return $stmt->fetchAll();
}
```

#### 15.3 Transactions, Savepoints, and Rollbacks

Transactions ensure data integrity by grouping operations that must succeed or fail together.

**Basic Transaction Management**

```php
$pdo->beginTransaction();

try {
    // Deduct from sender
    $stmt = $pdo->prepare('UPDATE accounts SET balance = balance - :amount WHERE id = :from');
    $stmt->execute(['amount' => 100, 'from' => $senderId]);
    
    // Add to recipient
    $stmt = $pdo->prepare('UPDATE accounts SET balance = balance + :amount WHERE id = :to');
    $stmt->execute(['amount' => 100, 'to' => $recipientId]);
    
    // Record the transfer
    $stmt = $pdo->prepare('INSERT INTO transfers (from_id, to_id, amount, created_at) VALUES (:from, :to, :amount, :now)');
    $stmt->execute([
        'from' => $senderId,
        'to' => $recipientId,
        'amount' => 100,
        'now' => date('Y-m-d H:i:s'),
    ]);
    
    $pdo->commit();
} catch (Exception $e) {
    $pdo->rollBack();
    throw $e;
}
```

**Transaction Isolation Levels**

```php
// Set isolation level before starting transaction
$pdo->exec('SET TRANSACTION ISOLATION LEVEL READ COMMITTED');
$pdo->beginTransaction();

// Or read uncommitted for reporting queries
$pdo->exec('SET TRANSACTION ISOLATION LEVEL READ UNCOMMITTED');
$pdo->beginTransaction();
```

Isolation levels and their guarantees:

| Level | Dirty Read | Non-Repeatable Read | Phantom Read |
|-------|------------|---------------------|--------------|
| READ UNCOMMITTED | Possible | Possible | Possible |
| READ COMMITTED | Prevented | Possible | Possible |
| REPEATABLE READ | Prevented | Prevented | Possible |
| SERIALIZABLE | Prevented | Prevented | Prevented |

**Savepoints**

Savepoints allow partial rollbacks within a transaction:

```php
$pdo->beginTransaction();

try {
    // Insert order
    $stmt = $pdo->prepare('INSERT INTO orders (user_id, total) VALUES (:user, :total)');
    $stmt->execute(['user' => $userId, 'total' => $total]);
    $orderId = $pdo->lastInsertId();
    
    // Create savepoint for items
    $pdo->exec('SAVEPOINT order_items');
    
    try {
        foreach ($items as $item) {
            $stmt = $pdo->prepare('INSERT INTO order_items (order_id, product_id, quantity) VALUES (:order, :product, :qty)');
            $stmt->execute([
                'order' => $orderId,
                'product' => $item->productId,
                'qty' => $item->quantity,
            ]);
            
            // Deduct inventory
            $stmt = $pdo->prepare('UPDATE inventory SET quantity = quantity - :qty WHERE product_id = :product');
            $stmt->execute(['qty' => $item->quantity, 'product' => $item->productId]);
        }
    } catch (Exception $e) {
        // Rollback items but keep the order
        $pdo->exec('ROLLBACK TO SAVEPOINT order_items');
        throw new OrderItemException('Failed to add items', 0, $e);
    }
    
    $pdo->commit();
} catch (Exception $e) {
    $pdo->rollBack();
    throw $e;
}
```

**Deadlock Handling**

Transactions can encounter deadlocks, especially under high concurrency:

```php
function transferWithRetry(int $from, int $to, float $amount, int $maxRetries = 3): void
{
    $attempt = 0;
    $pdo = getConnection();
    
    while ($attempt < $maxRetries) {
        try {
            $pdo->beginTransaction();
            
            // Lock rows in consistent order to prevent deadlocks
            $ids = [$from, $to];
            sort($ids); // Always lock in same order
            
            foreach ($ids as $id) {
                $stmt = $pdo->prepare('SELECT balance FROM accounts WHERE id = :id FOR UPDATE');
                $stmt->execute(['id' => $id]);
            }
            
            // Perform transfer logic
            // ...
            
            $pdo->commit();
            return;
            
        } catch (PDOException $e) {
            $pdo->rollBack();
            
            // Check for deadlock (MySQL error 1213, PostgreSQL error 40P01)
            if ($e->getCode() === '40001' || $e->errorInfo[1] === 1213) {
                $attempt++;
                if ($attempt >= $maxRetries) {
                    throw new \RuntimeException('Transaction failed after retries', 0, $e);
                }
                
                // Exponential backoff
                usleep((2 ** $attempt) * 10000); // 10ms, 20ms, 40ms...
                continue;
            }
            
            throw $e;
        }
    }
}
```

**Nested Transactions with Savepoints**

Simulate nested transactions using savepoints:

```php
class TransactionManager
{
    private PDO $pdo;
    private int $transactionLevel = 0;
    
    public function __construct(PDO $pdo)
    {
        $this->pdo = $pdo;
    }
    
    public function begin(): void
    {
        if ($this->transactionLevel === 0) {
            $this->pdo->beginTransaction();
        } else {
            $this->pdo->exec("SAVEPOINT LEVEL_{$this->transactionLevel}");
        }
        
        $this->transactionLevel++;
    }
    
    public function commit(): void
    {
        $this->transactionLevel--;
        
        if ($this->transactionLevel === 0) {
            $this->pdo->commit();
        }
        // Savepoints don't need explicit commit
    }
    
    public function rollback(): void
    {
        $this->transactionLevel--;
        
        if ($this->transactionLevel === 0) {
            $this->pdo->rollBack();
        } else {
            $this->pdo->exec("ROLLBACK TO SAVEPOINT LEVEL_{$this->transactionLevel}");
        }
    }
}

// Usage
$tm = new TransactionManager($pdo);

$tm->begin();
try {
    // Outer operation
    $tm->begin();
    try {
        // Inner operation
        $tm->commit();
    } catch (Exception $e) {
        $tm->rollback(); // Only rolls back inner operation
    }
    $tm->commit();
} catch (Exception $e) {
    $tm->rollback(); // Rolls back everything
}
```

#### 15.4 Fetch Modes and Data Mapping

**Fetch Mode Constants**

PDO provides numerous fetch modes for different result formats:

```php
// FETCH_ASSOC: Column names as keys (default)
$rows = $stmt->fetchAll(PDO::FETCH_ASSOC);
// [['id' => 1, 'name' => 'Alice'], ['id' => 2, 'name' => 'Bob']]

// FETCH_NUM: Numeric indices
$rows = $stmt->fetchAll(PDO::FETCH_NUM);
// [[0 => 1, 1 => 'Alice'], [0 => 2, 1 => 'Bob']]

// FETCH_BOTH: Both associative and numeric (default pre-8.x)
$rows = $stmt->fetchAll(PDO::FETCH_BOTH);
// [['id' => 1, 0 => 1, 'name' => 'Alice', 1 => 'Alice'], ...]

// FETCH_OBJ: Anonymous objects
$rows = $stmt->fetchAll(PDO::FETCH_OBJ);
// Array of stdClass objects with column names as properties

// FETCH_CLASS: Specific class instances
$rows = $stmt->fetchAll(PDO::FETCH_CLASS, User::class);
// Array of User objects

// FETCH_COLUMN: Single column (scalar values)
$names = $stmt->fetchAll(PDO::FETCH_COLUMN, 1); // Column index 1
// ['Alice', 'Bob', 'Charlie']

// FETCH_KEY_PAIR: Two-column key-value pairs
$data = $stmt->fetchAll(PDO::FETCH_KEY_PAIR);
// ['key1' => 'value1', 'key2' => 'value2']

// FETCH_GROUP: Group rows by first column
$grouped = $stmt->fetchAll(PDO::FETCH_GROUP);
// [1 => [['name' => 'Alice', ...]], 2 => [['name' => 'Bob', ...]]]

// FETCH_UNIQUE: Index by first column
$indexed = $stmt->fetchAll(PDO::FETCH_UNIQUE);
// [1 => ['name' => 'Alice', ...], 2 => ['name' => 'Bob', ...]]
```

**Mapping to Domain Objects**

```php
class User
{
    public function __construct(
        public readonly int $id,
        public readonly string $name,
        public readonly string $email,
        public readonly ?DateTimeImmutable $createdAt = null,
    ) {}
    
    public static function fromRow(array $row): self
    {
        return new self(
            id: (int) $row['id'],
            name: $row['name'],
            email: $row['email'],
            createdAt: $row['created_at']
                ? new DateTimeImmutable($row['created_at'])
                : null,
        );
    }
}

// Repository using mapping
class UserRepository
{
    public function __construct(private PDO $pdo) {}
    
    public function findById(int $id): ?User
    {
        $stmt = $this->pdo->prepare('SELECT * FROM users WHERE id = :id');
        $stmt->execute(['id' => $id]);
        $row = $stmt->fetch();
        
        return $row ? User::fromRow($row) : null;
    }
    
    public function findAll(): array
    {
        $stmt = $this->pdo->query('SELECT * FROM users ORDER BY name');
        
        return array_map(
            fn(array $row): User => User::fromRow($row),
            $stmt->fetchAll()
        );
    }
    
    public function findActive(): array
    {
        $stmt = $this->pdo->query('SELECT * FROM users WHERE status = "active"');
        
        // Using FETCH_CLASS with constructor arguments
        return $stmt->fetchAll(
            PDO::FETCH_FUNC,
            fn(int $id, string $name, string $email, ?string $createdAt): User =>
                new User(
                    id: $id,
                    name: $name,
                    email: $email,
                    createdAt: $createdAt ? new DateTimeImmutable($createdAt) : null,
                )
        );
    }
}
```

**Custom Fetch Mode with FETCH_FUNC**

```php
$stmt = $pdo->query('SELECT id, first_name, last_name FROM users');

$users = $stmt->fetchAll(
    PDO::FETCH_FUNC,
    function (int $id, string $firstName, string $lastName): array {
        return [
            'id' => $id,
            'fullName' => "{$firstName} {$lastName}",
            'initials' => strtoupper($firstName[0] . $lastName[0]),
        ];
    }
);
```

**Lazy Fetching with Cursors**

For large result sets, use cursors to avoid loading everything into memory:

```php
// MySQL: Use unbuffered query
$pdo->setAttribute(PDO::MYSQL_ATTR_USE_BUFFERED_QUERY, false);

$stmt = $pdo->prepare('SELECT * FROM large_table');
$stmt->execute();

while ($row = $stmt->fetch()) {
    processRow($row);
    
    // Current row is freed automatically when fetching next
}

// Generic: Scrollable cursor
$stmt = $pdo->prepare('SELECT * FROM large_table', [
    PDO::ATTR_CURSOR => PDO::CURSOR_SCROLL,
]);
$stmt->execute();

// Fetch rows one at a time
while ($row = $stmt->fetch(PDO::FETCH_ASSOC, PDO::FETCH_ORI_NEXT)) {
    processRow($row);
}
```

#### 15.5 Connection Pooling and Persistent Connections

**Understanding PHP's Connection Model**

Unlike Java or .NET, PHP follows a share-nothing architecture. Each request creates its own resources, including database connections. Connection pooling must be handled differently.

**Persistent Connections**

Persistent connections survive across requests within the same PHP-FPM worker:

```php
$options = [
    PDO::ATTR_PERSISTENT => true,
];

$pdo = new PDO($dsn, $user, $pass, $options);
```

Advantages:
- Reduces connection overhead for frequently accessed databases
- Can improve performance for applications with high connection churn

Disadvantages:
- Requires careful state management
- Can exhaust database connection limits
- Idle connections may be terminated by the database
- Stale connections may serve requests after database restart

**Managing Persistent Connections Safely**

```php
class SafePersistentConnection
{
    private PDO $pdo;
    private string $dsn;
    private string $user;
    private string $pass;
    
    public function __construct(string $dsn, string $user, string $pass)
    {
        $this->dsn = $dsn;
        $this->user = $user;
        $this->pass = $pass;
        $this->connect();
    }
    
    private function connect(): void
    {
        $options = [
            PDO::ATTR_ERRMODE => PDO::ERRMODE_EXCEPTION,
            PDO::ATTR_PERSISTENT => true,
            PDO::ATTR_EMULATE_PREPARES => false,
        ];
        
        $this->pdo = new PDO($this->dsn, $this->user, $this->pass, $options);
        
        // Reset state for reused connection
        $this->resetState();
    }
    
    private function resetState(): void
    {
        $this->pdo->exec("SET time_zone = '+00:00'");
        $this->pdo->exec("SET NAMES 'utf8mb4'");
        
        // Clear any temporary tables
        try {
            $this->pdo->exec('DROP TEMPORARY TABLE IF EXISTS temp_results');
        } catch (PDOException $e) {
            // Temporary table might not exist
        }
    }
    
    public function getConnection(): PDO
    {
        // Verify connection is alive
        try {
            $this->pdo->query('SELECT 1');
        } catch (PDOException $e) {
            // Connection lost, reconnect
            $this->connect();
        }
        
        return $this->pdo;
    }
}
```

**Connection Pooling with ProxySQL**

For high-traffic applications, use a database proxy like ProxySQL for connection pooling:

```php
// Application connects to ProxySQL instead of database directly
$dsn = 'mysql:host=proxysql;port=6033;dbname=myapp;charset=utf8mb4';
$pdo = new PDO($dsn, $user, $pass);
// ProxySQL manages connection pooling to the actual MySQL servers
```

This approach provides:
- True connection pooling across all PHP-FPM workers
- Query caching and routing
- Read/write splitting
- Automatic failover

**Connection Limits and Configuration**

```php
// Monitor and manage connections
$stmt = $pdo->query('SHOW STATUS LIKE "Threads_connected"');
$connections = $stmt->fetch(PDO::FETCH_COLUMN, 1);

if ($connections > ($maxConnections * 0.8)) {
    error_log("Warning: Database connections at 80% capacity: {$connections}");
}
```

**Best Practices for Production**

1. Use connection timeout settings:
```php
$options = [
    PDO::ATTR_TIMEOUT => 5, // 5-second timeout
    PDO::ATTR_PERSISTENT => true,
];
```

2. Implement circuit breaker pattern:
```php
class CircuitBreaker
{
    private int $failureCount = 0;
    private int $threshold = 5;
    private ?int $lastFailureTime = null;
    private int $timeout = 60; // seconds
    
    public function execute(callable $operation): mixed
    {
        if ($this->isOpen()) {
            throw new \RuntimeException('Circuit breaker is open');
        }
        
        try {
            $result = $operation();
            $this->failureCount = 0;
            return $result;
        } catch (PDOException $e) {
            $this->failureCount++;
            $this->lastFailureTime = time();
            throw $e;
        }
    }
    
    private function isOpen(): bool
    {
        if ($this->failureCount >= $this->threshold) {
            if (time() - $this->lastFailureTime < $this->timeout) {
                return true;
            }
            $this->failureCount = 0; // Try again after timeout
        }
        return false;
    }
}
```

3. Implement graceful degradation:
```php
class DatabaseHealthCheck
{
    public function isHealthy(): bool
    {
        try {
            $pdo = getConnection();
            $pdo->query('SELECT 1');
            return true;
        } catch (PDOException $e) {
            return false;
        }
    }
    
    public function getReadReplica(): ?PDO
    {
        $replicas = [
            'mysql:host=replica1;dbname=myapp',
            'mysql:host=replica2;dbname=myapp',
        ];
        
        foreach ($replicas as $dsn) {
            try {
                $pdo = new PDO($dsn, getenv('DB_USER'), getenv('DB_PASS'), [
                    PDO::ATTR_TIMEOUT => 2,
                ]);
                return $pdo;
            } catch (PDOException $e) {
                continue; // Try next replica
            }
        }
        
        return null; // All replicas down
    }
}
```

---

### Chapter 16: Advanced Data Storage

#### 16.1 Redis Integration for Caching and Sessions

Redis provides high-performance in-memory data storage for caching, sessions, queues, and real-time features.

**Connecting to Redis**

```php
// Using phpredis extension
$redis = new Redis();

try {
    $redis->connect('127.0.0.1', 6379, 2.5); // host, port, timeout
    $redis->auth($_ENV['REDIS_PASSWORD']);   // if authentication enabled
    $redis->select(0);                        // select database 0
    
    echo "Connected to Redis\n";
} catch (RedisException $e) {
    throw new RuntimeException('Redis connection failed', 0, $e);
}

// Persistent connection
$redis->pconnect('127.0.0.1', 6379);

// Cluster connection
$cluster = new RedisCluster(null, [
    'node1:6379',
    'node2:6379',
    'node3:6379',
]);
```

**Caching Patterns**

```php
class RedisCache
{
    public function __construct(private Redis $redis) {}
    
    // Cache-Aside pattern
    public function get(string $key, callable $callback, int $ttl = 3600): mixed
    {
        $cached = $this->redis->get($key);
        
        if ($cached !== false) {
            return unserialize($cached);
        }
        
        $value = $callback();
        $this->redis->setex($key, $ttl, serialize($value));
        
        return $value;
    }
    
    // Multi-get for batch operations
    public function getMultiple(array $keys, callable $callback): array
    {
        $cached = $this->redis->mget($keys);
        $missing = [];
        $results = [];
        
        foreach ($keys as $index => $key) {
            if ($cached[$index] !== false) {
                $results[$key] = unserialize($cached[$index]);
            } else {
                $missing[] = $key;
            }
        }
        
        if (!empty($missing)) {
            $fetched = $callback($missing);
            $pipeline = $this->redis->multi(Redis::PIPELINE);
            
            foreach ($fetched as $key => $value) {
                $results[$key] = $value;
                $pipeline->setex($key, 3600, serialize($value));
            }
            
            $pipeline->exec();
        }
        
        return $results;
    }
    
    // Cache with stampede protection
    public function getWithLock(string $key, callable $callback, int $ttl = 3600, int $lockTimeout = 10): mixed
    {
        $cached = $this->redis->get($key);
        
        if ($cached !== false) {
            return unserialize($cached);
        }
        
        $lockKey = "lock:{$key}";
        $lock = $this->redis->set($lockKey, '1', ['nx', 'ex' => $lockTimeout]);
        
        if (!$lock) {
            // Another process is regenerating
            usleep(100000); // Wait 100ms
            return $this->getWithLock($key, $callback, $ttl, $lockTimeout);
        }
        
        try {
            $value = $callback();
            $this->redis->setex($key, $ttl, serialize($value));
            return $value;
        } finally {
            $this->redis->del($lockKey);
        }
    }
}
```

**Redis for Sessions**

Store PHP sessions in Redis for better performance and multi-server compatibility:

```php
// php.ini or runtime configuration
ini_set('session.save_handler', 'redis');
ini_set('session.save_path', 'tcp://127.0.0.1:6379?auth=redis_password&prefix=session:&database=0');

// Custom session handler with more control
class RedisSessionHandler implements SessionHandlerInterface
{
    private Redis $redis;
    private int $lifetime;
    
    public function __construct(Redis $redis, int $lifetime = 86400)
    {
        $this->redis = $redis;
        $this->lifetime = $lifetime;
    }
    
    public function open(string $path, string $name): bool
    {
        return true;
    }
    
    public function close(): bool
    {
        return true;
    }
    
    public function read(string $id): string|false
    {
        $data = $this->redis->get("session:{$id}");
        return $data !== false ? $data : '';
    }
    
    public function write(string $id, string $data): bool
    {
        $this->redis->setex("session:{$id}", $this->lifetime, $data);
        return true;
    }
    
    public function destroy(string $id): bool
    {
        $this->redis->del("session:{$id}");
        return true;
    }
    
    public function gc(int $maxLifetime): int|false
    {
        // Redis handles expiration automatically
        return 0;
    }
}

// Register custom handler
$handler = new RedisSessionHandler($redis, 86400);
session_set_save_handler($handler, true);
session_start();
```

**Redis Data Structures**

```php
// Hashes - great for storing objects
$redis->hMSet('user:1', [
    'name' => 'Alice',
    'email' => 'alice@example.com',
    'age' => 30,
]);
$user = $redis->hGetAll('user:1');
$name = $redis->hGet('user:1', 'name');

// Lists - queues and activity feeds
$redis->lPush('queue:emails', json_encode(['to' => 'alice@example.com']));
$redis->lPush('queue:emails', json_encode(['to' => 'bob@example.com']));
$task = json_decode($redis->rPop('queue:emails'), true);

// Sets - unique collections
$redis->sAdd('user:1:friends', 2, 3, 4);
$redis->sAdd('user:2:friends', 1, 3, 5);
$mutual = $redis->sInter('user:1:friends', 'user:2:friends');

// Sorted Sets - rankings and leaderboards
$redis->zAdd('leaderboard', 1500, 'player1');
$redis->zAdd('leaderboard', 1200, 'player2');
$redis->zAdd('leaderboard', 1800, 'player3');
$top3 = $redis->zRevRange('leaderboard', 0, 2, true);

// Bitmaps - feature flags and analytics
$redis->setBit('user:1:permissions', 0, true);  // Can read
$redis->setBit('user:1:permissions', 1, false); // Cannot write
$canRead = $redis->getBit('user:1:permissions', 0);

// HyperLogLog - unique counting (approximate)
$redis->pfAdd('visitors:today', 'user1', 'user2', 'user3');
$redis->pfAdd('visitors:today', 'user2', 'user4');
$uniqueVisitors = $redis->pfCount('visitors:today'); // ~4
```

**Rate Limiting with Redis**

```php
class RateLimiter
{
    public function __construct(private Redis $redis) {}
    
    public function attempt(string $key, int $maxAttempts, int $windowSeconds): bool
    {
        $now = time();
        $windowStart = $now - $windowSeconds;
        
        $redisKey = "ratelimit:{$key}";
        
        // Remove old entries
        $this->redis->zRemRangeByScore($redisKey, 0, $windowStart);
        
        // Count current attempts
        $attempts = $this->redis->zCard($redisKey);
        
        if ($attempts >= $maxAttempts) {
            return false;
        }
        
        // Add current attempt
        $this->redis->zAdd($redisKey, $now, uniqid('', true));
        $this->redis->expire($redisKey, $windowSeconds + 1);
        
        return true;
    }
    
    public function getRemaining(string $key, int $maxAttempts, int $windowSeconds): int
    {
        $windowStart = time() - $windowSeconds;
        $this->redis->zRemRangeByScore("ratelimit:{$key}", 0, $windowStart);
        $attempts = $this->redis->zCard("ratelimit:{$key}");
        
        return max(0, $maxAttempts - $attempts);
    }
}

// Usage
$limiter = new RateLimiter($redis);
if ($limiter->attempt("api:{$userId}", 60, 60)) {
    handleRequest();
} else {
    http_response_code(429);
    echo 'Rate limit exceeded';
}
```

#### 16.2 MongoDB and Document-Oriented Patterns

MongoDB stores data as flexible JSON-like documents, making it ideal for certain use cases alongside relational databases.

**Connecting to MongoDB**

```php
// Using mongodb extension
$client = new MongoDB\Client(
    'mongodb://user:password@localhost:27017/myapp?authSource=admin',
    [],
    [
        'typeMap' => [
            'array' => 'array',
            'document' => 'array',
            'root' => 'array',
        ],
    ]
);

$database = $client->selectDatabase('myapp');
$collection = $database->selectCollection('users');
```

**CRUD Operations**

```php
// Insert
$result = $collection->insertOne([
    'name' => 'Alice Johnson',
    'email' => 'alice@example.com',
    'preferences' => [
        'theme' => 'dark',
        'language' => 'en',
    ],
    'tags' => ['customer', 'premium'],
    'created_at' => new MongoDB\BSON\UTCDateTime(),
]);

$id = $result->getInsertedId();

// Insert multiple
$collection->insertMany([
    ['name' => 'Bob', 'email' => 'bob@example.com'],
    ['name' => 'Charlie', 'email' => 'charlie@example.com'],
]);

// Find
$user = $collection->findOne(['_id' => $id]);
$user = $collection->findOne(['email' => 'alice@example.com']);

// Find with filters
$premiumUsers = $collection->find([
    'tags' => 'premium',
    'preferences.theme' => 'dark',
], [
    'sort' => ['name' => 1],
    'limit' => 10,
    'projection' => ['name' => 1, 'email' => 1, '_id' => 0],
]);

foreach ($premiumUsers as $user) {
    echo "{$user['name']} <{$user['email']}>\n";
}

// Update
$collection->updateOne(
    ['_id' => $id],
    ['$set' => [
        'preferences.theme' => 'light',
        'updated_at' => new MongoDB\BSON\UTCDateTime(),
    ]]
);

// Update with upsert (insert if not exists)
$collection->updateOne(
    ['email' => 'alice@example.com'],
    ['$setOnInsert' => ['name' => 'Alice', 'created_at' => new MongoDB\BSON\UTCDateTime()]],
    ['upsert' => true]
);

// Delete
$collection->deleteOne(['_id' => $id]);
```

**Document Design Patterns**

```php
// Embedded documents - data accessed together
$blogPost = [
    'title' => 'Introduction to MongoDB',
    'author' => [
        'name' => 'Alice',
        'avatar' => 'https://example.com/alice.jpg',
    ],
    'comments' => [
        [
            'user' => 'Bob',
            'text' => 'Great article!',
            'created_at' => new MongoDB\BSON\UTCDateTime(),
        ],
    ],
];

// Referenced documents - data accessed independently
$user = [
    '_id' => new MongoDB\BSON\ObjectId(),
    'name' => 'Alice',
];

$order = [
    'user_id' => $user['_id'], // Reference to user
    'items' => [
        ['product_id' => $productId, 'quantity' => 2],
    ],
    'total' => 99.98,
];

// Bucket pattern - time series data
$sensorReading = [
    'sensor_id' => 'SENSOR_001',
    'date' => '2024-01-15',
    'hour' => 14,
    'readings' => [
        ['minute' => 0, 'value' => 23.5],
        ['minute' => 1, 'value' => 23.6],
        // ... 60 readings per hour
    ],
];
```

**Aggregation Pipeline**

```php
// Complex analytics with aggregation
$pipeline = [
    // Match stage - filter documents
    ['$match' => ['tags' => 'premium']],
    
    // Group stage - aggregate data
    ['$group' => [
        '_id' => '$preferences.theme',
        'count' => ['$sum' => 1],
        'avg_age' => ['$avg' => '$age'],
    ]],
    
    // Sort stage
    ['$sort' => ['count' => -1]],
    
    // Project stage - reshape documents
    ['$project' => [
        'theme' => '$_id',
        'count' => 1,
        'avg_age' => ['$round' => ['$avg_age', 2]],
        '_id' => 0,
    ]],
];

$results = $collection->aggregate($pipeline);

foreach ($results as $result) {
    echo "Theme: {$result['theme']}, Users: {$result['count']}\n";
}
```

**Indexing**

```php
// Create indexes for query performance
$collection->createIndex(['email' => 1], ['unique' => true]);
$collection->createIndex(['tags' => 1, 'preferences.theme' => 1]);
$collection->createIndex(['created_at' => -1]);

// Text index for full-text search
$collection->createIndex(['name' => 'text', 'email' => 'text', 'bio' => 'text']);
$results = $collection->find(['$text' => ['$search' => 'alice developer']]);

// Geospatial index
$collection->createIndex(['location' => '2dsphere']);
$nearby = $collection->find([
    'location' => [
        '$near' => [
            '$geometry' => ['type' => 'Point', 'coordinates' => [-73.97, 40.77]],
            '$maxDistance' => 1000, // meters
        ],
    ],
]);
```

#### 16.3 Elasticsearch Basics for Search

Elasticsearch provides powerful full-text search capabilities that complement traditional databases.

**Connecting to Elasticsearch**

```php
$client = Elastic\Elasticsearch\ClientBuilder::create()
    ->setHosts(['localhost:9200'])
    ->setBasicAuthentication('elastic', $_ENV['ES_PASSWORD'])
    ->build();
```

**Indexing Documents**

```php
// Index a document
$params = [
    'index' => 'articles',
    'id' => 'article_1',
    'body' => [
        'title' => 'Getting Started with PHP 8',
        'content' => 'PHP 8 introduces many new features including...',
        'author' => ['name' => 'Alice Smith', 'id' => 1],
        'tags' => ['php', 'tutorial', 'php8'],
        'published_at' => '2024-01-15T10:00:00Z',
        'status' => 'published',
    ],
];

$response = $client->index($params);

// Bulk indexing
$params = ['body' => []];
for ($i = 1; $i <= 100; $i++) {
    $params['body'][] = [
        'index' => [
            '_index' => 'articles',
            '_id' => "article_{$i}",
        ],
    ];
    $params['body'][] = [
        'title' => "Article {$i}",
        'content' => "Content for article {$i}...",
        'tags' => ['php', 'tutorial'],
        'published_at' => date('c', strtotime("-{$i} days")),
    ];
}
$client->bulk($params);
```

**Searching**

```php
// Full-text search
$params = [
    'index' => 'articles',
    'body' => [
        'query' => [
            'multi_match' => [
                'query' => 'php 8 features',
                'fields' => ['title^3', 'content'], // title is 3x more important
            ],
        ],
        'highlight' => [
            'fields' => [
                'title' => new stdClass(),
                'content' => new stdClass(),
            ],
        ],
    ],
];

$results = $client->search($params);

foreach ($results['hits']['hits'] as $hit) {
    echo "Score: {$hit['_score']}\n";
    echo "Title: {$hit['_source']['title']}\n";
    if (isset($hit['highlight'])) {
        echo "Highlights: " . implode(' ... ', $hit['highlight']['content'] ?? []) . "\n";
    }
}
```

**Filtering and Aggregations**

```php
// Filtered search with aggregations
$params = [
    'index' => 'articles',
    'body' => [
        'query' => [
            'bool' => [
                'must' => [
                    ['match' => ['content' => 'php']],
                ],
                'filter' => [
                    ['term' => ['status' => 'published']],
                    ['range' => ['published_at' => ['gte' => '2024-01-01']]],
                ],
            ],
        ],
        'aggs' => [
            'popular_tags' => [
                'terms' => ['field' => 'tags', 'size' => 10],
            ],
            'articles_over_time' => [
                'date_histogram' => [
                    'field' => 'published_at',
                    'calendar_interval' => 'month',
                ],
            ],
        ],
    ],
];

$results = $client->search($params);
$tags = $results['aggregations']['popular_tags']['buckets'];
```

#### 16.4 File-Based Storage: JSON, XML, YAML, and CSV

**JSON Handling**

JSON is the lingua franca of modern web applications:

```php
// Encoding
$data = [
    'name' => 'Alice',
    'email' => 'alice@example.com',
    'preferences' => [
        'theme' => 'dark',
        'notifications' => true,
    ],
];

// Pretty print with flags
$json = json_encode($data, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE | JSON_UNESCAPED_SLASHES);

// Writing to file
file_put_contents('data.json', $json, LOCK_EX);

// Decoding
$jsonString = file_get_contents('data.json');
$decoded = json_decode($jsonString, true, 512, JSON_THROW_ON_ERROR);

if (json_last_error() !== JSON_ERROR_NONE) {
    throw new RuntimeException('Invalid JSON: ' . json_last_error_msg());
}

// Streaming large JSON
class JsonStreamWriter
{
    private $handle;
    private bool $firstItem = true;
    
    public function __construct(string $path)
    {
        $this->handle = fopen($path, 'w');
        fwrite($this->handle, "[\n");
    }
    
    public function addRecord(array $record): void
    {
        if (!$this->firstItem) {
            fwrite($this->handle, ",\n");
        }
        fwrite($this->handle, "  " . json_encode($record));
        $this->firstItem = false;
    }
    
    public function close(): void
    {
        fwrite($this->handle, "\n]");
        fclose($this->handle);
    }
}

// PHP 8.3 JSON validation without decoding
if (json_validate($jsonString)) {
    echo "Valid JSON\n";
} else {
    echo "Invalid JSON: " . json_last_error_msg() . "\n";
}
```

**XML Handling**

XML remains important for legacy systems, SOAP APIs, and configuration:

```php
// SimpleXML for basic XML
$xml = simplexml_load_file('config.xml');

foreach ($xml->database->children() as $key => $value) {
    echo "{$key}: {$value}\n";
}

// DOMDocument for complex XML manipulation
$dom = new DOMDocument('1.0', 'UTF-8');
$dom->formatOutput = true;

$root = $dom->createElement('users');
$dom->appendChild($root);

$users = [
    ['name' => 'Alice', 'email' => 'alice@example.com'],
    ['name' => 'Bob', 'email' => 'bob@example.com'],
];

foreach ($users as $data) {
    $user = $dom->createElement('user');
    $user->setAttribute('email', $data['email']);
    
    $name = $dom->createElement('name', $data['name']);
    $user->appendChild($name);
    
    $root->appendChild($user);
}

$dom->save('users.xml');

// XMLReader for large files
$reader = new XMLReader();
$reader->open('large-file.xml');

while ($reader->read()) {
    if ($reader->nodeType === XMLReader::ELEMENT && $reader->name === 'user') {
        $node = new SimpleXMLElement($reader->readOuterXML());
        processUser($node);
    }
}
$reader->close();
```

**YAML Processing**

YAML is popular for configuration files:

```php
// Requires yaml extension or symfony/yaml
use Symfony\Component\Yaml\Yaml;

// Parsing
$config = Yaml::parseFile('config.yaml');
echo $config['database']['host'];

// Dumping
$yaml = Yaml::dump($config, 4, 2, Yaml::DUMP_MULTI_LINE_LITERAL_BLOCK);
file_put_contents('config.yaml', $yaml);

// Example config.yaml:
// database:
//     host: localhost
//     port: 3306
//     name: myapp
// cache:
//     driver: redis
//     host: localhost
```

**CSV Processing**

CSV is ubiquitous for data import/export:

```php
// Reading CSV
$handle = fopen('data.csv', 'r');
$headers = fgetcsv($handle); // First row as headers

$records = [];
while (($row = fgetcsv($handle)) !== false) {
    $records[] = array_combine($headers, $row);
}
fclose($handle);

// Writing CSV
$handle = fopen('export.csv', 'w');
fputcsv($handle, ['Name', 'Email', 'Age']); // Headers

foreach ($users as $user) {
    fputcsv($handle, [
        $user->name,
        $user->email,
        $user->age,
    ]);
}
fclose($handle);

// CSV with custom settings
$handle = fopen('data.csv', 'r');
stream_filter_append($handle, 'convert.iconv.ISO-8859-1/UTF-8');

while (($row = fgetcsv($handle, 0, ';', '"', '\\')) !== false) {
    // Using semicolon separator, double-quote enclosure, backslash escape
    processRow($row);
}

// League/CSV for advanced CSV operations
use League\Csv\Reader;
use League\Csv\Writer;

$csv = Reader::createFromPath('data.csv', 'r');
$csv->setHeaderOffset(0);

foreach ($csv->getRecords() as $record) {
    echo $record['Name'] . ': ' . $record['Email'] . "\n";
}

// Filter and transform
$stmt = $csv->select(function (array $record): bool {
    return $record['Age'] >= 18;
})->slice(0, 100);
```

**Serialization Best Practices**

Choose the right format for your use case:

```php
// JSON: API responses, configuration, data interchange
$apiResponse = json_encode($data);

// XML: SOAP services, legacy systems, documents
$soapEnvelope = $dom->saveXML();

// YAML: Human-readable configuration, documentation
$config = Yaml::dump($settings);

// CSV: Tabular data export, spreadsheet compatibility
fputcsv($handle, $row);

// PHP serialize: Internal caching (not for data interchange)
$cached = serialize($complexObject);

// MessagePack: Compact binary format for APIs
$packed = msgpack_pack($data);

// Parquet/Avro: Big data analytics
// Use specialized libraries for columnar storage
```

---

## Part V: Web Development


### Chapter 17: HTTP and Web Fundamentals

#### 17.1 Request/Response Lifecycle and Superglobals

Understanding the HTTP request/response lifecycle is essential for effective web development. PHP provides access to request data through superglobal arrays that are automatically populated for each request.

**The Complete HTTP Lifecycle in PHP**

When a browser sends a request to a PHP application, a precise sequence of events unfolds:

1. **DNS Resolution**: The browser resolves the domain name to an IP address.

2. **TCP Connection**: A TCP connection is established to the server on port 80 (HTTP) or 443 (HTTPS).

3. **TLS Handshake** (HTTPS): Certificate validation, cipher negotiation, and session key exchange occur.

4. **HTTP Request**: The browser sends the HTTP request including the request line, headers, and body.

5. **Web Server Reception**: Nginx or Apache receives the request and determines how to handle it.

6. **PHP Invocation**: For PHP files, the web server forwards the request to PHP-FPM via FastCGI.

7. **Superglobal Population**: PHP populates the superglobal arrays with request data.

8. **Script Execution**: The PHP script executes, processing the request and generating a response.

9. **Response Transmission**: The response is sent back through FastCGI to the web server.

10. **HTTP Response**: The web server sends the HTTP response to the browser.

11. **Browser Rendering**: The browser parses and renders the response, initiating additional requests for resources.

**Superglobal Arrays**

PHP provides nine superglobal arrays accessible from any scope:

```php
// $_GET - URL query parameters
// URL: /search?q=php+8&page=2&sort=date
$query = $_GET['q'] ?? '';           // 'php 8'
$page = (int) ($_GET['page'] ?? 1);  // 2
$sort = $_GET['sort'] ?? 'relevance'; // 'date'

// $_POST - Form data from POST requests
$username = $_POST['username'] ?? '';
$password = $_POST['password'] ?? '';
$remember = isset($_POST['remember']); // Checkbox handling

// $_REQUEST - Combined GET, POST, and COOKIE data
// Use with caution; prefer specific superglobals
$token = $_REQUEST['csrf_token'] ?? '';

// $_SERVER - Server and execution environment information
$requestMethod = $_SERVER['REQUEST_METHOD'];
$requestUri = $_SERVER['REQUEST_URI'];
$userAgent = $_SERVER['HTTP_USER_AGENT'] ?? '';
$clientIp = $_SERVER['HTTP_X_FORWARDED_FOR'] 
    ?? $_SERVER['REMOTE_ADDR'] 
    ?? 'unknown';
$isHttps = ($_SERVER['HTTPS'] ?? 'off') === 'on';
$host = $_SERVER['HTTP_HOST'] ?? 'localhost';

// $_FILES - Uploaded file information
$uploadedFile = $_FILES['avatar'] ?? null;
if ($uploadedFile && $uploadedFile['error'] === UPLOAD_ERR_OK) {
    $tmpPath = $uploadedFile['tmp_name'];
    $originalName = $uploadedFile['name'];
    $size = $uploadedFile['size'];
    $mimeType = $uploadedFile['type']; // Client-supplied, don't trust
}

// $_COOKIE - Cookie values sent by the browser
$sessionId = $_COOKIE['PHPSESSID'] ?? '';
$rememberToken = $_COOKIE['remember_me'] ?? '';

// $_SESSION - Session data (must call session_start() first)
session_start();
$_SESSION['user_id'] = 42;
$_SESSION['last_activity'] = time();
$userId = $_SESSION['user_id'] ?? null;

// $_ENV - Environment variables (from php.ini variables_order)
$dbHost = $_ENV['DB_HOST'] ?? 'localhost';
$appEnv = $_ENV['APP_ENV'] ?? 'production';

// $GLOBALS - All global variables
$GLOBALS['config'] = ['debug' => true];
```

**Building a Request Abstraction**

Raw superglobals work for simple scripts but professional applications benefit from request abstraction:

```php
class Request
{
    private array $query;
    private array $body;
    private array $server;
    private array $headers;
    private array $cookies;
    private array $files;
    private ?string $method;
    private ?string $path;
    
    public static function capture(): self
    {
        $request = new self();
        $request->query = $_GET;
        $request->body = $_POST;
        $request->server = $_SERVER;
        $request->cookies = $_COOKIE;
        $request->files = $_FILES;
        $request->method = $_SERVER['REQUEST_METHOD'] ?? 'GET';
        
        // Parse path from request URI
        $uri = $_SERVER['REQUEST_URI'] ?? '/';
        $path = parse_url($uri, PHP_URL_PATH);
        $request->path = $path !== false ? $path : '/';
        
        // Extract headers
        $request->headers = [];
        foreach ($_SERVER as $key => $value) {
            if (str_starts_with($key, 'HTTP_')) {
                $headerName = str_replace('_', '-', substr($key, 5));
                $request->headers[$headerName] = $value;
            }
        }
        
        // Special headers
        if (isset($_SERVER['CONTENT_TYPE'])) {
            $request->headers['Content-Type'] = $_SERVER['CONTENT_TYPE'];
        }
        if (isset($_SERVER['CONTENT_LENGTH'])) {
            $request->headers['Content-Length'] = $_SERVER['CONTENT_LENGTH'];
        }
        
        return $request;
    }
    
    public function getMethod(): string
    {
        return $this->method;
    }
    
    public function getPath(): string
    {
        return $this->path;
    }
    
    public function input(string $key, mixed $default = null): mixed
    {
        // Check POST body first, then query parameters
        return $this->body[$key] ?? $this->query[$key] ?? $default;
    }
    
    public function query(string $key, mixed $default = null): mixed
    {
        return $this->query[$key] ?? $default;
    }
    
    public function post(string $key, mixed $default = null): mixed
    {
        return $this->body[$key] ?? $default;
    }
    
    public function header(string $name, ?string $default = null): ?string
    {
        return $this->headers[$name] ?? $default;
    }
    
    public function bearerToken(): ?string
    {
        $header = $this->header('Authorization');
        if ($header && str_starts_with($header, 'Bearer ')) {
            return substr($header, 7);
        }
        return null;
    }
    
    public function wantsJson(): bool
    {
        $accept = $this->header('Accept', '');
        return str_contains($accept, '/json') || str_contains($accept, '+json');
    }
    
    public function isMethod(string $method): bool
    {
        return strtoupper($this->method) === strtoupper($method);
    }
    
    public function getClientIp(): string
    {
        return $this->header('X-Forwarded-For') 
            ?? $this->server['REMOTE_ADDR'] 
            ?? '127.0.0.1';
    }
    
    public function all(): array
    {
        return array_merge($this->query, $this->body);
    }
    
    public function only(array $keys): array
    {
        return array_intersect_key($this->all(), array_flip($keys));
    }
    
    public function except(array $keys): array
    {
        return array_diff_key($this->all(), array_flip($keys));
    }
    
    public function has(string $key): bool
    {
        return isset($this->body[$key]) || isset($this->query[$key]);
    }
    
    public function hasFile(string $key): bool
    {
        return isset($this->files[$key]) && $this->files[$key]['error'] === UPLOAD_ERR_OK;
    }
    
    public function file(string $key): ?array
    {
        return $this->hasFile($key) ? $this->files[$key] : null;
    }
}
```

**Reading Raw Request Body**

For JSON APIs, read and parse the raw request body:

```php
$rawBody = file_get_contents('php://input');

if ($request->header('Content-Type') === 'application/json') {
    $data = json_decode($rawBody, true, 512, JSON_THROW_ON_ERROR);
    // Use $data instead of $_POST
}
```

**HTTP Method Override**

Browsers only support GET and POST natively. For REST APIs, use method override:

```php
$method = $_SERVER['REQUEST_METHOD'] ?? 'GET';

// Check for method override via _method parameter
if ($method === 'POST' && isset($_POST['_method'])) {
    $method = strtoupper($_POST['_method']);
}

// Check for X-HTTP-Method-Override header
$override = $_SERVER['HTTP_X_HTTP_METHOD_OVERRIDE'] ?? null;
if ($override && $method === 'POST') {
    $method = strtoupper($override);
}
```

#### 17.2 Sessions and Cookies: Security and Best Practices

**Cookie Fundamentals**

Cookies store small pieces of data on the client, sent with every request to the domain that set them:

```php
// Setting a cookie
setcookie(
    'user_preference',
    'dark_mode',
    [
        'expires' => time() + 86400 * 30,  // 30 days
        'path' => '/',
        'domain' => '.example.com',         // Available to all subdomains
        'secure' => true,                    // HTTPS only
        'httponly' => true,                  // Inaccessible to JavaScript
        'samesite' => 'Lax',                // CSRF protection
    ]
);

// Reading a cookie
$preference = $_COOKIE['user_preference'] ?? 'light_mode';

// Deleting a cookie
setcookie('user_preference', '', [
    'expires' => time() - 3600,
    'path' => '/',
    'secure' => true,
    'httponly' => true,
    'samesite' => 'Lax',
]);
```

**Cookie Security Attributes**

- **secure**: Cookie only sent over HTTPS connections. Always enable in production.
- **httponly**: Cookie inaccessible to JavaScript (`document.cookie`). Prevents XSS cookie theft.
- **samesite**: Controls cross-site request cookie behavior:
  - `Strict`: Cookie never sent on cross-site requests
  - `Lax`: Cookie sent on top-level navigation, not on subrequests (forms, AJAX)
  - `None`: Cookie sent on all cross-site requests (requires `secure`)

**PHP Session Management**

Sessions maintain server-side state across requests:

```php
// Configuration (before session_start())
ini_set('session.name', 'APP_SESSION_ID');     // Custom session name
ini_set('session.cookie_lifetime', '86400');    // 24-hour session
ini_set('session.cookie_secure', '1');          // HTTPS only
ini_set('session.cookie_httponly', '1');        // No JavaScript access
ini_set('session.cookie_samesite', 'Lax');      // CSRF protection
ini_set('session.gc_maxlifetime', '86400');     // Server-side lifetime
ini_set('session.use_strict_mode', '1');        // Prevent session fixation
ini_set('session.use_only_cookies', '1');       // No session ID in URL
ini_set('session.sid_length', '48');            // Longer session IDs
ini_set('session.sid_bits_per_character', '6');  // More entropy

session_start();

// Regenerate session ID after privilege changes
session_regenerate_id(true); // Delete old session

// Store data
$_SESSION['user_id'] = $user->id;
$_SESSION['authenticated_at'] = time();

// Retrieve data
$userId = $_SESSION['user_id'] ?? null;

// Destroy session
session_destroy();
```

**Custom Session Storage**

For better performance and multi-server compatibility, use Redis for sessions:

```php
class SecureSessionHandler implements SessionHandlerInterface
{
    private Redis $redis;
    private int $lifetime;
    
    public function __construct(Redis $redis, int $lifetime = 86400)
    {
        $this->redis = $redis;
        $this->lifetime = $lifetime;
    }
    
    public function open(string $path, string $name): bool
    {
        return true;
    }
    
    public function close(): bool
    {
        return true;
    }
    
    public function read(string $id): string|false
    {
        $data = $this->redis->get("session:{$id}");
        
        if ($data !== false) {
            // Validate session fingerprint (browser/user agent binding)
            $session = unserialize($data);
            if (isset($session['_fingerprint'])) {
                $currentFingerprint = $this->generateFingerprint();
                if (!hash_equals($session['_fingerprint'], $currentFingerprint)) {
                    $this->redis->del("session:{$id}");
                    return '';
                }
            }
            return $data;
        }
        
        return '';
    }
    
    public function write(string $id, string $data): bool
    {
        // Add fingerprint to session data
        $sessionData = unserialize($data);
        if (!isset($sessionData['_fingerprint'])) {
            $sessionData['_fingerprint'] = $this->generateFingerprint();
        }
        $secured = serialize($sessionData);
        
        $this->redis->setex("session:{$id}", $this->lifetime, $secured);
        return true;
    }
    
    public function destroy(string $id): bool
    {
        $this->redis->del("session:{$id}");
        return true;
    }
    
    public function gc(int $maxLifetime): int|false
    {
        // Redis handles expiration automatically
        return 0;
    }
    
    private function generateFingerprint(): string
    {
        $components = [
            $_SERVER['HTTP_USER_AGENT'] ?? '',
            $_SERVER['HTTP_ACCEPT_LANGUAGE'] ?? '',
            // First two octets of IP (changes less frequently)
            implode('.', array_slice(explode('.', $_SERVER['REMOTE_ADDR'] ?? '0.0.0.0'), 0, 2)),
        ];
        
        return hash('sha256', implode('|', $components));
    }
}

$handler = new SecureSessionHandler($redis, 86400);
session_set_save_handler($handler, true);
session_start();
```

**Session Security Best Practices**

```php
class SessionSecurityManager
{
    public static function initialize(): void
    {
        // Prevent session fixation
        if (!isset($_SESSION['initialized'])) {
            session_regenerate_id(true);
            $_SESSION['initialized'] = true;
        }
        
        // Session timeout
        $timeout = 1800; // 30 minutes
        if (isset($_SESSION['last_activity']) && (time() - $_SESSION['last_activity'] > $timeout)) {
            session_unset();
            session_destroy();
            session_start();
        }
        $_SESSION['last_activity'] = time();
        
        // IP validation (optional, can cause issues with mobile users)
        if (isset($_SESSION['ip_address']) && $_SESSION['ip_address'] !== $_SERVER['REMOTE_ADDR']) {
            // Only enforce if IP changed significantly (different /24 subnet)
            $current = explode('.', $_SERVER['REMOTE_ADDR']);
            $stored = explode('.', $_SESSION['ip_address']);
            
            if ($current[0] !== $stored[0] || $current[1] !== $stored[1]) {
                session_destroy();
                header('Location: /login?error=session_expired');
                exit();
            }
        }
        $_SESSION['ip_address'] = $_SERVER['REMOTE_ADDR'];
    }
}
```

**Remember Me Implementation**

```php
class RememberMeToken
{
    private PDO $pdo;
    
    public function __construct(PDO $pdo)
    {
        $this->pdo = $pdo;
    }
    
    public function createToken(int $userId): string
    {
        // Generate selector and validator
        $selector = bin2hex(random_bytes(16));
        $validator = bin2hex(random_bytes(32));
        
        // Store hash of validator
        $hashedValidator = hash('sha256', $validator);
        
        $stmt = $this->pdo->prepare(
            'INSERT INTO auth_tokens (selector, hashed_validator, user_id, expires_at)
             VALUES (:selector, :validator, :user_id, :expires)'
        );
        $stmt->execute([
            'selector' => $selector,
            'validator' => $hashedValidator,
            'user_id' => $userId,
            'expires' => date('Y-m-d H:i:s', strtotime('+30 days')),
        ]);
        
        // Send selector+validator to client
        return "{$selector}:{$validator}";
    }
    
    public function validateToken(string $token): ?int
    {
        $parts = explode(':', $token);
        if (count($parts) !== 2) {
            return null;
        }
        
        [$selector, $validator] = $parts;
        
        $stmt = $this->pdo->prepare(
            'SELECT * FROM auth_tokens WHERE selector = :selector AND expires_at > NOW()'
        );
        $stmt->execute(['selector' => $selector]);
        $row = $stmt->fetch();
        
        if (!$row) {
            return null;
        }
        
        if (hash_equals($row['hashed_validator'], hash('sha256', $validator))) {
            // Delete old token and issue new one (token rotation)
            $stmt = $this->pdo->prepare('DELETE FROM auth_tokens WHERE selector = :selector');
            $stmt->execute(['selector' => $selector]);
            
            return (int) $row['user_id'];
        }
        
        // Invalid token - possible theft, delete all user tokens
        $stmt = $this->pdo->prepare('DELETE FROM auth_tokens WHERE user_id = :user_id');
        $stmt->execute(['user_id' => $row['user_id']]);
        
        return null;
    }
}
```

#### 17.3 Headers, Status Codes, and Content Negotiation

**HTTP Status Codes**

```php
class Response
{
    private const STATUS_TEXTS = [
        200 => 'OK',
        201 => 'Created',
        204 => 'No Content',
        301 => 'Moved Permanently',
        302 => 'Found',
        304 => 'Not Modified',
        400 => 'Bad Request',
        401 => 'Unauthorized',
        403 => 'Forbidden',
        404 => 'Not Found',
        405 => 'Method Not Allowed',
        409 => 'Conflict',
        422 => 'Unprocessable Entity',
        429 => 'Too Many Requests',
        500 => 'Internal Server Error',
        502 => 'Bad Gateway',
        503 => 'Service Unavailable',
    ];
    
    private int $statusCode;
    private array $headers = [];
    private mixed $body;
    
    public function __construct(mixed $body = '', int $statusCode = 200, array $headers = [])
    {
        $this->body = $body;
        $this->statusCode = $statusCode;
        $this->headers = $headers;
    }
    
    public function setStatusCode(int $code): self
    {
        $this->statusCode = $code;
        return $this;
    }
    
    public function setHeader(string $name, string $value): self
    {
        $this->headers[$name] = $value;
        return $this;
    }
    
    public static function json(array $data, int $statusCode = 200): self
    {
        return new self(
            json_encode($data, JSON_UNESCAPED_UNICODE),
            $statusCode,
            ['Content-Type' => 'application/json; charset=utf-8']
        );
    }
    
    public static function html(string $html, int $statusCode = 200): self
    {
        return new self(
            $html,
            $statusCode,
            ['Content-Type' => 'text/html; charset=utf-8']
        );
    }
    
    public static function redirect(string $url, int $statusCode = 302): self
    {
        return new self('', $statusCode, ['Location' => $url]);
    }
    
    public function send(): void
    {
        // Send status code
        http_response_code($this->statusCode);
        
        // Send headers
        foreach ($this->headers as $name => $value) {
            header("{$name}: {$value}");
        }
        
        // Send body
        echo $this->body;
    }
}
```

**Common Response Patterns**

```php
// Success responses
Response::json(['data' => $user], 200)->send();
Response::json(['message' => 'Created'], 201)->send();
Response::json(null, 204)->send();

// Redirection
Response::redirect('/login', 302)->send();
Response::redirect('/new-url', 301)->send(); // Permanent

// Client errors
Response::json(['error' => 'Not Found'], 404)->send();
Response::json(['errors' => ['name' => 'Required']], 422)->send();

// Server errors
Response::json(['error' => 'Internal Server Error'], 500)->send();
```

**Content Negotiation**

Respond to different formats based on the request's Accept header:

```php
class ContentNegotiator
{
    public function negotiateResponse(Request $request, array $data): Response
    {
        $accept = $request->header('Accept', '*/*');
        
        // Parse Accept header
        $types = $this->parseAcceptHeader($accept);
        
        foreach ($types as $type => $quality) {
            switch ($type) {
                case 'application/json':
                case 'application/vnd.api+json':
                    return Response::json($data);
                    
                case 'text/html':
                    return $this->renderHtml($data);
                    
                case 'application/xml':
                    return $this->renderXml($data);
                    
                case 'text/csv':
                    return $this->renderCsv($data);
            }
        }
        
        // Default to JSON
        return Response::json($data);
    }
    
    private function parseAcceptHeader(string $accept): array
    {
        $types = [];
        $parts = explode(',', $accept);
        
        foreach ($parts as $part) {
            $subParts = explode(';', trim($part));
            $type = trim($subParts[0]);
            $quality = 1.0;
            
            foreach (array_slice($subParts, 1) as $param) {
                if (str_starts_with(trim($param), 'q=')) {
                    $quality = (float) substr(trim($param), 2);
                }
            }
            
            $types[$type] = $quality;
        }
        
        arsort($types);
        return $types;
    }
    
    private function renderXml(array $data): Response
    {
        $xml = new SimpleXMLElement('<response/>');
        $this->arrayToXml($data, $xml);
        return new Response(
            $xml->asXML(),
            200,
            ['Content-Type' => 'application/xml; charset=utf-8']
        );
    }
    
    private function arrayToXml(array $data, SimpleXMLElement $xml): void
    {
        foreach ($data as $key => $value) {
            if (is_numeric($key)) {
                $key = 'item';
            }
            if (is_array($value)) {
                $child = $xml->addChild($key);
                $this->arrayToXml($value, $child);
            } else {
                $xml->addChild($key, htmlspecialchars((string) $value));
            }
        }
    }
}
```

**Caching Headers**

```php
class CacheHeaders
{
    public static function cacheFor(int $seconds): array
    {
        return [
            'Cache-Control' => "public, max-age={$seconds}, s-maxage={$seconds}",
            'Expires' => gmdate('D, d M Y H:i:s', time() + $seconds) . ' GMT',
        ];
    }
    
    public static function noCache(): array
    {
        return [
            'Cache-Control' => 'no-cache, no-store, must-revalidate, private',
            'Expires' => '0',
            'Pragma' => 'no-cache',
        ];
    }
    
    public static function etag(string $content): string
    {
        $etag = '"' . hash('sha256', $content) . '"';
        return $etag;
    }
    
    public static function notModified(string $etag, string $content): bool
    {
        $ifNoneMatch = $_SERVER['HTTP_IF_NONE_MATCH'] ?? '';
        if ($ifNoneMatch === $etag) {
            http_response_code(304);
            return true;
        }
        return false;
    }
}
```

#### 17.4 Handling GET, POST, PUT, DELETE, and PATCH

**Method-Based Routing**

Professional applications route requests based on HTTP method and URI:

```php
class Router
{
    private array $routes = [];
    
    public function get(string $path, callable|array $handler): self
    {
        return $this->addRoute('GET', $path, $handler);
    }
    
    public function post(string $path, callable|array $handler): self
    {
        return $this->addRoute('POST', $path, $handler);
    }
    
    public function put(string $path, callable|array $handler): self
    {
        return $this->addRoute('PUT', $path, $handler);
    }
    
    public function patch(string $path, callable|array $handler): self
    {
        return $this->addRoute('PATCH', $path, $handler);
    }
    
    public function delete(string $path, callable|array $handler): self
    {
        return $this->addRoute('DELETE', $path, $handler);
    }
    
    private function addRoute(string $method, string $path, callable|array $handler): self
    {
        $this->routes[] = [
            'method' => $method,
            'path' => $path,
            'pattern' => $this->compilePath($path),
            'handler' => $handler,
        ];
        return $this;
    }
    
    private function compilePath(string $path): string
    {
        // Convert {param} to named regex groups
        $pattern = preg_replace('/\{([a-zA-Z_]+)\}/', '(?P<$1>[^/]+)', $path);
        return '#^' . $pattern . '$#';
    }
    
    public function dispatch(Request $request): Response
    {
        $method = $request->getMethod();
        $path = $request->getPath();
        
        foreach ($this->routes as $route) {
            if ($route['method'] !== $method) {
                continue;
            }
            
            if (preg_match($route['pattern'], $path, $matches)) {
                // Extract named parameters
                $params = array_filter($matches, 'is_string', ARRAY_FILTER_USE_KEY);
                return $this->executeHandler($route['handler'], $params, $request);
            }
        }
        
        return new Response('Not Found', 404);
    }
    
    private function executeHandler(callable|array $handler, array $params, Request $request): Response
    {
        if (is_callable($handler)) {
            return $handler($request, ...$params);
        }
        
        // [Controller::class, 'method'] format
        [$class, $method] = $handler;
        $controller = new $class();
        return $controller->$method($request, ...$params);
    }
}
```

**RESTful Controller Example**

```php
class ArticleController
{
    private ArticleRepository $articles;
    
    public function __construct()
    {
        $this->articles = new ArticleRepository();
    }
    
    // GET /articles - List all articles
    // GET /articles?page=2&per_page=20&sort=title&order=asc
    public function index(Request $request): Response
    {
        $page = max(1, (int) ($request->query('page', 1)));
        $perPage = min(100, max(1, (int) ($request->query('per_page', 20))));
        $sort = $request->query('sort', 'created_at');
        $order = strtoupper($request->query('order', 'DESC')) === 'ASC' ? 'ASC' : 'DESC';
        
        $articles = $this->articles->paginate($page, $perPage, $sort, $order);
        
        return Response::json([
            'data' => $articles->toArray(),
            'meta' => [
                'current_page' => $page,
                'per_page' => $perPage,
                'total' => $articles->total(),
                'total_pages' => $articles->lastPage(),
            ],
        ]);
    }
    
    // GET /articles/{id} - Show single article
    public function show(Request $request, int $id): Response
    {
        $article = $this->articles->find($id);
        
        if (!$article) {
            return Response::json(['error' => 'Article not found'], 404);
        }
        
        // Check If-None-Match for caching
        $etag = CacheHeaders::etag(json_encode($article));
        if (CacheHeaders::notModified($etag, '')) {
            return new Response('', 304);
        }
        
        return Response::json(['data' => $article], 200)
            ->setHeader('ETag', $etag);
    }
    
    // POST /articles - Create new article
    public function store(Request $request): Response
    {
        $data = json_decode(file_get_contents('php://input'), true);
        
        // Validate input
        $validator = new ArticleValidator();
        $errors = $validator->validate($data);
        
        if (!empty($errors)) {
            return Response::json(['errors' => $errors], 422);
        }
        
        $article = $this->articles->create($data);
        
        return Response::json(['data' => $article], 201)
            ->setHeader('Location', "/articles/{$article->id}");
    }
    
    // PUT /articles/{id} - Replace entire article
    public function replace(Request $request, int $id): Response
    {
        $article = $this->articles->find($id);
        
        if (!$article) {
            return Response::json(['error' => 'Article not found'], 404);
        }
        
        $data = json_decode(file_get_contents('php://input'), true);
        
        // Validate all fields (PUT requires complete representation)
        $validator = new ArticleValidator();
        $errors = $validator->validateAll($data);
        
        if (!empty($errors)) {
            return Response::json(['errors' => $errors], 422);
        }
        
        $article = $this->articles->replace($id, $data);
        
        return Response::json(['data' => $article]);
    }
    
    // PATCH /articles/{id} - Partial update
    public function update(Request $request, int $id): Response
    {
        $article = $this->articles->find($id);
        
        if (!$article) {
            return Response::json(['error' => 'Article not found'], 404);
        }
        
        $data = json_decode(file_get_contents('php://input'), true);
        
        // Validate only provided fields
        $validator = new ArticleValidator();
        $errors = $validator->validatePartial($data);
        
        if (!empty($errors)) {
            return Response::json(['errors' => $errors], 422);
        }
        
        $article = $this->articles->update($id, $data);
        
        return Response::json(['data' => $article]);
    }
    
    // DELETE /articles/{id} - Delete article
    public function destroy(Request $request, int $id): Response
    {
        $article = $this->articles->find($id);
        
        if (!$article) {
            return Response::json(['error' => 'Article not found'], 404);
        }
        
        $this->articles->delete($id);
        
        return new Response('', 204);
    }
}

// Route registration
$router = new Router();

$router->get('/articles', [ArticleController::class, 'index']);
$router->get('/articles/{id}', [ArticleController::class, 'show']);
$router->post('/articles', [ArticleController::class, 'store']);
$router->put('/articles/{id}', [ArticleController::class, 'replace']);
$router->patch('/articles/{id}', [ArticleController::class, 'update']);
$router->delete('/articles/{id}', [ArticleController::class, 'destroy']);
```

**Handling File Uploads**

```php
class FileUploadController
{
    private const ALLOWED_MIME_TYPES = [
        'image/jpeg' => 'jpg',
        'image/png' => 'png',
        'image/gif' => 'gif',
        'image/webp' => 'webp',
        'application/pdf' => 'pdf',
    ];
    
    private const MAX_FILE_SIZE = 10 * 1024 * 1024; // 10MB
    
    // POST /uploads
    public function upload(Request $request): Response
    {
        $file = $request->file('file');
        
        if (!$file) {
            return Response::json(['error' => 'No file uploaded'], 400);
        }
        
        // Validate size
        if ($file['size'] > self::MAX_FILE_SIZE) {
            return Response::json(['error' => 'File too large. Maximum size is 10MB.'], 422);
        }
        
        // Validate MIME type using fileinfo
        $finfo = new finfo(FILEINFO_MIME_TYPE);
        $mimeType = $finfo->file($file['tmp_name']);
        
        if (!isset(self::ALLOWED_MIME_TYPES[$mimeType])) {
            return Response::json(['error' => "File type '{$mimeType}' not allowed."], 422);
        }
        
        // Store file
        $extension = self::ALLOWED_MIME_TYPES[$mimeType];
        $filename = bin2hex(random_bytes(16)) . '.' . $extension;
        $storagePath = '/var/www/storage/uploads/' . date('Y/m/d');
        
        if (!is_dir($storagePath)) {
            mkdir($storagePath, 0755, true);
        }
        
        $destination = $storagePath . '/' . $filename;
        
        if (!move_uploaded_file($file['tmp_name'], $destination)) {
            return Response::json(['error' => 'Failed to store file.'], 500);
        }
        
        // Record in database
        $fileRecord = [
            'original_name' => $file['name'],
            'stored_path' => $destination,
            'mime_type' => $mimeType,
            'size' => $file['size'],
            'created_at' => date('Y-m-d H:i:s'),
        ];
        
        return Response::json(['data' => $fileRecord], 201);
    }
}
```

---

### Chapter 18: Building APIs

#### 18.1 RESTful Architecture and Resource Design

REST (Representational State Transfer) is an architectural style for designing networked applications. Well-designed REST APIs are intuitive, consistent, and follow established conventions.

**REST Principles**

1. **Stateless**: Each request contains all information needed to process it.
2. **Resource-Based**: Resources (nouns) are identified by URIs.
3. **Standard Methods**: HTTP methods define operations on resources.
4. **Representations**: Resources can have multiple representations (JSON, XML).
5. **HATEOAS**: Responses include links to related resources (optional but recommended).

**Resource Naming Conventions**

```php
// Good: Plural nouns, hierarchical relationships
GET    /articles              // List articles
GET    /articles/123          // Get article 123
GET    /articles/123/comments // Get comments for article 123
POST   /articles              // Create article
PUT    /articles/123          // Replace article 123
PATCH  /articles/123          // Update article 123 partially
DELETE /articles/123          // Delete article 123

// Avoid: Verbs in URIs
// GET /getArticles        ❌ Wrong
// POST /createArticle     ❌ Wrong
// POST /articles          ✅ Correct (creates)

// Good: Query parameters for filtering/pagination
GET /articles?status=published&page=2&per_page=20

// Good: Sub-resources for relationships
GET /users/42/orders           // User's orders
POST /users/42/orders          // Create order for user
GET /orders/789/items          // Items in an order
```

**API Versioning Strategies**

```php
// Strategy 1: URI Versioning (most common)
// https://api.example.com/v1/articles
// https://api.example.com/v2/articles

// Strategy 2: Header Versioning
// Accept: application/vnd.api.v1+json
// Accept: application/vnd.api.v2+json

// Strategy 3: Query Parameter Versioning
// https://api.example.com/articles?version=1

// Implementation with URI versioning
$router->group('/v1', function (Router $router): void {
    $router->get('/articles', [ArticleController::class, 'index']);
    $router->get('/articles/{id}', [ArticleController::class, 'show']);
});

$router->group('/v2', function (Router $router): void {
    $router->get('/articles', [ArticleV2Controller::class, 'index']);
    $router->get('/articles/{id}', [ArticleV2Controller::class, 'show']);
    // V2 includes author data
});
```

**Resource Response Format**

```php
class ApiResource
{
    public static function collection(array $items, array $meta = []): array
    {
        return [
            'data' => array_map(fn($item) => self::transform($item), $items),
            'meta' => $meta,
            'links' => self::collectionLinks(),
        ];
    }
    
    public static function item($item): array
    {
        return [
            'data' => self::transform($item),
        ];
    }
    
    public static function created($item, string $location): Response
    {
        return Response::json(['data' => self::transform($item)], 201)
            ->setHeader('Location', $location);
    }
    
    private static function transform($item): array
    {
        if ($item instanceof Article) {
            return [
                'id' => $item->id,
                'type' => 'articles',
                'attributes' => [
                    'title' => $item->title,
                    'content' => $item->content,
                    'status' => $item->status->value,
                    'created_at' => $item->createdAt->format('c'),
                    'updated_at' => $item->updatedAt?->format('c'),
                ],
                'relationships' => [
                    'author' => [
                        'data' => ['id' => $item->authorId, 'type' => 'users'],
                        'links' => [
                            'related' => "/api/v1/users/{$item->authorId}",
                        ],
                    ],
                ],
                'links' => [
                    'self' => "/api/v1/articles/{$item->id}",
                ],
            ];
        }
        
        return [];
    }
    
    private static function collectionLinks(): array
    {
        return [
            'self' => $_SERVER['REQUEST_URI'],
        ];
    }
}
```

**Error Response Format**

```php
class ApiError
{
    public static function notFound(string $message = 'Resource not found'): Response
    {
        return self::error(404, 'not_found', $message);
    }
    
    public static function validationFailed(array $errors): Response
    {
        return self::error(422, 'validation_failed', 'Validation failed', $errors);
    }
    
    public static function unauthorized(string $message = 'Unauthorized'): Response
    {
        return self::error(401, 'unauthorized', $message);
    }
    
    public static function forbidden(string $message = 'Forbidden'): Response
    {
        return self::error(403, 'forbidden', $message);
    }
    
    public static function serverError(string $message = 'Internal server error'): Response
    {
        return self::error(500, 'server_error', $message);
    }
    
    private static function error(
        int $statusCode,
        string $code,
        string $message,
        ?array $details = null,
    ): Response {
        $body = [
            'error' => [
                'code' => $code,
                'message' => $message,
                'status' => $statusCode,
            ],
        ];
        
        if ($details !== null) {
            $body['error']['details'] = $details;
        }
        
        return Response::json($body, $statusCode);
    }
}
```

#### 18.2 JSON Serialization and Validation

**JSON API Request Processing**

```php
abstract class ApiController
{
    protected function parseJsonBody(Request $request): array
    {
        $contentType = $request->header('Content-Type', '');
        
        if (!str_contains($contentType, 'application/json')) {
            throw new ApiException(
                'Content-Type must be application/json',
                415
            );
        }
        
        $body = file_get_contents('php://input');
        
        if (empty($body)) {
            throw new ApiException('Request body is empty', 400);
        }
        
        try {
            $data = json_decode(
                $body,
                true,
                512,
                JSON_THROW_ON_ERROR | JSON_BIGINT_AS_STRING
            );
        } catch (\JsonException $e) {
            throw new ApiException(
                'Invalid JSON: ' . $e->getMessage(),
                400,
                $e
            );
        }
        
        return $data;
    }
}
```

**JSON Serialization with Custom Classes**

```php
interface JsonSerializable
{
    public function jsonSerialize(): mixed;
}

class User implements \JsonSerializable
{
    public function __construct(
        public readonly int $id,
        public readonly string $name,
        public readonly string $email,
        private readonly string $passwordHash,
        public readonly ?DateTimeImmutable $createdAt = null,
    ) {}
    
    public function jsonSerialize(): array
    {
        return [
            'id' => $this->id,
            'name' => $this->name,
            'email' => $this->email,
            // Note: passwordHash is excluded intentionally
            'created_at' => $this->createdAt?->format('c'),
        ];
    }
}

// Custom JSON encoder with date handling
class JsonEncoder
{
    public static function encode(mixed $data, int $flags = 0): string
    {
        $flags |= JSON_UNESCAPED_UNICODE | JSON_UNESCAPED_SLASHES;
        
        return json_encode($data, $flags, 512);
    }
    
    public static function encodeResponse(array $data, int $statusCode = 200): Response
    {
        $json = self::encode($data, JSON_PRETTY_PRINT);
        
        if (json_last_error() !== JSON_ERROR_NONE) {
            throw new \RuntimeException('JSON encoding failed: ' . json_last_error_msg());
        }
        
        return new Response(
            $json,
            $statusCode,
            ['Content-Type' => 'application/json; charset=utf-8']
        );
    }
}
```

**Input Validation**

```php
class Validator
{
    private array $errors = [];
    private array $data;
    
    public function __construct(array $data)
    {
        $this->data = $data;
    }
    
    public function required(string ...$fields): self
    {
        foreach ($fields as $field) {
            if (!isset($this->data[$field]) || $this->data[$field] === '') {
                $this->errors[$field][] = "The {$field} field is required.";
            }
        }
        return $this;
    }
    
    public function email(string ...$fields): self
    {
        foreach ($fields as $field) {
            if (isset($this->data[$field]) && $this->data[$field] !== '') {
                if (!filter_var($this->data[$field], FILTER_VALIDATE_EMAIL)) {
                    $this->errors[$field][] = "The {$field} must be a valid email address.";
                }
            }
        }
        return $this;
    }
    
    public function string(string ...$fields): self
    {
        foreach ($fields as $field) {
            if (isset($this->data[$field]) && !is_string($this->data[$field])) {
                $this->errors[$field][] = "The {$field} must be a string.";
            }
        }
        return $this;
    }
    
    public function integer(string ...$fields): self
    {
        foreach ($fields as $field) {
            if (isset($this->data[$field]) && !is_int($this->data[$field])) {
                $this->errors[$field][] = "The {$field} must be an integer.";
            }
        }
        return $this;
    }
    
    public function min(string $field, int $min): self
    {
        if (isset($this->data[$field])) {
            $value = $this->data[$field];
            
            if (is_string($value) && mb_strlen($value) < $min) {
                $this->errors[$field][] = "The {$field} must be at least {$min} characters.";
            }
            
            if (is_int($value) && $value < $min) {
                $this->errors[$field][] = "The {$field} must be at least {$min}.";
            }
        }
        return $this;
    }
    
    public function max(string $field, int $max): self
    {
        if (isset($this->data[$field])) {
            $value = $this->data[$field];
            
            if (is_string($value) && mb_strlen($value) > $max) {
                $this->errors[$field][] = "The {$field} must not exceed {$max} characters.";
            }
            
            if (is_int($value) && $value > $max) {
                $this->errors[$field][] = "The {$field} must not exceed {$max}.";
            }
        }
        return $this;
    }
    
    public function in(string $field, array $values): self
    {
        if (isset($this->data[$field]) && !in_array($this->data[$field], $values, true)) {
            $allowed = implode(', ', $values);
            $this->errors[$field][] = "The {$field} must be one of: {$allowed}.";
        }
        return $this;
    }
    
    public function nullable(string ...$fields): self
    {
        foreach ($fields as $field) {
            if (isset($this->data[$field]) && $this->data[$field] === null) {
                // Allow null values
                continue;
            }
        }
        return $this;
    }
    
    public function custom(string $field, callable $callback, string $message): self
    {
        if (isset($this->data[$field])) {
            if (!$callback($this->data[$field], $this->data)) {
                $this->errors[$field][] = $message;
            }
        }
        return $this;
    }
    
    public function passes(): bool
    {
        return empty($this->errors);
    }
    
    public function fails(): bool
    {
        return !$this->passes();
    }
    
    public function errors(): array
    {
        return $this->errors;
    }
    
    public function validated(): array
    {
        if ($this->fails()) {
            throw new ValidationException($this->errors);
        }
        
        return $this->data;
    }
}

// Usage in controller
class UserController extends ApiController
{
    public function store(Request $request): Response
    {
        try {
            $data = $this->parseJsonBody($request);
            
            $validator = (new Validator($data))
                ->required('name', 'email', 'password')
                ->string('name')
                ->min('name', 2)
                ->max('name', 100)
                ->email('email')
                ->string('password')
                ->min('password', 8)
                ->max('password', 100)
                ->custom('name', function (string $name): bool {
                    return !preg_match('/<[^>]*>/', $name);
                }, 'The name must not contain HTML tags.');
            
            if ($validator->fails()) {
                return ApiError::validationFailed($validator->errors());
            }
            
            $validatedData = $validator->validated();
            $user = $this->users->create($validatedData);
            
            return ApiResource::created($user, "/api/v1/users/{$user->id}");
            
        } catch (ApiException $e) {
            return Response::json(['error' => $e->getMessage()], $e->getCode());
        }
    }
}
```

#### 18.3 Authentication: API Keys, OAuth2, and JWT

**API Key Authentication**

```php
class ApiKeyAuthenticator
{
    private PDO $pdo;
    
    public function __construct(PDO $pdo)
    {
        $this->pdo = $pdo;
    }
    
    public function authenticate(Request $request): ?int
    {
        $apiKey = $this->extractKey($request);
        
        if ($apiKey === null) {
            return null;
        }
        
        // Hash the key for lookup (store hashed keys, not plaintext)
        $hashedKey = hash('sha256', $apiKey);
        
        $stmt = $this->pdo->prepare(
            'SELECT user_id, permissions, expires_at 
             FROM api_keys 
             WHERE hashed_key = :key AND revoked_at IS NULL'
        );
        $stmt->execute(['key' => $hashedKey]);
        $row = $stmt->fetch();
        
        if (!$row) {
            return null;
        }
        
        if ($row['expires_at'] && new DateTime($row['expires_at']) < new DateTime()) {
            return null;
        }
        
        // Update last used timestamp
        $stmt = $this->pdo->prepare(
            'UPDATE api_keys SET last_used_at = NOW() WHERE hashed_key = :key'
        );
        $stmt->execute(['key' => $hashedKey]);
        
        return (int) $row['user_id'];
    }
    
    private function extractKey(Request $request): ?string
    {
        // Check Authorization header
        $auth = $request->header('Authorization');
        if ($auth && str_starts_with($auth, 'Bearer ')) {
            return substr($auth, 7);
        }
        
        // Check X-API-Key header
        $apiKey = $request->header('X-API-Key');
        if ($apiKey) {
            return $apiKey;
        }
        
        // Check query parameter (least secure, avoid if possible)
        return $request->query('api_key');
    }
}
```

**JWT (JSON Web Token) Authentication**

```php
class JwtAuth
{
    private string $secret;
    private string $algorithm;
    private int $accessTokenExpiry;
    private int $refreshTokenExpiry;
    
    public function __construct(
        string $secret,
        string $algorithm = 'HS256',
        int $accessTokenExpiry = 3600,
        int $refreshTokenExpiry = 604800,
    ) {
        $this->secret = $secret;
        $this->algorithm = $algorithm;
        $this->accessTokenExpiry = $accessTokenExpiry;
        $this->refreshTokenExpiry = $refreshTokenExpiry;
    }
    
    public function generateAccessToken(int $userId, array $claims = []): string
    {
        $payload = array_merge($claims, [
            'sub' => $userId,
            'iat' => time(),
            'exp' => time() + $this->accessTokenExpiry,
            'type' => 'access',
        ]);
        
        return $this->encode($payload);
    }
    
    public function generateRefreshToken(int $userId): string
    {
        $payload = [
            'sub' => $userId,
            'iat' => time(),
            'exp' => time() + $this->refreshTokenExpiry,
            'type' => 'refresh',
            'jti' => bin2hex(random_bytes(16)),
        ];
        
        return $this->encode($payload);
    }
    
    public function validateToken(string $token): ?array
    {
        try {
            $payload = $this->decode($token);
            
            // Verify expiration
            if (isset($payload['exp']) && $payload['exp'] < time()) {
                return null;
            }
            
            return $payload;
        } catch (\Exception $e) {
            return null;
        }
    }
    
    private function encode(array $payload): string
    {
        $header = ['alg' => $this->algorithm, 'typ' => 'JWT'];
        
        $segments = [
            $this->base64UrlEncode(json_encode($header)),
            $this->base64UrlEncode(json_encode($payload)),
        ];
        
        $signingInput = implode('.', $segments);
        $signature = hash_hmac('sha256', $signingInput, $this->secret, true);
        $segments[] = $this->base64UrlEncode($signature);
        
        return implode('.', $segments);
    }
    
    private function decode(string $token): array
    {
        $parts = explode('.', $token);
        
        if (count($parts) !== 3) {
            throw new \RuntimeException('Invalid token format');
        }
        
        [$header, $payload, $signature] = $parts;
        
        // Verify signature
        $signingInput = "{$header}.{$payload}";
        $expectedSignature = $this->base64UrlEncode(
            hash_hmac('sha256', $signingInput, $this->secret, true)
        );
        
        if (!hash_equals($expectedSignature, $signature)) {
            throw new \RuntimeException('Invalid signature');
        }
        
        return json_decode($this->base64UrlDecode($payload), true, 512, JSON_THROW_ON_ERROR);
    }
    
    private function base64UrlEncode(string $data): string
    {
        return rtrim(strtr(base64_encode($data), '+/', '-_'), '=');
    }
    
    private function base64UrlDecode(string $data): string
    {
        return base64_decode(strtr($data, '-_', '+/'));
    }
}

// Authentication middleware
class AuthMiddleware
{
    private JwtAuth $jwt;
    
    public function __construct(JwtAuth $jwt)
    {
        $this->jwt = $jwt;
    }
    
    public function handle(Request $request, callable $next): Response
    {
        $token = $this->extractToken($request);
        
        if ($token === null) {
            return ApiError::unauthorized('No authentication token provided');
        }
        
        $payload = $this->jwt->validateToken($token);
        
        if ($payload === null) {
            return ApiError::unauthorized('Invalid or expired token');
        }
        
        // Add user ID to request for downstream handlers
        $request = $request->withAttribute('user_id', $payload['sub']);
        
        return $next($request);
    }
    
    private function extractToken(Request $request): ?string
    {
        $auth = $request->header('Authorization');
        
        if ($auth && str_starts_with($auth, 'Bearer ')) {
            return substr($auth, 7);
        }
        
        return null;
    }
}
```

**OAuth2 Flow**

```php
class OAuth2Server
{
    private PDO $pdo;
    private string $clientSecret;
    
    public function authorize(Request $request): Response
    {
        $clientId = $request->query('client_id');
        $redirectUri = $request->query('redirect_uri');
        $responseType = $request->query('response_type');
        $scope = $request->query('scope', '');
        $state = $request->query('state', '');
        
        // Validate client
        $client = $this->validateClient($clientId, $redirectUri);
        if (!$client) {
            return ApiError::notFound('Invalid client');
        }
        
        // For authorization code flow, redirect user to login
        if (!isset($_SESSION['user_id'])) {
            $_SESSION['oauth_request'] = [
                'client_id' => $clientId,
                'redirect_uri' => $redirectUri,
                'response_type' => $responseType,
                'scope' => $scope,
                'state' => $state,
            ];
            return Response::redirect('/login');
        }
        
        // Generate authorization code
        $code = bin2hex(random_bytes(32));
        
        // Store authorization code
        $stmt = $this->pdo->prepare(
            'INSERT INTO oauth_codes (code, client_id, user_id, scope, expires_at)
             VALUES (:code, :client_id, :user_id, :scope, DATE_ADD(NOW(), INTERVAL 10 MINUTE))'
        );
        $stmt->execute([
            'code' => hash('sha256', $code),
            'client_id' => $clientId,
            'user_id' => $_SESSION['user_id'],
            'scope' => $scope,
        ]);
        
        // Build redirect
        $redirectUrl = $redirectUri . '?' . http_build_query([
            'code' => $code,
            'state' => $state,
        ]);
        
        return Response::redirect($redirectUrl);
    }
    
    public function token(Request $request): Response
    {
        $grantType = $request->post('grant_type');
        
        return match ($grantType) {
            'authorization_code' => $this->handleAuthorizationCodeGrant($request),
            'refresh_token' => $this->handleRefreshTokenGrant($request),
            'client_credentials' => $this->handleClientCredentialsGrant($request),
            default => ApiError::notFound('Unsupported grant type'),
        };
    }
    
    private function handleAuthorizationCodeGrant(Request $request): Response
    {
        $code = $request->post('code');
        $redirectUri = $request->post('redirect_uri');
        $clientId = $request->post('client_id');
        $clientSecret = $request->post('client_secret');
        
        // Validate client credentials
        $client = $this->validateClient($clientId, $redirectUri, $clientSecret);
        if (!$client) {
            return ApiError::unauthorized('Invalid client credentials');
        }
        
        // Validate authorization code
        $hashedCode = hash('sha256', $code);
        $stmt = $this->pdo->prepare(
            'SELECT * FROM oauth_codes WHERE code = :code AND client_id = :client_id AND expires_at > NOW()'
        );
        $stmt->execute(['code' => $hashedCode, 'client_id' => $clientId]);
        $authCode = $stmt->fetch();
        
        if (!$authCode) {
            return ApiError::unauthorized('Invalid or expired authorization code');
        }
        
        // Delete used code
        $stmt = $this->pdo->prepare('DELETE FROM oauth_codes WHERE code = :code');
        $stmt->execute(['code' => $hashedCode]);
        
        // Generate tokens
        $jwt = new JwtAuth($_ENV['JWT_SECRET']);
        $accessToken = $jwt->generateAccessToken($authCode['user_id']);
        $refreshToken = $jwt->generateRefreshToken($authCode['user_id']);
        
        return Response::json([
            'access_token' => $accessToken,
            'token_type' => 'Bearer',
            'expires_in' => 3600,
            'refresh_token' => $refreshToken,
            'scope' => $authCode['scope'],
        ]);
    }
    
    private function validateClient(string $clientId, string $redirectUri, ?string $secret = null): ?array
    {
        $stmt = $this->pdo->prepare(
            'SELECT * FROM oauth_clients WHERE client_id = :client_id AND redirect_uri = :redirect_uri'
        );
        $stmt->execute(['client_id' => $clientId, 'redirect_uri' => $redirectUri]);
        $client = $stmt->fetch();
        
        if (!$client) {
            return null;
        }
        
        if ($secret !== null && !hash_equals($client['client_secret'], $secret)) {
            return null;
        }
        
        return $client;
    }
    
    private function handleRefreshTokenGrant(Request $request): Response
    {
        // Validate refresh token and issue new tokens
        // Similar to access token generation
    }
    
    private function handleClientCredentialsGrant(Request $request): Response
    {
        // Machine-to-machine authentication
        // No user context, only client authentication
    }
}
```

#### 18.4 Rate Limiting and Versioning

**Rate Limiting Implementation**

```php
class RateLimiter
{
    private Redis $redis;
    
    public function __construct(Redis $redis)
    {
        $this->redis = $redis;
    }
    
    public function tooManyAttempts(string $key, int $maxAttempts, int $decaySeconds): bool
    {
        $key = "ratelimit:{$key}";
        $now = microtime(true);
        $windowStart = $now - $decaySeconds;
        
        // Remove expired entries
        $this->redis->zRemRangeByScore($key, '-inf', $windowStart);
        
        // Count attempts in window
        $attempts = $this->redis->zCard($key);
        
        if ($attempts >= $maxAttempts) {
            return true;
        }
        
        // Add this attempt
        $this->redis->zAdd($key, $now, uniqid('', true) . microtime());
        $this->redis->expire($key, $decaySeconds + 1);
        
        return false;
    }
    
    public function getRemainingAttempts(string $key, int $maxAttempts, int $decaySeconds): int
    {
        $key = "ratelimit:{$key}";
        $windowStart = microtime(true) - $decaySeconds;
        
        $this->redis->zRemRangeByScore($key, '-inf', $windowStart);
        $attempts = $this->redis->zCard($key);
        
        return max(0, $maxAttempts - $attempts);
    }
    
    public function retryAfter(string $key, int $decaySeconds): int
    {
        $key = "ratelimit:{$key}";
        $oldest = $this->redis->zRange($key, 0, 0, true);
        
        if (empty($oldest)) {
            return 0;
        }
        
        $oldestTime = reset($oldest);
        return max(0, (int) ceil($oldestTime + $decaySeconds - microtime(true)));
    }
}

// Rate limiting middleware
class RateLimitMiddleware
{
    private RateLimiter $limiter;
    private int $maxAttempts;
    private int $decaySeconds;
    
    public function __construct(RateLimiter $limiter, int $maxAttempts = 60, int $decaySeconds = 60)
    {
        $this->limiter = $limiter;
        $this->maxAttempts = $maxAttempts;
        $this->decaySeconds = $decaySeconds;
    }
    
    public function handle(Request $request, callable $next): Response
    {
        $key = $this->resolveRequestSignature($request);
        
        if ($this->limiter->tooManyAttempts($key, $this->maxAttempts, $this->decaySeconds)) {
            $retryAfter = $this->limiter->retryAfter($key, $this->decaySeconds);
            
            return new Response(
                json_encode(['error' => 'Too Many Requests', 'retry_after' => $retryAfter]),
                429,
                [
                    'Content-Type' => 'application/json',
                    'Retry-After' => (string) $retryAfter,
                    'X-RateLimit-Limit' => (string) $this->maxAttempts,
                    'X-RateLimit-Remaining' => '0',
                ]
            );
        }
        
        $response = $next($request);
        
        $remaining = $this->limiter->getRemainingAttempts($key, $this->maxAttempts, $this->decaySeconds);
        
        return $response
            ->setHeader('X-RateLimit-Limit', (string) $this->maxAttempts)
            ->setHeader('X-RateLimit-Remaining', (string) $remaining);
    }
    
    private function resolveRequestSignature(Request $request): string
    {
        // Use authenticated user ID if available, otherwise IP
        return $request->getAttribute('user_id') 
            ?? sha1($request->getClientIp());
    }
}
```

#### 18.5 Introduction to GraphQL with PHP

GraphQL provides a flexible alternative to REST for complex data requirements.

**Basic GraphQL Server Setup**

```php
class GraphQLServer
{
    private array $schema;
    private array $resolvers;
    
    public function schema(array $schema): self
    {
        $this->schema = $schema;
        return $this;
    }
    
    public function resolvers(array $resolvers): self
    {
        $this->resolvers = $resolvers;
        return $this;
    }
    
    public function handle(Request $request): Response
    {
        $body = json_decode(file_get_contents('php://input'), true);
        
        $query = $body['query'] ?? '';
        $variables = $body['variables'] ?? [];
        $operationName = $body['operationName'] ?? null;
        
        try {
            $result = $this->execute($query, $variables, $operationName);
            return Response::json($result);
        } catch (\Exception $e) {
            return Response::json([
                'errors' => [['message' => $e->getMessage()]],
            ], 400);
        }
    }
    
    private function execute(string $query, array $variables, ?string $operationName): array
    {
        // Parse query (simplified - in production use a proper parser)
        $ast = $this->parseQuery($query);
        $operation = $this->findOperation($ast, $operationName);
        
        return $this->executeOperation($operation, $variables);
    }
    
    private function executeOperation(array $operation, array $variables): array
    {
        $rootField = $operation['selections'][0];
        $fieldName = $rootField['name'];
        
        // Call resolver
        $resolver = $this->resolvers['Query'][$fieldName] ?? null;
        if (!$resolver) {
            throw new \RuntimeException("No resolver for {$fieldName}");
        }
        
        $args = $this->resolveArgs($rootField['arguments'] ?? [], $variables);
        $result = $resolver($args);
        
        // Resolve sub-fields
        return [
            'data' => [
                $fieldName => $this->resolveFields($result, $rootField['selections'] ?? []),
            ],
        ];
    }
    
    private function resolveFields(mixed $parent, array $selections): array
    {
        $data = [];
        
        foreach ($selections as $selection) {
            $fieldName = $selection['name'];
            
            if (is_array($parent)) {
                $data[$fieldName] = $parent[$fieldName] ?? null;
            } elseif (is_object($parent)) {
                $method = 'get' . ucfirst($fieldName);
                $data[$fieldName] = method_exists($parent, $method) 
                    ? $parent->$method() 
                    : ($parent->$fieldName ?? null);
            }
            
            // Resolve nested selections
            if (!empty($selection['selections'])) {
                $nestedData = $data[$fieldName];
                $data[$fieldName] = is_array($nestedData) && isset($nestedData[0])
                    ? array_map(fn($item) => $this->resolveFields($item, $selection['selections']), $nestedData)
                    : $this->resolveFields($nestedData, $selection['selections']);
            }
        }
        
        return $data;
    }
    
    private function parseQuery(string $query): array
    {
        // Simplified parser - in production use webonyx/graphql-php
        return [];
    }
    
    private function findOperation(array $ast, ?string $operationName): array
    {
        // Find the requested operation
        return [];
    }
    
    private function resolveArgs(array $args, array $variables): array
    {
        $resolved = [];
        foreach ($args as $arg) {
            $value = $arg['value'];
            if (str_starts_with($value, '$')) {
                $varName = substr($value, 1);
                $resolved[$arg['name']] = $variables[$varName] ?? null;
            } else {
                $resolved[$arg['name']] = $value;
            }
        }
        return $resolved;
    }
}

// Schema definition and resolvers
$server = new GraphQLServer();

$server->schema([
    'Query' => [
        'fields' => [
            'user' => ['type' => 'User', 'args' => ['id' => 'Int!']],
            'articles' => ['type' => '[Article]', 'args' => ['page' => 'Int', 'limit' => 'Int']],
        ],
    ],
    'User' => [
        'fields' => [
            'id' => 'Int',
            'name' => 'String',
            'email' => 'String',
            'posts' => '[Article]',
        ],
    ],
]);

$userRepository = new UserRepository();
$articleRepository = new ArticleRepository();

$server->resolvers([
    'Query' => [
        'user' => fn(array $args) => $userRepository->find($args['id']),
        'articles' => fn(array $args) => $articleRepository->paginate(
            $args['page'] ?? 1,
            $args['limit'] ?? 20,
        ),
    ],
    'User' => [
        'posts' => fn(User $user) => $articleRepository->findByAuthor($user->id),
    ],
]);
```

---

### Chapter 19: Templating and Frontend Integration

#### 19.1 Separation of Concerns and MVC Basics

The Model-View-Controller pattern separates application logic from presentation:

```php
// Model: Business logic and data
class Article
{
    public function __construct(
        public readonly int $id,
        public readonly string $title,
        public readonly string $content,
        public readonly DateTimeImmutable $createdAt,
    ) {}
}

class ArticleRepository
{
    public function findLatest(int $limit = 10): array
    {
        // Database query
        return [];
    }
}

// Controller: Handles requests, coordinates model and view
class HomeController
{
    private ArticleRepository $articles;
    
    public function __construct(ArticleRepository $articles)
    {
        $this->articles = $articles;
    }
    
    public function index(): Response
    {
        $articles = $this->articles->findLatest(5);
        
        return new ViewResponse('home', [
            'articles' => $articles,
            'pageTitle' => 'Latest Articles',
        ]);
    }
}

// View: Presentation logic only
// templates/home.php
?>
<?php $this->layout('main', ['title' => $pageTitle]) ?>

<h1>Latest Articles</h1>

<?php if (empty($articles)): ?>
    <p>No articles yet.</p>
<?php else: ?>
    <div class="articles">
        <?php foreach ($articles as $article): ?>
            <article class="article-card">
                <h2>
                    <a href="/articles/<?= $article->id ?>">
                        <?= htmlspecialchars($article->title, ENT_QUOTES, 'UTF-8') ?>
                    </a>
                </h2>
                <time datetime="<?= $article->createdAt->format('c') ?>">
                    <?= $article->createdAt->format('F j, Y') ?>
                </time>
                <p><?= nl2br(htmlspecialchars(
                    mb_substr($article->content, 0, 200) . '...',
                    ENT_QUOTES,
                    'UTF-8'
                )) ?></p>
            </article>
        <?php endforeach; ?>
    </div>
<?php endif; ?>
```

#### 19.2 Native PHP Templating

PHP itself is a templating language. With proper practices, native PHP templates are fast and maintainable.

**Template Engine Class**

```php
class View
{
    private string $templatesPath;
    private ?string $layout = null;
    private array $sections = [];
    private string $currentSection = '';
    
    public function __construct(string $templatesPath)
    {
        $this->templatesPath = rtrim($templatesPath, '/');
    }
    
    public function render(string $template, array $data = []): string
    {
        // Extract variables for template
        extract($data, EXTR_SKIP);
        
        // Start output buffering
        ob_start();
        
        // Include the template
        include $this->templatesPath . '/' . $template . '.php';
        
        $content = ob_get_clean();
        
        // Apply layout if set
        if ($this->layout) {
            $layout = $this->layout;
            $this->layout = null;
            
            ob_start();
            include $this->templatesPath . '/' . $layout . '.php';
            return ob_get_clean();
        }
        
        return $content;
    }
    
    protected function layout(string $name): void
    {
        $this->layout = $name;
    }
    
    protected function section(string $name): void
    {
        $this->currentSection = $name;
        ob_start();
    }
    
    protected function endSection(): void
    {
        $this->sections[$this->currentSection] = ob_get_clean();
    }
    
    protected function yield(string $name): void
    {
        echo $this->sections[$name] ?? '';
    }
    
    protected function include(string $template, array $data = []): void
    {
        echo $this->render($template, $data);
    }
    
    // Helper methods for escaping
    protected function e(?string $value): string
    {
        return htmlspecialchars($value ?? '', ENT_QUOTES | ENT_SUBSTITUTE, 'UTF-8');
    }
    
    protected function raw(string $value): string
    {
        return $value;
    }
}

// Layout template (templates/layouts/main.php)
?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title><?= $this->e($title ?? 'My Application') ?></title>
    <link rel="stylesheet" href="/css/app.css">
    <?= $this->yield('styles') ?>
</head>
<body>
    <header>
        <?php $this->include('partials.navigation') ?>
    </header>
    
    <main>
        <?= $this->yield('content') ?>
    </main>
    
    <footer>
        <?php $this->include('partials.footer') ?>
    </footer>
    
    <script src="/js/app.js"></script>
    <?= $this->yield('scripts') ?>
</body>
</html>

<?php
// Page template
$this->layout('layouts.main');
$this->section('content');
?>

<h1><?= $this->e($pageTitle) ?></h1>

<div class="content">
    <?= $content ?>
</div>

<?php $this->endSection(); ?>
```

#### 19.3 Twig and Blade Engine Deep Dive

**Twig Integration**

```php
// Install: composer require "twig/twig:^3.0"

class TwigViewRenderer
{
    private \Twig\Environment $twig;
    
    public function __construct(string $templatesPath, string $cachePath = null)
    {
        $loader = new \Twig\Loader\FilesystemLoader($templatesPath);
        
        $options = [
            'cache' => $cachePath ?? false,
            'auto_reload' => true,
            'strict_variables' => true,
            'debug' => $_ENV['APP_DEBUG'] ?? false,
        ];
        
        $this->twig = new \Twig\Environment($loader, $options);
        
        // Register extensions
        $this->twig->addExtension(new \Twig\Extension\DebugExtension());
        
        // Register custom functions
        $this->registerFunctions();
        
        // Register custom filters
        $this->registerFilters();
    }
    
    public function render(string $template, array $data = []): string
    {
        return $this->twig->render($template, $data);
    }
    
    private function registerFunctions(): void
    {
        $this->twig->addFunction(new \Twig\TwigFunction('route', function (string $name, array $params = []): string {
            return $this->generateRoute($name, $params);
        }));
        
        $this->twig->addFunction(new \Twig\TwigFunction('asset', function (string $path): string {
            $manifest = json_decode(file_get_contents(__DIR__ . '/../public/mix-manifest.json'), true);
            return $manifest[$path] ?? $path;
        }));
    }
    
    private function registerFilters(): void
    {
        $this->twig->addFilter(new \Twig\TwigFilter('money', function (float $amount, string $currency = 'USD'): string {
            return (new NumberFormatter('en_US', NumberFormatter::CURRENCY))
                ->formatCurrency($amount, $currency);
        }));
        
        $this->twig->addFilter(new \Twig\TwigFilter('excerpt', function (string $text, int $length = 200): string {
            if (mb_strlen($text) <= $length) {
                return $text;
            }
            return mb_substr($text, 0, $length) . '...';
        }));
    }
}

// Twig template example
?>
{% extends 'layouts/main.twig' %}

{% block title %}{{ pageTitle }}{% endblock %}

{% block content %}
<h1>{{ pageTitle }}</h1>

{% if articles is empty %}
    <p>No articles yet.</p>
{% else %}
    <div class="articles">
        {% for article in articles %}
            <article class="article-card">
                <h2>
                    <a href="{{ route('articles.show', {id: article.id}) }}">
                        {{ article.title }}
                    </a>
                </h2>
                <time datetime="{{ article.createdAt|date('c') }}">
                    {{ article.createdAt|date('F j, Y') }}
                </time>
                <p>{{ article.content|excerpt(150)|nl2br }}</p>
            </article>
        {% endfor %}
    </div>
{% endif %}

{% if pagination.pages > 1 %}
    <nav class="pagination">
        {% for page in pagination.pages %}
            {% if page == pagination.current %}
                <span class="current">{{ page }}</span>
            {% else %}
                <a href="?page={{ page }}">{{ page }}</a>
            {% endif %}
        {% endfor %}
    </nav>
{% endif %}
{% endblock %}
```

#### 19.4 CSRF Protection and Form Security

**Complete Form Building with Security**

```php
class FormBuilder
{
    private string $csrfToken;
    private array $errors = [];
    private array $oldInput = [];
    
    public function __construct(SecurityManager $security)
    {
        $this->csrfToken = $security->generateCsrfToken();
        $this->errors = $_SESSION['_errors'] ?? [];
        $this->oldInput = $_SESSION['_old_input'] ?? [];
        
        unset($_SESSION['_errors'], $_SESSION['_old_input']);
    }
    
    public function open(string $method, string $action, array $attributes = []): string
    {
        $method = strtoupper($method);
        $attributes['method'] = $method === 'GET' ? 'GET' : 'POST';
        $attributes['action'] = $action;
        
        if (isset($attributes['enctype']) && $attributes['enctype'] === 'multipart') {
            $attributes['enctype'] = 'multipart/form-data';
        }
        
        $html = '<form ' . $this->buildAttributes($attributes) . '>';
        
        // Add CSRF token
        if (!in_array($method, ['GET', 'HEAD', 'OPTIONS'])) {
            $html .= '<input type="hidden" name="_token" value="' . $this->e($this->csrfToken) . '">';
        }
        
        // Method spoofing for PUT/PATCH/DELETE
        if (!in_array($method, ['GET', 'POST'])) {
            $html .= '<input type="hidden" name="_method" value="' . $this->e($method) . '">';
        }
        
        return $html;
    }
    
    public function close(): string
    {
        return '</form>';
    }
    
    public function text(string $name, string $label, array $attributes = []): string
    {
        $value = $this->oldInput[$name] ?? $attributes['value'] ?? '';
        $error = $this->errors[$name] ?? null;
        
        $html = '<div class="form-group' . ($error ? ' has-error' : '') . '">';
        $html .= '<label for="' . $this->e($name) . '">' . $this->e($label) . '</label>';
        $html .= '<input type="text" name="' . $this->e($name) . '" id="' . $this->e($name) . '" value="' . $this->e($value) . '" ' . $this->buildAttributes($attributes) . '>';
        
        if ($error) {
            $html .= '<span class="error-message">' . $this->e($error) . '</span>';
        }
        
        $html .= '</div>';
        return $html;
    }
    
    public function textarea(string $name, string $label, array $attributes = []): string
    {
        $value = $this->oldInput[$name] ?? $attributes['value'] ?? '';
        unset($attributes['value']);
        
        $error = $this->errors[$name] ?? null;
        
        $html = '<div class="form-group' . ($error ? ' has-error' : '') . '">';
        $html .= '<label for="' . $this->e($name) . '">' . $this->e($label) . '</label>';
        $html .= '<textarea name="' . $this->e($name) . '" id="' . $this->e($name) . '" ' . $this->buildAttributes($attributes) . '>' . $this->e($value) . '</textarea>';
        
        if ($error) {
            $html .= '<span class="error-message">' . $this->e($error) . '</span>';
        }
        
        $html .= '</div>';
        return $html;
    }
    
    public function select(string $name, string $label, array $options, array $attributes = []): string
    {
        $selected = $this->oldInput[$name] ?? $attributes['selected'] ?? null;
        unset($attributes['selected']);
        
        $error = $this->errors[$name] ?? null;
        
        $html = '<div class="form-group' . ($error ? ' has-error' : '') . '">';
        $html .= '<label for="' . $this->e($name) . '">' . $this->e($label) . '</label>';
        $html .= '<select name="' . $this->e($name) . '" id="' . $this->e($name) . '" ' . $this->buildAttributes($attributes) . '>';
        
        foreach ($options as $value => $optionLabel) {
            $isSelected = (string) $value === (string) $selected ? ' selected' : '';
            $html .= '<option value="' . $this->e((string) $value) . '"' . $isSelected . '>' . $this->e($optionLabel) . '</option>';
        }
        
        $html .= '</select>';
        
        if ($error) {
            $html .= '<span class="error-message">' . $this->e($error) . '</span>';
        }
        
        $html .= '</div>';
        return $html;
    }
    
    public function submit(string $label, array $attributes = []): string
    {
        return '<button type="submit" ' . $this->buildAttributes($attributes) . '>' . $this->e($label) . '</button>';
    }
    
    private function buildAttributes(array $attributes): string
    {
        $html = '';
        foreach ($attributes as $key => $value) {
            if (is_bool($value)) {
                if ($value) {
                    $html .= $this->e($key) . ' ';
                }
            } else {
                $html .= $this->e($key) . '="' . $this->e($value) . '" ';
            }
        }
        return trim($html);
    }
    
    private function e(string $value): string
    {
        return htmlspecialchars($value, ENT_QUOTES | ENT_SUBSTITUTE, 'UTF-8');
    }
}
```

**CSRF Token Management**

```php
class SecurityManager
{
    private SessionHandlerInterface $session;
    
    public function generateCsrfToken(): string
    {
        if (!isset($_SESSION['_csrf_token'])) {
            $_SESSION['_csrf_token'] = bin2hex(random_bytes(32));
        }
        
        return $_SESSION['_csrf_token'];
    }
    
    public function validateCsrfToken(string $token): bool
    {
        if (!isset($_SESSION['_csrf_token'])) {
            return false;
        }
        
        $valid = hash_equals($_SESSION['_csrf_token'], $token);
        
        // Token is valid for one use only
        unset($_SESSION['_csrf_token']);
        
        return $valid;
    }
    
    public function flashErrors(array $errors): void
    {
        $_SESSION['_errors'] = $errors;
    }
    
    public function flashOldInput(array $input): void
    {
        $_SESSION['_old_input'] = $input;
    }
}
```

**Form Processing Controller**

```php
class ArticleFormController
{
    private ArticleRepository $articles;
    private SecurityManager $security;
    
    public function create(Request $request): Response
    {
        if ($request->isMethod('POST')) {
            // Validate CSRF token
            $token = $request->post('_token', '');
            
            if (!$this->security->validateCsrfToken($token)) {
                return Response::redirect('/articles/create?error=invalid_token');
            }
            
            // Validate input
            $validator = (new Validator($request->all()))
                ->required('title', 'content')
                ->min('title', 5)
                ->max('title', 255)
                ->min('content', 50);
            
            if ($validator->fails()) {
                $this->security->flashErrors($validator->errors());
                $this->security->flashOldInput($request->all());
                return Response::redirect('/articles/create');
            }
            
            // Create article
            $article = $this->articles->create($validator->validated());
            
            $_SESSION['_success'] = 'Article created successfully!';
            return Response::redirect("/articles/{$article->id}");
        }
        
        // Display form
        return new ViewResponse('articles.create', [
            'form' => new FormBuilder($this->security),
        ]);
    }
}
```

---

## Part VI: Security


### Chapter 20: Application Security

#### 20.1 XSS Prevention and Output Escaping

Cross-Site Scripting (XSS) remains one of the most common web application vulnerabilities. XSS attacks inject malicious scripts into web pages viewed by other users. PHP applications must systematically prevent XSS through proper output escaping.

**Understanding XSS Attack Vectors**

XSS attacks come in three primary forms:

**Stored XSS**: Malicious script is stored on the server (database, file, comment) and served to users.

```php
// Vulnerable: Comment system without escaping
$comment = $_POST['comment']; // "<script>alert('XSS')</script>"
// Stored in database
// Later displayed:
echo "<div class='comment'>{$comment}</div>";

// Safe: Escape all output
echo "<div class='comment'>" . htmlspecialchars($comment, ENT_QUOTES, 'UTF-8') . "</div>";
```

**Reflected XSS**: Malicious script is reflected off the web server in a response.

```php
// Vulnerable: Search results
$query = $_GET['q'];
echo "<h1>Search results for: {$query}</h1>";

// Attacker sends link: /search?q=<script>steal(document.cookie)</script>

// Safe: Escape the search query
$query = $_GET['q'];
echo "<h1>Search results for: " . htmlspecialchars($query, ENT_QUOTES, 'UTF-8') . "</h1>";
```

**DOM-Based XSS**: Attack occurs in client-side JavaScript.

```html
<!-- Vulnerable JavaScript -->
<script>
const name = new URLSearchParams(location.search).get('name');
document.getElementById('greeting').innerHTML = `Hello, ${name}`;
</script>

<!-- Safe JavaScript -->
<script>
const name = new URLSearchParams(location.search).get('name');
document.getElementById('greeting').textContent = `Hello, ${name}`;
</script>
```

**Context-Aware Escaping**

Different HTML contexts require different escaping strategies:

```php
class OutputEscaper
{
    // HTML body context
    public static function html(string $value): string
    {
        return htmlspecialchars($value, ENT_QUOTES | ENT_SUBSTITUTE, 'UTF-8');
    }
    
    // HTML attribute context
    public static function attr(string $value): string
    {
        return htmlspecialchars($value, ENT_QUOTES, 'UTF-8');
    }
    
    // JavaScript context
    public static function js(string $value): string
    {
        return json_encode($value, JSON_UNESCAPED_UNICODE | JSON_HEX_TAG | JSON_HEX_AMP | JSON_HEX_APOS | JSON_HEX_QUOT);
    }
    
    // CSS context
    public static function css(string $value): string
    {
        // Only allow safe CSS values
        if (preg_match('/^[a-zA-Z0-9\-_#.()%, ]+$/', $value)) {
            return $value;
        }
        return '';
    }
    
    // URL context
    public static function url(string $value): string
    {
        return rawurlencode($value);
    }
    
    // URL parameter in HTML attribute
    public static function urlAttr(string $url): string
    {
        // Only allow http/https URLs in attributes
        if (preg_match('/^https?:\/\//i', $url)) {
            return self::attr($url);
        }
        return '';
    }
    
    // Rich text (allow some HTML)
    public static function richText(string $html): string
    {
        // Use HTML Purifier or a strict allowlist
        return (new HtmlPurifier())->purify($html);
    }
}

// Context-specific escaping in templates
?>

<!-- HTML body context -->
<p><?= OutputEscaper::html($user->bio) ?></p>

<!-- HTML attribute context -->
<input type="text" value="<?= OutputEscaper::attr($_GET['name'] ?? '') ?>">

<!-- JavaScript context -->
<script>
    const userData = <?= OutputEscaper::js($userData) ?>;
    const message = <?= OutputEscaper::js($message) ?>;
</script>

<!-- URL context -->
<a href="https://example.com/redirect?url=<?= OutputEscaper::url($returnUrl) ?>">Back</a>

<!-- CSS context (inline styles) -->
<div style="color: <?= OutputEscaper::css($userColor) ?>">Colored text</div>
```

**Content Security Policy Headers**

CSP provides an additional layer of defense against XSS:

```php
class SecurityHeaders
{
    public static function setCSP(): void
    {
        $csp = [
            "default-src 'self'",
            "script-src 'self' 'nonce-" . self::generateNonce() . "'",
            "style-src 'self' 'unsafe-inline'",
            "img-src 'self' data: https:",
            "font-src 'self'",
            "connect-src 'self' https://api.example.com",
            "frame-ancestors 'none'",
            "form-action 'self'",
            "base-uri 'self'",
            "object-src 'none'",
        ];
        
        header("Content-Security-Policy: " . implode('; ', $csp));
    }
    
    public static function generateNonce(): string
    {
        $nonce = bin2hex(random_bytes(16));
        $_SESSION['csp_nonce'] = $nonce;
        return $nonce;
    }
    
    public static function cspNonce(): string
    {
        if (!isset($_SESSION['csp_nonce'])) {
            self::generateNonce();
        }
        return $_SESSION['csp_nonce'];
    }
}

// Include nonce in script tags
?>
<script nonce="<?= SecurityHeaders::cspNonce() ?>">
    // Inline JavaScript allowed by CSP
</script>

<!-- External scripts from allowed sources -->
<script src="/js/app.js" nonce="<?= SecurityHeaders::cspNonce() ?>"></script>
```

**HTML Purifier for Rich Text**

When you must allow HTML input, use a proven sanitization library:

```php
class RichTextSanitizer
{
    private \HTMLPurifier $purifier;
    
    public function __construct()
    {
        $config = \HTMLPurifier_Config::createDefault();
        
        // Allow only specific tags and attributes
        $config->set('HTML.Allowed', 'p,b,i,em,strong,a[href|title],ul,ol,li,br,blockquote,code,pre,h2,h3,h4');
        $config->set('HTML.AllowedAttributes', '*.class,a.href,a.title');
        $config->set('URI.AllowedSchemes', ['http' => true, 'https' => true, 'mailto' => true]);
        $config->set('AutoFormat.RemoveEmpty', true);
        $config->set('AutoFormat.AutoParagraph', true);
        
        $this->purifier = new \HTMLPurifier($config);
    }
    
    public function sanitize(string $dirtyHtml): string
    {
        return $this->purifier->purify($dirtyHtml);
    }
}

// Usage
$sanitizer = new RichTextSanitizer();
$cleanHtml = $sanitizer->sanitize($_POST['content']);
// Only allowed HTML tags remain
```

#### 20.2 SQL Injection Defense Strategies

SQL injection occurs when user input is incorporated directly into SQL queries. Prepared statements are the primary defense, but multiple strategies are needed for comprehensive protection.

**Understanding SQL Injection**

```php
// VULNERABLE: Direct string interpolation
$id = $_GET['id'];
$query = "SELECT * FROM users WHERE id = {$id}";
$result = $pdo->query($query);

// Attacker input: 1; DROP TABLE users; --
// Results in: SELECT * FROM users WHERE id = 1; DROP TABLE users; --

// VULNERABLE: Even with escaping (don't rely on this)
$id = mysqli_real_escape_string($conn, $_GET['id']);
$query = "SELECT * FROM users WHERE id = {$id}"; // Still risky

// SAFE: Prepared statements
$stmt = $pdo->prepare('SELECT * FROM users WHERE id = :id');
$stmt->execute(['id' => $id]);
```

**Prepared Statements for All Queries**

```php
class SecureRepository
{
    private PDO $pdo;
    
    // Basic select
    public function findById(int $id): ?array
    {
        $stmt = $this->pdo->prepare('SELECT * FROM users WHERE id = :id');
        $stmt->execute(['id' => $id]);
        return $stmt->fetch() ?: null;
    }
    
    // Dynamic ORDER BY and GROUP BY (cannot use prepared statements)
    public function findAll(string $orderBy = 'created_at', string $direction = 'DESC'): array
    {
        // Whitelist approach for column names
        $allowedColumns = ['id', 'name', 'email', 'created_at'];
        $allowedDirections = ['ASC', 'DESC'];
        
        if (!in_array($orderBy, $allowedColumns, true)) {
            throw new InvalidArgumentException('Invalid column: ' . $orderBy);
        }
        
        if (!in_array(strtoupper($direction), $allowedDirections, true)) {
            throw new InvalidArgumentException('Invalid direction: ' . $direction);
        }
        
        // Safe to interpolate after whitelist validation
        $direction = strtoupper($direction);
        $query = "SELECT * FROM users ORDER BY {$orderBy} {$direction}";
        
        return $this->pdo->query($query)->fetchAll();
    }
    
    // Dynamic IN clause
    public function findByIds(array $ids): array
    {
        if (empty($ids)) {
            return [];
        }
        
        // Generate placeholders: :id0, :id1, :id2
        $placeholders = [];
        $params = [];
        
        foreach ($ids as $index => $id) {
            $key = ":id{$index}";
            $placeholders[] = $key;
            $params[$key] = (int) $id;
        }
        
        $placeholdersStr = implode(', ', $placeholders);
        $stmt = $this->pdo->prepare("SELECT * FROM users WHERE id IN ({$placeholdersStr})");
        $stmt->execute($params);
        
        return $stmt->fetchAll();
    }
    
    // LIKE clause
    public function searchByName(string $query): array
    {
        $stmt = $this->pdo->prepare('SELECT * FROM users WHERE name LIKE :query');
        $stmt->execute(['query' => '%' . $query . '%']);
        return $stmt->fetchAll();
    }
    
    // Dynamic table names with whitelist
    public function countRecords(string $table): int
    {
        $allowedTables = ['users', 'articles', 'comments'];
        
        if (!in_array($table, $allowedTables, true)) {
            throw new InvalidArgumentException('Invalid table: ' . $table);
        }
        
        $stmt = $this->pdo->query("SELECT COUNT(*) FROM {$table}");
        return (int) $stmt->fetchColumn();
    }
}
```

**Secondary SQL Injection Defenses**

```php
class DatabaseSecurity
{
    // Least privilege principle
    public static function createConnection(): PDO
    {
        // Use different database users for different access levels
        $readUser = new PDO(
            'mysql:host=127.0.0.1;dbname=myapp;charset=utf8mb4',
            'app_readonly',
            $_ENV['DB_READ_PASSWORD'],
            [PDO::ATTR_ERRMODE => PDO::ERRMODE_EXCEPTION]
        );
        
        $writeUser = new PDO(
            'mysql:host=127.0.0.1;dbname=myapp;charset=utf8mb4',
            'app_readwrite',
            $_ENV['DB_WRITE_PASSWORD'],
            [PDO::ATTR_ERRMODE => PDO::ERRMODE_EXCEPTION]
        );
        
        // Use read-only connection where possible
        return $readUser;
    }
    
    // Input type validation
    public static function validateInput(mixed $value): mixed
    {
        // Force appropriate types
        if (is_numeric($value)) {
            return filter_var($value, FILTER_VALIDATE_INT) !== false 
                ? (int) $value 
                : (float) $value;
        }
        
        // Remove null bytes (bypass attempts)
        if (is_string($value)) {
            return str_replace("\0", '', $value);
        }
        
        return $value;
    }
    
    // Query timeout protection
    public static function executeWithTimeout(PDO $pdo, string $query, array $params, int $timeout = 10): \PDOStatement
    {
        $pdo->exec("SET SESSION max_execution_time = {$timeout}000"); // MySQL 5.7+
        $stmt = $pdo->prepare($query);
        return $stmt;
    }
}

// Application-level query logging for detection
class QueryLogger
{
    private array $queries = [];
    
    public function logQuery(string $query, float $duration): void
    {
        // Log suspicious patterns
        $suspicious = [
            'UNION\s+SELECT',
            '--',
            ';\s*DROP\s+',
            ';\s*DELETE\s+',
            'INFORMATION_SCHEMA',
            'xp_cmdshell',
            'LOAD_FILE',
        ];
        
        foreach ($suspicious as $pattern) {
            if (preg_match('/' . $pattern . '/i', $query)) {
                error_log("SUSPICIOUS QUERY: {$query} | Duration: {$duration}s | IP: {$_SERVER['REMOTE_ADDR']}");
                
                // Alert security team
                $this->sendSecurityAlert('Possible SQL injection attempt', [
                    'query' => $query,
                    'ip' => $_SERVER['REMOTE_ADDR'],
                    'user_agent' => $_SERVER['HTTP_USER_AGENT'] ?? '',
                ]);
                
                break;
            }
        }
        
        $this->queries[] = ['query' => $query, 'duration' => $duration];
    }
}
```

#### 20.3 CSRF Tokens and SameSite Cookies

Cross-Site Request Forgery (CSRF) forces authenticated users to perform unwanted actions.

**Understanding CSRF**

```php
// The Attack Scenario:
// 1. User logs into bank.com
// 2. User visits evil.com (without logging out)
// 3. Evil.com has hidden form:
// <form action="https://bank.com/transfer" method="POST">
//   <input type="hidden" name="to" value="attacker">
//   <input type="hidden" name="amount" value="1000">
// </form>
// 4. User's browser sends authenticated request
// 5. Money transferred without user's knowledge
```

**Comprehensive CSRF Protection**

```php
class CsrfProtection
{
    private const TOKEN_LENGTH = 32;
    private const TOKEN_LIFETIME = 7200; // 2 hours
    
    public function generateToken(): string
    {
        if (!isset($_SESSION['csrf_tokens'])) {
            $_SESSION['csrf_tokens'] = [];
        }
        
        // Clean expired tokens
        $this->cleanExpiredTokens();
        
        // Generate new token
        $token = bin2hex(random_bytes(self::TOKEN_LENGTH));
        
        $_SESSION['csrf_tokens'][$token] = [
            'created_at' => time(),
            'used' => false,
        ];
        
        return $token;
    }
    
    public function validateToken(string $token): bool
    {
        if (!isset($_SESSION['csrf_tokens'][$token])) {
            return false;
        }
        
        $tokenData = &$_SESSION['csrf_tokens'][$token];
        
        // Check expiration
        if (time() - $tokenData['created_at'] > self::TOKEN_LIFETIME) {
            unset($_SESSION['csrf_tokens'][$token]);
            return false;
        }
        
        // Check if already used (one-time token)
        if ($tokenData['used']) {
            return false;
        }
        
        // Mark as used for one-time tokens
        $tokenData['used'] = true;
        
        return true;
    }
    
    public function getToken(): string
    {
        $token = $this->generateToken();
        $this->storeInCookie($token);
        return $token;
    }
    
    private function storeInCookie(string $token): void
    {
        setcookie(
            'XSRF-TOKEN',
            $token,
            [
                'expires' => time() + self::TOKEN_LIFETIME,
                'path' => '/',
                'domain' => '',
                'secure' => true,
                'httponly' => false, // Must be readable by JavaScript
                'samesite' => 'Strict',
            ]
        );
    }
    
    public function validateDoubleSubmit(): bool
    {
        $headerToken = $_SERVER['HTTP_X_XSRF_TOKEN'] ?? $_SERVER['HTTP_X_CSRF_TOKEN'] ?? '';
        $cookieToken = $_COOKIE['XSRF-TOKEN'] ?? '';
        $bodyToken = $_POST['_token'] ?? '';
        
        // Accept token from header or body
        $requestToken = $headerToken ?: $bodyToken;
        
        if (empty($requestToken) || empty($cookieToken)) {
            return false;
        }
        
        return hash_equals($cookieToken, $requestToken);
    }
    
    private function cleanExpiredTokens(): void
    {
        $now = time();
        foreach ($_SESSION['csrf_tokens'] as $token => $data) {
            if ($now - $data['created_at'] > self::TOKEN_LIFETIME) {
                unset($_SESSION['csrf_tokens'][$token]);
            }
        }
    }
    
    // Generate token for AJAX requests
    public function ajaxToken(): string
    {
        $token = $this->generateToken();
        
        // Store in a cookie readable by JavaScript
        setcookie(
            'XSRF-TOKEN',
            $token,
            [
                'expires' => 0,
                'path' => '/',
                'secure' => true,
                'httponly' => false, // JavaScript can read it
                'samesite' => 'Strict',
            ]
        );
        
        return $token;
    }
}
```

**CSRF Middleware**

```php
class CsrfMiddleware
{
    private CsrfProtection $csrf;
    
    public function __construct(CsrfProtection $csrf)
    {
        $this->csrf = $csrf;
    }
    
    public function handle(Request $request, callable $next): Response
    {
        // Only validate state-changing methods
        if ($this->requiresProtection($request->getMethod())) {
            // Try traditional token validation first
            $token = $request->post('_token')
                ?? $request->header('X-CSRF-Token')
                ?? $request->header('X-XSRF-Token');
            
            if ($token && $this->csrf->validateToken($token)) {
                return $next($request);
            }
            
            // Try double submit cookie
            if ($this->csrf->validateDoubleSubmit()) {
                return $next($request);
            }
            
            // Check Origin/Referer headers
            if ($this->validOrigin($request)) {
                return $next($request);
            }
            
            return new Response('CSRF token mismatch', 403);
        }
        
        return $next($request);
    }
    
    private function requiresProtection(string $method): bool
    {
        return !in_array($method, ['GET', 'HEAD', 'OPTIONS']);
    }
    
    private function validOrigin(Request $request): bool
    {
        $origin = $request->header('Origin');
        $referer = $request->header('Referer');
        
        if ($origin) {
            $originHost = parse_url($origin, PHP_URL_HOST);
            return $originHost === $_SERVER['HTTP_HOST'];
        }
        
        if ($referer) {
            $refererHost = parse_url($referer, PHP_URL_HOST);
            return $refererHost === $_SERVER['HTTP_HOST'];
        }
        
        return false;
    }
}
```

**SameSite Cookie Configuration**

```php
class CookieManager
{
    public static function set(string $name, string $value, array $options = []): void
    {
        $defaults = [
            'expires' => 0,
            'path' => '/',
            'domain' => '',
            'secure' => true,
            'httponly' => true,
            'samesite' => 'Lax',
        ];
        
        $options = array_merge($defaults, $options);
        
        setcookie($name, $value, $options);
    }
    
    public static function sessionConfig(): void
    {
        ini_set('session.cookie_secure', '1');
        ini_set('session.cookie_httponly', '1');
        ini_set('session.cookie_samesite', 'Lax');
        ini_set('session.use_only_cookies', '1');
        ini_set('session.use_strict_mode', '1');
    }
    
    public static function securityHeaders(): array
    {
        return [
            'X-Frame-Options' => 'DENY',
            'X-Content-Type-Options' => 'nosniff',
            'X-XSS-Protection' => '1; mode=block',
            'Referrer-Policy' => 'strict-origin-when-cross-origin',
            'Permissions-Policy' => 'geolocation=(), microphone=(), camera=()',
        ];
    }
}
```

#### 20.4 Command Injection and Path Traversal

**Command Injection Prevention**

```php
class CommandExecutor
{
    // VULNERABLE
    public function ping(string $host): string
    {
        // Don't do this!
        return shell_exec("ping -c 4 {$host}");
    }
    // Attacker input: google.com; rm -rf /
    
    // SAFE: Use escapeshellarg
    public function pingSafe(string $host): string
    {
        $host = escapeshellarg($host);
        return shell_exec("ping -c 4 {$host}");
    }
    
    // SAFE: Use specific functions instead of shell
    public function createZip(string $sourceDir, string $targetFile): bool
    {
        // Instead of: exec("zip -r {$targetFile} {$sourceDir}")
        $zip = new ZipArchive();
        if ($zip->open($targetFile, ZipArchive::CREATE) !== true) {
            return false;
        }
        
        $files = new RecursiveIteratorIterator(
            new RecursiveDirectoryIterator($sourceDir)
        );
        
        foreach ($files as $file) {
            if (!$file->isDir()) {
                $zip->addFile($file->getRealPath(), $file->getFilename());
            }
        }
        
        return $zip->close();
    }
    
    // SAFE: Whitelist approach
    public function executeAction(string $action): ?string
    {
        $allowedActions = [
            'clear-cache' => 'rm -rf /var/cache/app/*',
            'restart-queue' => 'supervisorctl restart queue-worker',
        ];
        
        if (!array_key_exists($action, $allowedActions)) {
            throw new InvalidArgumentException('Invalid action');
        }
        
        return shell_exec($allowedActions[$action]);
    }
    
    // SAFE: Parameterized approach
    public function convertImage(string $input, string $output, int $quality = 80): void
    {
        // Validate inputs
        if (!in_array(pathinfo($input, PATHINFO_EXTENSION), ['jpg', 'png', 'webp'])) {
            throw new InvalidArgumentException('Invalid input format');
        }
        
        if (!in_array(pathinfo($output, PATHINFO_EXTENSION), ['jpg', 'png', 'webp'])) {
            throw new InvalidArgumentException('Invalid output format');
        }
        
        $quality = max(0, min(100, $quality));
        
        $cmd = sprintf(
            'convert %s -quality %d %s',
            escapeshellarg($input),
            $quality,
            escapeshellarg($output)
        );
        
        shell_exec($cmd);
    }
}
```

**Path Traversal Prevention**

```php
class SecureFileAccess
{
    private string $basePath;
    
    public function __construct(string $basePath)
    {
        $this->basePath = realpath($basePath);
        
        if ($this->basePath === false) {
            throw new RuntimeException('Invalid base path');
        }
    }
    
    public function readFile(string $userPath): ?string
    {
        $fullPath = $this->resolvePath($userPath);
        
        if ($fullPath === null) {
            return null;
        }
        
        if (!is_file($fullPath)) {
            return null;
        }
        
        return file_get_contents($fullPath);
    }
    
    public function resolvePath(string $userPath): ?string
    {
        // Clean the path
        $cleanPath = $this->sanitizePath($userPath);
        
        // Build full path
        $fullPath = $this->basePath . DIRECTORY_SEPARATOR . $cleanPath;
        
        // Resolve any relative components
        $realPath = realpath($fullPath);
        
        if ($realPath === false) {
            return null;
        }
        
        // Verify path is within base directory
        if (!str_starts_with($realPath, $this->basePath . DIRECTORY_SEPARATOR) 
            && $realPath !== $this->basePath) {
            return null;
        }
        
        return $realPath;
    }
    
    private function sanitizePath(string $path): string
    {
        // Remove null bytes
        $path = str_replace("\0", '', $path);
        
        // Remove directory traversal attempts
        $path = str_replace(['../', '..\\'], '', $path);
        
        // Remove any path components that are just dots
        $parts = explode('/', str_replace('\\', '/', $path));
        $parts = array_filter($parts, fn(string $part): bool => $part !== '.' && $part !== '..');
        
        return implode('/', $parts);
    }
    
    // Filesystem whitelist for critical operations
    public function serveStaticFile(string $requestPath): void
    {
        $extension = strtolower(pathinfo($requestPath, PATHINFO_EXTENSION));
        
        // Whitelist allowed extensions
        $allowedExtensions = ['css', 'js', 'jpg', 'jpeg', 'png', 'gif', 'svg', 'ico', 'pdf'];
        
        if (!in_array($extension, $allowedExtensions, true)) {
            http_response_code(403);
            exit('Forbidden');
        }
        
        $fullPath = $this->resolvePath($requestPath);
        
        if ($fullPath === null) {
            http_response_code(404);
            exit('Not found');
        }
        
        // Serve with appropriate headers
        $mimeTypes = [
            'css' => 'text/css',
            'js' => 'application/javascript',
            'jpg' => 'image/jpeg',
            'png' => 'image/png',
            'svg' => 'image/svg+xml',
        ];
        
        header('Content-Type: ' . ($mimeTypes[$extension] ?? 'application/octet-stream'));
        header('X-Content-Type-Options: nosniff');
        readfile($fullPath);
    }
}

// Usage
$fileAccess = new SecureFileAccess('/var/www/uploads');

// These are all blocked
$fileAccess->readFile('../../../etc/passwd');     // null - path traversal
$fileAccess->readFile('./config/database.php\0.jpg'); // null - null byte
$fileAccess->readFile('file.txt');                // Valid - within base path
```

#### 20.5 File Upload Security and Validation

**Secure File Upload Handler**

```php
class SecureFileUpload
{
    private const ALLOWED_MIME_TYPES = [
        'image/jpeg' => 'jpg',
        'image/png' => 'png',
        'image/gif' => 'gif',
        'image/webp' => 'webp',
        'application/pdf' => 'pdf',
        'text/plain' => 'txt',
        'text/csv' => 'csv',
    ];
    
    private const MAX_FILE_SIZE = 10 * 1024 * 1024; // 10MB
    private const STORAGE_PATH = '/var/www/storage/uploads';
    
    private array $errors = [];
    
    public function handle(array $file): ?UploadedFile
    {
        // Validate upload succeeded
        if ($file['error'] !== UPLOAD_ERR_OK) {
            $this->errors[] = $this->getUploadErrorMessage($file['error']);
            return null;
        }
        
        // Validate file size
        if ($file['size'] > self::MAX_FILE_SIZE) {
            $this->errors[] = 'File exceeds maximum size of ' . (self::MAX_FILE_SIZE / 1024 / 1024) . 'MB';
            return null;
        }
        
        // Validate filename
        $originalName = $file['name'];
        if (!$this->isValidFilename($originalName)) {
            $this->errors[] = 'Invalid filename';
            return null;
        }
        
        // Validate MIME type (never trust client-supplied type)
        $realMimeType = $this->detectMimeType($file['tmp_name']);
        
        if (!array_key_exists($realMimeType, self::ALLOWED_MIME_TYPES)) {
            $this->errors[] = "File type '{$realMimeType}' is not allowed";
            return null;
        }
        
        // Additional validation based on type
        if (str_starts_with($realMimeType, 'image/')) {
            if (!$this->validateImage($file['tmp_name'])) {
                $this->errors[] = 'Invalid image file';
                return null;
            }
        }
        
        // Generate secure filename
        $extension = self::ALLOWED_MIME_TYPES[$realMimeType];
        $storedName = $this->generateSecureFilename($extension);
        
        // Create storage directory
        $storageDir = self::STORAGE_PATH . '/' . date('Y/m/d');
        if (!is_dir($storageDir)) {
            mkdir($storageDir, 0750, true);
        }
        
        $destination = $storageDir . '/' . $storedName;
        
        // Move uploaded file
        if (!move_uploaded_file($file['tmp_name'], $destination)) {
            $this->errors[] = 'Failed to store uploaded file';
            return null;
        }
        
        // Set restrictive permissions
        chmod($destination, 0640);
        
        return new UploadedFile(
            originalName: $originalName,
            storedName: $storedName,
            path: $destination,
            mimeType: $realMimeType,
            size: $file['size'],
        );
    }
    
    private function detectMimeType(string $path): string
    {
        // Use fileinfo extension (most reliable)
        $finfo = new finfo(FILEINFO_MIME_TYPE);
        $mimeType = $finfo->file($path);
        
        // Fallback to mime_content_type if needed
        if ($mimeType === false) {
            $mimeType = mime_content_type($path);
        }
        
        // Double check for dangerous types
        $dangerousTypes = [
            'application/x-httpd-php',
            'application/x-php',
            'text/php',
            'application/octet-stream', // Too generic
        ];
        
        if (in_array($mimeType, $dangerousTypes)) {
            return 'application/octet-stream'; // Treat as binary
        }
        
        return $mimeType;
    }
    
    private function validateImage(string $path): bool
    {
        // Verify it's a real image (not a PHP script renamed as .jpg)
        $imageInfo = @getimagesize($path);
        
        if ($imageInfo === false) {
            return false;
        }
        
        // Verify dimensions are reasonable
        $width = $imageInfo[0];
        $height = $imageInfo[1];
        
        if ($width > 10000 || $height > 10000) {
            return false; // Unreasonably large
        }
        
        // Strip EXIF data for privacy/security
        if (function_exists('exif_read_data')) {
            // Process with GD to strip metadata
            $newImage = imagecreatefromstring(file_get_contents($path));
            if ($newImage !== false) {
                imagepng($newImage, $path . '.clean');
                rename($path . '.clean', $path);
                imagedestroy($newImage);
            }
        }
        
        return true;
    }
    
    private function isValidFilename(string $name): bool
    {
        // Check for path traversal characters
        if (str_contains($name, '/') || str_contains($name, '\\')) {
            return false;
        }
        
        // Check for null bytes
        if (str_contains($name, "\0")) {
            return false;
        }
        
        // Check length
        if (strlen($name) > 255) {
            return false;
        }
        
        // Allow only safe characters
        return (bool) preg_match('/^[a-zA-Z0-9._-]+$/', $name);
    }
    
    private function generateSecureFilename(string $extension): string
    {
        return bin2hex(random_bytes(16)) . '.' . $extension;
    }
    
    private function getUploadErrorMessage(int $error): string
    {
        return match ($error) {
            UPLOAD_ERR_INI_SIZE => 'File exceeds upload_max_filesize directive',
            UPLOAD_ERR_FORM_SIZE => 'File exceeds MAX_FILE_SIZE directive',
            UPLOAD_ERR_PARTIAL => 'File was only partially uploaded',
            UPLOAD_ERR_NO_FILE => 'No file was uploaded',
            UPLOAD_ERR_NO_TMP_DIR => 'Missing temporary folder',
            UPLOAD_ERR_CANT_WRITE => 'Failed to write file to disk',
            UPLOAD_ERR_EXTENSION => 'Upload stopped by extension',
            default => 'Unknown upload error',
        };
    }
    
    public function getErrors(): array
    {
        return $this->errors;
    }
}

class UploadedFile
{
    public function __construct(
        public readonly string $originalName,
        public readonly string $storedName,
        public readonly string $path,
        public readonly string $mimeType,
        public readonly int $size,
    ) {}
}
```

---

### Chapter 21: Authentication and Cryptography

#### 21.1 Password Hashing with `password_hash()`

PHP provides robust password hashing functions that should be used exclusively for password storage.

**Proper Password Hashing**

```php
class PasswordManager
{
    private array $options = [
        'cost' => 12, // Higher = more secure but slower
    ];
    
    public function hash(string $password): string
    {
        // Validate password strength first
        $this->validatePasswordStrength($password);
        
        // Hash the password
        $hash = password_hash($password, PASSWORD_BCRYPT, $this->options);
        
        if ($hash === false) {
            throw new RuntimeException('Password hashing failed');
        }
        
        return $hash;
    }
    
    public function verify(string $password, string $hash): bool
    {
        // Use password_verify - timing attack safe
        $valid = password_verify($password, $hash);
        
        // Check if hash needs rehashing (algorithm or options changed)
        if ($valid && password_needs_rehash($hash, PASSWORD_BCRYPT, $this->options)) {
            // Rehash and store new hash
            $newHash = $this->hash($password);
            $this->updatePasswordHash($newHash);
        }
        
        return $valid;
    }
    
    public function validatePasswordStrength(string $password): void
    {
        $errors = [];
        
        if (strlen($password) < 12) {
            $errors[] = 'Password must be at least 12 characters';
        }
        
        if (!preg_match('/[A-Z]/', $password)) {
            $errors[] = 'Password must contain at least one uppercase letter';
        }
        
        if (!preg_match('/[a-z]/', $password)) {
            $errors[] = 'Password must contain at least one lowercase letter';
        }
        
        if (!preg_match('/[0-9]/', $password)) {
            $errors[] = 'Password must contain at least one number';
        }
        
        if (!preg_match('/[^A-Za-z0-9]/', $password)) {
            $errors[] = 'Password must contain at least one special character';
        }
        
        // Check against common passwords
        if ($this->isCommonPassword($password)) {
            $errors[] = 'This password is too common';
        }
        
        if (!empty($errors)) {
            throw new PasswordValidationException(implode('; ', $errors));
        }
    }
    
    private function isCommonPassword(string $password): bool
    {
        // Check against a list of common passwords
        $commonPasswords = [
            'password', '12345678', 'qwerty123', 'admin123',
            'letmein', 'welcome1', 'monkey', 'dragon',
        ];
        
        $lowercase = strtolower($password);
        
        if (in_array($lowercase, $commonPasswords)) {
            return true;
        }
        
        // Check against Have I Been Pwned API (k-anonymity)
        $sha1 = strtoupper(sha1($password));
        $prefix = substr($sha1, 0, 5);
        $suffix = substr($sha1, 5);
        
        $response = file_get_contents("https://api.pwnedpasswords.com/range/{$prefix}");
        
        if ($response !== false) {
            foreach (explode("\n", $response) as $line) {
                [$hashSuffix, $count] = explode(':', trim($line));
                if (strtoupper($hashSuffix) === $suffix) {
                    return true;
                }
            }
        }
        
        return false;
    }
    
    public function upgradeHashAlgorithm(string $password, string $oldHash): ?string
    {
        // Support migrating from legacy hashing
        if (str_starts_with($oldHash, '$2y$')) {
            // Already bcrypt
            if (password_needs_rehash($oldHash, PASSWORD_BCRYPT, $this->options)) {
                return $this->hash($password);
            }
            return null;
        }
        
        // Legacy MD5/SHA1 migration
        if (strlen($oldHash) === 32) { // MD5
            if (md5($password) === $oldHash) {
                return $this->hash($password);
            }
        }
        
        if (strlen($oldHash) === 40) { // SHA1
            if (sha1($password) === $oldHash) {
                return $this->hash($password);
            }
        }
        
        return null;
    }
}

class PasswordValidationException extends RuntimeException {}
```

**Argon2 Support**

PHP 7.2+ supports Argon2, the winner of the Password Hashing Competition:

```php
class Argon2PasswordManager extends PasswordManager
{
    private array $argonOptions = [
        'memory_cost' => 65536,  // 64 MB
        'time_cost' => 4,
        'threads' => 3,
    ];
    
    public function hash(string $password): string
    {
        $this->validatePasswordStrength($password);
        
        return password_hash($password, PASSWORD_ARGON2ID, $this->argonOptions);
    }
}
```

#### 21.2 Encryption, Decryption, and SSL/TLS

**Symmetric Encryption**

```php
class Encryptor
{
    private string $key;
    private string $cipher;
    
    public function __construct(string $key, string $cipher = 'aes-256-gcm')
    {
        $this->validateKey($key, $cipher);
        $this->key = $key;
        $this->cipher = $cipher;
    }
    
    public function encrypt(string $plaintext): string
    {
        $ivLength = openssl_cipher_iv_length($this->cipher);
        $iv = random_bytes($ivLength);
        
        $tag = ''; // For authenticated encryption
        
        $ciphertext = openssl_encrypt(
            $plaintext,
            $this->cipher,
            $this->key,
            OPENSSL_RAW_DATA,
            $iv,
            $tag,
            '',
            16 // tag length
        );
        
        if ($ciphertext === false) {
            throw new EncryptionException('Encryption failed');
        }
        
        // Store IV, tag, and ciphertext together
        return base64_encode($iv . $tag . $ciphertext);
    }
    
    public function decrypt(string $encoded): string
    {
        $data = base64_decode($encoded);
        
        if ($data === false) {
            throw new EncryptionException('Invalid encoded data');
        }
        
        $ivLength = openssl_cipher_iv_length($this->cipher);
        $iv = substr($data, 0, $ivLength);
        $tag = substr($data, $ivLength, 16); // GCM tag is 16 bytes
        $ciphertext = substr($data, $ivLength + 16);
        
        $plaintext = openssl_decrypt(
            $ciphertext,
            $this->cipher,
            $this->key,
            OPENSSL_RAW_DATA,
            $iv,
            $tag
        );
        
        if ($plaintext === false) {
            throw new EncryptionException('Decryption failed - data may be tampered');
        }
        
        return $plaintext;
    }
    
    private function validateKey(string $key, string $cipher): void
    {
        $keyLength = strlen($key);
        $requiredLength = openssl_cipher_key_length($cipher);
        
        if ($keyLength !== $requiredLength) {
            throw new InvalidArgumentException(
                "Key length is {$keyLength} bytes, {$requiredLength} required for {$cipher}"
            );
        }
    }
}

// Usage for database field encryption
class EncryptedField
{
    private Encryptor $encryptor;
    
    public function encryptForDatabase(string $sensitiveData): string
    {
        return $this->encryptor->encrypt($sensitiveData);
    }
    
    public function decryptFromDatabase(string $encryptedData): string
    {
        return $this->encryptor->decrypt($encryptedData);
    }
}

// Store encrypted values in database
$userSsn = $encryptor->encrypt('123-45-6789');
// INSERT INTO users (ssn) VALUES (:ssn)
```

**Key Management**

```php
class KeyManager
{
    private string $keyPath;
    private string $keyEncryptionKey; // KEK - used to encrypt/decrypt DEKs
    
    public function generateDataEncryptionKey(): string
    {
        return bin2hex(random_bytes(32)); // AES-256 key
    }
    
    public function encryptKey(string $key): string
    {
        // Encrypt DEK with KEK before storage
        $encryptor = new Encryptor($this->keyEncryptionKey);
        return $encryptor->encrypt($key);
    }
    
    public function decryptKey(string $encryptedKey): string
    {
        $encryptor = new Encryptor($this->keyEncryptionKey);
        return $encryptor->decrypt($encryptedKey);
    }
    
    public function rotateKeys(): void
    {
        // Generate new DEK
        $newKey = $this->generateDataEncryptionKey();
        
        // Re-encrypt all data with new key
        $this->reencryptAllData($newKey);
        
        // Store new encrypted key
        $encryptedNewKey = $this->encryptKey($newKey);
        file_put_contents($this->keyPath . '/key.txt', $encryptedNewKey);
    }
    
    private function reencryptAllData(string $newKey): void
    {
        $oldKey = $this->getCurrentKey();
        $oldEncryptor = new Encryptor($oldKey);
        $newEncryptor = new Encryptor($newKey);
        
        // Process all encrypted records
        // SELECT id, encrypted_data FROM sensitive_data
        // For each row:
        //   $plaintext = $oldEncryptor->decrypt($row['encrypted_data']);
        //   $newCiphertext = $newEncryptor->encrypt($plaintext);
        //   UPDATE sensitive_data SET encrypted_data = $newCiphertext WHERE id = $row['id']
    }
    
    private function getCurrentKey(): string
    {
        $encryptedKey = file_get_contents($this->keyPath . '/key.txt');
        return $this->decryptKey($encryptedKey);
    }
}
```

**SSL/TLS Configuration**

```php
class SslConfiguration
{
    public static function configureSecureContext(): array
    {
        return [
            'ssl' => [
                'verify_peer' => true,
                'verify_peer_name' => true,
                'allow_self_signed' => false,
                'cafile' => '/etc/ssl/certs/ca-certificates.crt',
                'ciphers' => 'ECDHE-ECDSA-AES256-GCM-SHA384:ECDHE-RSA-AES256-GCM-SHA384',
                'disable_compression' => true,
                'SNI_enabled' => true,
            ],
        ];
    }
    
    public static function createSecureContext(): resource
    {
        $context = stream_context_create(self::configureSecureContext());
        return $context;
    }
    
    public static function secureFileGetContents(string $url): string
    {
        $context = self::createSecureContext();
        $result = file_get_contents($url, false, $context);
        
        if ($result === false) {
            throw new RuntimeException("Failed to fetch {$url}");
        }
        
        return $result;
    }
    
    public static function secureCurlOptions(): array
    {
        return [
            CURLOPT_SSL_VERIFYPEER => true,
            CURLOPT_SSL_VERIFYHOST => 2,
            CURLOPT_SSLVERSION => CURL_SSLVERSION_TLSv1_2,
            CURLOPT_CAINFO => '/etc/ssl/certs/ca-certificates.crt',
        ];
    }
}
```

#### 21.3 Role-Based Access Control (RBAC)

```php
enum Permission: string
{
    case ViewUsers = 'users.view';
    case CreateUsers = 'users.create';
    case EditUsers = 'users.edit';
    case DeleteUsers = 'users.delete';
    
    case ViewArticles = 'articles.view';
    case CreateArticles = 'articles.create';
    case EditArticles = 'articles.edit';
    case DeleteArticles = 'articles.delete';
    case PublishArticles = 'articles.publish';
    
    case ViewReports = 'reports.view';
    case ExportReports = 'reports.export';
    
    case ManageRoles = 'roles.manage';
    case ViewAuditLog = 'audit.view';
}

enum Role: string
{
    case Admin = 'admin';
    case Editor = 'editor';
    case Author = 'author';
    case Viewer = 'viewer';
    
    public function permissions(): array
    {
        return match ($this) {
            self::Admin => Permission::cases(),
            
            self::Editor => [
                Permission::ViewArticles,
                Permission::CreateArticles,
                Permission::EditArticles,
                Permission::DeleteArticles,
                Permission::PublishArticles,
                Permission::ViewReports,
                Permission::ViewUsers,
            ],
            
            self::Author => [
                Permission::ViewArticles,
                Permission::CreateArticles,
                Permission::EditArticles,
            ],
            
            self::Viewer => [
                Permission::ViewArticles,
                Permission::ViewUsers,
            ],
        };
    }
    
    public function hasPermission(Permission $permission): bool
    {
        return in_array($permission, $this->permissions(), true);
    }
}

class AccessControl
{
    private array $userPermissions;
    
    public function __construct(private User $user)
    {
        $this->userPermissions = $this->loadPermissions($user);
    }
    
    public function can(Permission|string $permission): bool
    {
        if (is_string($permission)) {
            $permission = Permission::from($permission);
        }
        
        return in_array($permission, $this->userPermissions, true);
    }
    
    public function cannot(Permission|string $permission): bool
    {
        return !$this->can($permission);
    }
    
    public function authorize(Permission|string $permission): void
    {
        if ($this->cannot($permission)) {
            throw new AccessDeniedException(
                "Access denied: {$permission->value} permission required"
            );
        }
    }
    
    public function canAny(array $permissions): bool
    {
        foreach ($permissions as $permission) {
            if ($this->can($permission)) {
                return true;
            }
        }
        return false;
    }
    
    public function canAll(array $permissions): bool
    {
        foreach ($permissions as $permission) {
            if (!$this->can($permission)) {
                return false;
            }
        }
        return true;
    }
    
    private function loadPermissions(User $user): array
    {
        // Get user's roles and their permissions
        $roles = $this->getUserRoles($user);
        $permissions = [];
        
        foreach ($roles as $role) {
            $permissions = array_merge($permissions, $role->permissions());
        }
        
        // Add any direct user permissions (overrides)
        $directPermissions = $this->getDirectPermissions($user);
        $permissions = array_merge($permissions, $directPermissions);
        
        // Remove any denied permissions
        $deniedPermissions = $this->getDeniedPermissions($user);
        $permissions = array_diff($permissions, $deniedPermissions);
        
        return array_unique($permissions);
    }
    
    private function getUserRoles(User $user): array
    {
        // Fetch from database
        // SELECT r.name FROM roles r
        // JOIN user_roles ur ON r.id = ur.role_id
        // WHERE ur.user_id = :user_id
        return [Role::Editor]; // Example
    }
    
    private function getDirectPermissions(User $user): array
    {
        // Individual permissions granted to user
        return [];
    }
    
    private function getDeniedPermissions(User $user): array
    {
        // Permissions explicitly denied even if role has them
        return [];
    }
}

// Middleware integration
class AuthorizationMiddleware
{
    private AccessControl $access;
    
    public function requirePermission(Permission $permission): callable
    {
        return function (Request $request, callable $next) use ($permission): Response {
            $this->access->authorize($permission);
            return $next($request);
        };
    }
    
    public function requireAnyPermission(array $permissions): callable
    {
        return function (Request $request, callable $next) use ($permissions): Response {
            if (!$this->access->canAny($permissions)) {
                $required = implode(', ', array_map(fn($p) => $p->value, $permissions));
                throw new AccessDeniedException("Access denied: any of [{$required}] required");
            }
            return $next($request);
        };
    }
}

// Controller usage
class ArticleController
{
    private AccessControl $access;
    
    public function store(Request $request): Response
    {
        $this->access->authorize(Permission::CreateArticles);
        
        // Authorized - proceed with creation
    }
    
    public function destroy(Request $request, int $id): Response
    {
        $this->access->authorize(Permission::DeleteArticles);
        
        $article = Article::findOrFail($id);
        
        // Additional ownership check
        if ($article->author_id !== Auth::user()->id 
            && !$this->access->can(Permission::DeleteArticles)) {
            throw new AccessDeniedException('You can only delete your own articles');
        }
        
        $article->delete();
    }
}
```

#### 21.4 Secure Randomness and Token Generation

**Cryptographically Secure Random Values**

```php
class SecureRandom
{
    // Generate cryptographically secure random bytes
    public static function bytes(int $length = 32): string
    {
        return random_bytes($length);
    }
    
    // Generate a random integer
    public static function int(int $min, int $max): int
    {
        return random_int($min, $max);
    }
    
    // Generate a random string (hex)
    public static function hex(int $length = 32): string
    {
        return bin2hex(random_bytes($length / 2));
    }
    
    // Generate a random string (alphanumeric)
    public static function alphanumeric(int $length = 32): string
    {
        $chars = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789';
        $result = '';
        $charsLength = strlen($chars);
        
        for ($i = 0; $i < $length; $i++) {
            $result .= $chars[self::int(0, $charsLength - 1)];
        }
        
        return $result;
    }
    
    // Generate a URL-safe random string
    public static function urlSafe(int $length = 32): string
    {
        return rtrim(strtr(base64_encode(random_bytes($length)), '+/', '-_'), '=');
    }
}
```

**Token Generation for Various Purposes**

```php
class TokenGenerator
{
    private PDO $pdo;
    
    // Password reset token
    public function generatePasswordResetToken(int $userId): string
    {
        $token = SecureRandom::urlSafe(32);
        $hashedToken = hash('sha256', $token);
        
        $stmt = $this->pdo->prepare(
            'UPDATE password_resets SET used_at = NOW() WHERE user_id = :user_id AND used_at IS NULL'
        );
        $stmt->execute(['user_id' => $userId]);
        
        $stmt = $this->pdo->prepare(
            'INSERT INTO password_resets (user_id, hashed_token, expires_at, created_at)
             VALUES (:user_id, :token, DATE_ADD(NOW(), INTERVAL 1 HOUR), NOW())'
        );
        $stmt->execute([
            'user_id' => $userId,
            'token' => $hashedToken,
        ]);
        
        return $token;
    }
    
    public function validatePasswordResetToken(string $token): ?int
    {
        $hashedToken = hash('sha256', $token);
        
        $stmt = $this->pdo->prepare(
            'SELECT user_id FROM password_resets 
             WHERE hashed_token = :token 
             AND used_at IS NULL 
             AND expires_at > NOW()'
        );
        $stmt->execute(['token' => $hashedToken]);
        $row = $stmt->fetch();
        
        if (!$row) {
            return null;
        }
        
        // Mark token as used
        $stmt = $this->pdo->prepare(
            'UPDATE password_resets SET used_at = NOW() WHERE hashed_token = :token'
        );
        $stmt->execute(['token' => $hashedToken]);
        
        return (int) $row['user_id'];
    }
    
    // Email verification token
    public function generateEmailVerificationToken(int $userId): string
    {
        return $this->generateSignedToken($userId, 'email_verify', 48);
    }
    
    // API key generation
    public function generateApiKey(): string
    {
        $prefix = 'sk_'; // sk = secret key
        $random = SecureRandom::alphanumeric(48);
        return $prefix . $random;
    }
    
    // Signed tokens (prevents tampering)
    private function generateSignedToken(int $userId, string $purpose, int $expiryHours): string
    {
        $payload = [
            'user_id' => $userId,
            'purpose' => $purpose,
            'expires_at' => time() + ($expiryHours * 3600),
            'token_id' => SecureRandom::hex(16),
        ];
        
        $payloadJson = json_encode($payload);
        $signature = hash_hmac('sha256', $payloadJson, $_ENV['APP_KEY']);
        
        return base64_encode($payloadJson . '.' . $signature);
    }
    
    public function validateSignedToken(string $token, string $purpose): ?int
    {
        $decoded = base64_decode($token);
        
        if ($decoded === false) {
            return null;
        }
        
        $parts = explode('.', $decoded);
        
        if (count($parts) !== 2) {
            return null;
        }
        
        [$payloadJson, $signature] = $parts;
        
        // Verify signature
        $expectedSignature = hash_hmac('sha256', $payloadJson, $_ENV['APP_KEY']);
        
        if (!hash_equals($expectedSignature, $signature)) {
            return null;
        }
        
        $payload = json_decode($payloadJson, true);
        
        if (!$payload || $payload['purpose'] !== $purpose) {
            return null;
        }
        
        if ($payload['expires_at'] < time()) {
            return null;
        }
        
        return $payload['user_id'];
    }
}

// Secure session ID generation
session_start();

// PHP 7.1+ improved session ID generation
ini_set('session.sid_length', '48');
ini_set('session.sid_bits_per_character', '6'); // More entropy per character
session_regenerate_id(true);
```

**Constant-Time Comparison**

```php
class TimingSafeComparison
{
    // Always use hash_equals for comparing security tokens
    public static function compare(string $known, string $user): bool
    {
        return hash_equals($known, $user);
    }
    
    // Example: Never do this for security comparisons
    public static function unsafeCompare(string $known, string $user): bool
    {
        return $known === $user; // Vulnerable to timing attacks
    }
    
    // HMAC verification
    public static function verifyHmac(string $message, string $hmac, string $key): bool
    {
        $expectedHmac = hash_hmac('sha256', $message, $key);
        return hash_equals($expectedHmac, $hmac);
    }
}

// Webhook signature verification
class WebhookVerifier
{
    private string $webhookSecret;
    
    public function verifySignature(string $payload, string $signatureHeader): bool
    {
        $signature = hash_hmac('sha256', $payload, $this->webhookSecret);
        $expected = "sha256={$signature}";
        
        return hash_equals($expected, $signatureHeader);
    }
    
    public function handleWebhook(Request $request): Response
    {
        $payload = file_get_contents('php://input');
        $signature = $request->header('X-Webhook-Signature', '');
        
        if (!$this->verifySignature($payload, $signature)) {
            return new Response('Invalid signature', 403);
        }
        
        // Process webhook
        $data = json_decode($payload, true);
        // ...
        
        return new Response('OK', 200);
    }
}
```

---


## Part VII: Testing and Quality Assurance


### Chapter 22: Unit Testing with PHPUnit

#### 22.1 Installation, Configuration, and Test Structure

PHPUnit is the de facto standard for testing PHP applications. It provides a comprehensive framework for writing and running tests, from simple unit tests to complex integration test suites.

**Installing PHPUnit**

```bash
# Install as a development dependency
composer require --dev phpunit/phpunit ^11.0

# Verify installation
./vendor/bin/phpunit --version

# Or install globally
wget https://phar.phpunit.de/phpunit-11.phar
chmod +x phpunit-11.phar
sudo mv phpunit-11.phar /usr/local/bin/phpunit
```

**PHPUnit Configuration**

Create `phpunit.xml` in your project root:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<phpunit 
    xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xsi:noNamespaceSchemaLocation="https://schema.phpunit.de/11.0/phpunit.xsd"
    bootstrap="tests/bootstrap.php"
    colors="true"
    stopOnFailure="false"
    cacheDirectory=".phpunit.cache"
    beStrictAboutOutputDuringTests="true"
    beStrictAboutChangesToGlobalState="true"
    failOnRisky="true"
    failOnWarning="true"
>
    <testsuites>
        <testsuite name="Unit">
            <directory>tests/Unit</directory>
        </testsuite>
        <testsuite name="Integration">
            <directory>tests/Integration</directory>
        </testsuite>
        <testsuite name="Feature">
            <directory>tests/Feature</directory>
        </testsuite>
    </testsuites>

    <source>
        <include>
            <directory>src</directory>
        </include>
        <exclude>
            <directory>src/Resources</directory>
        </exclude>
    </source>

    <coverage>
        <report>
            <html outputDirectory="coverage" lowUpperBound="50" highLowerBound="90"/>
            <text outputFile="php://stdout" showUncoveredFiles="true"/>
        </report>
    </coverage>

    <php>
        <env name="APP_ENV" value="testing"/>
        <env name="DB_DATABASE" value="testing"/>
        <env name="CACHE_DRIVER" value="array"/>
        <env name="SESSION_DRIVER" value="array"/>
        <env name="MAIL_MAILER" value="array"/>
        <ini name="display_errors" value="On"/>
        <ini name="error_reporting" value="E_ALL"/>
    </php>
</phpunit>
```

**Bootstrap File**

Create `tests/bootstrap.php` to set up the testing environment:

```php
<?php
declare(strict_types=1);

require_once __DIR__ . '/../vendor/autoload.php';

// Set up testing environment
putenv('APP_ENV=testing');

// Load environment variables for testing
$dotenv = Dotenv\Dotenv::createImmutable(__DIR__ . '/..', '.env.testing');
$dotenv->load();

// Initialize test database or other resources
// Database::initialize();
```

**Test Structure and Organization**

Tests mirror the source directory structure:

```
project/
├── src/
│   ├── Models/
│   │   └── User.php
│   ├── Services/
│   │   └── PaymentService.php
│   └── Utils/
│       └── StringHelper.php
├── tests/
│   ├── Unit/
│   │   ├── Models/
│   │   │   └── UserTest.php
│   │   ├── Services/
│   │   │   └── PaymentServiceTest.php
│   │   └── Utils/
│   │       └── StringHelperTest.php
│   ├── Integration/
│   │   └── Database/
│   │       └── UserRepositoryTest.php
│   └── Feature/
│       └── Api/
│           └── UserEndpointTest.php
```

**Writing Your First Test**

```php
<?php
declare(strict_types=1);

namespace Tests\Unit\Utils;

use PHPUnit\Framework\TestCase;
use App\Utils\StringHelper;

class StringHelperTest extends TestCase
{
    public function testTruncateReturnsShortString(): void
    {
        $text = 'Hello World';
        $result = StringHelper::truncate($text, 5);
        
        $this->assertSame('He...', $result);
    }
    
    public function testTruncateReturnsFullStringWhenShorter(): void
    {
        $text = 'Hello';
        $result = StringHelper::truncate($text, 10);
        
        $this->assertSame('Hello', $result);
    }
    
    public function testTruncateThrowsExceptionForNegativeLength(): void
    {
        $this->expectException(\InvalidArgumentException::class);
        
        StringHelper::truncate('Hello', -1);
    }
}
```

**Running Tests**

```bash
# Run all tests
./vendor/bin/phpunit

# Run specific test suite
./vendor/bin/phpunit --testsuite=Unit

# Run specific test file
./vendor/bin/phpunit tests/Unit/Utils/StringHelperTest.php

# Run specific test method
./vendor/bin/phpunit --filter testTruncateReturnsShortString

# Run with verbose output
./vendor/bin/phpunit --verbose

# Run with testdox (human-readable output)
./vendor/bin/phpunit --testdox

# Generate code coverage
./vendor/bin/phpunit --coverage-html coverage/
```

#### 22.2 Assertions, Data Providers, and Fixtures

**Common Assertions**

```php
class AssertionExamplesTest extends TestCase
{
    public function testEqualityAssertions(): void
    {
        // Strict equality (type and value)
        $this->assertSame(42, 42);
        $this->assertSame('hello', 'hello');
        $this->assertSame(['a', 'b'], ['a', 'b']);
        
        // Loose equality
        $this->assertEquals(42, '42');
        $this->assertEquals(['a' => 1], ['a' => '1']);
        
        // Not equal
        $this->assertNotSame(42, '42');
        $this->assertNotEquals(42, 43);
    }
    
    public function testTypeAssertions(): void
    {
        $this->assertIsArray([1, 2, 3]);
        $this->assertIsString('hello');
        $this->assertIsInt(42);
        $this->assertIsFloat(3.14);
        $this->assertIsBool(true);
        $this->assertIsObject(new \stdClass());
        $this->assertNull(null);
        $this->assertNotNull('value');
    }
    
    public function testBooleanAssertions(): void
    {
        $this->assertTrue(true);
        $this->assertFalse(false);
        $this->assertTrue(1 === 1);
    }
    
    public function testContainsAssertions(): void
    {
        $this->assertContains(3, [1, 2, 3, 4]);
        $this->assertContains('world', 'hello world');
        $this->assertContains('key', ['key' => 'value']);
        
        $this->assertStringContainsString('PHP', 'Learning PHP');
        $this->assertStringStartsWith('Hello', 'Hello World');
        $this->assertStringEndsWith('.txt', 'document.txt');
        
        $this->assertMatchesRegularExpression('/\d{3}-\d{3}-\d{4}/', '555-123-4567');
    }
    
    public function testCountAssertions(): void
    {
        $this->assertCount(3, [1, 2, 3]);
        $this->assertCount(0, []);
        $this->assertNotEmpty(['item']);
        $this->assertEmpty([]);
    }
    
    public function testExceptionAssertions(): void
    {
        // Expect specific exception
        $this->expectException(\InvalidArgumentException::class);
        $this->expectExceptionMessage('Invalid value');
        $this->expectExceptionCode(400);
        
        throw new \InvalidArgumentException('Invalid value', 400);
    }
    
    public function testFileAssertions(): void
    {
        $this->assertFileExists('/path/to/file.txt');
        $this->assertFileDoesNotExist('/path/to/missing.txt');
        $this->assertDirectoryExists('/path/to/dir');
        $this->assertFileIsReadable('/path/to/readable.txt');
    }
    
    public function testJsonAssertions(): void
    {
        $this->assertJson('{"name":"Alice","age":30}');
        $this->assertJsonStringEqualsJsonString(
            '{"name":"Alice"}',
            '{"name":"Alice"}'
        );
    }
    
    public function testObjectAssertions(): void
    {
        $user = new \stdClass();
        $user->name = 'Alice';
        
        $this->assertObjectHasProperty('name', $user);
        $this->assertInstanceOf(\stdClass::class, $user);
    }
}
```

**Data Providers**

Data providers supply multiple test cases to a single test method:

```php
class CalculatorTest extends TestCase
{
    /**
     * @dataProvider additionProvider
     * @dataProvider additionalAdditionProvider
     */
    public function testAdd(int $a, int $b, int $expected): void
    {
        $calculator = new Calculator();
        
        $this->assertSame($expected, $calculator->add($a, $b));
    }
    
    public static function additionProvider(): array
    {
        return [
            'zeros' => [0, 0, 0],
            'positive numbers' => [1, 2, 3],
            'negative numbers' => [-1, -2, -3],
            'mixed signs' => [-5, 10, 5],
            'large numbers' => [1000, 2000, 3000],
        ];
    }
    
    public static function additionalAdditionProvider(): array
    {
        return [
            'zero plus number' => [0, 5, 5],
            'number plus zero' => [5, 0, 5],
        ];
    }
    
    /**
     * @dataProvider divisionProvider
     */
    public function testDivide(int $a, int $b, int|float $expected, bool $expectException = false): void
    {
        if ($expectException) {
            $this->expectException(\DivisionByZeroError::class);
        }
        
        $calculator = new Calculator();
        $result = $calculator->divide($a, $b);
        
        if (!$expectException) {
            $this->assertSame($expected, $result);
        }
    }
    
    public static function divisionProvider(): array
    {
        return [
            'basic division' => [10, 2, 5],
            'non-integer result' => [10, 3, 10 / 3],
            'negative division' => [-10, 2, -5],
            'division by zero' => [10, 0, null, true],
        ];
    }
}
```

**Named Data Sets for Better Error Messages**

```php
public static function userProvider(): array
{
    return [
        'admin user' => [
            'user' => ['id' => 1, 'role' => 'admin', 'email' => 'admin@example.com'],
            'expectedAccess' => ['users', 'settings', 'reports'],
        ],
        'regular user' => [
            'user' => ['id' => 2, 'role' => 'user', 'email' => 'user@example.com'],
            'expectedAccess' => ['profile'],
        ],
        'guest user' => [
            'user' => ['id' => null, 'role' => 'guest', 'email' => null],
            'expectedAccess' => ['login'],
        ],
    ];
}

/**
 * @dataProvider userProvider
 */
public function testUserPermissions(array $user, array $expectedAccess): void
{
    $accessControl = new AccessControl(new User($user));
    
    foreach ($expectedAccess as $resource) {
        $this->assertTrue(
            $accessControl->canAccess($resource),
            "User with role {$user['role']} should access {$resource}"
        );
    }
}
```

**Test Fixtures (setUp and tearDown)**

```php
class UserRepositoryTest extends TestCase
{
    private ?PDO $pdo = null;
    private ?UserRepository $repository = null;
    private array $testUsers = [];
    
    protected function setUp(): void
    {
        // Runs before each test method
        $this->pdo = new PDO(
            'sqlite::memory:',
            null,
            null,
            [PDO::ATTR_ERRMODE => PDO::ERRMODE_EXCEPTION]
        );
        
        // Create test schema
        $this->pdo->exec('
            CREATE TABLE users (
                id INTEGER PRIMARY KEY AUTOINCREMENT,
                name TEXT NOT NULL,
                email TEXT UNIQUE NOT NULL,
                created_at TEXT NOT NULL
            )
        ');
        
        $this->repository = new UserRepository($this->pdo);
    }
    
    protected function tearDown(): void
    {
        // Runs after each test method
        $this->pdo = null;
        $this->repository = null;
    }
    
    public function testInsertUser(): void
    {
        $user = $this->repository->create([
            'name' => 'Alice',
            'email' => 'alice@example.com',
        ]);
        
        $this->assertNotNull($user->id);
        $this->assertSame('Alice', $user->name);
    }
    
    public function testFindByEmail(): void
    {
        // Insert test data
        $this->repository->create([
            'name' => 'Bob',
            'email' => 'bob@example.com',
        ]);
        
        $user = $this->repository->findByEmail('bob@example.com');
        
        $this->assertNotNull($user);
        $this->assertSame('Bob', $user->name);
    }
}

// setUpBeforeClass and tearDownAfterClass run once per test class
class DatabaseIntegrationTest extends TestCase
{
    private static ?PDO $sharedConnection = null;
    
    public static function setUpBeforeClass(): void
    {
        self::$sharedConnection = new PDO(
            'mysql:host=127.0.0.1;dbname=testing',
            'test_user',
            'test_password',
            [PDO::ATTR_ERRMODE => PDO::ERRMODE_EXCEPTION]
        );
        
        // Run migrations
        self::$sharedConnection->exec('CREATE TABLE IF NOT EXISTS ...');
    }
    
    public static function tearDownAfterClass(): void
    {
        // Clean up test data
        self::$sharedConnection->exec('DELETE FROM users');
        self::$sharedConnection = null;
    }
}
```

**Custom Assertions**

```php
trait CustomAssertions
{
    protected function assertValidEmail(string $email, string $message = ''): void
    {
        $this->assertMatchesRegularExpression(
            '/^[\w.%+-]+@[\w.-]+\.[a-zA-Z]{2,}$/',
            $email,
            $message ?: "{$email} is not a valid email address"
        );
    }
    
    protected function assertIsValidJson(string $json, string $message = ''): void
    {
        $data = json_decode($json, true);
        $this->assertNotNull(
            $data,
            $message ?: 'String is not valid JSON'
        );
        $this->assertSame(JSON_ERROR_NONE, json_last_error());
    }
    
    protected function assertArrayHasKeys(array $keys, array $array, string $message = ''): void
    {
        foreach ($keys as $key) {
            $this->assertArrayHasKey(
                $key,
                $array,
                $message ?: "Array missing key: {$key}"
            );
        }
    }
    
    protected function assertResponseSuccessful(array $response): void
    {
        $this->assertArrayHasKey('status', $response);
        $this->assertGreaterThanOrEqual(200, $response['status']);
        $this->assertLessThan(300, $response['status']);
    }
}

class UserApiTest extends TestCase
{
    use CustomAssertions;
    
    public function testCreateUserResponse(): void
    {
        $response = [
            'status' => 201,
            'data' => [
                'id' => 1,
                'name' => 'Alice',
                'email' => 'alice@example.com',
            ],
        ];
        
        $this->assertResponseSuccessful($response);
        $this->assertArrayHasKeys(['id', 'name', 'email'], $response['data']);
        $this->assertValidEmail($response['data']['email']);
    }
}
```

#### 22.3 Mocking, Stubbing, and Test Doubles

Test doubles replace real dependencies with controlled substitutes, enabling isolated testing.

**Creating Mocks and Stubs**

```php
class OrderServiceTest extends TestCase
{
    public function testPlaceOrderCalculatesTotal(): void
    {
        // Create a mock for the PaymentGateway
        $paymentGateway = $this->createMock(PaymentGateway::class);
        
        // Configure the mock's behavior
        $paymentGateway
            ->expects($this->once())
            ->method('charge')
            ->with($this->equalTo(100.00))
            ->willReturn(new PaymentResult(true, 'txn_123'));
        
        // Alternative: createStub for simpler cases (no expectations)
        $inventoryService = $this->createStub(InventoryService::class);
        $inventoryService
            ->method('checkAvailability')
            ->willReturn(true);
        $inventoryService
            ->method('reserve')
            ->willReturn(true);
        
        $orderService = new OrderService($paymentGateway, $inventoryService);
        
        $result = $orderService->placeOrder([
            'items' => [['product_id' => 1, 'quantity' => 2, 'price' => 50.00]],
            'user_id' => 1,
        ]);
        
        $this->assertTrue($result->isSuccessful());
        $this->assertSame('txn_123', $result->getTransactionId());
    }
    
    public function testPlaceOrderThrowsExceptionOnPaymentFailure(): void
    {
        $paymentGateway = $this->createMock(PaymentGateway::class);
        $paymentGateway
            ->method('charge')
            ->willThrowException(new PaymentFailedException('Card declined'));
        
        $inventoryService = $this->createStub(InventoryService::class);
        $inventoryService->method('checkAvailability')->willReturn(true);
        
        $orderService = new OrderService($paymentGateway, $inventoryService);
        
        $this->expectException(PaymentFailedException::class);
        
        $orderService->placeOrder([
            'items' => [['product_id' => 1, 'quantity' => 1, 'price' => 99.99]],
            'user_id' => 1,
        ]);
    }
}
```

**Advanced Mock Configuration**

```php
class NotificationServiceTest extends TestCase
{
    public function testSendNotificationWithMethodVerification(): void
    {
        $mailer = $this->createMock(Mailer::class);
        
        // Verify method called exactly once
        $mailer->expects($this->once())
               ->method('send')
               ->willReturn(true);
        
        // Verify method called with specific arguments
        $mailer->expects($this->exactly(2))
               ->method('addRecipient')
               ->withConsecutive(
                   ['alice@example.com'],
                   ['bob@example.com'],
               );
        
        // Verify method never called
        $mailer->expects($this->never())
               ->method('sendToAll');
        
        $service = new NotificationService($mailer);
        $service->notify(['alice@example.com', 'bob@example.com'], 'Test message');
    }
    
    public function testWithCallbackMatcher(): void
    {
        $logger = $this->createMock(LoggerInterface::class);
        
        $logger->expects($this->once())
               ->method('log')
               ->with(
                   $this->equalTo('error'),
                   $this->callback(function (string $message): bool {
                       return str_contains($message, 'User') 
                           && str_contains($message, 'not found');
                   })
               );
        
        $service = new UserService($logger);
        $service->findUser(999); // Should log error
    }
    
    public function testReturnValueMap(): void
    {
        $cache = $this->createMock(CacheInterface::class);
        
        // Different return values for different arguments
        $cache->method('get')
              ->willReturnMap([
                  ['user:1', 'Alice'],
                  ['user:2', 'Bob'],
                  ['user:999', null],
              ]);
        
        $this->assertSame('Alice', $cache->get('user:1'));
        $this->assertSame('Bob', $cache->get('user:2'));
        $this->assertNull($cache->get('user:999'));
    }
    
    public function testReturnCallback(): void
    {
        $repository = $this->createMock(UserRepository::class);
        
        // Dynamic return values based on arguments
        $repository->method('findById')
                   ->willReturnCallback(function (int $id): ?User {
                       if ($id > 0 && $id <= 100) {
                           return new User($id, "User {$id}");
                       }
                       return null;
                   });
        
        $this->assertNotNull($repository->findById(42));
        $this->assertNull($repository->findById(999));
    }
    
    public function testWithAnyParameter(): void
    {
        $mailer = $this->createMock(Mailer::class);
        
        // Accept any argument
        $mailer->expects($this->exactly(3))
               ->method('send')
               ->with(
                   $this->anything(),
                   $this->stringContains('Order'),
                   $this->isType('string')
               );
    }
}
```

**Partial Mocks**

```php
class ReportServiceTest extends TestCase
{
    public function testGenerateReport(): void
    {
        // Create partial mock - only mock specific methods
        $service = $this->getMockBuilder(ReportService::class)
            ->onlyMethods(['fetchData', 'formatData'])
            ->getMock();
        
        // Mock the data fetching
        $service->method('fetchData')
                ->willReturn([
                    ['month' => 'January', 'sales' => 1000],
                    ['month' => 'February', 'sales' => 1200],
                ]);
        
        // Let formatData use the real implementation
        $service->expects($this->once())
                ->method('formatData')
                ->willReturnCallback(function (array $data): array {
                    // Real formatting logic
                    return array_map(fn($row) => [
                        'label' => $row['month'],
                        'value' => $row['sales'],
                    ], $data);
                });
        
        $report = $service->generateReport();
        
        $this->assertCount(2, $report);
        $this->assertSame('January', $report[0]['label']);
    }
}
```

**Dummy, Fake, and Spy Objects**

```php
// Dummy: Passed but never used
class DummyLogger implements LoggerInterface
{
    public function log(string $level, string $message): void {}
    public function error(string $message): void {}
    public function warning(string $message): void {}
}

// Fake: Working implementation for testing
class FakePaymentGateway implements PaymentGatewayInterface
{
    private array $transactions = [];
    
    public function charge(float $amount): PaymentResult
    {
        $transaction = [
            'id' => 'fake_' . count($this->transactions),
            'amount' => $amount,
            'status' => 'success',
        ];
        
        $this->transactions[] = $transaction;
        
        return new PaymentResult(true, $transaction['id']);
    }
    
    public function getTransactions(): array
    {
        return $this->transactions;
    }
    
    public function shouldFailNext(): void
    {
        // Set flag to fail next transaction
    }
}

// Spy: Records calls for later verification
class SpyMailer implements MailerInterface
{
    private array $sent = [];
    
    public function send(string $recipient, string $subject, string $body): bool
    {
        $this->sent[] = [
            'recipient' => $recipient,
            'subject' => $subject,
            'body' => $body,
        ];
        return true;
    }
    
    public function wasSentTo(string $email): bool
    {
        foreach ($this->sent as $mail) {
            if ($mail['recipient'] === $email) {
                return true;
            }
        }
        return false;
    }
    
    public function sentCount(): int
    {
        return count($this->sent);
    }
    
    public function lastSent(): ?array
    {
        return $this->sent[count($this->sent) - 1] ?? null;
    }
}

// Using spy in test
class RegistrationServiceTest extends TestCase
{
    public function testWelcomeEmailSent(): void
    {
        $mailer = new SpyMailer();
        $service = new RegistrationService($mailer);
        
        $service->register('Alice', 'alice@example.com', 'password123');
        
        $this->assertTrue($mailer->wasSentTo('alice@example.com'));
        $this->assertSame(1, $mailer->sentCount());
        
        $lastEmail = $mailer->lastSent();
        $this->assertStringContainsString('Welcome', $lastEmail['subject']);
    }
}
```

#### 22.4 Code Coverage and Mutation Testing

**Understanding Code Coverage**

Code coverage measures which lines, branches, and paths are executed during tests:

```bash
# Generate HTML coverage report
./vendor/bin/phpunit --coverage-html coverage/

# Generate text coverage report
./vendor/bin/phpunit --coverage-text

# Generate Clover XML for CI tools
./vendor/bin/phpunit --coverage-clover coverage.xml

# Generate Cobertura XML
./vendor/bin/phpunit --coverage-cobertura coverage.xml

# Require minimum coverage
./vendor/bin/phpunit --coverage-text --path-coverage --min-coverage 80
```

**Coverage Configuration in phpunit.xml**

```xml
<coverage>
    <report>
        <html outputDirectory="coverage" lowUpperBound="50" highLowerBound="90"/>
        <text outputFile="php://stdout" showUncoveredFiles="false" showOnlySummary="true"/>
        <clover outputFile="coverage/clover.xml"/>
    </report>
    <include>
        <directory suffix=".php">src</directory>
    </include>
    <exclude>
        <directory suffix=".php">src/Resources</directory>
        <directory suffix=".php">src/Migrations</directory>
        <file>src/bootstrap.php</file>
    </exclude>
</coverage>
```

**Testing Uncovered Code**

```php
class UserService
{
    public function processUser(array $data): ?User
    {
        // Validate input
        if (empty($data['email'])) {
            throw new \InvalidArgumentException('Email is required');
        }
        
        if (!filter_var($data['email'], FILTER_VALIDATE_EMAIL)) {
            throw new \InvalidArgumentException('Invalid email');
        }
        
        // Check if user exists
        $existing = $this->findByEmail($data['email']);
        if ($existing) {
            if ($existing->isDeleted()) {
                return $this->restoreUser($existing);
            }
            return $existing;
        }
        
        // Create new user
        $user = $this->create($data);
        
        // Send welcome email if flag set
        if (($data['send_welcome'] ?? false) && $user->email) {
            $this->sendWelcomeEmail($user);
        }
        
        // Log the action
        $this->logger->info('User processed', [
            'user_id' => $user->id,
            'email' => $user->email,
            'is_new' => !isset($existing),
        ]);
        
        return $user;
    }
}

class UserServiceTest extends TestCase
{
    private UserService $service;
    private UserRepository $repository;
    private MailerInterface $mailer;
    private LoggerInterface $logger;
    
    protected function setUp(): void
    {
        $this->repository = $this->createMock(UserRepository::class);
        $this->mailer = $this->createMock(MailerInterface::class);
        $this->logger = $this->createMock(LoggerInterface::class);
        
        $this->service = new UserService($this->repository, $this->mailer, $this->logger);
    }
    
    public function testProcessNewUser(): void
    {
        $this->repository->method('findByEmail')->willReturn(null);
        $this->repository->method('create')->willReturn(
            new User(1, 'alice@example.com', 'Alice', false)
        );
        
        $this->logger->expects($this->once())
                     ->method('info')
                     ->with('User processed');
        
        $user = $this->service->processUser([
            'email' => 'alice@example.com',
            'name' => 'Alice',
            'send_welcome' => true,
        ]);
        
        $this->assertNotNull($user);
        $this->assertSame(1, $user->id);
    }
    
    public function testProcessExistingUser(): void
    {
        $existingUser = new User(2, 'bob@example.com', 'Bob', false);
        
        $this->repository->method('findByEmail')
                         ->with('bob@example.com')
                         ->willReturn($existingUser);
        
        $this->repository->expects($this->never())->method('create');
        
        $user = $this->service->processUser([
            'email' => 'bob@example.com',
            'name' => 'Bob',
        ]);
        
        $this->assertSame($existingUser, $user);
    }
    
    public function testProcessDeletedUser(): void
    {
        $deletedUser = new User(3, 'charlie@example.com', 'Charlie', true);
        
        $this->repository->method('findByEmail')->willReturn($deletedUser);
        $this->repository->method('restore')->willReturn(
            new User(3, 'charlie@example.com', 'Charlie', false)
        );
        
        $user = $this->service->processUser([
            'email' => 'charlie@example.com',
            'name' => 'Charlie',
        ]);
        
        $this->assertFalse($user->isDeleted());
    }
    
    public function testProcessUserWithInvalidEmailThrowsException(): void
    {
        $this->expectException(\InvalidArgumentException::class);
        $this->expectExceptionMessage('Invalid email');
        
        $this->service->processUser([
            'email' => 'not-an-email',
            'name' => 'Test',
        ]);
    }
    
    public function testProcessUserWithEmptyEmailThrowsException(): void
    {
        $this->expectException(\InvalidArgumentException::class);
        $this->expectExceptionMessage('Email is required');
        
        $this->service->processUser([
            'email' => '',
            'name' => 'Test',
        ]);
    }
}
```

**Mutation Testing with Infection**

Mutation testing verifies test quality by introducing bugs and checking if tests catch them:

```bash
# Install Infection
composer require --dev infection/infection

# Run mutation testing
./vendor/bin/infection

# With configuration
./vendor/bin/infection --configuration=infection.json5 --threads=4

# Only mutate specific files
./vendor/bin/infection --filter=src/Services --show-mutations
```

**Infection Configuration**

```json5
// infection.json5
{
    "$schema": "vendor/infection/infection/schema.json",
    "source": {
        "directories": ["src"]
    },
    "mutators": {
        "@default": true,
        "@function_signature": false,
        "TrueValue": false,
        "FalseValue": false
    },
    "logs": {
        "text": "infection.log",
        "summary": "infection-summary.log",
        "html": "infection-report.html",
        "perMutator": "infection-per-mutator.md"
    },
    "minMsi": 80,
    "minCoveredMsi": 90,
    "timeout": 10
}
```

**Improving Mutation Score**

```php
// Original code with low mutation score
class DiscountCalculator
{
    public function calculate(float $total, bool $isHolidaySeason): float
    {
        if ($isHolidaySeason) {
            return $total * 0.8; // 20% discount
        }
        
        if ($total > 100) {
            return $total * 0.9; // 10% discount
        }
        
        return $total;
    }
}

// Test that catches mutations
class DiscountCalculatorTest extends TestCase
{
    /**
     * @dataProvider discountProvider
     */
    public function testCalculate(float $total, bool $isHoliday, float $expected): void
    {
        $calculator = new DiscountCalculator();
        
        $result = $calculator->calculate($total, $isHoliday);
        
        $this->assertSame($expected, $result);
    }
    
    public static function discountProvider(): array
    {
        return [
            'holiday season always gives 20 percent' => [100.00, true, 80.00],
            'holiday season on small order' => [50.00, true, 40.00],
            'large order regular season' => [150.00, false, 135.00],
            'exactly at threshold' => [100.00, false, 100.00],
            'small order regular season' => [50.00, false, 50.00],
            'zero amount holiday' => [0.00, true, 0.00],
            'zero amount regular' => [0.00, false, 0.00],
        ];
    }
    
    // This test catches boundary mutation (changing > to >=)
    public function testBoundaryCondition(): void
    {
        $calculator = new DiscountCalculator();
        
        $this->assertSame(100.00, $calculator->calculate(100.00, false));
        $this->assertSame(99.00, $calculator->calculate(110.00, false));
    }
}
```

---

### Chapter 23: Quality Tools and CI/CD

#### 23.1 Static Analysis with PHPStan and Psalm

Static analysis tools detect type errors, potential bugs, and code issues without running the code.

**PHPStan Setup and Configuration**

```bash
# Install PHPStan
composer require --dev phpstan/phpstan

# Run analysis
./vendor/bin/phpstan analyse src tests

# Generate configuration
./vendor/bin/phpstan init
```

```yaml
# phpstan.neon
parameters:
    level: 8 # Strictest level
    
    paths:
        - src
    
    excludePaths:
        - src/Migrations/*
        - src/Resources/*
    
    checkMissingIterableValueType: true
    checkGenericClassInNonGenericObjectType: true
    
    treatPhpDocTypesAsCertain: false
    
    universalObjectCratesClasses:
        - stdClass
    
    ignoreErrors:
        - '#Dynamic call to static method#'
        - message: '#Cannot access property#'
          path: src/Legacy/*.php
    
    earlyTerminatingMethodCalls:
        App\Helpers\Debug:
            - dd
            - dump
    
    stubFiles:
        - stubs/WordPress.stub
```

**Running PHPStan with Strict Rules**

```bash
# Install additional strict rules
composer require --dev phpstan/phpstan-strict-rules

# Run at maximum level
./vendor/bin/phpstan analyse --level=max --memory-limit=2G

# Generate baseline (ignore existing errors)
./vendor/bin/phpstan analyse --generate-baseline

# Check baseline hasn't grown
./vendor/bin/phpstan analyse --baseline=phpstan-baseline.neon
```

**PHPStan Custom Rules**

```php
// Custom PHPStan rule: detect SQL injection vulnerabilities
class SQLInjectionRule implements \PHPStan\Rules\Rule
{
    public function getNodeType(): string
    {
        return \PhpParser\Node\Expr\MethodCall::class;
    }
    
    public function processNode(
        \PhpParser\Node $node,
        \PHPStan\Analyser\Scope $scope,
    ): array {
        if (!$node->name instanceof \PhpParser\Node\Identifier) {
            return [];
        }
        
        if ($node->name->name !== 'query') {
            return [];
        }
        
        // Check if argument is concatenated string
        $args = $node->getArgs();
        if (count($args) > 0 && $args[0]->value instanceof \PhpParser\Node\Expr\BinaryOp\Concat) {
            return [
                \PHPStan\Rules\RuleErrorBuilder::message(
                    'Potential SQL injection: concatenating strings in query()'
                )
                ->identifier('security.sqlInjection')
                ->build(),
            ];
        }
        
        return [];
    }
}
```

**Psalm Configuration**

```bash
# Install Psalm
composer require --dev vimeo/psalm

# Initialize
./vendor/bin/psalm --init

# Run analysis
./vendor/bin/psalm
```

```xml
<!-- psalm.xml -->
<?xml version="1.0"?>
<psalm
    errorLevel="1"
    resolveFromConfigFile="true"
    xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xmlns="https://getpsalm.org/schema/config"
    xsi:schemaLocation="https://getpsalm.org/schema/config vendor/vimeo/psalm/config.xsd"
    findUnusedBaselineEntry="true"
    findUnusedCode="false"
>
    <projectFiles>
        <directory name="src"/>
        <ignoreFiles>
            <directory name="vendor"/>
            <directory name="tests"/>
        </ignoreFiles>
    </projectFiles>

    <stubs>
        <file name="stubs/WordPress.stub"/>
    </stubs>

    <issueHandlers>
        <MissingConstructor>
            <errorLevel type="suppress">
                <directory name="src/Models"/>
            </errorLevel>
        </MissingConstructor>

        <PropertyNotSetInConstructor>
            <errorLevel type="suppress">
                <directory name="src/DTOs"/>
            </errorLevel>
        </PropertyNotSetInConstructor>
    </issueHandlers>
</psalm>
```

**Psalm Security Analysis**

```bash
# Install security analysis plugin
composer require --dev psalm/plugin-laravel
composer require --dev psalm/plugin-phpunit

# Run with taint analysis
./vendor/bin/psalm --taint-analysis

# Show info about issues
./vendor/bin/psalm --show-info=true
```

**Integrating Static Analysis in Development**

```php
// phpstan.neon - Custom type specification
parameters:
    typeAliases:
        UserId: 'int'
        EmailAddress: 'string'
    
    earlyTerminatingMethodCalls:
        Illuminate\Support\Facades\Response:
            - abort
            - redirect

// Custom PHPDoc for static analysis
class UserRepository
{
    /**
     * @param UserId $id
     * @return User|null
     */
    public function findById(int $id): ?User
    {
        return User::find($id);
    }
    
    /**
     * @return array<int, User>
     */
    public function findAll(): array
    {
        return User::all()->all();
    }
    
    /**
     * @param array<string, mixed> $criteria
     * @return array<int, User>
     */
    public function findBy(array $criteria): array
    {
        return User::where($criteria)->get()->all();
    }
}
```

#### 23.2 Code Style: PHP-CS-Fixer and PHPCS

**PHP-CS-Fixer Setup**

```bash
composer require --dev friendsofphp/php-cs-fixer

# Check code style
./vendor/bin/php-cs-fixer fix --dry-run --diff

# Fix code style
./vendor/bin/php-cs-fixer fix

# Create configuration
./vendor/bin/php-cs-fixer init
```

```php
// .php-cs-fixer.dist.php
<?php

$finder = PhpCsFixer\Finder::create()
    ->in([
        __DIR__ . '/src',
        __DIR__ . '/tests',
    ])
    ->exclude([
        'vendor',
        'storage',
        'bootstrap/cache',
    ])
    ->notPath('Migrations/*')
    ->name('*.php')
    ->ignoreDotFiles(true)
    ->ignoreVCS(true);

return (new PhpCsFixer\Config())
    ->setRules([
        '@PSR12' => true,
        '@PHP82Migration' => true,
        
        // Array notation
        'array_syntax' => ['syntax' => 'short'],
        'no_multiline_whitespace_around_double_arrow' => true,
        
        // Strict types
        'declare_strict_types' => true,
        
        // Spacing
        'binary_operator_spaces' => [
            'default' => 'single_space',
            'operators' => [
                '=>' => 'align_single_space_minimal',
            ],
        ],
        'blank_line_after_opening_tag' => true,
        'blank_line_before_statement' => [
            'statements' => ['return', 'throw', 'try'],
        ],
        'method_argument_space' => [
            'on_multiline' => 'ensure_fully_multiline',
        ],
        
        // PHPDoc
        'phpdoc_align' => ['align' => 'left'],
        'phpdoc_no_empty_return' => true,
        'phpdoc_order' => true,
        'phpdoc_separation' => true,
        'phpdoc_trim' => true,
        
        // Imports
        'no_unused_imports' => true,
        'ordered_imports' => ['sort_algorithm' => 'alpha'],
        
        // Modern PHP
        'modernize_strpos' => true,
        'no_superfluous_phpdoc_tags' => false,
        'nullable_type_declaration_for_default_null_value' => true,
        
        // Control structures
        'trailing_comma_in_multiline' => [
            'elements' => ['arrays', 'arguments', 'parameters'],
        ],
        'yoda_style' => ['equal' => false, 'identical' => false],
        
        // Casting
        'cast_spaces' => ['space' => 'none'],
        'modernize_types_casting' => true,
        
        // Operators
        'concat_space' => ['spacing' => 'one'],
        'not_operator_with_space' => false,
        'not_operator_with_successor_space' => false,
        'increment_style' => ['style' => 'post'],
        
        // Miscellaneous
        'single_quote' => true,
        'no_trailing_comma_in_singleline' => true,
        'no_whitespace_in_blank_line' => true,
        'no_extra_blank_lines' => [
            'tokens' => [
                'extra',
                'throw',
                'use',
            ],
        ],
    ])
    ->setFinder($finder)
    ->setRiskyAllowed(true)
    ->setUsingCache(true)
    ->setCacheFile(__DIR__ . '/.php_cs.cache');
```

**PHP CodeSniffer**

```bash
composer require --dev squizlabs/php_codesniffer

# Check standards
./vendor/bin/phpcs src/ --standard=PSR12

# Generate report
./vendor/bin/phpcs --report=full --report-file=phpcs-report.txt

# Auto-fix issues
./vendor/bin/phpcbf src/
```

```xml
<!-- phpcs.xml -->
<?xml version="1.0"?>
<ruleset name="Custom Standard">
    <description>Custom PHP coding standard based on PSR-12</description>

    <!-- Include PSR-12 standard -->
    <rule ref="PSR12">
        <!-- Exclude specific rules -->
        <exclude name="PSR12.Files.FileHeader.SpacingAfterBlock"/>
    </rule>

    <!-- File requirements -->
    <rule ref="Generic.Files.LineLength">
        <properties>
            <property name="lineLimit" value="120"/>
            <property name="absoluteLineLimit" value="150"/>
        </properties>
    </rule>

    <!-- Documentation -->
    <rule ref="Generic.Commenting.DocComment">
        <exclude name="Generic.Commenting.DocComment.MissingShort"/>
    </rule>

    <!-- Naming conventions -->
    <rule ref="Generic.NamingConventions.CamelCapsFunctionName">
        <properties>
            <property name="strict" value="true"/>
        </properties>
    </rule>

    <!-- Security -->
    <rule ref="Security.BadFunctions.EasyRFI"/>
    <rule ref="Security.BadFunctions.EasyXSS"/>

    <!-- File exclusions -->
    <exclude-pattern>*/vendor/*</exclude-pattern>
    <exclude-pattern>*/storage/*</exclude-pattern>
    <exclude-pattern>*/cache/*</exclude-pattern>
    <exclude-pattern>*/Migrations/*</exclude-pattern>

    <!-- File inclusion -->
    <file>src</file>
    <file>tests</file>
</ruleset>
```

**Pre-Commit Hook Integration**

```json
// composer.json
{
    "scripts": {
        "cs-check": "php-cs-fixer fix --dry-run --diff",
        "cs-fix": "php-cs-fixer fix",
        "phpstan": "phpstan analyse --memory-limit=256M",
        "test": "phpunit",
        "check-all": [
            "@cs-check",
            "@phpstan",
            "@test"
        ]
    }
}
```

```yaml
# .pre-commit-config.yaml
repos:
  - repo: local
    hooks:
      - id: composer-check
        name: PHP Quality Checks
        entry: composer check-all
        language: system
        files: \.php$
        pass_filenames: false
```

#### 23.3 GitHub Actions and Automated Testing Pipelines

**Basic PHP CI Pipeline**

```yaml
# .github/workflows/ci.yml
name: CI Pipeline

on:
  push:
    branches: [main, develop]
  pull_request:
    branches: [main]

jobs:
  test:
    runs-on: ubuntu-latest
    
    strategy:
      matrix:
        php-version: ['8.1', '8.2', '8.3']
        dependency-version: [prefer-lowest, prefer-stable]
    
    steps:
      - uses: actions/checkout@v4
      
      - name: Setup PHP
        uses: shivammathur/setup-php@v2
        with:
          php-version: ${{ matrix.php-version }}
          extensions: mbstring, pdo, pdo_mysql, redis, intl, zip
          coverage: xdebug
          tools: composer:v2
      
      - name: Cache dependencies
        uses: actions/cache@v3
        with:
          path: vendor
          key: ${{ runner.os }}-php-${{ matrix.php-version }}-${{ matrix.dependency-version }}-${{ hashFiles('composer.lock') }}
          restore-keys: |
            ${{ runner.os }}-php-${{ matrix.php-version }}-${{ matrix.dependency-version }}-
      
      - name: Install dependencies
        run: composer update --${{ matrix.dependency-version }} --no-interaction --no-progress
      
      - name: Run tests
        run: vendor/bin/phpunit --coverage-clover=coverage.xml
      
      - name: Upload coverage
        uses: codecov/codecov-action@v3
        with:
          file: ./coverage.xml
          flags: php-${{ matrix.php-version }}

  static-analysis:
    runs-on: ubuntu-latest
    
    steps:
      - uses: actions/checkout@v4
      
      - name: Setup PHP
        uses: shivammathur/setup-php@v2
        with:
          php-version: '8.3'
          tools: composer:v2
      
      - name: Cache dependencies
        uses: actions/cache@v3
        with:
          path: vendor
          key: ${{ runner.os }}-static-analysis-${{ hashFiles('composer.lock') }}
      
      - name: Install dependencies
        run: composer install --no-interaction --no-progress
      
      - name: Run PHPStan
        run: vendor/bin/phpstan analyse --no-progress --error-format=github
      
      - name: Run Psalm
        run: vendor/bin/psalm --output-format=github
      
      - name: Check code style
        run: vendor/bin/php-cs-fixer fix --dry-run --diff

  security:
    runs-on: ubuntu-latest
    
    steps:
      - uses: actions/checkout@v4
      
      - name: Setup PHP
        uses: shivammathur/setup-php@v2
        with:
          php-version: '8.3'
          tools: composer:v2
      
      - name: Install dependencies
        run: composer install --no-interaction --no-progress
      
      - name: Audit dependencies
        run: composer audit
      
      - name: Run security checks
        run: vendor/bin/psalm --taint-analysis
```

**Matrix Testing with Services**

```yaml
# .github/workflows/integration-tests.yml
name: Integration Tests

on:
  push:
    branches: [main]
  pull_request:
    branches: [main]

jobs:
  integration:
    runs-on: ubuntu-latest
    
    strategy:
      matrix:
        php-version: ['8.2', '8.3']
        database: [mysql:8.0, postgres:15, mariadb:11]
    
    services:
      mysql:
        image: mysql:8.0
        env:
          MYSQL_ROOT_PASSWORD: password
          MYSQL_DATABASE: testing
        ports:
          - 3306:3306
        options: >-
          --health-cmd="mysqladmin ping"
          --health-interval=10s
          --health-timeout=5s
          --health-retries=3
      
      redis:
        image: redis:7-alpine
        ports:
          - 6379:6379
        options: >-
          --health-cmd="redis-cli ping"
          --health-interval=10s
          --health-timeout=5s
          --health-retries=3
    
    steps:
      - uses: actions/checkout@v4
      
      - name: Setup PHP
        uses: shivammathur/setup-php@v2
        with:
          php-version: ${{ matrix.php-version }}
          extensions: pdo, pdo_mysql, pdo_pgsql, redis
      
      - name: Install dependencies
        run: composer install --no-interaction --no-progress
      
      - name: Run migrations
        run: php artisan migrate
        env:
          DB_CONNECTION: testing
          DB_HOST: 127.0.0.1
          DB_DATABASE: testing
          DB_USERNAME: root
          DB_PASSWORD: password
      
      - name: Run integration tests
        run: vendor/bin/phpunit --testsuite=Integration
        env:
          DB_CONNECTION: testing
          DB_HOST: 127.0.0.1
          DB_DATABASE: testing
          DB_USERNAME: root
          DB_PASSWORD: password
          REDIS_HOST: 127.0.0.1
```

**Performance Regression Testing**

```yaml
# .github/workflows/performance.yml
name: Performance Tests

on:
  pull_request:
    branches: [main]

jobs:
  benchmark:
    runs-on: ubuntu-latest
    
    steps:
      - uses: actions/checkout@v4
      
      - name: Setup PHP
        uses: shivammathur/setup-php@v2
        with:
          php-version: '8.3'
          extensions: mbstring
      
      - name: Install dependencies
        run: composer install --no-interaction --no-progress
      
      - name: Run benchmarks
        run: |
          vendor/bin/phpbench run --report=aggregate --output=benchmarks.md
      
      - name: Compare with baseline
        run: |
          if [ -f benchmarks/baseline.json ]; then
            vendor/bin/phpbench compare --reference=benchmarks/baseline.json --report=compare
          fi
      
      - name: Store baseline
        if: github.event_name == 'push' && github.ref == 'refs/heads/main'
        run: cp benchmarks/report.json benchmarks/baseline.json
```

#### 23.4 Pre-commit Hooks and Linting

**Git Hook Manager Setup**

```bash
# Install GrumPHP for PHP-focused git hooks
composer require --dev phpro/grumphp

# Or use CaptainHook
composer require --dev captainhook/captainhook
```

**GrumPHP Configuration**

```yaml
# grumphp.yml
grumphp:
    hooks_dir: ~
    hooks_preset: local
    git_dir: .
    bin_dir: vendor/bin
    
    hooks:
        pre-commit:
            - { task: 'phpcs', triggered_by: ['php'] }
            - { task: 'phpcsfixer', triggered_by: ['php'] }
            - { task: 'phpstan', triggered_by: ['php'] }
            - { task: 'phpunit', triggered_by: ['php'] }
    
    tasks:
        phpcs:
            standard: 'phpcs.xml'
            tab_width: 4
            whitelist_patterns: []
            ignore_patterns: ['vendor/']
            triggered_by: ['php']
        
        phpcsfixer:
            allow_risky: true
            config: '.php-cs-fixer.dist.php'
            triggered_by: ['php']
        
        phpstan:
            configuration: 'phpstan.neon'
            level: 8
            memory_limit: '512M'
            use_grumphp_paths: true
            triggered_by: ['php']
        
        phpunit:
            always_execute: false
            config_file: 'phpunit.xml'
            testsuite: 'Unit'
            group: ['quick']
            triggered_by: ['php']
        
        securitychecker:
            lockfile: './composer.lock'
            run_always: false
```

**Custom Lint Script**

```json
// composer.json
{
    "scripts": {
        "lint": [
            "php-cs-fixer fix --dry-run",
            "phpstan analyse",
            "phpcs --standard=phpcs.xml src/"
        ],
        "lint:fix": [
            "php-cs-fixer fix",
            "phpcbf --standard=phpcs.xml src/"
        ],
        "pre-commit": [
            "@lint",
            "phpunit --testsuite=Unit --stop-on-failure"
        ]
    }
}
```

**Custom Git Hooks**

```bash
#!/bin/bash
# .git/hooks/pre-commit

echo "Running pre-commit checks..."

# Check PHP syntax
for file in $(git diff --cached --name-only --diff-filter=ACM | grep '\.php$'); do
    php -l "$file"
    if [ $? -ne 0 ]; then
        echo "Syntax error in $file"
        exit 1
    fi
done

# Run linter on staged files
STAGED_FILES=$(git diff --cached --name-only --diff-filter=ACM | grep '\.php$' | tr '\n' ' ')
if [ -n "$STAGED_FILES" ]; then
    vendor/bin/php-cs-fixer fix --dry-run $STAGED_FILES
    if [ $? -ne 0 ]; then
        echo "Code style issues found. Run 'composer cs-fix' to fix."
        exit 1
    fi
    
    vendor/bin/phpstan analyse $STAGED_FILES
    if [ $? -ne 0 ]; then
        echo "Static analysis failed."
        exit 1
    fi
fi

echo "Pre-commit checks passed."
exit 0
```

**Editor Integration**

```json
// .vscode/settings.json
{
    "php.suggest.basic": false,
    "php.validate.enable": true,
    "php.validate.run": "onSave",
    
    "phpstan.enabled": true,
    "phpstan.configFile": "phpstan.neon",
    "phpstan.level": "8",
    
    "php-cs-fixer.enable": true,
    "php-cs-fixer.onsave": true,
    "php-cs-fixer.config": ".php-cs-fixer.dist.php",
    
    "editor.formatOnSave": true,
    "editor.codeActionsOnSave": {
        "source.fixAll": "explicit"
    },
    
    "[php]": {
        "editor.defaultFormatter": "junstyle.php-cs-fixer",
        "editor.tabSize": 4,
        "editor.insertSpaces": true
    }
}
```

**Automated Code Review**

```php
// Custom PHPStan rule: ensure proper exception handling
class ExceptionHandlingRule implements \PHPStan\Rules\Rule
{
    public function getNodeType(): string
    {
        return \PhpParser\Node\Expr\MethodCall::class;
    }
    
    public function processNode(
        \PhpParser\Node $node,
        \PHPStan\Analyser\Scope $scope,
    ): array {
        $methodName = $node->name->name;
        
        // List of methods that throw exceptions
        $dangerousMethods = [
            'findOrFail',
            'firstOrFail',
            'sole',
        ];
        
        if (in_array($methodName, $dangerousMethods, true)) {
            // Check if inside try-catch
            if (!$this->isInsideTryCatch($node)) {
                return [
                    \PHPStan\Rules\RuleErrorBuilder::message(
                        "Method call {$methodName}() should be wrapped in try-catch"
                    )
                    ->identifier('exceptions.unhandled')
                    ->build(),
                ];
            }
        }
        
        return [];
    }
    
    private function isInsideTryCatch(\PhpParser\Node $node): bool
    {
        $parent = $node->getAttribute('parent');
        while ($parent !== null) {
            if ($parent instanceof \PhpParser\Node\Stmt\TryCatch) {
                return true;
            }
            $parent = $parent->getAttribute('parent');
        }
        return false;
    }
}
```

**Continuous Quality Monitoring**

```yaml
# .github/workflows/quality-report.yml
name: Quality Report

on:
  schedule:
    - cron: '0 0 * * 1' # Every Monday

jobs:
  quality:
    runs-on: ubuntu-latest
    
    steps:
      - uses: actions/checkout@v4
      
      - name: Setup PHP
        uses: shivammathur/setup-php@v2
        with:
          php-version: '8.3'
          coverage: xdebug
          tools: composer:v2
      
      - name: Install dependencies
        run: composer install --no-interaction --no-progress
      
      - name: Generate coverage
        run: vendor/bin/phpunit --coverage-clover=coverage.xml --coverage-text=coverage.txt
      
      - name: Run static analysis
        run: vendor/bin/phpstan analyse --error-format=json > phpstan.json
      
      - name: Count issues by type
        run: |
          echo "# Quality Report $(date +%Y-%m-%d)" > quality-report.md
          echo "" >> quality-report.md
          echo "## PHPStan" >> quality-report.md
          jq -r '.files[]?.messages[]? | "- \(.message)"' phpstan.json >> quality-report.md
          echo "" >> quality-report.md
          echo "## Code Coverage" >> quality-report.md
          cat coverage.txt >> quality-report.md
      
      - name: Upload report
        uses: actions/upload-artifact@v3
        with:
          name: quality-report
          path: quality-report.md
```

---

## Part VIII: The PHP Ecosystem

---

### Chapter 24: Composer and Dependency Management

#### 24.1 `composer.json` Schema and Version Constraints

Composer is the universal dependency manager for PHP, handling package installation, autoloading, and project configuration.

**The composer.json File Structure**

```json
{
    "name": "acme/my-application",
    "description": "A professional PHP application",
    "type": "project",
    "keywords": ["php", "application", "web"],
    "homepage": "https://example.com",
    "license": "MIT",
    "authors": [
        {
            "name": "Alice Johnson",
            "email": "alice@acme.com",
            "homepage": "https://alice.dev",
            "role": "Developer"
        }
    ],
    "support": {
        "email": "support@acme.com",
        "issues": "https://github.com/acme/app/issues",
        "wiki": "https://github.com/acme/app/wiki",
        "source": "https://github.com/acme/app"
    },
    "require": {
        "php": "^8.2",
        "ext-pdo": "*",
        "ext-mbstring": "*",
        "ext-json": "*",
        "laravel/framework": "^11.0",
        "symfony/http-foundation": "^7.0",
        "doctrine/dbal": "^4.0",
        "monolog/monolog": "^3.5",
        "guzzlehttp/guzzle": "^7.8",
        "league/flysystem": "^3.23"
    },
    "require-dev": {
        "phpunit/phpunit": "^11.0",
        "phpstan/phpstan": "^1.10",
        "friendsofphp/php-cs-fixer": "^3.46",
        "laravel/pint": "^1.13",
        "infection/infection": "^0.27",
        "mockery/mockery": "^1.6"
    },
    "suggest": {
        "ext-redis": "For Redis cache support",
        "ext-amqp": "For RabbitMQ queue support",
        "predis/predis": "Alternative Redis client"
    },
    "conflict": {
        "php": "<8.1",
        "laravel/framework": "<10.0"
    },
    "replace": {
        "acme/legacy-package": "self.version"
    },
    "provide": {
        "psr/log-implementation": "1.0"
    },
    "autoload": {
        "psr-4": {
            "App\\": "src/",
            "App\\Tests\\": "tests/"
        },
        "files": [
            "src/Helpers/functions.php",
            "src/Helpers/constants.php"
        ],
        "classmap": [
            "src/Legacy/",
            "lib/"
        ]
    },
    "autoload-dev": {
        "psr-4": {
            "Tests\\": "tests/"
        }
    },
    "config": {
        "optimize-autoloader": true,
        "preferred-install": "dist",
        "sort-packages": true,
        "platform": {
            "php": "8.2.0",
            "ext-pdo": "8.2.0"
        },
        "allow-plugins": {
            "phpstan/extension-installer": true,
            "infection/extension-installer": true
        },
        "process-timeout": 300,
        "use-parent-dir": false,
        "discard-changes": true,
        "github-protocols": ["https"],
        "vendor-dir": "vendor",
        "bin-dir": "bin"
    },
    "scripts": {
        "test": "phpunit",
        "test:unit": "phpunit --testsuite=Unit",
        "test:integration": "phpunit --testsuite=Integration",
        "analyse": "phpstan analyse --memory-limit=256M",
        "cs-check": "php-cs-fixer fix --dry-run --diff",
        "cs-fix": "php-cs-fixer fix",
        "check-all": [
            "@cs-check",
            "@analyse",
            "@test"
        ],
        "post-install-cmd": [
            "@php -r \"file_exists('.env') || copy('.env.example', '.env');\""
        ],
        "post-update-cmd": [
            "@php artisan optimize:clear"
        ],
        "pre-autoload-dump": [
            "Google\\Task\\Composer::cleanup"
        ],
        "post-autoload-dump": [
            "Illuminate\\Foundation\\ComposerScripts::postAutoloadDump",
            "@php artisan package:discover --ansi"
        ]
    },
    "scripts-descriptions": {
        "test": "Run all tests",
        "analyse": "Run static analysis with PHPStan",
        "cs-check": "Check code style",
        "cs-fix": "Fix code style automatically"
    },
    "extra": {
        "laravel": {
            "dont-discover": [
                "barryvdh/laravel-debugbar"
            ]
        },
        "branch-alias": {
            "dev-main": "1.x-dev"
        }
    },
    "minimum-stability": "stable",
    "prefer-stable": true
}
```

**Version Constraints**

Composer supports sophisticated version constraint expressions:

```json
{
    "require": {
        "vendor/package": "1.0.0",         // Exact version
        "vendor/package": ">=1.0",         // Greater than or equal
        "vendor/package": ">=1.0 <2.0",    // Range
        "vendor/package": ">=1.0 <1.1 || >=1.2", // Union
        "vendor/package": "1.0.*",         // Wildcard patch
        "vendor/package": "1.*",           // Wildcard minor
        "vendor/package": "~1.3",          // Next significant release (>=1.3 <2.0)
        "vendor/package": "~1.3.4",        // >=1.3.4 <1.4.0
        "vendor/package": "^1.3",          // Compatible (>=1.3 <2.0)
        "vendor/package": "^0.3",          // >=0.3 <0.4
        "vendor/package": "^1.3.4",        // >=1.3.4 <2.0.0
        "vendor/package": "dev-main",      // Branch
        "vendor/package": "dev-main#abc123", // Specific commit
        "vendor/package": "v1.2.3-beta1",   // Tagged release
    }
}
```

**Understanding Semantic Versioning**

```
MAJOR.MINOR.PATCH
^1.2.3  means >=1.2.3 <2.0.0  (backward-compatible changes allowed)
~1.2.3  means >=1.2.3 <1.3.0  (only patch-level changes allowed)
1.2.*   means >=1.2.0 <1.3.0  (wildcard)
```

**Platform Requirements**

```json
{
    "require": {
        "php": "^8.2",
        "ext-pdo": "*",
        "ext-mbstring": "*",
        "ext-gd": "^2.0",
        "ext-json": "*",
        "lib-pcre": ">=8.0",
        "lib-curl": "^7.0"
    },
    "config": {
        "platform": {
            "php": "8.2.14",
            "ext-pdo": "8.2.14",
            "ext-mbstring": "8.2.14"
        }
    }
}
```

**Private Repositories Configuration**

```json
{
    "repositories": [
        {
            "type": "composer",
            "url": "https://composer.example.com"
        },
        {
            "type": "vcs",
            "url": "https://github.com/acme/private-package"
        },
        {
            "type": "path",
            "url": "packages/acme-local/*",
            "options": {
                "symlink": true,
                "versions": {
                    "acme/local-package": "1.0.0"
                }
            }
        },
        {
            "type": "package",
            "package": {
                "name": "vendor/package",
                "version": "1.0.0",
                "type": "library",
                "dist": {
                    "url": "https://example.com/package.zip",
                    "type": "zip"
                },
                "autoload": {
                    "psr-4": {
                        "Vendor\\Package\\": "src/"
                    }
                }
            }
        }
    ]
}
```

#### 24.2 Autoloading, Scripts, and Plugins

**PSR-4 Deep Dive**

```php
// Directory structure matching PSR-4
src/
├── Models/
│   ├── User.php          // namespace App\Models;
│   └── Order.php         // namespace App\Models;
├── Services/
│   └── PaymentService.php // namespace App\Services;
└── Controllers/
    └── UserController.php // namespace App\Controllers;

// composer.json
{
    "autoload": {
        "psr-4": {
            "App\\": "src/",
            "App\\Database\\": "database/",
            "App\\Tests\\": "tests/"
        }
    }
}

// Generated autoloader maps:
// App\Models\User       → src/Models/User.php
// App\Models\Order      → src/Models/Order.php
// App\Services\PaymentService → src/Services/PaymentService.php
// App\Tests\Feature\UserTest  → tests/Feature/UserTest.php
```

**Classmap Autoloading**

```json
{
    "autoload": {
        "classmap": [
            "src/Legacy/",
            "lib/old-library/",
            "app/Helpers.php"
        ]
    }
}
```

Classmap autoloading scans directories and builds an explicit map of all classes. It's useful for legacy code that doesn't follow PSR-4:

```php
// Composer scans and generates:
// 'Legacy_User' => $baseDir . '/src/Legacy/User.php',
// 'OldLibrary_Autoloader' => $baseDir . '/lib/old-library/Autoloader.php',
```

**Files Autoloading**

```json
{
    "autoload": {
        "files": [
            "src/helpers.php",
            "src/constants.php"
        ]
    }
}
```

Files autoloading includes the specified files on every request. Use it for functions and constants that can't be autoloaded:

```php
// src/helpers.php
if (!function_exists('app_path')) {
    function app_path(string $path = ''): string
    {
        return __DIR__ . '/../app/' . ltrim($path, '/');
    }
}

// src/constants.php
define('APP_VERSION', '2.0.0');
define('API_BASE_URL', 'https://api.example.com/v1');
```

**Optimizing Autoloader for Production**

```bash
# Generate optimized autoloader
composer dump-autoload --optimize --no-dev

# With authoritative classmap (production)
composer dump-autoload --classmap-authoritative --no-dev

# With APCu cache
composer dump-autoload --apcu --no-dev

# Combined options
composer dump-autoload --optimize --classmap-authoritative --apcu --no-dev
```

**Composer Scripts**

Scripts automate development workflows:

```json
{
    "scripts": {
        "post-root-package-install": [
            "@php -r \"file_exists('.env') || copy('.env.example', '.env');\""
        ],
        "post-create-project-cmd": [
            "@php artisan key:generate --ansi"
        ],
        "post-autoload-dump": [
            "Illuminate\\Foundation\\ComposerScripts::postAutoloadDump",
            "@php artisan package:discover --ansi"
        ],
        "post-install-cmd": [
            "Illuminate\\Foundation\\ComposerScripts::postInstall",
            "@php artisan optimize"
        ],
        "post-update-cmd": [
            "@php artisan optimize:clear"
        ],
        
        "dev": [
            "Composer\\Config::disableProcessTimeout",
            "npx concurrently -k -c \"#93c5fd,#c4b5fd,#fdba74\" \"php artisan serve\" \"npm run dev\" \"php artisan queue:listen\""
        ],
        "setup": [
            "cp .env.example .env",
            "php artisan key:generate",
            "touch database/database.sqlite",
            "php artisan migrate --seed",
            "npm install",
            "npm run build"
        ],
        "fresh": [
            "php artisan migrate:fresh --seed",
            "php artisan optimize:clear"
        ]
    }
}
```

**Custom Composer Commands**

```json
{
    "scripts": {
        "deploy": [
            "git pull origin main",
            "composer install --no-dev --optimize-autoloader",
            "php artisan down",
            "php artisan migrate --force",
            "php artisan optimize",
            "php artisan up"
        ],
        "db:backup": [
            "php artisan db:backup --destination=s3"
        ]
    }
}
```

Run scripts with:

```bash
composer run-script deploy
composer deploy  # Short form
composer run db:backup
composer db:backup
```

**Event Hooks**

```json
{
    "scripts": {
        "pre-install-cmd": [
            "echo 'About to install dependencies...'"
        ],
        "post-install-cmd": [
            "@php artisan package:discover"
        ],
        "pre-update-cmd": [
            "echo 'About to update dependencies...'"
        ],
        "post-update-cmd": [
            "@php artisan optimize:clear"
        ],
        "pre-autoload-dump": [],
        "post-autoload-dump": [
            "Illuminate\\Foundation\\ComposerScripts::postAutoloadDump"
        ],
        "pre-status-cmd": [],
        "post-status-cmd": [],
        "pre-archive-cmd": [],
        "post-archive-cmd": []
    }
}
```

**Composer Plugins**

Plugins extend Composer's functionality. Common plugins:

```json
{
    "require": {
        "php-http/discovery": "^1.19",
        "phpstan/extension-installer": "^1.3",
        "infection/extension-installer": "^0.1",
        "cweagans/composer-patches": "^1.7",
        "wikimedia/composer-merge-plugin": "^2.1"
    },
    "config": {
        "allow-plugins": {
            "php-http/discovery": true,
            "phpstan/extension-installer": true,
            "infection/extension-installer": true,
            "cweagans/composer-patches": true,
            "wikimedia/composer-merge-plugin": true
        }
    },
    "extra": {
        "patches": {
            "vendor/package": {
                "Fix security issue": "patches/security-fix.patch",
                "Add custom feature": "patches/custom-feature.patch"
            }
        },
        "merge-plugin": {
            "include": [
                "local-packages/*/composer.json"
            ],
            "recurse": true,
            "replace": false,
            "merge-dev": true,
            "merge-extra": false
        }
    }
}
```

**Creating a Custom Composer Plugin**

```php
// src/MyComposerPlugin.php
namespace Acme\Composer;

use Composer\Composer;
use Composer\IO\IOInterface;
use Composer\Plugin\PluginInterface;
use Composer\EventDispatcher\EventSubscriberInterface;
use Composer\Script\ScriptEvents;

class MyPlugin implements PluginInterface, EventSubscriberInterface
{
    public function activate(Composer $composer, IOInterface $io): void
    {
        // Register plugin
        $io->write('My plugin activated!');
    }
    
    public function deactivate(Composer $composer, IOInterface $io): void
    {
        // Cleanup
    }
    
    public function uninstall(Composer $composer, IOInterface $io): void
    {
        // Remove plugin data
    }
    
    public static function getSubscribedEvents(): array
    {
        return [
            ScriptEvents::POST_INSTALL_CMD => 'onPostInstall',
            ScriptEvents::POST_UPDATE_CMD => 'onPostUpdate',
        ];
    }
    
    public function onPostInstall(): void
    {
        echo "Running custom post-install tasks...\n";
    }
    
    public function onPostUpdate(): void
    {
        echo "Running custom post-update tasks...\n";
    }
}
```

#### 24.3 Semantic Versioning and Private Repositories

**Understanding Caret vs Tilde Constraints**

```json
{
    "require": {
        "symfony/console": "^6.4",
        // ^6.4 means >=6.4.0 <7.0.0
        // Allows: 6.4.0, 6.4.5, 6.5.0, 6.9.9
        // Blocks: 6.3.9, 7.0.0
        
        "monolog/monolog": "~3.5",
        // ~3.5 means >=3.5.0 <4.0.0
        // Allows: 3.5.0, 3.5.1, 3.9.9
        // Blocks: 3.4.9, 4.0.0
        
        "psr/log": "^1.1|^2.0|^3.0",
        // Multiple ranges are OR'd together
        // Allows: 1.1.0 to 1.x, 2.0.0 to 2.x, 3.0.0 to 3.x
        
        "doctrine/orm": ">=2.14 <2.17",
        // Explicit range
        // Allows: 2.14.0 to 2.16.x
    }
}
```

**Stability Flags**

```json
{
    "require": {
        "vendor/stable-package": "^1.0",
        "vendor/beta-package": "^1.0@beta",
        "vendor/alpha-package": "dev-main",
        "vendor/specific-commit": "dev-main#a1b2c3d"
    },
    "minimum-stability": "stable",
    "prefer-stable": true
}
```

Stability levels: `dev`, `alpha`, `beta`, `RC`, `stable`

**Private Repository Setup**

```json
{
    "repositories": [
        {
            "type": "composer",
            "url": "https://packages.acme.com",
            "options": {
                "http": {
                    "header": [
                        "API-Token: YOUR_TOKEN"
                    ]
                }
            }
        }
    ],
    "config": {
        "http-basic": {
            "packages.acme.com": {
                "username": "your-username",
                "password": "your-token"
            }
        },
        "bearer": {
            "github.com": "ghp_YOUR_GITHUB_TOKEN"
        }
    }
}
```

**Satis: Private Package Repository**

```json
// satis.json
{
    "name": "acme/private-repository",
    "homepage": "https://packages.acme.com",
    "repositories": [
        { "type": "vcs", "url": "https://github.com/acme/private-package-1" },
        { "type": "vcs", "url": "https://github.com/acme/private-package-2" }
    ],
    "require": {
        "acme/private-package-1": "*",
        "acme/private-package-2": "*"
    },
    "require-dependencies": true,
    "require-dev-dependencies": true,
    "archive": {
        "directory": "dist",
        "format": "zip",
        "prefix-url": "https://packages.acme.com",
        "skip-dev": true
    },
    "config": {
        "http-basic": {
            "github.com": {
                "username": "token",
                "password": "ghp_YOUR_TOKEN"
            }
        }
    }
}
```

```bash
# Build Satis repository
php bin/satis build satis.json public/

# Serve with any web server
php -S localhost:8080 -t public/
```

#### 24.4 Security Auditing with `composer audit`

**Running Security Audits**

```bash
# Check for known vulnerabilities
composer audit

# Check with specific format
composer audit --format=json > security-report.json

# Exit with non-zero code if vulnerabilities found (for CI)
composer audit --locked

# Check only production dependencies
composer audit --no-dev
```

**Automated Security Checks**

```yaml
# .github/workflows/security.yml
name: Security Audit

on:
  schedule:
    - cron: '0 8 * * 1'  # Every Monday at 8 AM
  push:
    branches: [main]

jobs:
  security:
    runs-on: ubuntu-latest
    
    steps:
      - uses: actions/checkout@v4
      
      - name: Setup PHP
        uses: shivammathur/setup-php@v2
        with:
          php-version: '8.3'
          tools: composer:v2
      
      - name: Validate composer files
        run: composer validate --strict
      
      - name: Audit dependencies
        run: |
          composer audit --format=json > audit-report.json
          if [ $? -ne 0 ]; then
            cat audit-report.json
            exit 1
          fi
      
      - name: Check abandoned packages
        run: |
          composer outdated --direct --format=json > outdated.json
          echo "## Outdated Packages" >> $GITHUB_STEP_SUMMARY
          cat outdated.json >> $GITHUB_STEP_SUMMARY
```

**Vulnerability Response Process**

```php
// Example: Responding to vulnerability report
class SecurityAdvisoryHandler
{
    public function checkAffectedComponent(string $package, string $version): bool
    {
        // Check if our application uses the vulnerable version
        $installed = json_decode(
            file_get_contents('composer.lock'),
            true
        );
        
        foreach ($installed['packages'] as $installedPackage) {
            if ($installedPackage['name'] === $package) {
                $installedVersion = $installedPackage['version'];
                
                if (version_compare($installedVersion, $version, '>=')) {
                    return true;
                }
            }
        }
        
        return false;
    }
    
    public function applyPatch(string $package, string $patchFile): void
    {
        // Apply security patch using cweagans/composer-patches
        $composerJson = json_decode(
            file_get_contents('composer.json'),
            true
        );
        
        // Add patch configuration
        $composerJson['extra']['patches'][$package] = [
            'Security patch' => $patchFile,
        ];
        
        file_put_contents(
            'composer.json',
            json_encode($composerJson, JSON_PRETTY_PRINT | JSON_UNESCAPED_SLASHES)
        );
        
        // Apply patches
        exec('composer install --no-interaction');
    }
}
```

**Lock File Verification**

```bash
# Verify lock file is up to date (CI check)
composer validate --strict

# Check for modifications
composer install --dry-run

# Verify package signatures
composer verify

# Show changed packages
composer outdated --direct
```

---

### Chapter 25: Frameworks

#### 25.1 Laravel: Eloquent, Routing, and Blade

Laravel is the most popular PHP framework, providing an elegant syntax and comprehensive features for modern web development.

**Laravel Routing System**

```php
// routes/web.php
use App\Http\Controllers\ArticleController;
use App\Http\Controllers\UserController;
use Illuminate\Support\Facades\Route;

// Basic routes
Route::get('/', fn () => view('welcome'));
Route::get('/articles', [ArticleController::class, 'index']);
Route::get('/articles/{article}', [ArticleController::class, 'show']);

// Route groups with middleware
Route::middleware(['auth'])->group(function (): void {
    Route::get('/dashboard', [DashboardController::class, 'index']);
    Route::resource('articles', ArticleController::class);
    Route::resource('users', UserController::class)->except(['show']);
});

// API routes (routes/api.php)
Route::prefix('v1')->middleware('auth:sanctum')->group(function (): void {
    Route::apiResource('posts', PostController::class);
    Route::get('search', [SearchController::class, 'search']);
    Route::post('upload', [FileController::class, 'upload']);
});

// Route with rate limiting
Route::middleware(['throttle:uploads'])->group(function (): void {
    Route::post('/photos', [PhotoController::class, 'store'])
        ->middleware(['auth', 'verified']);
});

// Named routes with parameters
Route::get('/user/{user}/posts/{post}', [PostController::class, 'show'])
    ->name('users.posts.show')
    ->whereNumber(['user', 'post']);

// Route model binding
Route::get('/articles/{article:slug}', [ArticleController::class, 'showBySlug']);

// Fallback route
Route::fallback(fn () => response()->view('errors.404', [], 404));
```

**Eloquent ORM**

Eloquent provides an active record implementation for database interaction:

```php
// Model definition with relationships
class Article extends Model
{
    use HasFactory, SoftDeletes, Sluggable;
    
    protected $fillable = [
        'title', 'content', 'status', 'author_id',
    ];
    
    protected $casts = [
        'published_at' => 'datetime',
        'metadata' => 'array',
        'status' => ArticleStatus::class,
    ];
    
    protected $hidden = [
        'internal_notes',
    ];
    
    protected $appends = [
        'reading_time',
    ];
    
    // Relationships
    public function author(): BelongsTo
    {
        return $this->belongsTo(User::class, 'author_id');
    }
    
    public function comments(): HasMany
    {
        return $this->hasMany(Comment::class);
    }
    
    public function tags(): MorphToMany
    {
        return $this->morphToMany(Tag::class, 'taggable');
    }
    
    // Scopes
    public function scopePublished(Builder $query): Builder
    {
        return $query->where('status', ArticleStatus::Published)
                     ->whereNotNull('published_at')
                     ->where('published_at', '<=', now());
    }
    
    public function scopeByAuthor(Builder $query, int $authorId): Builder
    {
        return $query->where('author_id', $authorId);
    }
    
    // Accessors
    public function getReadingTimeAttribute(): int
    {
        $wordsPerMinute = 200;
        $wordCount = str_word_count(strip_tags($this->content));
        return (int) ceil($wordCount / $wordsPerMinute);
    }
    
    // Custom methods
    public function publish(): void
    {
        $this->update([
            'status' => ArticleStatus::Published,
            'published_at' => now(),
        ]);
        
        event(new ArticlePublished($this));
    }
    
    public function archive(): void
    {
        $this->update(['status' => ArticleStatus::Archived]);
    }
}

// Query examples
// Lazy loading
$articles = Article::published()
    ->with('author', 'tags')
    ->latest('published_at')
    ->paginate(10);

// Eager loading with constraints
$articles = Article::with(['comments' => function ($query): void {
    $query->approved()->latest()->limit(5);
}])->get();

// Subquery selects
$articles = Article::select(['*'])
    ->selectSub(
        Comment::selectRaw('count(*)')
            ->whereColumn('article_id', 'articles.id')
            ->approved(),
        'comment_count'
    )
    ->get();

// Chunking for large datasets
Article::published()->chunk(200, function ($articles): void {
    foreach ($articles as $article) {
        $article->updateSearchIndex();
    }
});

// Transaction with eloquent
DB::transaction(function () use ($article, $data): void {
    $article->update(['title' => $data['title']]);
    $article->tags()->sync($data['tags']);
    
    if ($data['publish'] ?? false) {
        $article->publish();
    }
});
```

**Blade Templating**

Blade provides elegant template syntax with zero performance overhead:

```blade
{{-- resources/views/layouts/app.blade.php --}}
<!DOCTYPE html>
<html lang="{{ str_replace('_', '-', app()->getLocale()) }}">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="csrf-token" content="{{ csrf_token() }}">
    <title>@yield('title', config('app.name'))</title>
    
    @vite(['resources/css/app.css', 'resources/js/app.js'])
    @stack('styles')
</head>
<body class="antialiased">
    <div id="app">
        @include('partials.navigation')
        
        <main class="py-4">
            @yield('content')
        </main>
        
        @include('partials.footer')
    </div>
    
    @stack('scripts')
    @livewireScripts
</body>
</html>

{{-- resources/views/articles/index.blade.php --}}
@extends('layouts.app')

@section('title', 'Articles')
@section('content')
    <div class="container mx-auto px-4">
        <div class="flex justify-between items-center mb-6">
            <h1 class="text-3xl font-bold">Articles</h1>
            @can('create', App\Models\Article::class)
                <a href="{{ route('articles.create') }}" 
                   class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
                    New Article
                </a>
            @endcan
        </div>
        
        @if(session('success'))
            <div class="bg-green-100 border border-green-400 text-green-700 px-4 py-3 rounded mb-4">
                {{ session('success') }}
            </div>
        @endif
        
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
            @forelse($articles as $article)
                <x-article-card :article="$article" />
            @empty
                <div class="col-span-full text-center py-12">
                    <p class="text-gray-500 text-lg">No articles found.</p>
                    <a href="{{ route('articles.create') }}" class="text-blue-500 hover:underline">
                        Write your first article
                    </a>
                </div>
            @endforelse
        </div>
        
        <div class="mt-8">
            {{ $articles->links() }}
        </div>
    </div>
@endsection

{{-- resources/views/components/article-card.blade.php --}}
@props(['article'])

<div class="bg-white rounded-lg shadow-md overflow-hidden">
    @if($article->featured_image)
        <img src="{{ Storage::url($article->featured_image) }}" 
             alt="{{ $article->title }}" 
             class="w-full h-48 object-cover">
    @endif
    
    <div class="p-6">
        <div class="flex items-center mb-2">
            @foreach($article->tags as $tag)
                <span class="bg-gray-200 text-gray-700 px-2 py-1 rounded-full text-xs mr-1">
                    {{ $tag->name }}
                </span>
            @endforeach
        </div>
        
        <h2 class="text-xl font-semibold mb-2">
            <a href="{{ route('articles.show', $article) }}" class="hover:text-blue-500">
                {{ $article->title }}
            </a>
        </h2>
        
        <p class="text-gray-600 mb-4">
            {{ Str::limit($article->excerpt ?? $article->content, 150) }}
        </p>
        
        <div class="flex items-center justify-between text-sm text-gray-500">
            <div class="flex items-center">
                <img src="{{ $article->author->avatar_url }}" 
                     alt="{{ $article->author->name }}" 
                     class="w-6 h-6 rounded-full mr-2">
                <span>{{ $article->author->name }}</span>
            </div>
            
            <div class="flex items-center space-x-4">
                <span>{{ $article->created_at->diffForHumans() }}</span>
                <span>{{ $article->reading_time }} min read</span>
            </div>
        </div>
    </div>
</div>

{{-- Blade Directives --}}
@auth
    {{-- User is authenticated --}}
@elseguest
    {{-- User is not authenticated --}}
@endguest

@hasSection('sidebar')
    <div class="sidebar">
        @yield('sidebar')
    </div>
@endif

@production
    {{-- Production-only code --}}
@endproduction

@env('local')
    {{-- Local environment only --}}
@endenv

@php($count = 1)
@while($count < 10)
    <p>Iteration {{ $count }}</p>
    @php($count++)
@endwhile

{{-- Service Injection --}}
@inject('metrics', 'App\Services\MetricsService')
<div>
    Monthly Revenue: {{ $metrics->monthlyRevenue() }}
</div>
```

#### 25.2 Symfony Components and Flex

Symfony provides reusable PHP components and a full-stack framework used by Laravel and many other projects.

**Symfony Components in Isolation**

```php
// Using Symfony components independently
// composer require symfony/http-foundation symfony/routing symfony/http-kernel

use Symfony\Component\HttpFoundation\Request;
use Symfony\Component\HttpFoundation\Response;
use Symfony\Component\Routing\Route;
use Symfony\Component\Routing\RouteCollection;
use Symfony\Component\Routing\Matcher\UrlMatcher;
use Symfony\Component\Routing\RequestContext;
use Symfony\Component\Routing\Generator\UrlGenerator;

// Define routes
$routes = new RouteCollection();

$routes->add('home', new Route('/', [
    '_controller' => [HomeController::class, 'index'],
], [], [], '', [], ['GET']));

$routes->add('article_show', new Route('/articles/{slug}', [
    '_controller' => [ArticleController::class, 'show'],
], [
    'slug' => '[a-z0-9-]+',
], [], '', [], ['GET']));

// Match incoming request
$request = Request::createFromGlobals();
$context = new RequestContext();
$context->fromRequest($request);

$matcher = new UrlMatcher($routes, $context);

try {
    $parameters = $matcher->match($request->getPathInfo());
    
    [$controllerClass, $method] = $parameters['_controller'];
    $controller = new $controllerClass();
    $response = $controller->$method($request, ...$parameters);
    
} catch (\Symfony\Component\Routing\Exception\ResourceNotFoundException $e) {
    $response = new Response('Not Found', 404);
} catch (\Symfony\Component\Routing\Exception\MethodNotAllowedException $e) {
    $response = new Response('Method Not Allowed', 405);
}

$response->send();

// Generate URLs
$generator = new UrlGenerator($routes, $context);
$url = $generator->generate('article_show', ['slug' => 'hello-world']);
// /articles/hello-world
```

**Dependency Injection Container**

```php
// services.yaml
parameters:
    app.supported_locales: ['en', 'fr', 'de', 'es']
    app.pagination.per_page: 20
    app.upload.max_size: 10485760

services:
    _defaults:
        autowire: true
        autoconfigure: true
        public: false
        bind:
            $projectDir: '%kernel.project_dir%'
            string $cdnUrl: '%env(CDN_URL)%'
    
    App\:
        resource: '../src/'
        exclude:
            - '../src/DependencyInjection/'
            - '../src/Entity/'
            - '../src/Kernel.php'
    
    App\Service\Payment\PaymentGatewayInterface:
        alias: 'App\Service\Payment\StripePaymentGateway'
    
    App\Service\Payment\PayPalPaymentGateway: ~
    App\Service\Payment\StripePaymentGateway:
        arguments:
            $apiKey: '%env(STRIPE_API_KEY)%'
            $webhookSecret: '%env(STRIPE_WEBHOOK_SECRET)%'
    
    App\EventListener\ExceptionListener:
        tags:
            - { name: kernel.event_listener, event: kernel.exception }
    
    App\Service\NewsletterService:
        decorates: 'App\Service\NewsletterServiceInterface'
        arguments:
            $decorated: '@.inner'
            $cache: '@cache.app'

// Using the container
class OrderController
{
    public function __construct(
        private PaymentGatewayInterface $paymentGateway,
        private EntityManagerInterface $entityManager,
        private EventDispatcherInterface $eventDispatcher,
        private LoggerInterface $logger,
    ) {}
    
    public function create(Request $request): Response
    {
        $order = new Order();
        // ... process order ...
        
        try {
            $paymentResult = $this->paymentGateway->charge(
                $order->getTotal(),
                $order->getPaymentMethod()
            );
            
            $this->entityManager->persist($order);
            $this->entityManager->flush();
            
            $this->eventDispatcher->dispatch(
                new OrderPlacedEvent($order)
            );
        } catch (PaymentException $e) {
            $this->logger->error('Payment failed', [
                'order_id' => $order->getId(),
                'error' => $e->getMessage(),
            ]);
            
            throw $e;
        }
        
        return $this->redirectToRoute('order_confirmation', [
            'id' => $order->getId(),
        ]);
    }
}
```

**Symfony Flex**

Flex is a Composer plugin that streamlines Symfony application management:

```bash
# Install Symfony with Flex
composer create-project symfony/skeleton my-project
cd my-project

# Add functionality through recipes
composer require logger          # Monolog integration
composer require orm             # Doctrine ORM
composer require template        # Twig templating
composer require mailer          # Email support
composer require messenger       # Message queue
composer require notifier        # Notifications
composer require translation     # i18n support
composer require serializer      # Serialization
composer require validator       # Validation
composer require security        # Authentication
composer require api             # API Platform
composer require admin           # EasyAdmin

# Development tools
composer require profiler --dev           # Debug toolbar
composer require debug --dev              # Debug component
composer require maker --dev              # Code generation
composer require phpunit-bridge --dev     # Testing utilities
```

**Creating a Symfony Bundle**

```php
// src/AcmeBlogBundle.php
namespace Acme\Blog;

use Symfony\Component\HttpKernel\Bundle\AbstractBundle;
use Symfony\Component\DependencyInjection\ContainerBuilder;
use Symfony\Component\DependencyInjection\Loader\Configurator\ContainerConfigurator;

class AcmeBlogBundle extends AbstractBundle
{
    public function loadExtension(
        array $config,
        ContainerConfigurator $container,
        ContainerBuilder $builder,
    ): void {
        $container->import('../config/services.yaml');
        
        // Process configuration
        $container->parameters()
            ->set('acme_blog.posts_per_page', $config['posts_per_page']);
    }
    
    public function prependExtension(
        ContainerConfigurator $container,
        ContainerBuilder $builder,
    ): void {
        // Prepend configuration to other bundles
        $builder->prependExtensionConfig('twig', [
            'paths' => [
                '%kernel.project_dir%/vendor/acme/blog/templates' => 'AcmeBlog',
            ],
        ]);
    }
}

// acme-blog.yaml (application config)
acme_blog:
    posts_per_page: 10
    enable_comments: true
    default_status: draft
```

#### 25.3 Slim and Micro-Framework Architecture

Slim is a lightweight micro-framework ideal for APIs and small applications.

**Basic Slim Application**

```php
<?php
// public/index.php
use Psr\Http\Message\ResponseInterface as Response;
use Psr\Http\Message\ServerRequestInterface as Request;
use Slim\Factory\AppFactory;

require __DIR__ . '/../vendor/autoload.php';

// Create app with container
$container = new \DI\Container();

AppFactory::setContainer($container);
$app = AppFactory::create();

// Add middleware
$app->addBodyParsingMiddleware();
$app->addRoutingMiddleware();
$app->addErrorMiddleware(true, true, true);

// Define routes
$app->get('/', function (Request $request, Response $response): Response {
    $response->getBody()->write(json_encode([
        'name' => 'My API',
        'version' => '1.0.0',
    ]));
    return $response->withHeader('Content-Type', 'application/json');
});

// Route group
$app->group('/api/v1', function (\Slim\Routing\RouteCollectorProxy $group): void {
    // List articles
    $group->get('/articles', [ArticleController::class, 'index']);
    
    // Get article
    $group->get('/articles/{id:[0-9]+}', [ArticleController::class, 'show']);
    
    // Create article (requires auth)
    $group->post('/articles', [ArticleController::class, 'store'])
        ->add(new AuthMiddleware());
    
    // Update article
    $group->put('/articles/{id:[0-9]+}', [ArticleController::class, 'update'])
        ->add(new AuthMiddleware());
    
    // Delete article
    $group->delete('/articles/{id:[0-9]+}', [ArticleController::class, 'destroy'])
        ->add(new AuthMiddleware());
});

// Run application
$app->run();
```

**Slim Controller Example**

```php
class ArticleController
{
    private ArticleRepository $repository;
    private Validator $validator;
    
    public function __construct(
        ArticleRepository $repository,
        Validator $validator,
    ) {
        $this->repository = $repository;
        $this->validator = $validator;
    }
    
    public function index(Request $request, Response $response): Response
    {
        $params = $request->getQueryParams();
        $page = (int) ($params['page'] ?? 1);
        $perPage = min(100, max(1, (int) ($params['per_page'] ?? 20)));
        
        $articles = $this->repository->paginate($page, $perPage);
        
        $payload = json_encode([
            'data' => $articles->items(),
            'meta' => [
                'current_page' => $articles->currentPage(),
                'last_page' => $articles->lastPage(),
                'per_page' => $articles->perPage(),
                'total' => $articles->total(),
            ],
        ]);
        
        $response->getBody()->write($payload);
        return $response->withHeader('Content-Type', 'application/json');
    }
    
    public function show(Request $request, Response $response, array $args): Response
    {
        $article = $this->repository->findById((int) $args['id']);
        
        if (!$article) {
            $response->getBody()->write(json_encode([
                'error' => 'Article not found',
            ]));
            return $response
                ->withStatus(404)
                ->withHeader('Content-Type', 'application/json');
        }
        
        $payload = json_encode(['data' => $article->toArray()]);
        
        $response->getBody()->write($payload);
        return $response->withHeader('Content-Type', 'application/json');
    }
    
    public function store(Request $request, Response $response): Response
    {
        $data = $request->getParsedBody();
        
        $errors = $this->validator->validate($data, [
            'title' => 'required|min:5|max:255',
            'content' => 'required|min:50',
            'status' => 'in:draft,published',
        ]);
        
        if (!empty($errors)) {
            $response->getBody()->write(json_encode(['errors' => $errors]));
            return $response
                ->withStatus(422)
                ->withHeader('Content-Type', 'application/json');
        }
        
        $article = $this->repository->create($data);
        
        $payload = json_encode(['data' => $article->toArray()]);
        
        $response->getBody()->write($payload);
        return $response
            ->withStatus(201)
            ->withHeader('Content-Type', 'application/json')
            ->withHeader('Location', '/api/v1/articles/' . $article->id);
    }
}
```

**Slim Middleware**

```php
class AuthMiddleware
{
    private JwtAuth $jwt;
    
    public function __construct(JwtAuth $jwt)
    {
        $this->jwt = $jwt;
    }
    
    public function __invoke(
        Request $request,
        RequestHandler $handler,
    ): Response {
        $authHeader = $request->getHeaderLine('Authorization');
        
        if (!$authHeader || !str_starts_with($authHeader, 'Bearer ')) {
            $response = new \Slim\Psr7\Response();
            $response->getBody()->write(json_encode([
                'error' => 'Missing or invalid Authorization header',
            ]));
            return $response
                ->withStatus(401)
                ->withHeader('Content-Type', 'application/json');
        }
        
        $token = substr($authHeader, 7);
        $payload = $this->jwt->validate($token);
        
        if (!$payload) {
            $response = new \Slim\Psr7\Response();
            $response->getBody()->write(json_encode([
                'error' => 'Invalid or expired token',
            ]));
            return $response
                ->withStatus(401)
                ->withHeader('Content-Type', 'application/json');
        }
        
        // Add user info to request
        $request = $request->withAttribute('user_id', $payload['sub']);
        $request = $request->withAttribute('user_role', $payload['role']);
        
        return $handler->handle($request);
    }
}

class RateLimitMiddleware
{
    private RateLimiter $limiter;
    private int $maxRequests;
    private int $windowSeconds;
    
    public function __construct(
        RateLimiter $limiter,
        int $maxRequests = 60,
        int $windowSeconds = 60,
    ) {
        $this->limiter = $limiter;
        $this->maxRequests = $maxRequests;
        $this->windowSeconds = $windowSeconds;
    }
    
    public function __invoke(
        Request $request,
        RequestHandler $handler,
    ): Response {
        $key = $this->getKey($request);
        
        if (!$this->limiter->attempt($key, $this->maxRequests, $this->windowSeconds)) {
            $response = new \Slim\Psr7\Response();
            $response->getBody()->write(json_encode([
                'error' => 'Rate limit exceeded',
                'retry_after' => $this->limiter->retryAfter($key),
            ]));
            return $response
                ->withStatus(429)
                ->withHeader('Content-Type', 'application/json');
        }
        
        $response = $handler->handle($request);
        
        return $response
            ->withHeader('X-RateLimit-Limit', (string) $this->maxRequests)
            ->withHeader('X-RateLimit-Remaining', (string) $this->limiter->remaining($key));
    }
    
    private function getKey(Request $request): string
    {
        // Use authenticated user ID or IP
        $userId = $request->getAttribute('user_id');
        if ($userId) {
            return "user:{$userId}";
        }
        
        $ip = $request->getServerParams()['REMOTE_ADDR'] ?? 'unknown';
        return "ip:{$ip}";
    }
}
```

#### 25.4 Choosing the Right Framework for Your Project

**Decision Matrix**

```php
// Framework comparison helper
class FrameworkSelector
{
    public function analyze(array $requirements): array
    {
        $frameworks = [
            'laravel' => $this->analyzeLaravel($requirements),
            'symfony' => $this->analyzeSymfony($requirements),
            'slim' => $this->analyzeSlim($requirements),
        ];
        
        return $this->rank($frameworks);
    }
    
    private function analyzeLaravel(array $requirements): array
    {
        $score = 0;
        
        // Strengths
        if ($requirements['type'] === 'monolith' 
            || $requirements['type'] === 'full-stack') {
            $score += 30;
        }
        
        if ($requirements['need_admin_panel'] ?? false) {
            $score += 15;
        }
        
        if (($requirements['team_size'] ?? 1) >= 3) {
            $score += 10; // Great ecosystem and community
        }
        
        // Weaknesses
        if (($requirements['customization'] ?? 0) > 8) {
            $score -= 10; // Opinionated, harder to customize deeply
        }
        
        return [
            'score' => $score,
            'pros' => [
                'Rich ecosystem with packages',
                'Excellent documentation',
                'Built-in authentication, queues, notifications',
                'Blade templating with component system',
                'Eloquent ORM for rapid development',
            ],
            'cons' => [
                'Opinionated architecture',
                'Heavier than micro-frameworks',
                'Magic methods can hide complexity',
                'Higher memory footprint',
            ],
        ];
    }
    
    private function analyzeSymfony(array $requirements): array
    {
        $score = 0;
        
        // Strengths
        if ($requirements['type'] === 'enterprise') {
            $score += 30;
        }
        
        if (($requirements['longevity'] ?? 5) > 5) {
            $score += 15; // LTS releases, backward compatibility
        }
        
        if (($requirements['customization'] ?? 0) > 7) {
            $score += 20; // Highly modular
        }
        
        // Weaknesses
        if (($requirements['rapid_prototyping'] ?? false)) {
            $score -= 10; // Steeper learning curve
        }
        
        return [
            'score' => $score,
            'pros' => [
                'Highly modular component system',
                'Strong backward compatibility',
                'LTS releases with security support',
                'Professional-grade dependency injection',
                'Used by Laravel and Drupal internally',
            ],
            'cons' => [
                'Steeper learning curve',
                'More configuration than Laravel',
                'Smaller ecosystem for ready-made features',
                'Less "magic" - more explicit coding needed',
            ],
        ];
    }
    
    private function analyzeSlim(array $requirements): array
    {
        $score = 0;
        
        // Strengths
        if ($requirements['type'] === 'api' 
            || $requirements['type'] === 'microservice') {
            $score += 30;
        }
        
        if (($requirements['performance'] ?? 5) > 8) {
            $score += 15; // Lightweight, fast
        }
        
        if (($requirements['customization'] ?? 0) > 9) {
            $score += 15; // Build your own stack
        }
        
        // Weaknesses
        if ($requirements['type'] === 'monolith') {
            $score -= 20;
        }
        
        return [
            'score' => $score,
            'pros' => [
                'Minimal overhead',
                'Fast performance',
                'Complete control over architecture',
                'Great for APIs and microservices',
                'Easy to learn',
            ],
            'cons' => [
                'Build everything yourself',
                'Limited built-in features',
                'Smaller community and packages',
                'No ORM, templating, or admin panel included',
            ],
        ];
    }
    
    private function rank(array $frameworks): array
    {
        uasort($frameworks, fn ($a, $b) => $b['score'] <=> $a['score']);
        return $frameworks;
    }
}

// Usage
$selector = new FrameworkSelector();
$results = $selector->analyze([
    'type' => 'api',
    'team_size' => 2,
    'performance' => 8,
    'customization' => 7,
    'rapid_prototyping' => true,
    'longevity' => 3,
]);
```

**Framework Selection Guidelines**

```php
// When to choose Laravel:
$chooseLaravel = [
    'Building a full-stack web application',
    'Team prefers rapid development over deep customization',
    'Need built-in features: auth, queues, notifications',
    'Want the largest PHP ecosystem of packages',
    'Building SaaS applications with common patterns',
];

// When to choose Symfony:
$chooseSymfony = [
    'Building enterprise applications with long lifecycles',
    'Need maximum flexibility and modularity',
    'Team has strong OOP and design pattern experience',
    'Building complex business logic',
    'Want LTS releases and strong backward compatibility',
];

// When to choose Slim:
$chooseSlim = [
    'Building lightweight APIs',
    'Microservices architecture',
    'Need maximum performance with minimal overhead',
    'Want complete control and minimal magic',
    'Building small applications or prototypes',
];
```

---
