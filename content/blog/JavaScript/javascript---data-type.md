---
title: JavaScript - Data type
date: 2020-12-27 10:12:09
category: JavaScript
thumbnail: { thumbnailSrc }
draft: false
---

## Contents 
1. Primitive Type
2. Reference Type
3. Primitive Type vs Reference Type 
4. ES6 Symbol
5. ES6 Map, Set, WeakMap, WeakSet

<br/>

### 1. Primitive Type
- Number 
- String 
- Boolean 
- Null
- Undefined 
- Symbol (ES6)

```
null vs undefined 
undefined: 값을 할당하지 않았을 때의 초기값
null: 개발자가 명시적으로 이 값이 비워져있음을 나타내는 값
```

<br/>

### 2. Reference Type (Object)
- Function
- Array
- RegExp
- Map (ES6)
- Set (ES6)
- WeakMap (ES6)
- WeakSet (ES6)

<br/>

### 3. Primitive Type vs Reference Type
> Primitive Type의 값은 콜스택에 저장되고, Reference Type의 값은 Heap에 저장된다. 
  그렇기 때문에 Primitive Type은 새로운 값이 할당될 때 콜스택의 메모리주소가 변하는 반면 Reference Type은 콜스택의 메모리주소가 변경되지 않는다. (Heap 메모리주소만 변경)

<br/>

| Type | Primitive Type | Reference Type |
| ---- | ---- | ---- |
| 변수선언 | 값이 들어갈 빈 메모리 슬롯을 찾아 메모리주소를 할당 | 값이 들어갈 빈 메모리 슬롯을 찾아 메모리주소를 할당
| 값할당 | 콜스택 메모리주소에 값을 할당 | 힙메모리에 값이 먼저 할당된 후, 콜스택에 힙메모리의 주소 할당 |
| 값변경 | 새로운 메모리주소에 새로운 값 할당 | 콜스택의 메모리주소는 변경되지 않음 |
| 값복사 | 새로운 메모리주소 할당 | 동일한 메모리주소 참조 |

<br/>

### 4. ES6 Symbol
### 5. ES6 Map, Set, WeakMap, WeakSet
