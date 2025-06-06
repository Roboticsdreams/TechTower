# Multithreading

[Tech-Interviews](../../README.md) -> [KnowledgeBase](../KnowledgeBase.md) -> [Java](../Java/Java.md) -> [Multithreading](./MultiThreading.md)

Important Java Multithreading & Concurrency Topics for Interview Prep

1. Introduction of Multithreading:
 - Definition of Multithreading
 - Benefits and Challenges of Multithreading
 - Processes vs. Threads
 - Multithreading in Java

2. Basics of Threads:
 - Creating Threads
 - Extending the Thread Class
 - Implementing the Runnable Interface
 - Thread Lifecycle 
 - New 
 - Runnable
 - Blocked
 - Waiting
 - Timed Waiting
 - Terminated
 - Thread Priority
 - Synchronization & Thread Safety
 - Synchronized Methods
 - Synchronized Blocks
 - Volatile Keyword

3. Inter Thread Communication and Synchronization
 - Inter-Thread Communication
 - wait(), notify(), and notifyAll() methods
 - Producer-Consumer Problem
 - Thread Joining

4. Some Advanced Topics
 - Thread Pools
 - Executor Framework
 - ThreadPoolExecutor
 - Callable and Future
 - Fork/Join Framework
 - ThreadLocal in Multithreading

5. Concurrency Utilities
 - java.util.concurrent Package
 - Executors and ExecutorService
 - Callable and Future
 - CompletableFuture
 - Scheduled ExecutorService
 - CountDownLatch, CyclicBarrier, Phaser, and Exchanger

6. Concurrent Collections 
 - ConcurrentHashMap
 - ConcurrentLinkedQueue and ConcurrentLinkedDeque
 - CopyOnWriteArrayList
 - BlockingQueue Interface
 - ArrayBlockingQueue
 - LinkedBlockingQueue
 - PriorityBlockingQueue

7. Atomic Variables
 - AtomicInteger, AtomicLong, and AtomicBoolean
 - AtomicReference and Atomic ReferenceArray
 - Compare-and-Swap Operations

8. Locks and Semaphores
 - ReentrantLock
 - ReadWriteLock
 - StampedLock
 - Semaphores
 - Lock and Condition Interface

9. Best Practices and Patterns
 - Thread Safety Best Practices
 - Immutable Objects
 - ThreadLocal Usage
 - Double-Checked Locking and its Issues
 - Concurrency Design Patterns

11. Common Concurrency Issues and Solutions
 - Deadlocks
 - Starvation
 - Livelocks
 - Race Conditions
 - Strategies for Avoiding Concurrency Issues

12. Java Memory Model (we have already covered it in start, but mostly will see from different thread perceptive)
 - Understanding Java Memory Model 
 - Happens-Before Relationship
 - Volatile and Final Fields

13. Java 9+ Features
 - Reactive Programming with Flow API
 - CompletableFuture Enhancements
 - Process API Updates

14. Java 11+ Features
 - Local-Variable Type Inference (var keyword)
 - Enhancements in Optional class
 - New Methods in the String class relevant to concurrency

Mastering Java Multithreading: Why It Matters🙎


 Multithreading allows concurrent execution of the program, mastering multithreading is crucial for enhancing performance and increase efficiency.


 Here’s why👇: 
- Enhanced Performance: Execute multiple tasks simultaneously for faster, more responsive applications.
- Improved Resource Utilization: Optimize CPU and memory usage for better resource management. 
- Concurrency: Manage concurrent tasks to build robust, scalable applications. 
- Responsiveness: Keep UIs responsive with background task handling. 

📚 Key Concepts
- Thread Lifecycle & Management
- Synchronization
- Thread Safety
- Executors & Thread Pools
- Atomic Variables