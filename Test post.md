---
title: "Test post"
date: "2025-01-01"
tags: ["intro"]
summary: "Summary post"
published: true
---

## In javascript everything is not an object
In javascript variables doesn't have types, values do.

### Primitive types
```javascript
console.log(typeof 42);              // "number"
console.log(typeof 'Hello');         // "string"
console.log(typeof true);            // "boolean"
console.log(typeof undefined);       // "undefined"
console.log(typeof Symbol('id'));    // "symbol"
console.log(typeof BigInt(123456));  // "bigint"
```
### Objects
```javascript
console.log(typeof {});              // "object"
console.log(typeof []);              // "object"
console.log(typeof null);            // "object"
console.log(typeof new Date());      // "object"
console.log(typeof new Map());       // "object"
console.log(typeof new Set());       // "object"
console.log(typeof /abc/);           // "object"
```
### Function
```javascript
console.log(typeof function() {});   // "function"
console.log(typeof (() => {}));      // "function"
console.log(typeof class MyClass {}); // "function"
```
### Another
```javascript
console.log(typeof NaN);             // "number"
console.log(typeof Infinity);        // "number"
console.log(typeof Math);            // "object"
console.log(typeof JSON);            // "object"
console.log(typeof console.log);     // "function"
```
