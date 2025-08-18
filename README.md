## Javascript Basics

<b>1.“What is the difference between synchronous and asynchronous JavaScript?”</b>

“Synchronous JavaScript executes code line by line, where each statement must finish before the next runs. Asynchronous JavaScript, on the other hand, allows tasks like timers, API calls, or file operations to run in the background without blocking the main thread. The results are later handled using callbacks, promises, or async/await.”

<b>2.“What is a Promise in JavaScript, and why is it used?”</b>

“A Promise in JavaScript is an object that represents the eventual completion or failure of an asynchronous operation. It has three states: pending (initial), fulfilled (resolved successfully), and rejected (failed). Promises help manage asynchronous code in a cleaner way, avoiding deeply nested callbacks.”

<b>3.“What is the difference between Promises and async/await in JavaScript?”</b>

“Promises are objects that represent the eventual result of an asynchronous operation, with three states: pending, fulfilled, or rejected. async/await is syntactic sugar over promises that makes asynchronous code look synchronous: async marks a function as asynchronous, and await pauses execution until the promise resolves, without blocking the main thread.”

<b>4.“Can you explain the Event Loop in JavaScript and how it handles asynchronous tasks?”</b>

“The Event Loop in JavaScript continuously checks the call stack. When the stack is empty, it takes tasks from the callback queue or microtask queue (like resolved promises) and pushes them to the stack for execution. This allows JavaScript to handle asynchronous operations without blocking the main thread.”
