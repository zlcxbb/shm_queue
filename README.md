# shm_queue
 spinlock实现的共享内存队列,可用于进程间或线程间通信。 

1. 可写入任意长度的数据
2. 队列支持单写单读、单写多读、多写单读、多写多读
3. 共享内存支持 mmap(文件或匿名), shmget
4. 实现了slab内存块分配器
