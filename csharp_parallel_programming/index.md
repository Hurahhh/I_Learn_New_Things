# Course Content

## 1. Task
### Cancelation Token
The CancellationTokenSource.Cancel() method does not cancel the operation itself. It just changes the IsCancellationRequested property value to true. So we as developers have to define cancellation logic by ourselves.

### Lock
Atomic operations are typically implemented using hardware instructions or software constructs that guarantee mutual exclusion, such as locks or critical sections.

### Atomic Operation
An atomic operation is a single, indivisible operation that must execute as if it were the only operation in the system. These operations are typically implemented using hardware instructions or software constructs that guarantee mutual exclusion, such as locks or critical sections. There for multiple threads cannot perform atomic operations on the same memory location at the same time.
