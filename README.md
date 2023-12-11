# HTML5 Presentation on Inter Process Communications
A dynamic and interactive web presentation made on IPC entirely using HTML, CSS and Javascript only.  

The aim of this presentation is to provide easy explanations about various types of Inter Process Communications,  
Shared memory, and message passing techniques in an animated and interactive format.


https://github.com/Navninja7/IPC-presentation-with-JS/assets/100609826/e504cdbc-1678-455e-b388-8937962a61eb



*Topics covered in the presentation:*  
**1.IPC and it's characteristics**  
**2.Shared memory and message passing**  
**3. Communication in client/server architecture**  
**4.Pros and Cons of IPC**  


*Presentation includes 3 interactive pages:*  
  
**1. Producer-Consumer Problem**  

The Producer-Consumer problem is a classical multi-process synchronization problem, that is we are trying to achieve synchronization between more than one process.  

There is one Producer in the producer-consumer problem, Producer is producing some items, whereas there is one Consumer that is consuming the items produced by the Producer. 
 The same memory buffer is shared by both producers and consumers which is of fixed-size.  

The task of the Producer is to produce the item, put it into the memory buffer, and again start producing items. Whereas the task of the Consumer is to consume the item from the memory buffer.  
![interactive1](https://github.com/Navninja7/IPC-presentation-with-JS/assets/100609826/aa023398-5d40-4282-9ba2-c65515cde64f)

**2. Blocking send and blocking receive**  

Blocking is considered synchronous and blocking send means the sender will be blocked until the message is received by receiver. Similarly, blocking receive has the receiver block until a message is available.  

![chrome_V3plG8fFC9](https://github.com/Navninja7/IPC-presentation-with-JS/assets/100609826/91986a13-7d10-4725-9216-1f7ee58165bc)

 **3. Non-blocking send & Non-blocking receive**  

Non-blocking is considered asynchronous and Non-blocking send has the sender sends the message and continue. Similarly, Non-blocking receive has the receiver receive a valid message or null.  

![chrome_eI6y98I3nI](https://github.com/Navninja7/IPC-presentation-with-JS/assets/100609826/22f9a0f2-26bd-40fa-8714-e420399bc42f)

 
