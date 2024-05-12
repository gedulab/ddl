# Deep Dive into Linux (DDL)

There are many ways to study Linux, the online course of "DDL" is one of them. The course is designed and delivered by Raymond Zhang, author of the Software Debugging book.

Steps for geheap core case 
1) extract the tar by tar -xvf corecase.tar.gz
2) start analzing by gdb
   gdb --core geheap_1972.core geheap
4) try following commands and see if you can find the root cause of the crash
   bt
   info reg
   info file
   x /6i $pc
   
