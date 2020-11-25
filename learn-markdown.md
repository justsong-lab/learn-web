# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

---

你好啊！
还是同一行。

不在同一行了。

# Markdown笔记
## 标题
第几级标题就是用几个"#"

例如：二级标题为"##"; 三级标题为"###"。

## 无序列表
- 使用“-” “+” “*”
+ "+"
* "*"

## 有序列表
1. 使用数字+英文点+空格(如，1. /2. /3. )
2. 可以嵌套有序列表
3. 也可以嵌套无序列表
    1. tab 缩进
    2. shift+tab 取消缩进

## 引用
使用'>'+ 引用内容即可

马保国说：
>年轻人不讲武德，不要搞窝里斗，谢谢各位！
>（引用跟段落一样，不会换行，可用空行来换行）
>
>换行了

## 链接
语法："["链接名称"]" "("链接地址")"

例如：[Note of HTML](https://sharlylv.github.io/learn-web/note2.html)
## 图片
语法: ! + "["alt"]" "("图片地址")"

例如：

![my profile photo](https://avatars2.githubusercontent.com/u/47977849?s=460&u=7d90c380a9811bd09bccc3af7c463fe37f96bb02&v=4)

![my profile photo2](https://sharlylv.github.io/learn-web/note2.html)


md文件也可以使用html语言

<img alt="my profile photo" src="https://avatars2.githubusercontent.com/u/47977849?s=460&u=7d90c380a9811bd09bccc3af7c463fe37f96bb02&v=4">


## 复选框
语法: 

"- [x] 待办1 (有x代表已完成)"

"- [ ] 待办2（空格代表未完成）"

- [x] eat
- [ ] sleep

## 字体格式
**bold** (两个*)

__bold__ （两个_）

*i* （一个*）

_i_ （一个_）

## 反引号
tab上面 `表示代码`

## 删除线
左右各两个~

~~删除线~~

**嵌套**

~~哈哈哈**嘿嘿嘿**_嘻嘻嘻_~~

## 代码块
```python
print("hello world")
```
```html
<img alt="my photo" src="/path">
```

## table
### left aligned
|atr1|atr2|
|:----|:----|
|entry1|entry2|
|q|r|

### right aligned
|atr1|atr2|
|----:|----:|
|entry1|entry2|
|q|r|

### center
|atr1|atr2|
|:----:|:----:|
|entry1|entry2|
|q|r|

表格里可以嵌套其他元素 比如列表 图片