# JavaScript Interview Questions — All-in-One

> Combined from:
>
> - https://www.geeksforgeeks.org/javascript/javascript-interview-questions/
> - https://www.interviewbit.com/javascript-interview-questions/
> - https://github.com/sudheerj/javascript-interview-questions/blob/master/README.md
>
> Duplicates removed. Total: ~522 concept questions + 86 coding/output-based questions.

---

## Part 1 — Core Concept Questions

### Variables, Scope & Hoisting

1. What is the purpose of the `let` keyword?
2. What is the difference between `let` and `var`?
3. What is the reason to choose the name `let` as a keyword?
4. What's the difference between `var`, `let`, and `const`, and what is the Temporal Dead Zone?
5. How do you redeclare variables in a switch block without an error?
6. What is the Temporal Dead Zone?
7. Does the `const` variable make the value immutable?
8. Can I redeclare `let` and `const` variables?
9. What is scope in JavaScript?
10. What is a Variable Scope in JavaScript?
11. What is lexical scope in JavaScript?
12. What is the difference between Lexical and Dynamic Scoping?
13. How does lexical scoping work with the `this` keyword in JavaScript?
14. What has to be done in order to put Lexical Scoping into practice?
15. What are global variables?
16. What are the problems with global variables?
17. What is the precedence order between local and global variables?
18. What are shadowing and illegal shadowing?
19. What is module scope in JavaScript?
20. What is an environment record?
21. What is Hoisting?
22. What is hoisting in JavaScript?
23. What is called Variable typing in JavaScript?
24. What are "truthy" and "falsy" values in JavaScript?
25. What are undeclared and undefined variables?
26. What are the differences between undeclared and undefined variables?

---

### Data Types & Type Coercion

27. What are the different data types present in JavaScript?
28. What are primitive data types?
29. What are the differences between primitives and non-primitives?
30. What is the difference between `null` and `undefined`?
31. What is null value?
32. What is undefined property?
33. What do you mean by Null in JavaScript?
34. What is negative infinity in JavaScript?
35. Why is `typeof null === "object"`?
36. What is `typeof` operator?
37. What is NaN property?
38. What is `isNaN`?
39. What is the difference between `isNaN` and `Number.isNaN`?
40. What is the use of `isNaN`, and how is it different from `Number.isNaN`?
41. What is the purpose of `isFinite` function?
42. What are wrapper objects?
43. Is JavaScript a statically typed or a dynamically typed language?
44. Is JavaScript statically typed or dynamically typed?
45. Why do we call JavaScript as dynamic language?
46. Explain Implicit Type Coercion in JavaScript.
47. Does JavaScript support automatic type conversion?
48. What is the purpose of double exclamation (`!!`)?
49. What is an Unary operator?
50. What is a void operator?
51. What is the purpose of `void 0`?
52. What is the comma operator?
53. What is the advantage of the comma operator?
54. What is the purpose of `eval`?
55. Is it recommended to use `eval`?

---

### Functions

56. What is a first class function?
57. What is a first order function?
58. What is a higher order function?
59. What is a higher-order function in JavaScript?
60. What are the examples of built-in higher order functions?
61. What are the benefits of higher order functions?
62. What is a unary function?
63. What is a pure function?
64. What are the benefits of pure functions?
65. What are the differences between pure and impure functions?
66. What is referential transparency?
67. What are the possible side-effects in JavaScript?
68. What is the currying function?
69. What is currying in JavaScript?
70. What are lambda expressions or arrow functions?
71. What are arrow functions?
72. What is an IIFE (Immediately Invoked Function Expression)?
73. What is an Immediately Invoked Function (IIFE) in JavaScript?
74. How to invoke an IIFE without any extra brackets?
75. What do you mean by Self Invoking Functions?
76. What is a first class function?
77. What are Higher Order Functions in JavaScript?
78. What is a rest parameter?
79. What happens if you do not use rest parameter as a last argument?
80. What is a spread operator?
81. What are default parameters?
82. What is the way to find the number of parameters expected by a function?
83. How to find the number of parameters expected by a function?
84. What are the function parameter rules?
85. What is an arguments object?
86. What are the differences between arguments object and rest parameter?
87. What are the differences between spread operator and rest parameter?
88. What is a Short circuit condition?
89. What is the use of a constructor function in JavaScript?
90. Can we define properties for functions?
91. What is Function Composition?
92. What are compose and pipe functions?
93. What is memoization?
94. Explain the concept of memoization in JavaScript?
95. What is recursion in a programming language?
96. What is the difference between Function constructor and function declaration?
97. What is the difference between function and class declarations?
98. What is an async function?
99. What are generator functions?
100. What are the different kinds of generators?
101. What is a thunk function?
102. What are asynchronous thunks?
103. What is a Proper Tail Call?
104. How to detect if a function is called as constructor?

