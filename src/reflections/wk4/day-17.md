# Tuesday
What are the three states of a Promise?
>The three states are Pending, Fulfilled, and Rejected. Pending is the promise is in the process of passing through the function. Fulfilled means it was successful. Rejected means something went wrong and needs to be fixed or it was a bad request.

How do promises seek to resolve the issues of "callback hell"?
>Instead of stopping the entire program, promises only run errors from one function and allow everything else to run. It makes it easier to pin point the issue.

What is the difference between .then() and .catch()?
>The catch() method returns a Promise and deals with rejected cases only. The then() method only passes on the error. This causes everything to stop and the entire page screams error at you.


## Link