# ExchangeX 📈

> Master Core Java by Building a Stock Exchange Simulator from Scratch

ExchangeX is a **pure Core Java project** designed to learn Java the way experienced engineers do — by building real software instead of memorizing definitions.

This repository is not just about creating a stock exchange simulator.

It is a structured journey towards mastering **Core Java, JVM fundamentals, design principles, concurrency, and production-grade engineering concepts** through project-based learning.

---

# 🎯 Objective

The goal of ExchangeX is to understand:

- What Java features are
- Why they were introduced
- What problems they solve
- How they work internally
- When to use them
- When not to use them
- Their tradeoffs
- Their production usage
- Their interview relevance

Every concept introduced in this project will be explored through:

```text
Business Requirement
        ↓
Java Concept
        ↓
Theory
        ↓
Internal Working
        ↓
Implementation
        ↓
Best Practices
        ↓
Production Perspective
        ↓
Interview Questions
        ↓
Scenario-Based Questions
        ↓
Interview Traps
        ↓
Code Review
```

---

# 🏗 Project Overview

ExchangeX simulates a stock exchange platform where traders can:

- Create accounts
- Manage portfolios
- Buy stocks
- Sell stocks
- Place market orders
- Place limit orders
- Track holdings
- View trade history
- Receive notifications
- Simulate concurrent trading
- Persist data locally

---

# 📦 Planned Modules

```text
ExchangeX
│
├── users
│   ├── Trader
│   └── Portfolio
│
├── stocks
│   └── Stock
│
├── orders
│   ├── Order
│   ├── BuyOrder
│   ├── SellOrder
│   ├── OrderType
│   └── OrderStatus
│
├── trades
│   └── Trade
│
├── exchange
│   ├── Exchange
│   ├── MatchingEngine
│   └── OrderBook
│
├── notifications
│
├── persistence
│
├── concurrency
│
└── app
    └── Main
```

---

# 🚀 Java Concepts Covered

## Core Java

- Classes
- Objects
- Constructors
- Encapsulation
- Inheritance
- Polymorphism
- Abstraction
- Interfaces
- Packages
- Access Modifiers

---

## Collections Framework

- List
- Set
- Queue
- Map
- HashMap
- TreeMap
- PriorityQueue
- ConcurrentHashMap

---

## Generics

- Generic Classes
- Generic Methods
- Type Safety
- Wildcards
- Bounded Types

---

## Exception Handling

- Checked Exceptions
- Unchecked Exceptions
- Custom Exceptions
- Exception Hierarchies

---

## File Handling

- File API
- Buffered Streams
- Serialization
- Deserialization

---

## Java 8+

- Lambda Expressions
- Functional Interfaces
- Streams API
- Method References
- Optional

---

## Date and Time API

- LocalDate
- LocalDateTime
- Instant
- Duration
- ZonedDateTime

---

## Concurrency

- Thread
- Runnable
- Callable
- Future
- ExecutorService
- Thread Pools
- Locks
- Synchronization
- Producer Consumer
- Atomic Classes

---

## Design Patterns

- Singleton
- Builder
- Factory
- Strategy
- Observer
- Command
- Decorator
- State

---

## JVM Internals

- Heap
- Stack
- Metaspace
- Class Loading
- Bytecode
- JIT Compilation
- Object Memory Layout
- Garbage Collection

---

# 📚 Learning Methodology

ExchangeX follows a **concept-first approach**.

Before writing code, we answer:

### What is it?

### Why does it exist?

### What problem does it solve?

### How does JVM implement it?

### What are the alternatives?

### What are the tradeoffs?

### How is it used in production?

### What do senior engineers discuss about it?

Only then do we implement it.

---

# 🎤 Interview-Oriented Learning

Each concept includes:

### Senior-Level Questions

Examples:

```text
Why would UUID hurt database indexing?

Can classes exist without objects?

How does class loading work?

Why are private variables not thread-safe?

What is object header in JVM?
```

---

### Scenario-Based Questions

Examples:

```text
ExchangeX has 10 million Trader objects.

How would you optimize memory consumption?

Two threads update wallet balance simultaneously.

What issues arise?

How would you solve them?
```

---

### Interview Traps

Examples:

```text
Java is purely object-oriented.

False

UUID guarantees uniqueness.

False

Objects are always allocated in heap.

Not necessarily
```

---

# 🎯 Target Audience

ExchangeX is ideal for:

- Java Developers
- Backend Engineers
- Interview Preparation
- System Design Learners
- Engineers transitioning into Java
- Developers seeking deeper JVM understanding

---

# 🛣 Learning Roadmap

### Phase 1

Domain Modeling

```text
Trader
Portfolio
Stock
Order
Trade
```

---

### Phase 2

Collections

```text
Holdings

Order Book

Watchlists

Trade History
```

---

### Phase 3

Persistence

```text
Serialization

File Storage

Snapshots
```

---

### Phase 4

Java 8 Features

```text
Streams

Functional Programming

Predicates

Comparators
```

---

### Phase 5

Concurrency

```text
Thread Pools

Matching Engine

Parallel Order Processing

ExecutorService
```

---

### Phase 6

Design Patterns

```text
Builder

Observer

Strategy

Factory

Singleton
```

---

### Phase 7

Networking

```text
Socket Programming

Exchange Server

Client Simulation
```

---

# 🧠 Philosophy

> Don't study Java and then build projects.

> Build projects and let the project force you to learn Java.

ExchangeX aims to make Java concepts stick through practical implementation, engineering discussions, and real-world scenarios.

---

# ⚡ Current Status

```text
Phase 1

In Progress

Currently Exploring:

✔ OOP Fundamentals
✔ Classes
✔ Objects
✔ JVM Basics
```

---

# 🤝 Contributions

This repository is primarily an educational initiative focused on mastering Java through project development.

Suggestions, discussions, and improvements are always welcome.

---

# 📌 Tech Stack

- Java
- JDK 21+
- IntelliJ IDEA
- Git
- Maven (later phase)

---

# ⭐ If you find ExchangeX useful

Consider starring the repository and following the journey toward mastering Core Java through real-world software development.