---

### Objects & Prototypes

105. What are the possible ways to create objects in JavaScript?
106. In JavaScript, how many different methods can you use to create an object?
107. What is a prototype chain?
108. What are object prototypes?
109. What is the purpose of using `Object.is` method?
110. How do you determine if two values are the same using Object?
111. How do you copy properties from one object to another?
112. What are the applications of the `assign` method?
113. What is a proxy object?
114. What is the purpose of the `seal` method?
115. What are the applications of the `seal` method?
116. What are the differences between the `freeze` and `seal` methods?
117. How do you determine if an object is sealed or not?
118. What is the `freeze` method?
119. What is the purpose of the `freeze` method?
120. Why do I need to use the `freeze` method?
121. What is the difference between `const` and `Object.freeze`?
122. How do you determine whether an object is frozen or not?
123. What are the different ways to make an object non-extensible?
124. How do you prevent an object from being extended?
125. How do you check whether an object can be extended or not?
126. How do you define multiple properties on an object?
127. How do you get enumerable key and value pairs?
128. What is the main difference between `Object.values` and `Object.entries` method?
129. How can you get the list of keys of any object?
130. How do you create an object with a prototype?
131. How do you list all properties of an object?
132. How do you get property descriptors of an object?
133. What are the attributes provided by a property descriptor?
134. What are JavaScript accessors?
135. How do you define property on Object constructor?
136. What is the difference between `get` and `defineProperty`?
137. What are the advantages of Getters and Setters?
138. Can I add getters and setters using `defineProperty` method?
139. What is Object Destructuring?
140. What are default values in destructuring assignment?
141. How do you swap variables in destructuring assignment?
142. What is destructuring aliases?
143. What is destructuring assignment?
144. What are enhanced object literals?
145. How do you check if a key exists in an object?
146. How do you loop through or enumerate a JavaScript object?
147. How do you test for an empty object?
148. What is a WeakSet?
149. What are the differences between WeakSet and Set?
150. List down the collection of methods available on WeakSet.
151. Explain WeakSet in JavaScript.
152. What is a WeakMap?
153. What are the differences between WeakMap and Map?
154. List down the collection of methods available on WeakMap.
155. Explain WeakMap in JavaScript.
156. How do you compare Object and Map?
157. What is the difference between prototypal and classical inheritance?
158. Do all objects have prototypes?
159. How do you get the prototype of an object?
160. What happens if I pass a string type for `getPrototypeOf` method?
161. How do you set the prototype of one object to another?
162. What is the difference between `__proto__` and `prototype`?
163. How do you extend classes?
164. What do you mean by the prototype design pattern?
165. Does JavaScript allow multiple inheritance?

---

### Closures & Execution Context

166. What are closures?
167. Explain Closures in JavaScript.
168. How to explain closures in JavaScript and when to use it?
169. Can closures leak memory?
170. What are the uses of closures?
171. What is global execution context?
172. What is function execution context?
173. What are the phases of execution context?
174. What is module pattern?

---

### Classes & OOP

