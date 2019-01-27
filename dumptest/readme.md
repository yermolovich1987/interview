This project is used to refresh the knowledge of taking thread dumps.

To figure out the PID of the process we can use JPS tool by simply running jps.

To generate the thread dump you can use:
jstack -l 11568 > thread_dump.txt

https://dzone.com/articles/how-to-read-a-thread-dump