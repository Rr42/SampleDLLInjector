# Demonstration of a simple DLL injector
This demonstration of a DLL injector in written in C++ for Windows with the help of Visual Studio 2017. 

**This project is for demonstration purposes only. The contributors of this repository will not take responsibility for any such damage.**

Have fun learning!

## Setting up the code
Before compiling the code make sure to properly set the `wPID` variable in the `DLLinjector/DLLinjector.cpp` file.

```
// Process ID of destination
	DWORD wPid = <PID to be set>;
```

You can find the PID of the process being targeted using task manager.