175. What are classes in ES6?
176. What are classes in JavaScript?
177. What is a constructor method?
178. What happens if you write constructor more than once in a class?
179. How do you call the constructor of a parent class?
180. How do you define instance and non-instance properties?
181. What is an object initializer?
182. What do you mean by JavaScript Design Patterns?
183. What are the event phases of a browser?
184. What is the difference between `==` and `===` operators?
185. What is the difference between `==` and `===` in JavaScript?

---

### The `this` Keyword

186. What is the `this` keyword in JavaScript?
187. Explain the `this` keyword.
188. What is the `this` keyword, and how does the call-site affect it?
189. What is the purpose of the `this` keyword in JavaScript?
190. What is the difference between `call`, `apply`, and `bind`?
191. What is the difference between `call()` and `apply()` methods?
192. How do `call`, `apply`, and `bind` change `this`?
193. Explain `call()`, `apply()`, and `bind()` methods.
194. How do you create your own `bind` method using either `call` or `apply` method?

---

### Strict Mode

195. What is a strict mode in JavaScript?
196. Why do you need strict mode?
197. How do you declare strict mode?
198. What is the 'Strict' mode in JavaScript and how can it be enabled?
199. What do you mean by strict mode in JavaScript and what are its characteristics?
200. What are the list of cases error thrown from non-strict mode to strict mode?
201. Is that possible to use expressions in switch cases?

---

### Asynchronous JavaScript

202. What is a callback function?
203. What are callbacks?
204. Why do we need callbacks?
205. Why do we use callbacks?
206. What is a callback hell?
207. What is callback in callback?
208. What is a promise?
209. Explain the concept of promises and how they work.
210. Why do you need a promise?
211. What is the use of promises in JavaScript?
212. Explain the three states of promise.
213. What are the main rules of promise?
214. What is promise chaining?
215. What is `Promise.all`?
216. What is the purpose of the `race` method in promise?
217. What are the pros and cons of promises over callbacks?
218. How do you prevent promises swallowing errors?
219. What is the easiest way to ignore promise errors?
220. How do you check if an object is a promise or not?
221. What is an async function?
222. How to use `await` outside of async function prior to ES2022?
223. What is the difference between Async/Await and Generators when used to achieve the same functionality?
224. What are server-sent events?
225. How do you receive server-sent event notifications?
226. How do you check browser support for server-sent events?
227. What are the events available for server sent events?
228. What is the event loop?
229. What is the call stack?
230. What is the event queue?
231. What are tasks in event loop?
232. What is a microtask?
233. What are different event loops?
234. What is the purpose of `queueMicrotask`?
235. What is a microTask queue?
236. What is an event table?
237. What is heap?
238. Explain microtasks vs macrotasks with a real example.
239. How does the JavaScript event loop work?
240. What is minimum timeout throttling?
241. How do you implement zero timeout in modern browsers?
242. What is debouncing?
243. What is throttling?
244. What are debouncing and throttling? Write a debounce function.

---

### ES6+ Modern JavaScript

245. What is ES6?
246. List down some of the features of ES6.
247. What's new in ECMAScript 2025 (ES2025)?
248. What is ECMAScript?
249. What are template literals?
250. What is a template literal in JavaScript?
251. What are template literals and when do you use them?
252. How do you write multi-line strings in template literals?
253. What are nesting templates?
254. What are tagged templates?
255. What are raw strings?
256. What are dynamic imports?
257. What are the use cases for dynamic imports?
258. What are typed arrays?
259. What are TypedArrays and when would you use them?
260. What are the advantages of module loaders?
261. What are modules?
262. Why do you need modules?
263. What are JavaScript modules, and how do you import/export them?
264. What is module scope in JavaScript?
265. What are ES modules? Explain default vs named exports.
266. What is for...of statement?
267. What are the differences between `for...of` and `for...in` statements?
268. What are the built-in iterables?
269. What is an Iterator?
270. How does synchronous iteration work?
271. What is an observable?
272. What are the differences between promises and observables?
273. What are the common use cases of observables?
274. What is RxJS?
275. What are the array mutation methods?
276. What is optional chaining?
277. What is nullish coalescing operator (`??`)?
278. What is globalThis, and what is the importance of it?
279. What is collation?
280. What is tree shaking?
281. What is the need of tree shaking?
282. What is a polyfill?
283. What is the difference between shim and polyfill?
284. What is Babel?
285. What is TypeScript?
286. What are the differences between JavaScript and TypeScript?
287. What are the advantages of TypeScript over JavaScript?
288. How do you use JavaScript libraries in TypeScript file?
289. What is Deno?
290. What is Node.js?
291. Is Node.js completely single threaded?
292. What is the MEAN stack?

