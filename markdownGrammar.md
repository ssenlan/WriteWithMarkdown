# Markdown基本语法

> 在使用Markdown之前你需要了解一下关于markdown的基本语法

## 1.标题 ##

+ 使用 `#` 表示标题，一级标题使用一个 `#` ，二级标题使用两个 `##` ，以此类推，共有六级标题。
+ 使用 `=====` 表示高阶标题，使用 `--------` 表示次阶标题。

1\. `#`和标题之间加一个空格，因为有时候不会被识别为标题。

2\. `=====` 和 `-----` 表示标题时，大于等于2个都可以表示。

3\. 通常在标题分级时使用标题标记。

### 示例1 ###

```markdown
# 这是一级标题
## 这是二级标题
### 这是三级标题
###### 这是六级标题
```

# 这是一级标题
## 这是二级标题
### 这是三级标题
###### 这是六级标题

### 示例2 ###

```markdown
这是一级标题
======

这是二级标题
--------------
```

这是一级标题
======

这是二级标题
--------------

## 2.引用 ##

使用 `>` 表示引用，`>>` 表示引用里面嵌套一层引用，以此类推。

1\. 如果 `>` 和 `>` 嵌套使用的话，从 `>>` 退到 `>` 时，必须之间要加一个空格或者 `>` 作为过渡，否则认为下一行和上一行是同一级别的引用。如示例所示。

2\. 引用标记里可以使用其他标记，如：有序列表或无序列表标记，代码标记等。

### 示例 ###

``` markdown
> 这是一级引用
>> 这是二级引用
>>> 这是三级引用

> 这是一级引用
```

> 这是一级引用
> > 这是二级引用
> >
> > > 这是三级引用

> 这是一级引用

## 3. 代码块 ##

使用三个 `` ` 表示代码块。

1\. 这个符号在 `ESC  ` 键下面，切换到英文下即可。

2\. 本文档所有使用讲解Markdown语法标记的地方都是使用代码块标记的。

``` markdown
@sada 
(sdada)
{sdaadadadasigkgkhg}
end
```

## 4.行内代码

使用``` ` 表示行内代码。本页部分文字中间的英文字母就是使用行内代码标记的。

### 示例

``` markdown
这是`javascript`代码
```

## 5.链接

使用` [](link)` 表示行内链接。其中：

* `[]` 内的内容为要添加链接的文字。
* `link` 为链接地址。

### 示例

有问题查[百度](www.baidu.com)，前提是你得会区分广告。

## 6.导入图片

使用` ![图片说明](图片地址)` 导入图片

## 7.粗体和斜体

1\. 使用 `**` 或者 `__` 表示粗体。

2\. 使用 `*` 或者 `_` 表示斜体。

3\. 前后的 `*` 或 `_` 要 __加粗__ 或 _倾斜_ 的字体之间不能有空格。

### 示例

``` markdown
**粗体1**    __粗体2__
*斜体*    _斜体_
```

## 8.列表

使用 `1\. 2\. 3\. ` 表示有序列表，使用 `*` 或 `-` 或 `+` 表示无序列表。

1\. 无序列表或有序列表标记和后面的文字要有一个空格隔开。

2\. 无序列表的项目符号是按照实心圆、空心圆、实心方格的层级关系递进的，如例2所示。通常情况下，同一层级使用同一种标记表示，便于自己查看和管理。

## 9.分割线

使用　`---` 或者 `***` 或者 `* * *` 表示水平分割线。

1\. 只要 `*` 或者 `-` 大于三个就可组成一条水平线。

2\. 使用 `---` 作为水平分割线时，要在它的前后都空一行，防止 `---` 被当成标题标记的表示方式。

### 示例

``` markdown
---

***

* * *
```

---

***

## 10.删除线

使用 `~~` 表示删除线。

注意 `~~` 和要添加删除线的文字之间不能有空格。

### 示例

``` markdown
~~这是一条删除线~~
```

~~这是一条删除线~~

## 参考来源

https://www.jianshu.com/p/357ba401c856