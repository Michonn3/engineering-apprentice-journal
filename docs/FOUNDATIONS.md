# Software Taxonomy

## Primary Question

> What kind of thing is this?

## Purpose

Imagine everything i software fitting into a hierarchy. This document is my software taxonomy.
When I encounter a new technology, my first question is:
    - What kind of thing is this?
Instead of memorizing isolated tools, I classify them into categories so I can understand their responsibilities and relationships.
This taxonomy is intended to grow alongside my engineering knowledge.

---

## When do I update this?

Whenever I learn a new technology or discover a better way to classify software.

---

## How should I use this document?

Before learning a new techology, determine:

1. What kind of thing is it?
2. What responsibility does it own?
3. Who communicates with it?
4. Where does it fit in the architecture?

## Software Taxonomy Layers

### Hardware

Physical machine: MacBook, CPU, RAM, SSD.

## Operating System

Manages the computer.

Examples:

- macOS
- Windows
- Linux

## Applications

Programs that run on the operating system.

Examples:
- Git
- VS Code
- Chrome

## Runtime

## Primary Responsibility

Execute programs written in a programming language.

Examples:

- Node.js runs JavaScript
- Python runs Python code
- JVM

## Who talks to it?

Developers. Other tools.

## Why does it exist?

Programs cannot execute themselves.

## Framework

A structured tool that gives the application a pattern to build within.

Examples:

- Express
- Flutter

## Library

Code my program imports and calls when needed.

Examples:

- Mongoose

## Cloud Service

Software running on someone else's computer that I access through the internet.

Examples:

- GitHub
- MongoDB Atlas

## Sofware Taxonomy Diagram

Hardware
|
|-- CPU
|-- RAM
|__ SSD

Operating System
|
|-- macOS
|-- Windows
|__ Linux

Applications
|
|-- Editors
|     |___ VS Code
|
|-- Browsers
|     |__ Chrome
|
|-- Runtimes
|     |__ Node.js
|
|-- Package Managers
|     |__ npm
|
|-- Developer tools
      |__ Flutter CLI

Frameworks
|
|-- Express
|__ Flutter

Libraries
|
|__ Mongoose

My Software
|
|__ Groceries to Kart

## Version Roadmap

### Version 1 - Classification
- Build my Software Engineering Taxonomy
- Define each major category
- Add examples from my current projects

### Version 2 - Relationships
- Explain how the categories interact
- Show who communicates with whom
- Compare similar concepts (framework va library, runtime vs operating system)

### Version 3 - Engineering Thinking
- Add tradeoffs
- Add design decisions
- Expand taxonomy as I learn new technologies