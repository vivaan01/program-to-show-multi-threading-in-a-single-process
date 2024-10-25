In C++, context switching can be demonstrated using the standard library’s std::thread class, which allows creating and running threads concurrently. The code example below uses threads to run multiple tasks, simulating context switching by having threads yield control periodically.

Key Concepts:

	•	Concurrency: Running multiple tasks in overlapping time periods, achieved through threads.
	•	Threads: Independent paths of execution within a program. Each thread has its own execution context, allowing simultaneous operations.
	•	Multithreading: Using multiple threads to execute concurrent tasks within a single program. Threads can share memory, so synchronizing access is critical to avoid data races.
Here’s a breakdown of programs, processes, and threads and how they relate to each other in computing:

1. Program

	•	A program is a collection of instructions that perform a specific task or solve a particular problem when executed by a computer.
	•	It’s typically written in a high-level programming language (like Python or C++) and stored as an executable file on disk.
	•	Example: A text editor, a web browser, or a simple script.

2. Process

	•	A process is an instance of a program that is currently executing. When you start a program, the operating system (OS) creates a process for it.
	•	It has its own memory space (e.g., stack, heap, code, and data segments), and it’s an independent entity.
	•	A process includes information like process ID (PID), process state, and associated resources.
	•	Example: Opening multiple browser windows creates multiple instances (processes) of the browser program.

3. Thread

	•	A thread is the smallest unit of execution within a process. Threads exist within processes, and each process can have multiple threads.
	•	Threads in the same process share the same memory space but have their own stack, register set, and program counter.
	•	Multiple threads in a single process allow concurrent execution, making applications faster and more efficient by performing tasks simultaneously.
	•	Example: In a web browser, one thread might render images, another load web pages, and another handle user input.
