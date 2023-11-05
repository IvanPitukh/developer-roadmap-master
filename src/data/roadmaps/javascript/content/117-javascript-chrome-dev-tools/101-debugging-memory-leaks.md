# Debugging Memory Leaks

In JavaScript, memory leaks commonly occur within heap allocated memory, where short lived objects are attached to long lived ones and the Garbage Collector cannot safely de-allocate that memory as it is still referenced from the root set (the global object).

Visit the following resources to learn more:

- [Catching memory leaks with Chrome DevTools](https://medium.com/coding-blocks/catching-memory-leaks-with-chrome-devtools-57b03acb6bb9)
- [Effective Javascript Debugging ](https://medium.com/swlh/effective-javascript-debugging-memory-leaks-75059b2436f6)
- [Debugging JavaScript memory leaks](https://www.debugbear.com/blog/debugging-javascript-memory-leaks)
- [Debugging Memory Leaks In Production JavaScript Applications](https://www.jackhoy.com/web-applications/2020/10/21/debugging-memory-leaks-in-nodejs.html)
