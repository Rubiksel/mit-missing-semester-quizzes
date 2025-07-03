## Answers

1. Using `ipdb` allows interactive debugging: setting breakpoints, stepping through code, inspecting variables, and modifying state on the fly.
2. It starts the `gdb` debugger with the program `sleep` and argument `20`. This lets the user attach to the process, set breakpoints, and inspect state.
3. It checks if a process is listening on TCP port 4444, helping verify if a server started correctly and is accepting connections on that port.
4. It contains system and application logs which provide error messages, warnings, and runtime info helpful for diagnosing system crashes, permission errors, or service failures.
5. It sends the message "Hello logs" to the system log (syslog), which can be viewed later in log files.
6. It is an interactive process viewer that shows CPU, memory, and I/O usage in real time. It helps identify processes consuming excessive resources or causing system bottlenecks.
7. `du` reports disk usage of directories/files, useful for spotting large files while `ncdu` is an interactive disk usage analyzer that allows user to navigate through the filesystem.
8. Logging libraries support configurable log levels, output formatting, timestamps, and can write logs to files or remote servers, making logs more manageable and suitable for production environments compared to print statements that can quickly overwhelm the output window.
9. It lists open files and the processes using them. It helps identify resource leaks, files or sockets in use, and diagnose problems.
10. `strace` traces system calls, showing interactions with the OS. `ltrace` traces library calls.
11. This command runs Python's profiler on `grep.py` with arguments, sorting the output by total time spent in each function (`tottime`), helping identify the slowest parts of the code.
12. This command runs `stress` with 1 CPU worker while collecting performance counters, useful for understanding CPU usage and efficiency under load.
13. This command collects detailed profiling data to be analyzed later, unlike `perf stat` which shows summary counters.
14. Call graphs show function call relationships and how much time is spent in each call stack, helping identify expensive call paths and optimization targets.
15. A flame graph visualizes stack traces sampled over time, with wider blocks representing more time spent. It helps quickly spot which functions or code paths consume the most CPU.
16. This command benchmarks and compares the two commands (`fd` vs `find`), running 3 warmup runs before measurements to mitigate caching and startup effects for more reliable timing.
17. Warmup runs prepare the system so that the real tests give accurate and consistent results.
18. Different tools provide complementary views (system-wide resource use, CPU counters, call stack info), giving a fuller understanding of bottlenecks and their causes.
19. Debuggers can alter timing, memory layout, and signal handling, sometimes hiding or changing bugs.
20. Optimizing without profiling risks focusing on non-critical code paths, wasting time and possibly introducing bugs. Profiling directs effort where it matters most for performance gains.
