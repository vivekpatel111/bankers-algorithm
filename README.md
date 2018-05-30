# :bank: Banker's Algorithm :books:

Banker’s Algorithm, which is a deadlock avoidance algorithm. It is called the Banker’s Algorithm, because it could be used by a bank to make sure that money is allocated in such a way that all customer needs are met. When a new process enters the system, it declares the maximum number of instances that are needed. This number cannot exceed the total number of resources in the system. If the process can be accommodated based upon the needs of the system, then resources are allocated, otherwise the process must wait. The algorithm is actually made up of two separate algorithms: the safety algorithm and the resource allocation algorithm.

*This program is tested using Borland C++ Compiler.*

## File Structure
| File Name | Description |
| --- | --- |
| BANKER.CPP | main application |
| CLASS.CPP | banker class declaration |
| DEFINE.CPP | banker class definitions |
| GRAPHICS.CPP | graphics related functions |


## Screenshots
### Application
> Main Application Window

![Main Application Window](screenshots/main-screen.png "Main Application Window")

### Algorithm

> Safe Sequence Check

![Safe Sequence Check](screenshots/safe-sequence-check.png "Safe Sequence Check")

> Safe Sequence Result

![Safe Sequence Result](screenshots/safe-sequence-result.png "Safe Sequence Result")

> Algorithm Inprogress

![Algorithm Inprogress](screenshots/inprogress.png "Algorithm Inprogress")

> Current State

![Current State](screenshots/current-state.png "Current State")

### Extra Flows
> Input Validation

![Input Validation](screenshots/input-validation.png "Input Validation")

> Memory Deallocation

![Memory Deallocation](screenshots/memory-deallocation.png "Memory Deallocation")