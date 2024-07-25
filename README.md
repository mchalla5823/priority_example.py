# priority_example.py
my_priority_queue = queue.PriorityQueue()

   # Add an element to the priority queue (priority, element)
   my_priority_queue.put((1, 'Task 1'))

   # Pop an element from the priority queue
   popped_element = my_priority_queue.get()

   # Show the output
   print("Popped element:", popped_element)
