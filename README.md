# Utilities
Various codes for helping with Backtesting


Code to read CSV files from folder

Multithreaded reading of files with each thread reading separate file will nto help due to the following reason :
Threads will be limited by I/O from hard drive. So only one thread can read from hard-drive at a time whereas other threads are blocked. So it is of no use to do multithreading.
https://stackoverflow.com/questions/18337471/how-can-i-read-multiple-files-faster

Multithreaded reding of single file
https://stackoverflow.com/questions/20934406/multi-threaded-reading-from-a-file-in-c
https://stackoverflow.com/questions/29028137/how-to-multithread-reading-a-file-in-c11

Code to read single CSV file 
https://stackoverflow.com/questions/33250380/c-skip-first-line-of-csv-file
https://stackoverflow.com/questions/9371238/why-is-reading-lines-from-stdin-much-slower-in-c-than-python?rq=1
https://www.quora.com/How-do-I-read-csv-files-in-c++

Read all files from a folder in C++
https://stackoverflow.com/questions/20544532/read-all-files-from-a-folder-c
http://forums.devarticles.com/c-c-help-52/c-opening-all-txt-files-in-a-folder-one-by-150745.html

Memory mapping to read huge amounts of data
https://blogs.msdn.microsoft.com/calvin_hsia/2016/06/30/mapped-files-give-very-fast-access-to-huge-amounts-of-data/
