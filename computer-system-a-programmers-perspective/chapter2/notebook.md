## 问题

## 信息存储

### 字数据大小
- 每台计算机有一字长，指针数据的标称大小。字长决定虚拟地址控件大小0~2^w-1

```
--------------------------------------------
|            c声明             |  字节数   |
--------------------------------------------
|  有符号     |     无符号     |32位 | 64位|
--------------------------------------------
|  char       | unsigned char  |  1  |  1  |
--------------------------------------------
|  short      | unsigned short |  2  |  2  |
--------------------------------------------
|  int        |  unsigned      |  4  |  4  |
--------------------------------------------
|  long       | unsigned long  |  4  |  8  |
--------------------------------------------
| int32_t     | uint32_t       |  4  |  4  |
--------------------------------------------
| int64_t     | uint64_t       |  8  |  8  |
--------------------------------------------
| char *      |                |  4  |  8  |
--------------------------------------------
| float       |                |  4  |  4  |
--------------------------------------------
| double      |                |  8  |  8  |
--------------------------------------------
```

### 寻址和字节顺序

- where is the address, how the multi bytes show

### 表示代码
- 计算机不认识代码，计算机只识别二进制

### 布尔代数简介


## 作业

