# Finalize-vs-Dispose
Before getting into finalize and dispose we must know about Gargbage collector. The garbage collector in the.Net CLR executes as part of our application and is in charge of reclaiming the memory of objects that are no longer in use. Memory for objects that are no longer referenced is freed by the garbage collector, while memory for upcoming allocations is retained. 
 
#Finalize
The finalize() method is defined in the System.object class.Garbage collection calls the finalize method to purge the memory of unmanaged resources. It is specified that finalise() is protected. This is necessary because only the garbage collector should have access to the method finalise(), which must not be accessible from outside the class.
 
#Dispose
 The dispose() method is declared under the interface IDisposable.There is no automated call to this procedure. When developing a custom class that will be utilised by others, the programmer must manually implement it.
The method's performance is quick, and it immediately releases the resources that a class object was holding. 
