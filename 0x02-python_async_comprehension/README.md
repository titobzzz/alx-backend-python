An async comprehension is an asynchronous version of a classical comprehension.
Asyncio supports two types of asynchronous comprehensions, they are the “async for” comprehension and the “await” comprehension.
Comprehensions allow data collections like lists, dicts, and sets to be created in a concise way.list comprehension allows a list to be created from a for expression within the new list expressionasynchronous comprehension allows a list, set, or dict to be created using the “async for” expression with an asynchronous iterable.
This will create and schedule coroutines or tasks as needed and yield their results into a list.
Recall that the “async for” expression may only be used within coroutines and tasks.

