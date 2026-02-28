![Banner](Cover.png)

# Hey! I'm Megan, a final year Mechatronic Engineering student @ AUT.

--- 

## Projects

### ToDo Application with specialised hardware intergration *(in progress)*
**Technology:** Java, JavaFX, Microcontrollers, Serial Communcation

This project involves the development of a desktop to do list application which connects to custom hardware which displays the list, marks tasks as completed and tracks time spent on the task. 

### Core Features
- Add, edit, and delete tasks  
- Categorise and prioritise tasks  
- Track task completion status  
- Persistent task storage  
- Real-time serial communication with ESP32  
- Hardware-triggered task updates  
- External peripherals (e.g., LEDs, buttons, display modules) for physical interaction  
- Clean, modular JavaFX interface  

---

### How It Works
The application is structured into four clear layers:

**1. User Interface Layer**
- JavaFX-based GUI  
- Modular screens and reusable UI components  
- Event-driven task interaction  

**2. Business Logic Layer**
- Task management controller  
- State handling and validation  
- Decoupled service classes  

**3. Hardware Integration Layer**
- Serial communication using Java libraries  
- Command protocol between Java application and ESP32  
- Event handling for hardware-triggered actions  

**4. Embedded System Layer (ESP32)**
- Firmware handling button inputs and peripheral control  
- GPIO management for LEDs and other components  
- Bidirectional communication with desktop application  

---

### External Peripherals Used
- E-Paper display
- Digital chess clock mechanism
- Potentiometer
- LEDs (task status indicators)  
- Serial communication interface (USB/UART)  

---

### Skills Strengthened
- Embedded systems integration  
- Serial protocol design  
- Microcontroller programming (ESP32)  
- Hardware-software system design  
- Event-driven programming  
- Real-time state synchronisation  
- Debugging across hardware and software environments  
- Modular architectural design  

---

### Overall Impact
This project extended beyond traditional desktop application development by combining embedded systems with GUI-based software.

## Previous Assignments

##  Software Construction / The Blank Manager (ENSE600)  
**Semester 2, 2025**  
**Grade: A+**
In ENSE600, I worked in a team to design and develop a full desktop application using Java. Through this course, I learned to:

- Describe the fundamental issues, concepts, and practices associated with software design and construction  
- Demonstrate the ability to learn and apply new technical knowledge and skills  
- Apply appropriate design techniques to the development of object-oriented software  
- Assess the quality of software design and implementation  
- Explain software reuse as a concept  
- Select and apply appropriate approaches to software reuse  
- Explain the principles of effective user interface design and apply these to interface development  
- Describe the principles and objectives of software testing  
- Apply appropriate testing techniques to ensure software quality  

My teammate and I received an **A+** for our assignment.

---

### Assignment 2 - A+
- GUI-Based Inventory & Budget Management Application  
- Database Integration (Apache Derby Embedded)  
- Design Patterns & SOLID Principles  
- Unit Testing & Git Version Control  

---

### What the Application Is
A full-featured inventory and budget management system that allows users to:
- Log in or create accounts  
- Manage inventory items  
- Track purchases and transactions  
- Record income and expenses  
- Visualise spending via budget quadrants  
- Generate and export shopping lists  
- Store persistent user data between sessions  

---

### How It Works
The application was structured into three clear layers:

**1. User Interface Layer**
- Modular panel-based GUI  
- Shared theming system for consistent design  
- Custom UI components for improved usability  

**2. Business Logic Layer**
- Manager classes handling inventory, transactions, and budgeting logic  
- Clear separation between UI and core functionality  

**3. Database Layer**
- Apache Derby Embedded database  
- Automated setup without manual configuration  
- Multiple read/write interactions using JDBC  

Unit tests were implemented to validate login functionality and database behaviour.  
Git was used to track development history with multiple commits and collaborative workflows.

---

### Skills Strengthened
- Layered application architecture  
- Clean separation of concerns  
- Design pattern implementation  
- Database-driven application development  
- Embedded database configuration  
- Writing robust, testable code  
- Applying JUnit for functional testing  
- Refactoring and removing code smells  
- Professional collaboration using Git  

---

##  Data Structures and Algorithms (COMP610)  
**Semester 2, 2025**  
**Grade: A+ (100/100 for both assignments)**
In COMP610, I developed a strong foundation in algorithm design, data structures, and concurrent programming. Throughout the course, I learned to:

- Design and implement linear data structures including linked lists, stacks, queues, and sets  
- Develop and analyse multithreaded programs with proper synchronization  
- Implement algorithms that parse, traverse, and manipulate structured data  
- Design and utilise tree-based structures, maps, and key-driven systems  
- Apply graph traversal algorithms for pathfinding problems  
- Evaluate algorithm efficiency and reason about time complexity  

---

### Assignment 1 - A+ (100/100)
#### Linked List & Palindrome Checker
Implemented a fully generic linked list from scratch, including stack and queue abstractions, and used them to build a palindrome-checking application.

**Skills developed:**
- Pointer-based data structures  
- Recursive and iterative traversal  
- Abstract data type design  
- Stack vs Queue behaviour  
- Generics and comparison logic  

---

#### Snake Game
Built a functional Snake game using my custom Linked List implementation to manage snake growth and dynamic element removal.

**Skills developed:**
- Applying data structures to real-time systems  
- Game state management  
- Event-driven programming  
- Dynamic list manipulation  
- GUI design and interaction  

---

#### Multithreaded Ship & Port Simulation
Designed a concurrency simulation where multiple ships (threads) compete for access to a shared port resource, implemented in both synchronized and unsynchronized modes.

**Skills developed:**
- Thread lifecycle management  
- Race condition analysis  
- Synchronization and monitor objects  
- Shared resource protection  
- GUI integration with concurrent logic  

---

### Assignment 2 - A+ (100/100)
#### Binary Search Tree & Student Manager App
Designed a fully generic Binary Search Tree supporting sorting and searching by multiple key types (String and Float), including reverse traversal in O(n).

**Skills developed:**
- Recursive tree construction  
- In-order traversal algorithms  
- Time complexity analysis  
- Generic key comparison  
- Separation of data model and structure  

---

#### Noise Removing App (Median Filter + QuickSort)
Implemented a median filter image processor using a custom-built QuickSort algorithm to remove salt-and-pepper noise from images.

**Skills developed:**
- QuickSort implementation from first principles  
- Partition logic and recursion  
- Sliding window algorithms  
- Pixel-level data manipulation  
- Bridging theory with applied image processing  

---

#### Maze Solver & Pathfinder
Built a graph-based maze solver that parses text input, constructs a graph representation, performs depth-first search traversal, animates exploration, and highlights the final path.

**Skills developed:**
- Graph modelling and traversal (DFS)  
- Backtracking algorithms  
- File parsing and data mapping  
- Algorithm visualisation  
- Modular system design (builder, solver, GUI separation)  

---

### Overall Impact
Across both courses, I implemented core computer science and software engineering concepts from first principles.

These projects strengthened my ability to:
- Translate abstract theory into working software  
- Analyse performance and algorithmic complexity  
- Build modular, maintainable systems  
- Integrate backend logic with interactive GUIs  
- Reason about concurrency and shared-state systems  