---

### DOM, BOM & Browser APIs

293. What is the DOM?
294. What are events?
295. What is an event flow?
296. What is event capturing?
297. What is event bubbling?
298. What are event bubbling, capturing, and delegation?
299. What is an event delegation?
300. What is event delegation and why does it matter?
301. Why is it important to remove event listeners after use?
302. What is BOM?
303. What is the difference between `window` and `document`?
304. What are the different methods to find HTML elements in DOM?
305. How many ways can an HTML element be accessed in JavaScript code?
306. What are the tools or techniques used for debugging JavaScript code?
307. What is a debugger statement?
308. Why do we use the word "debugger" in JavaScript?
309. What is the purpose of breakpoints in debugging?
310. How do you change the style of a HTML element?
311. How do you access history in JavaScript?
312. How do you detect caps lock key turned on or not?
313. What is the purpose of `clearTimeout` method?
314. What is the purpose of `clearInterval` method?
315. What is the use of `setTimeout`?
316. What is the use of `setInterval`?
317. Explain the working of timers in JavaScript and explain the drawbacks of using the timer, if any.
318. How do you redirect to a new page in JavaScript?
319. How do you get the current URL with JavaScript?
320. What are the various URL properties of location object?
321. How do you get query string values in JavaScript?
322. How do you decode or encode a URL in JavaScript?
323. How do you encode a URL?
324. How do you decode a URL?
325. How do you submit a form using JavaScript?
326. How to submit a form using JavaScript?
327. How do you perform form validation using JavaScript?
328. How do you perform form validation without JavaScript?
329. What are the DOM methods available for constraint validation?
330. What are the available constraint validation DOM properties?
331. What are the validity properties?
332. Give an example usage of the `rangeOverflow` property.
333. What is the use of `preventDefault` method?
334. What is the use of `stopPropagation` method?
335. What are the steps involved in `return false` usage?
336. How do you detect a browser language preference?
337. How do you detect a mobile browser?
338. How do you detect a mobile browser without regexp?
339. How do you detect if JavaScript is disabled on the page?
340. How to detect system dark mode in JavaScript?
341. How do you find operating system details?
342. Explain how to detect the operating system on the client machine?
343. What are the properties used to get size of window?
344. How do you get the image width and height using JS?
345. What is the purpose of `requestAnimationFrame` method?
346. What is the `Intl` object?
347. What are the properties of the `Intl` object?
348. How do you perform language specific date and time formatting?
349. What are the types of Pop up boxes available in JavaScript?

---

### Web Storage, Cookies & Workers

350. What is web storage?
351. How do you access web storage?
352. What are the methods available on session storage?
353. What is a storage event and its event handler?
354. Why do you need web storage?
355. How do you check web storage browser support?
356. What is the main difference between `localStorage` and `sessionStorage`?
357. What are the differences between cookie, local storage and session storage?
358. What is the difference between `localStorage`, `sessionStorage`, and cookies?
359. What is a Cookie?
360. Why do you need a Cookie?
361. What are the options in a cookie?
362. How do you delete a cookie?
363. What is a post message?
364. Is PostMessage secure?
365. What are the problems with `postMessage` target origin as wildcard?
366. How do you avoid receiving postMessages from attackers?
367. Can I avoid using postMessages completely?
368. Is postMessages synchronous?
369. What is a service worker?
370. How do you manipulate DOM using a service worker?
371. How do you reuse information across service worker restarts?
372. How do you check web workers browser support?
373. Give an example of a web worker.
374. What are the restrictions of web workers on DOM?
375. What is IndexedDB?
376. What are PWAs?

