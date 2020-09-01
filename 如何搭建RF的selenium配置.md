#### 1.导入SeleniumLibrary

```shell
pip installl robotframework-SeleniumLibrary
```
#### 2.新建工程

1.  New Project——选择type为directory，选择format为txt
2. New Suite——选择type为file，选择format为txt
3. 在Suite，新建Test Case

#### 3.导入SeleniumLibrary库
1. 在Suite下的add import下点击library
2. 名称区分大小写

#### 4.安装WebDriver
注意：
- chrome：ChromeDriver
- Fierfox:getodriver
- IE:IEDriverServer

将WebDriver复制python3.7的安装路径根目录下
#### 5.如何使用
- 在case中分别添加格式、地址或定位元素、内容

eg:打开百度
|  操作   | 定位元素  |内容|
|  ----  | ----  | ---- |
| add browser  | https://ww.baidu.com |chrome|
