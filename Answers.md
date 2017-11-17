What are the order of insertions/removals for the following data structures?
	
	Stack - The last item that was put into the array is also the first one out.
	Queue - The first item into the array is also the first one out.


What is the retreival time complexity for the following data structures?
	
	Linked List - The slowest out of the three methods since it has to go through the entire list sequentially. O(n) 
	
	Hash Table - The fastest methods of the three since you can direclty access an index. O(1)

	Binary Search Trees - The second fastest out of the three. If the tree is in order then the search should be cut in half. O(log n)


What are some advantages to using a Hash Tables over an array in JavaScript?

One advantage that hash tables have over arrays are that hash tables are faster to use because you can direclty access an index. With an array, you would have to go through all the indexes, which is time consuming. When searching for an index, hash tables also take about the same amount of time to look up an index compared to arrays which is dependent on where the item is in the array. 