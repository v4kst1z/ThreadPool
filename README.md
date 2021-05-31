# ThreadPool
A simple C++11 Thread Pool implementation

```
ThreadPool& tp = ThreadPool::getInstance(4);
auto num = tp.enqueue([]() { return 10;  });
std::cout << num.get() << std::endl;
```
