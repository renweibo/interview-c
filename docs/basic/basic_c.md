# C 语言基础

# cheat sheet



# 字符串相关：字符串、字符数组、字符串数组

string，array of char，array of strings
## 字符串

- 打印


## 字符串数组 array of strings

- 初始化，展示

```c
#include <stdio.h>

const char * array[] = {
    "First entry",
    "Second entry",
    "Third entry",
};

#define LEN(array) (sizeof (array) / sizeof (const char *))

int main () {
    int i;

    for (i = 0; i < LEN(array); i++) {
        printf ("%d: %s\n", i, array[i]);
    }
    return 0;
}
```

# 实用功能

## 日志相关

## 异常相关

## 网络相关

# 设计模式 与 反模式



# 开发技巧

## 调试相关

## 内存泄漏排查

## 死锁排查