---

### Performance & Optimization

377. What is garbage collection in V8 (mark-and-sweep)?
378. What are the optimization techniques of V8 engine?
379. What are hidden classes?
380. What is inline caching?
381. What are "deopts" and what causes them?
382. What causes memory leaks in JS apps? How do you detect them?
383. What are the possible reasons for memory leaks?
384. What is the difference between reflow and repaint?
385. How do you prevent expensive reflows and repaints?
386. What is the purpose of double tilde (`~~`) operator?
387. What are the different ways to execute external scripts?
388. What is the role of deferred scripts in JavaScript?
389. What are some advantages of using External JavaScript?
390. Mention some advantages of JavaScript.
391. What are various operators supported by JavaScript?
392. What are the bitwise operators available in JavaScript?
393. Is JavaScript faster than server side script?

---

### Regular Expressions, Errors & Miscellaneous

394. What is a Regular Expression?
395. What are the string methods that accept Regular expression?
396. What are modifiers in regular expression?
397. What are regular expression patterns?
398. What is a RegExp object?
399. How do you search a string for a pattern?
400. What is the purpose of `exec` method?
401. What is the difference between `exec()` and `test()` methods in JavaScript?
402. What is an error object?
403. When do you get a syntax error?
404. What are the different error names from error object?
405. What are the various statements in error handling?
406. How do you handle errors in JavaScript? Explain `try/catch/finally` and custom errors.
407. What is the purpose of Error object?
408. What is the purpose of EvalError object?
409. What is same-origin policy?
410. What is AJAX?
411. What are the different ways to deal with Asynchronous Code?
412. How to cancel a fetch request?
413. What is web speech API?
414. What is jQuery?
415. What is V8 JavaScript engine?
416. What paradigm is JavaScript?
417. What is the difference between internal and external JavaScript?
418. What is the difference between native, host and user objects?
419. What is the difference between document `load` and `DOMContentLoaded` events?
420. Is JavaScript a compiled or interpreted language?
421. Is JavaScript a case-sensitive language?
422. Is there any relation between Java and JavaScript?
423. Who created JavaScript?
424. What are the two types of loops in JavaScript?
425. What is the purpose of switch-case?
426. What are the conventions to be followed for the usage of switch case?
427. What are break and continue statements?
428. What are JS labels?
429. What are the benefits of keeping declarations at the top?
430. What are the benefits of initializing variables?
431. What are the recommendations to create new objects?
432. What is an app shell model?
433. How would you design a concurrency limiter for async tasks?
434. What is the distinction between client-side and server-side JavaScript?
435. What is the difference between ViewState and SessionState?

---

### Strings, Arrays & Date Utilities

436. What is the purpose of the array `slice` method?
437. What is the purpose of the array `splice` method?
438. What is the difference between `slice` and `splice`?
439. What is the purpose of some method in arrays?
440. How do you combine two or more arrays?
441. How do you check whether or not an array includes a particular value?
442. How do you compare scalar arrays?
443. How do you empty an array?
444. How do you get unique values of an array?
445. How do you remove falsy values from an array?
446. How do you map the array values without using `map` method?
447. How do you flatten multi dimensional arrays?
448. What is the easiest way to resize an array?
449. How do you create an array with some data?
450. How do you sort elements in an array?
451. What is the purpose of `compareFunction` while sorting arrays?
452. How do you reverse an array?
453. How do you reverse an array without modifying the original array?
454. How do you find the min and max values in an array?
455. How do you find the min and max values without Math functions?
456. What are the array mutation methods?
457. How do you create polyfills for `map`, `filter` and `reduce` methods?
458. What is the difference between `map` and `forEach` functions?
459. What is the difference between `map()` and `forEach()`?
460. What is the difference between dense and sparse arrays?
461. What are the different ways to create sparse arrays?
462. What is the purpose of some method in arrays?
463. What is ArrayBuffer?
464. What are typed arrays?
465. How do you trim a string in JavaScript?
466. How do you trim a string at the beginning or ending?
467. How do you make the first letter of the string in uppercase?
468. How to convert a string to title case with JavaScript?
469. How do you check whether a string contains a substring?
470. How do you check if a string starts with another string?
471. How do you validate an email in JavaScript?
472. How do you define multiline strings?
473. How do you create specific number of copies of a string?
474. How do you return all matching strings against a regular expression?
475. What is the difference between `substring` and `substr` methods?
476. Which method is used to retrieve a character from a certain index?
477. How to remove all line breaks from a string?
478. How do you display the current date in JavaScript?
479. How do you compare two date objects?
480. How do you convert date to another timezone in JavaScript?
481. How do you get the timezone offset of a date object?
482. How do you generate random integers?
483. Can you write a random integers function to print integers within a range?
484. How do you round numbers to certain decimals?
485. How do you print numbers with commas as thousand separators?
486. What is the easiest way to convert an array to an object?
487. How do you add a key value pair in JavaScript?
488. How do you assign default values to variables?
489. Is the `!--` notation a special operator?

