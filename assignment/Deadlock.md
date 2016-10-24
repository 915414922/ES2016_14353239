#The picture

![Deadlock_in_Ubantu](https://github.com/915414922/ES2016_14353239/blob/master/Deadlock.PNG)

#Four reason for deadlock

互斥条件：一个资源每次只能被一个进程使用。
请求与保持条件：一个进程因请求资源而阻塞时，对已获得的资源保持不放。
不剥夺条件:进程已获得的资源，在末使用完之前，不能强行剥夺。
循环等待条件:若干进程之间形成一种头尾相接的循环等待资源关系。

#The reason for Deadlock this time 

from t.start(),when thread t is running,we run run().In run(),it has methodB(),the synchronized code.

But when count==0,it began to methodA(),the synchronized too.So when they use at the same time,Deadlock appear.  
