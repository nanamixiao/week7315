# week7315

## part I 
//PUSH(S,4), PUSH(S,1), PUSH(S,3), POP(S), PUSH(S,8), and POP(S)

begining     :      S [null,null,null,null,null,null]

 S [4,null,null,null,null,null]  

 S [4,1,null,null,null,null]

S [4,1,3,null,null,null]

S [4,1,null,null,null,null]

S [4,1,8,null,null,null]

S [4,1,null,null,null,null]



## part II 
//ENQUEUE(Q,4), ENQUEUE(Q,1), ENQUEUE(Q,3), DEQUEUE(Q), ENQUEUE(Q,8), and DEQUEUE(Q)

begining  [null,null,null,null,null,null]

[4,null,null,null,null,null]

[4,1,null,null,null,null]

[4,1,3,null,null,null]

[null,1,3,null,null,null]

[null,1,3,8,null,null]

[null,null,3,8,null,null]

## part III
add both on the top 


ENQUEUE
  if (tail+1) % capacity = head
      error("Queue overflow")




DEQUEUE(Q)
      if head == tail then
      error("Queue underflow")

## part IV 

front insert 

first have to move -1 position  * front = (front-1+capacity) % capacity then insert the value 


front delete 
first read the number , then move   *  front =(front+1)% capacity. 

back insert
first insert the value then move  * rear = (rear+1)%capacity

back delete 
first -1 positon then delete the value , *  rear = (rear-1+capacity)%capacity



### video

https://youtu.be/7MXM4UcILLY