---

### Console, Debugging & Utility

490. What are the placeholders from console object?
491. Is it possible to add CSS to console messages?
492. How do you style the console output using CSS?
493. What is the purpose of `dir` method of console object?
494. Is it possible to debug HTML elements in console?
495. How do you display data in a tabular format using console object?
496. How do you group and nest console output?
497. What is the shortcut to get a timestamp?
498. What is the easiest multi condition checking?
499. How do you capture the browser back button?
500. How do you disable right click in the web page?
501. How do you get the status of a checkbox?
502. How do you create a copy to clipboard button?
503. How do you load CSS and JS files dynamically?
504. How do you verify that an argument is a Number or not?
505. How do you create a custom HTML element?
506. What is the purpose of `JSON.stringify`?
507. How do you parse a JSON string?
508. What is JSON and its common operations?
509. What is JSON?
510. What are the syntax rules of JSON?
511. Why do you need JSON?
512. How do you define JSON arrays?
513. What are enums available in JavaScript?
514. What is an enum?
515. What is an empty statement and purpose of it?
516. How do you get the metadata of a module?
517. What is the purpose of `uneval`?
518. What is the difference between `uneval` and `eval`?
519. Can I use reserved words as identifiers?
520. Does JavaScript support namespaces?
521. How do you declare a namespace?
522. How do you invoke JavaScript code in an iframe from the parent page?

---

### Deep Copy, Proxy, Reflection & Advanced APIs

523. What is the difference between Shallow and Deep copy?
524. What is `structuredClone` and how is it used for deep copying objects?
525. How does structured clone differ from JSON serialization?
526. What is pass by value and pass by reference?
527. Explain passed by value and passed by reference.
528. What are the real world use cases of proxy?
529. What is a decorator?
530. Give an example of statements affected by automatic semicolon insertion.
531. Does JavaScript use mixins?
532. Give a mixin example using Object composition.
533. What are the benefits of mixins?
534. What is obfuscation in JavaScript?
535. Why do you need Obfuscation?
536. What is Minification?
537. What are the advantages of minification?
538. What are the differences between obfuscation and Encryption?
539. What are the common tools used for minification?
540. What is the purpose of `queueMicrotask`?
541. How do you make an object iterable in JavaScript?
542. What is the purpose of the `delete` operator?
543. How to delete property-specific values?
544. What is a conditional operator in JavaScript?
545. Can you apply chaining on conditional operator?
546. What are the ways to execute JavaScript after a page load?
547. Can you give an example of when you really need a semicolon?
548. What is the difference between a parameter and an argument?
549. Explain how to read and write a file using JavaScript?
550. What is the purpose of the following JavaScript code? (`var scope = "global scope"` with nested function returning lexical scope)
551. Write a JavaScript code for adding new elements dynamically.
552. What will be logged by this code? `for (let i = 0; i < 3; i++) { setTimeout(() => console.log(i), i * 100); }`
553. What's the return-value difference between `x++` and `++x`?
554. Is it possible to break JavaScript code into several lines?

