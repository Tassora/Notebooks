# Markdown
## 1. 基础语法
### 1.1 标题
&emsp;&emsp;使用 `#` 来表示标题，`#` 的个数表示标题的等级。
```markdown
# 这是一级标题
## 这是二级标题
### 这是三级标题
```

### 1.2 段落
&emsp;&emsp;直接输入即可达到效果
```markdown
I really like using Markdown.
I really like Python
```

### 1.3 强调
- **斜体**: 用单个星号 `*` 包围文本
- **加粗**: 用两个星号 `**` 包围文本
```markdown
*这是斜体*
**这是加粗**
***又是斜体又是加粗***
```

### 1.4 引用
&emsp;&emsp;使用`>`表示引用，多个引用多个`>`，嵌套引用就连续两个`>`
```markdown
> 引用一句话

> 第一层引用
>> 第二层引用
```
### 1.5 分割线
```markdown
第一句话
***
第二句话
```
### 1.6 列表
- 有序列表
```markdown
1. First item
2. Second iteem
3. Third item
```
- 无序列表
```markdown
- First item
- Second item
- Third item
- - Third First item
- - Third Second item
```
### 1.7 代码块
&emsp;&emsp;三个``` ` ``` + 语言名称
````markdown
  ```Python
  print('hello world')
  ```
````
### 1.8 删除线
&emsp;&emsp;~~前后使用两个```~```~~
```
~~这里的内容会被横线遮挡~~
```
### 1.9 任务清单
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

## 2. 进阶语法
### 2.1 表格
&emsp;&emsp;第二行的冒号的位置，可以控制在哪边对齐
```markdown
|列1|列2|列3|
|:-|:-:|-:|
|内容1|内容2|内容3|
``` 
### 2.2 链接
- 自定义名字的链接效果：[Tassora](https://tassora.github.io/Notebooks/intro.html "点击跳转")
- 网址名字的效果：<https://tassora.github.io/Notebooks/intro.html>
```markdown
[Tassora](https://tassora.github.io/Notebooks/intro.html "点击跳转")
<https://tassora.github.io/Notebooks/intro.html>
```
### 2.3 图片
&emsp;&emsp;语法类似链接
```markdown
![Sora](sora.jpg "sora")
```
### 2.4 脚注
```
这里是注释一[^注释一], 然后是注释二[^注释二].
[^注释一]: 点击右侧返回原来的地方.
[^注释二]: 点击右侧返回原来的地方.
```
### 2.5 设置锚点
&emsp;&emsp;此处暂时使用HTML语法代替
```
(<h5 id="test">)锚点设置</h5>
[跳转到锚点](#test)
```