# florest
Simple Implementation of Linked List and Tree

`npm install florest`

`var Florest = require('florest')`

#####You can create a linked list with:

`var singly = Florest.Link.create("singly", "List Name");`

or

`var doubly = Florest.Link.create("doubly", "List Name");`

#####You can then manipulate your list with add(value), remove(position) or get(position):
`singly.add(1);`
`singly.add(2);`
`singly.add(3);`

`singly.remove(2);`

`var list_at_2 = singly.get(2);`

#####You can display all nodes in the list with display():
`singly.display();`
