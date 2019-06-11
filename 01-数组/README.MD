# 找出数组中的最大值，用 apply 实现？

## 1. 用 apply 实现：
```
let arr = [1, 34, 45, 2, 100]
let max = Math.max.apply(null, arr)

console.log(max) // 100
```

## 2. 用展开运算符实现：
```
let arr = [1, 34, 45, 2, 100]
let max = Math.max(...arr)

console.log(max) // 100
```