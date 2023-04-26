# Course Content

## 1. Task
### Cancelation Token
The CancellationTokenSource.Cancel() method does not cancel the operation itself. It just changes the IsCancellationRequested property value to true. So we as developers have to define cancellation logic by ourselves.