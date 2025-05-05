# PLS-Assignment-
Category                    Description                                                                                        |
| ----------------------- | -------------------------------------------------------------------------------------------------- |
| **Fixed Stack Dynamic** | Fixed-size array allocated on the stack. Not resizable.                                            |
| **Stack Dynamic**       | Stack-like behavior but with dynamic resizing during runtime.                                      |
| **Fixed Heap Dynamic**  | Fixed-size array allocated on the heap.                                                            |
| **Heap Dynamic**        | Heap-based and resizable array, typically using a dynamic data structure like ArrayList or Vector. |

 COMPARISON: C++ vs Java Memory Allocation Location


| Category            | C++                                                        | Java                                                                     |
| ------------------- | ---------------------------------------------------------- | ------------------------------------------------------------------------ |
| Fixed Stack Dynamic | Uses stack memory, e.g., `int arr[5]` inside functions     | Uses stack for local variables, but all arrays are actually heap objects |
| Stack Dynamic       | Resizes using manual heap allocation (`new[]`, `delete[]`) | Uses arrays with dynamic resizing (manual copying or `ArrayList`)        |
| Fixed Heap Dynamic  | Allocated with `new int[]`, managed manually               | Arrays are always heap-allocated (e.g., `new int[10]`)                   |
| Heap Dynamic        | Uses `std::vector` or custom classes with resizing         | Uses `ArrayList`, which resizes automatically                            |


Performance Notes
C++ offers more control and is faster in low-level operations but is prone to memory leaks and errors without careful management.

Java abstracts away memory management and bounds checking but adds some overhead due to its garbage collector.
