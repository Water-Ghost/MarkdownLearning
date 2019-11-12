MarkDown语法简介
=============================

下面是Markdwown的语法概述。  

## 一、标题  

### 1 Setext形式  
代码  
```markdown
H1
===
H2
---
=和-的数量无限制，只支持两级标题。
```  

### 2 atx形式  
代码  
```markdown  
# 一级标题
## 二级标题
###### 6级标题
```  


## 二、强调  
```markdown
斜体、黑体及两者结合
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
```  
`>>>`  
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

## 三、列表  
### 无序列表  
```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```  
`>>>`  
* Item 1
* Item 2
  * Item 2a
  * Item 2b

### 有序列表  
```
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
```
`>>>`  
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

## 四、链接  
```
Markdown format: 
![Alt Text](url)
![logo](/images/logo.png)

Html format:
<img src="url" width="75" hegiht="75" align=center />
```  
`>>>`  
![logo](/images/logo.png)  
<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="75" hegiht="75" align=center />  

## 五、块引用
```
As Kanye West said:

> We're living the future so
> the present is our past.
```  
`>>>`  
As Kanye West said:

> We're living the future so
> the present is our past.
