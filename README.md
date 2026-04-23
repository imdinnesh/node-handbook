# Node.js Handbook: A Comprehensive Guide

Welcome to the **Node.js Handbook**! This repository is a curated collection of deep-dive notes, architectural insights, and practical examples covering everything from the basics of the V8 engine to advanced stream management and testing methodologies.

Whether you're a frontend developer looking to master the backend or a seasoned Node.js engineer refining your knowledge of the event loop, these notes provide a structured path to mastery.

---

## Table of Contents

Explore the chapters below to dive into specific topics:

### Getting Started
1.  [**Introduction to Node.js**](01.Intro.md) - Core architecture, V8, and the JavaScript advantage.
2.  [**Browser vs Node.js**](02.Diff.md) - Key differences in the environment and APIs.
3.  [**V8 Engine**](03.Engine.md) - How JavaScript is compiled and executed.
4.  [**The `package.json` File**](04.Package.md) - Managing dependencies and metadata.

### Networking & Web Technologies
5.  [**The Fetch API**](05.Fetch.md) - Making HTTP requests in Node.js.
6.  [**WebSockets**](06.WebSocket.md) - Real-time bidirectional communication.
7.  [**Environment Variables**](07.Env.md) - Managing configurations with `.env`.
8.  [**Profiling & Performance**](08.Profile.md) - Tools and techniques for optimization.
9.  [**WebAssembly**](09.WebAssembly.md) - Running high-performance code in Node.js.

### Tools & Utilities
10. [**Running Scripts**](10.Script.md) - Executing Node.js files and scripts.
11. [**The REPL**](11.Repl.md) - Interactive programming in the terminal.
12. [**Console API**](12.Console.md) - Beyond `console.log`: debugging and timing.
13. [**Accepting Input**](13.Input.md) - Handling CLI arguments and interactive prompts.
14. [**Process Object**](14.Process.md) - Interacting with the current execution process.

### Filesystem & I/O
15. [**File Statistics**](15.Stats.md) - Reading file metadata.
16. [**Path Module**](16.Path.md) - Practical path manipulations.
17. [**Reading Files**](17.Read.md) - Strategies for reading data.
18. [**Writing Files**](18.Write.md) - Persisting data to disk.
19. [**File Descriptors**](19.Descriptors.md) - Understanding how Node.js tracks open files.
20. [**Filesystem Deep Dive**](20.FileSystems.md) - Advanced filesystem operations.
21. [**Folder Management**](21.Folders.md) - Creating, deleting, and navigating directories.

### Asynchronous Programming
22. [**Introduction to Async**](22.AsyncIntro.md) - Callbacks and the non-blocking nature.
23. [**Async Flow Control**](23.AsyncFlowControl.md) - Managing complex asynchronous operations.
24. [**Promises**](24.Promise.md) - Deep dive into modern async patterns.
25. [**Timers**](25.Timers.md) - `setTimeout`, `setInterval`, and timing nuances.

### The Event Loop & Concurrency
26. [**Blocking vs Non-Blocking**](26.BlockNonBlock.md) - Identifying performance bottlenecks.
27. [**The Event Loop**](27.EventLoop.md) - The heart of Node.js execution.
28. [**EventEmitter**](28.EventEmiter.md) - Building event-driven architectures.
29. [**`process.nextTick()`**](29.NextTick.md) - Understanding the microtask queue.
30. [**`setImmediate()`**](30.SetImmediate.md) - Managing immediate execution.
31. [**Event Loop Best Practices**](31.DontsEventLoop.md) - What NOT to do in Node.js.

### Advanced Topics & Quality
32. [**TypeScript in Node.js**](32.Typescript.md) - Setup, configuration, and best practices.
33. [**Streams**](33.Streams.md) - Handling large volumes of data efficiently.
34. [**Backpressure**](34.BackPressure.md) - Managing data flow mismatch in streams.
35. [**Testing**](35.Tests.md) - Unit testing, mocking, and quality assurance.

---

## Features of these Notes

- **Code-First**: Every concept is illustrated with practical, runnable examples.
- **Modern Standards**: documentation reflects recent Node.js versions and ESM syntax.
- **Visual Callouts**: Important tips, warnings, and performance notes are highlighted for quick reference.

---

> [!TIP]
> To get the most out of this handbook, it is recommended to follow the chapters sequentially if you are new to Node.js, or jump straight to **Chapter 27** if you want to master the internal architecture.

Happy Coding!
