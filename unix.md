how unix works?
https://neilkakkar.com/unix.html

Syscall?
https://www.youtube.com/watch?v=fLS99zJDHOc

What's an inode? symlink vs hardlink
https://www.youtube.com/watch?v=tMVj22EWg6A

ext4 layout, what is a file, block size,

hardlink cross system, you connected another disk - can you hardlink to a file on that disk?

 
process lifecycle.
state of the process zombie(D), running (R), sleep(S), uninterruptable sleep (D)
kill -9 which states it works with?
is zombie a normal state? process always goes to zombie state after it notifies parent

inter process communication linux (IPC): stdin, stdout, shared memory, signals.
what are signals? SIGINT, SIGTERM, SIGKILL
what is interruptable 

bash can trap for signal SIGINT
you can override everything except SIGKILL, but if you want you can do it too

PID, GID
 

What is a namespace?
https://www.youtube.com/watch?v=-YnMr1lj4Z8


what is definitely will not work for docker but works VM
you cannot run windows on docker!


cat proc meminfo (the more you can interpret the results the better)
buffers, residential memory (it's where the processes live, if this memory is free, but everything else is 100% then we are OK)
how to monitor memory, what if it's more than 95% occupied.

SYSCALL READ/WRITE
you first write to buffer (because you don't want to write every byte directly to disk) and it write to a file
caches - normally operation OS, where are they coming from?



what is a descriptor 

page cache https://en.wikipedia.org/wiki/Page_cache this is how you read from file
