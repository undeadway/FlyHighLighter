# FlyHighLighter

## Chinese

### 关于
纯JS 打造同于将代码输出成网页格式的代码高亮器。  

### 支持的语言列表

* C
* C++
* CSS
* HTML
* JAVA
* JAVASCRIPT
* JSON
* PHP
* SQL
* VB
* VBA
* VBSCRIPT
* VB.NET
* XML

### 安装
#### Node.js
在Node.js中，只需要执行`npm install flyhighlighter`即可。

#### 浏览器
只需要将`dist`文件夹下已编译好的`FlyHighLighter.js`复制到项目中去即可。  
`FlyHighLighter`依赖`Coralian`，所以请一并复制`coralian.js`。

### 使用
在项目中导入`FlyHighLighter.js`和`coralian.js`。  
然后可以通过下面的代码来使用 `FlyHighLighter`
```
var source = "var source = 'test code'";
var langName = "javascript";
var output = FlyHighLighter.execute(source, langName);
```
执行完毕后的`output`即最终可以直接显示的HTML。

## English

### About
A source code highlighter created by pure javascript.

### Supported languages list
* C
* C++
* CSS
* HTML
* JAVA
* JAVASCRIPT
* JSON
* PHP
* SQL
* VB
* VBA
* VBSCRIPT
* VB.NET
* XML

### Install
#### Node.js
It just to run the `npm install flyhighlighter` command on node.js side.
#### Browser
Copy the compired file `FlyHighLighter` to client.  
And `FlyHighLighter` has relied by `Coralian`, so also copy the file `coralian.js` to client.

### Using
```
var source = "var source = 'test code'";
var langName = "javascript";
var output = FlyHighLighter.execute(source, langName);
```