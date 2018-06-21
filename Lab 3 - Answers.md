**Lab 3**


The main difference between LinkedList and ArrayList in running the tests is performance and time complexity depending on which method you are using. 

For add/remove methods, LinkedLinkeds are more efficient and run in O(1) constant time because no matter the size of the list, we can use an iterator to dictate where specifically in the List we want to add/remove. We don't have the shift the entire Array (like with Arrays), we just change where the pointer looks to for the next node. The ArrayList add/remove time complexity is relative to n, the number of elements.

For access methods, we see the opposite - that ArrayLists are better. For LinkedList, in order to get, we have to go through the entire LinkedList and is dependent on the number of elements, O(n). ArrayLists can directly access every element in the list so regardless of the number of elements, the time complexity is constant O(1).  

Graph: [https://loyolauniversitychicago-my.sharepoint.com/:x:/g/personal/swang27_luc_edu/EQ-o93bdM7RDnRM2eU82viQBSqqoJ3AFhmYK6Apl7u7spw?e=CE0bIc](https://loyolauniversitychicago-my.sharepoint.com/:x:/g/personal/swang27_luc_edu/EQ-o93bdM7RDnRM2eU82viQBSqqoJ3AFhmYK6Apl7u7spw?e=CE0bIc "Lab 3 Performance Graph")
