## Questions

1. What is the benefit of using `python -m ipdb bubble.py` for debugging over inserting print statements?
2. What does `gdb --args sleep 20` do, and why might it be useful for understanding program execution?
3. When would you use `sudo lsof | grep ":4444.LISTEN"` while debugging a networked application?
4. What kind of information can be found in `/var/log`, and how can this help in debugging system-level issues?
5. What does `logger "Hello logs"` do?
6. How does `htop` help in identifying performance issues during debugging or profiling?
7. When debugging storage-related performance, how might `du` and `ncdu` help identify problems?
8. What are the advantages of using a logging library like logger instead of simple print statements for debugging?9. What is the purpose of `lsof`, and how can it help debug file or socket-related resource issues?
10. How can `strace` and `ltrace` be used to debug a program that hangs or crashes on startup?
11. What does  
    `python -m cProfile -s tottime grep.py 1000 '^(import(\s*def)[^,]*$' *.py`  
    do, and how does the `-s tottime` option assist in finding bottlenecks?
12. What does `sudo perf stat stress -c 1` measure, and what kind of performance questions can it help answer?
13. How does `sudo perf record stress -c 1` differ from `perf stat`, and what type of profiling output does it produce?
14. What kind of insights can be gained from analyzing a call graph?
15. What is a flame graph, and how does it help identify performance bottlenecks?
16. What is the purpose of using  
    `hyperfine --warmup 3 'fd -e jpg' 'find . -iname "*.jpg"'`,  
    and how does it improve performance benchmarking?
17. What is the difference between warmup runs and measurement runs in benchmarking tools like `hyperfine`?
18. Why is it important to use multiple performance tools (e.g. `perf`, `htop`, `flame-graph`) when diagnosing slowness in code?
19. Why might a program behave differently inside a debugger like `gdb` or `ipdb`?
20. What are some risks of over-optimizing before profiling, and how can profiling tools prevent wasted effort?
