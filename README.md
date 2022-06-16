Monty Interpreter

The intepreter can be run as either a stack (LIFO) or as a queue(FIFO).

Monty Opcodes
* PUSH
  Usage: push <int>
  Pushes an element to the stack
  The parameter <int> must be an integer

* Pall
  Prints all values in the stack/queue, starting from top

* Pint
  Prints the top value of the stack/queue

* Pop
  Removes the top element of the stack/ queue

* Swap
  Swaps the top two elements of the stack/queue

* nop
  Does not do anything

* Add
  Adds the top two elements of the stack/queue
  The result is sorted in the second elemnt from the top and the top element is popped

* sub
  Subtracts the top element of the stack/queue from second element from top
  The result is stored in the second elemnt from the top and the top elemnt is removed

* mul
  Multiplies the top two elements of the stack/queue
  The result is stored in the second element from the top and the top elemnt is removed

* div
  Divides the second elemnt from the top of the stack/queue by the top element
  The result is stored in the second element from the top and the top element is removed

* rotl/ rotr
  Rotates the top and bottom element of the stack/queue respectivelly

* stack
  Switches a queue to stack mode 

* queue
 Switches a stack to queue mode
