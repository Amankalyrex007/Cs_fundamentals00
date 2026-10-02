[README.MD](https://github.com/user-attachments/files/32967818/README.MD)
# CS Fundamentals — Interview Preparation

A focused collection of **Computer Science fundamentals** for technical placement and interview preparation.

This repository is organized into four core subjects:

- **OOP — Object-Oriented Programming**
- **DBMS — Database Management Systems**
- **OS — Operating Systems**
- **CN — Computer Networks**

Each official interview question has its **own `.md` solution file**, making the repository easy to study, revise, and navigate.

---

## 📚 Subjects

| Subject | Questions | Main Areas |
|---|---:|---|
| OOP | 28 | OOP concepts, design principles, relationships, practical design |
| DBMS | 32 | Databases, normalization, transactions, indexing, scaling |
| OS | 32 | Processes, threads, scheduling, synchronization, memory |
| CN | 32 | Networking models, TCP/UDP, HTTP, IP/DNS, practical networking |
| **Total** | **124** | **CS Fundamentals** |

The question counts above follow the topic counts specified in the source question list.

---

# 1. OOP — Object-Oriented Programming

**28 questions**

## Core OOP Concepts

- Object-Oriented Programming
- Four pillars of OOP
- Classes and objects
- Encapsulation
- Abstraction
- Inheritance
- Polymorphism
- Compile-time vs runtime polymorphism
- Method overloading vs overriding
- Dynamic method dispatch
- Constructors
- Destructors
- Interface vs abstract class
- Composition vs inheritance
- Association, aggregation, and composition
- Access modifiers
- `this` / `self`
- `super`
- Static members
- Class vs instance variables

## Deeper / Practical OOP

- Composition over inheritance
- Liskov Substitution Principle
- SOLID principles
- Dependency inversion
- Coupling and cohesion
- Shallow copy vs deep copy
- Designing a class hierarchy
- OOP principles used in projects

> **Preparation focus:** OOP is especially important for software/backend interviews and can be connected directly to Python and backend projects.

---

# 2. DBMS — Database Management Systems

**32 questions**

## Database Fundamentals

- DBMS
- DBMS vs RDBMS
- Database schema
- Tables, rows, columns, and records
- Primary and foreign keys
- Candidate keys
- Composite keys
- Constraints
- Normalization
- 1NF, 2NF, 3NF, and BCNF
- Why normalization is needed
- Denormalization

## Transactions & Concurrency

- Transactions
- ACID properties
- Transaction isolation levels
- Dirty reads
- Non-repeatable reads
- Phantom reads
- Database deadlocks
- Deadlock prevention and handling

## Indexing & Performance

- Database indexes
- How indexes improve query performance
- Disadvantages of indexes
- Clustered vs non-clustered indexes
- Composite indexes
- Choosing columns to index
- Why indexes can make writes slower
- SQL query optimization
- `EXPLAIN` / query execution plans

## Practical & Scaling

- SQL vs NoSQL
- Database scaling strategies
- Replication
- Sharding
- Large-scale database design

---

# 3. Operating Systems

**32 questions**

## Processes & Threads

- Operating systems
- Processes
- Threads
- Process vs thread
- Advantages of multithreading
- Process Control Block (PCB)
- Context switching
- Cost of context switching
- User-level vs kernel-level threads

## CPU Scheduling

- CPU scheduling
- FCFS
- SJF
- Round Robin
- Priority Scheduling
- Preemptive vs non-preemptive scheduling
- Starvation
- Aging
- Waiting time
- Turnaround time

## Synchronization

- Race conditions
- Critical sections
- Mutex
- Semaphore
- Mutex vs semaphore
- Monitors
- Deadlocks
- Four necessary conditions for deadlock
- Deadlock prevention vs avoidance vs detection

## Memory

- Virtual memory
- Paging
- Segmentation
- Page faults
- Page replacement
- Thrashing
- Stack vs heap
- Fragmentation

> **Preparation focus:** Understand the core concepts and calculations rather than trying to memorize every scheduling algorithm equally.

---

# 4. CN — Computer Networks

**32 questions**

## Networking Fundamentals

- Computer networks
- OSI model
- TCP/IP model
- OSI vs TCP/IP
- What happens when entering a URL in a browser

### URL Request Flow

```text
URL
 ↓
DNS
 ↓
TCP connection
 ↓
TLS (HTTPS)
 ↓
HTTP request
 ↓
Server
 ↓
HTTP response
 ↓
Browser rendering
```

## TCP / UDP / HTTP

- TCP
- UDP
- TCP vs UDP
- TCP three-way handshake
- TCP connection termination
- TCP flow control
- TCP congestion control
- HTTP
- HTTP vs HTTPS
- HTTP methods
- HTTP status codes
- HTTP/1.1 vs HTTP/2
- HTTP/3

## IP / DNS / Routing

- IP addresses
- IPv4 vs IPv6
- DNS
- DNS resolution
- DHCP
- NAT
- Subnets
- Routers
- MAC addresses
- MAC address vs IP address

## Practical Networking

- Sockets
- Ports
- TCP connection failures
- Debugging an API that works locally but not from another machine
- Proxies
- Reverse proxies
- Load balancers
- CDNs
- Network caching

---

# 🗂️ Repository Structure

Each question is maintained as a **separate Markdown file**.

```text
CS-Fundamentals/
│
├── README.md
│
├── OOP/
│   ├── 01-what-is-oop.md
│   ├── 02-four-pillars-of-oop.md
│   ├── 03-class-and-object.md
│   ├── ...
│   └── 28-oop-principles-in-project.md
│
├── DBMS/
│   ├── 01-what-is-dbms.md
│   ├── 02-dbms-vs-rdbms.md
│   ├── 03-database-schema.md
│   ├── ...
│   └── 32-large-scale-database-design.md
│
├── OS/
│   ├── 01-what-is-operating-system.md
│   ├── 02-process.md
│   ├── 03-thread.md
│   ├── ...
│   └── 32-fragmentation.md
│
└── CN/
    ├── 01-what-is-computer-network.md
    ├── 02-osi-model.md
    ├── 03-tcp-ip-model.md
    ├── ...
    └── 32-network-caching.md
```

> The filenames shown above illustrate the intended organization. The actual repository filenames may differ.

---

# 📝 Solution File Structure

Each individual question is documented in its own Markdown file.

A typical solution should make the concept easy to:

- **Understand**
- **Remember**
- **Explain in an interview**
- **Apply in practical scenarios**
- **Debug when relevant**

For conceptual questions, the explanation can follow:

```text
Definition
    ↓
Why it is needed
    ↓
How it works
    ↓
Intuition / Example
    ↓
Practical use
    ↓
Interview takeaway
```

For comparison questions:

```text
Concept A  ←→  Concept B
        ↓
Comparison table
        ↓
When each is appropriate
        ↓
Interview takeaway
```

For practical questions:

```text
Problem
   ↓
Approach
   ↓
Step-by-step reasoning
   ↓
Implementation / Example
   ↓
Trade-offs
   ↓
Practical considerations
```

---

# 🎯 Preparation Goal

This repository is designed to build a strong foundation in the four major CS subjects commonly discussed in software placement and technical interviews:

```text
                 CS FUNDAMENTALS
                       │
        ┌──────────────┼──────────────┐
        │              │              │
       OOP            DBMS            OS
        │              │              │
        └──────────────┼──────────────┘
                       │
                       CN
```

The goal is not only to memorize definitions, but to be able to:

**UNDERSTAND → REMEMBER → APPLY → DEBUG → EXPLAIN IN AN INTERVIEW**

---

## 📌 Coverage

- **OOP:** 28 questions
- **DBMS:** 32 questions
- **OS:** 32 questions
- **CN:** 32 questions
- **Total:** 124 questions

---

## 🚀 How to Use This Repository

### 1. Start with the subject

Choose one of:

```text
OOP
DBMS
OS
CN
```

### 2. Study one question at a time

Open the corresponding `.md` file and understand the explanation.

### 3. Practice explaining it

Try explaining the concept without looking at the solution.

### 4. Connect theory to practice

Where applicable, relate the concept to:

- Programming
- Backend development
- Databases
- Operating systems
- Networking
- Real-world system behavior

### 5. Revise before interviews

Use the individual Markdown files as quick revision notes.

---

## 📖 Source Question List

The subject organization and question coverage in this README are based on the project's **CS Fundamentals question list** covering:

- OOP
- DBMS
- Operating Systems
- Computer Networks

The repository keeps the question-based structure while maintaining each solution independently.
