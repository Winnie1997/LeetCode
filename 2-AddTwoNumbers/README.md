## 2. Add Two Numbers 两数相加
给出两个**非空**的链表用来表示两个非负的整数。其中，它们各自的位数是按照 逆序 的方式存储的，并且它们的每个节点只能存储**一位**数字。

如果，我们将这两个数相加起来，则会返回一个新的链表来表示它们的和。

您可以假设除了数字 0 之外，这两个数都不会以 0 开头。

**示例：**

```
输入：(2 -> 4 -> 3) + (5 -> 6 -> 4)
输出：7 -> 0 -> 8
原因：342 + 465 = 807
```

###  C++

- 需要考虑两个链表长度不一样的情况，较短的链表则补0。
- 每一位计算的时候需要考虑进位问题。
- 两个链表结束遍历的时候仍需要考虑进位是否需要添加节点。