---

## Part 2 — Coding / Output-Based Questions

1. What is the output of below code? (`new Vehicle("Honda", "white", "2010", "UK")`)
2. What is the output of below code? (`let x = (y = 0); x++; y++`)
3. What is the output of below code? (`main()` with `setTimeout` and two `console.log`)
4. What is the output of the equality check? (`console.log(0.1 + 0.2 === 0.3)`)
5. What is the output of below code? (`var y = 1; if (function f() {}) { y += typeof f; }`)
6. What is the output of below code? (`function foo() { return; { message: "Hello World" } }`)
7. What is the output of below code? (`delete myChars[0]` on array)
8. What is the output of below code in latest Chrome? (`new Array(3)`, sparse arrays)
9. What is the output of below code? (object with `prop2()` and `["prop" + 3]()` methods)
10. What is the output of below code? (`console.log(1 < 2 < 3); console.log(3 > 2 > 1)`)
11. What is the output of below code in non-strict mode? (`function printNumbers(first, second, first)`)
12. What is the output of below code? (`const printNumbersArrow = (first, second, first) => {}`)
13. What is the output of below code? (`const arrowFunc = () => arguments.length`)
14. What is the output of below code? (`String.prototype.trimLeft.name === "trimStart"`)
15. What is the output of below code? (`console.log(Math.max())`)
16. What is the output of below code? (`console.log(10 == [10]); console.log(10 == [[[[[[[10]]]]]]])`)
17. What is the output of below code? (`console.log(10 + "10"); console.log(10 - "10")`)
18. What is the output of below code? (`console.log([0] == false); if ([0]) {...}`)
19. What is the output of below code? (`console.log([1, 2] + [3, 4])`)
20. What is the output of below code? (`new Set([1,1,2,3,4])` and `new Set("Firefox")`)
21. What is the output of below code? (`console.log(NaN === NaN)`)
22. What is the output of below code? (`numbers.indexOf(NaN)`)
23. What is the output of below code? (`let [a, ...b, c] = [1, 2, 3, 4, 5]`)
24. What is the output of below code? (`const arr = [1, 2, 3]; arr[10] = 99; console.log(arr.length)`)
25. What is the output of below code? (`let x = 0; console.log(x++); console.log(++x)`)
26. What is the output of below code? (`const a = [1,2,3]; const b = [1,2,3]; console.log(a == b, a === b)`)
27. What is the output of below code? (`async function func() { return 10; }`)
28. What is the output of below code? (`async function func() { await 10; }`)
29. What is the output of below code? (`processArray` using `forEach` with `await`)
30. What is the output of below code? (`process` using `async forEach` with `"Process completed!"`)
31. What is the output of below code? (`new Set().add("+0").add("-0").add(NaN).add(undefined).add(NaN)`)
32. What is the output of below code? (`Symbol("one") === Symbol("one")` and `Symbol.for("two") === Symbol.for("two")`)
33. What is the output of below code? (`const sym1 = new Symbol("one")`)
34. What is the output of below code? (`!typeof myNumber === "string"`)
35. What is the output of below code? (`JSON.stringify` with `undefined`, functions, and Symbols)
36. What is the output of below code? (`new.target.name` in class inheritance)
37. What is the output of below code? (`const [x, ...y, z] = [1, 2, 3, 4]`)
38. What is the output of below code? (`const { a: x = 10, b: y = 20 } = { a: 30 }`)
39. What is the output of below code? (`function area({ length = 10, width = 20 })` called without args)
40. What is the output of below code? (nested destructuring `[, , { name }] = props`)
41. What is the output of below code? (`checkType(num = 1)` called with `undefined`, `""`, `null`)
42. What is the output of below code? (`function add(item, items = [])` called twice)
43. What is the output of below code? (`greet("Hello", "John")` with `message = greeting + " " + name` default)
44. What is the output of below code? (`function outer(f = inner())` where `inner` is declared inside)
45. What is the output of below code? (`function myFun(x, y, ...manyMoreArgs)`)
46. What is the output of below code? (`const obj = { key: "value" }; const array = [...obj]`)
47. What is the output of below code? (`var myGenObj = new myGenFunc()`)
48. What is the output of below code? (generator with `yield 1; return 2; yield 3`)
49. What is the output of below code? (generator with `for...of` and `break`, reused)
50. What is the output of below code? (`const num = 0o38`)
51. What is the output of below code? (`new Square(10)` used before class declaration)
52. What is the output of below code? (`walk` and `run` called without object context)
53. What is the output of below code? (`Car extends Vehicle` where `Car.start()` calls `super.start()`)
54. What is the output of below code? (`const USER = { age: 30 }; USER.age = 25`)
55. What is the output of below code? (`console.log("🙂" === "🙂")`)
56. What is the output of below code? (`console.log(typeof typeof typeof true)`)
57. What is the output of below code? (`let zero = new Number(0); if (zero) {...}`)
58. What is the output of below code in non-strict mode? (`msg.name = "John"` on a string primitive)
59. What is the output of below code? (closure with outer `let count = 10` and inner `let count = 11`)
60. What is the output of below code? (`true && 'hi'`, `true && 'hi' && 1`, `true && '' && 0`)
61. What is the output of below code? (`let arr = [1,2,3]; let str = "1,2,3"; console.log(arr == str)`)
62. What is the output of below code? (`getMessage()` called before arrow function assignment)
63. What is the output of below code? (`quickPromise.then(...)` vs `console.log("program finished")`)
64. What is the output of below code? (`console.log("First line")` chained with array forEach and `"Third line"`)
65. Write a function that returns a random HEX color.
66. What is the output of below code? (`var of = ["of"]; for (var of of of) {...}`)
67. What is the output of below code? (`[11, 25, 31, 23, 33, 18, 200].sort()`)
68. What is the output order of below code? (`setTimeout`, `Promise.resolve`, `console.log("3")`)
69. What is the output of below code? (`console.log(name)` before IIFE `(function message() {})`)
70. What is the output of below code? (`message()` with two same-name function declarations)
71. What is the output of below code? (`changeCurrentCity` function with `var` hoisting)
72. What is the output of below code in order? (nested `second()`, `first()`, global `message`)
73. What is the output of below code? (`var expressionOne = function functionOne() {}; functionOne()`)
74. What is the output of below code? (`user.eat()` with inner `eatFruit` using regular function and `this`)
75. What is the output of below code? (string immutability — `message[0] = "J"` vs string reassignment)
76. What is the output of below code? (`user1 === user2` with two identical objects)
77. What is the output of below code? (`setTimeout` closure capturing `const message` declared after it)
78. What is the output of below code? (`const a = new Number(10); const b = 10; console.log(a === b)`)
79. What is the type of below function? (`function add(a, b) { console.log(...); return a + b; }`)
80. What is the output of below code? (`Promise.all` with one resolve and one reject)
81. What is the output of below code? (`try { setTimeout(() => { throw new Error(...) }) } catch(err) {}`)
82. What is the output of below code? (`let a = 10; if (true) { let a = 20; ... }`)
83. What is the output of below code? (`arr.length = 0` on a non-empty array)
84. How do you verify two strings are anagrams or not?
85. What is the output of below code? (`printHello()` and `printMessage()` with nested function hoisting)
86. What is the time taken to execute below timeout callback? (`setTimeout` with 5s delay inside a 10s while loop)
87. What is the output of below code? (`["wöchentlich", "Woche", "wäre", "Wann"].sort()`)
88. What is the output of below code? (`func(undefined)` vs `func()` with default param + `arguments.length`)
89. What is the output of below code? (`numbers.reduce` counting odd values + IIFE using XOR bit shifting)
90. What will be the result of this expression? (`null ?? 'default'`, `undefined ?? 'default'`, `false ?? 'default'`)
91. What would be the result of `3 + 2 + "7"`?
92. What would be the result of `1 + 2 + '3'`?
