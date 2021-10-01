
# Multi-Threading
As you might know, multi-threading is an execution model that multiple threads can be executed at the same time on a single CPU core. The operating system assigns small slices of computing time to each thread and switch between. If multiple CPU cores are available, then multiple threads can be executed truly in parallel. Due to the power of multithreading, the total time needed for multiple tasks can be significantly reduced.
In computer science, the concept of running several tasks at the same time is described as Concurrency. It is a crucial topic that you need to learn almost everywhere in modern software programming. And iOS framework provides a couple of APIs for concurrent programming, such as Grand Central Dispatch(GCD), NSOperationQueue and NSThread.

# Common Challenges

While multithreading is powerful, it comes with great complexity and also introduces two common issues. One is race conditions and the other is deadlocks. Generally, these all are related to managing access to shared resources.

Race Conditions
A race condition is an undesirable situation that occurs when a system attempts to perform two or more operations at the same time. Critical race conditions often happen when the processes or threads depend on some shared state.
