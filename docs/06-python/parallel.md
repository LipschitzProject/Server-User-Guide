在Python中使用多进程的方式有Multiprocessing、Pandarallel等方式。通常新手在使用多进程处理大数据时，不会考虑内存占用问题。在Linux系统中，一旦内存和缓存都被占用完，系统就会陷入宕机。

最简易的避免过度占用内存的方法是优化你提交给多进程的函数，尽量精简输入给该函数的数据大小。