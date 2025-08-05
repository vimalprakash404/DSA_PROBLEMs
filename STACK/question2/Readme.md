# 🧩 Min Stack

## Problem Statement

Design a stack that supports the following operations in constant time:
- `push(x)`: Push element x onto stack.
- `pop()`: Removes the element on top of the stack.
- `top()`: Get the top element.
- `getMin()`: Retrieve the minimum element in the stack.

---

### Example

```js
stack.push(-2)
stack.push(0)
stack.push(-3)
stack.getMin() // -3
stack.pop()
stack.top()    // 0
stack.getMin() // -2
```