---
layout: post
title: 如何在命令行打印一颗漂亮的二叉树？
---

## 为什么想要写这样一个东西
我在写一个leetcode的个人测试框架，所有框架代码及我每道leetcode的解答在[这里](https://github.com/CurryPseudo/LeetCode)。 

我每写一道新的题目，会加入自己的测试用例，测试框架会漂亮地打印出结果是多少，是否正确。这可以极大地提高我刷题的效率。  

在我刷到[LeetCode94-二叉树的中序遍历](https://leetcode-cn.com/problems/binary-tree-inorder-traversal/)时，我发现我很喜欢leetcode网站给出二叉树样例（中间的树状形式）的方式：  

>输入: [1,null,2,3]  
><pre>
>   1
>    \
>     2
>    /
>   3
></pre>
>输出: [1,3,2]  

我想用这种方式来打印我测试用例的输入与输出中的二叉树，并且使其结点值支持所有类型。

