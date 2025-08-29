1.	Difference between getElementsById and getElementsByClassName
-->	getElementById selects an element only through its unique ID.
--> It returns only one element.
On the other hand-
-->	getElementsByClassName selects every element that’s included in a particular class.
-->	It returns a whole html collection.


2.	Difference between querySelector and querySelectorAll
-->	queryselector selects only the first element that matches.
-->	Whereas,querySelectorAll selects all the elements that matches


3.	How to create and insert a new element into the DOM
At first we create a new element then set its content, afterwards we insert it into the html structer as per desire.


4.	Event Bubbling
When an event on an element first runs on that element then moves up through its parent elements.


5.	Event Delegation
It’s a pattern to handle events efficiently.We can implement a function has many event listeners using a single function and single event.
It’s a technique where a single event listener on a parent element handles events for its child.


6.	Difference between preventDefault() and stopPropagation()
preventDefault() It cancels any event if its cancelable.Its like preventing a link from opening the url.It generally prevents any default action.
Conversely,
Propagation is bubbling up to a parent element or capturing down to child elements.So stopPropagation() prevents propagation of the same event from being called.
