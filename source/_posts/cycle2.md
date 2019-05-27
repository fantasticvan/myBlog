---
title: Cycle 2
---
- 1、 `for..in..`依次把list或tuple中的每个元素迭代出来
```
sum = 0
for x in [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]:
    sum = sum + x
print(sum)

```
- 2、`while`
```
sum = 0
n = 99
while n > 0:
    sum = sum + n
    n = n - 2
print(sum)
```

- 3、其他关键字
```
1) break 退出循环
2) continue 跳过当前的这次循环，直接开始下一次循环。
```