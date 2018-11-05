# Quiz-05-11


Stack/
Data structure w/limited access- stack, queue.
They collect data, objects and containers can be either arrays or linked lists.
Stack has only 2 operations: pop and push, and the principle is FILO- First in Last out. The example of stack is plates in box, so we need to remove last added plate in order to remove the plate we add first. 
Besides pop and push, in stacks we can define is_empty, peek, size.
The complexity of stack is O(1), which means it finish in a limited time and do not depend on number of objects. also we use stack in reversin word or in a tower of Hanoi.




Tower of Hanoi/
we have 3 stacks(first,middle,last), and we need to move all circles from first stack to last one, in a same order.
Assume, in a first stack we have 4 circles, and we know that we can only pop the cirsle which is in the top and push it somewhere we want(in middle or last stack). so we know that the last circle, which is the biggest, must be the last one in the last stack. we ignore that, and assume that now our circles are 3 and we need to move them  to the middle stack, now the order of stacks is first, last, middle, that means that the ordered stack will become middle stack for 3 circles. now we pop the top circle, move it to last, 2nd cirle too, then 3rd circle we move  to middle stack(pop, push), 2nd circle pop from last, push to middle, and the smallest (pop,push). now we have sequence of 3 circles. then we switch sstacks (first, middle,last), pop the largest circle and push in last, then pop circles from middle stack in sequence, and push to first one, then starting from top, pop circles and push in last one. we move all cicles from first stack to last one, in the same order. 
