## 记录网页中如何嵌入代码框

##### 功能引用googlearchive/code-prettify
   > github地址：https://github.com/googlearchive/code-prettify
-----
#### 使用方法：
1. 引入script
   > ``<script src="https://cdn.jsdelivr.net/gh/google/code-prettify@master/loader/run_prettify.js"></script> ``

2. html中，使用如下方式引入代码块：
    ```
    <pre class="prettyprint linenums">class HelloWorld{
    public static void main(){
        System.out.println("hello!");
        <a href="#">hello</a>
            }
    }</pre>
    ```
--------------------------------------

### 代码框主题请参考下面的链接：
   > https://raw.githack.com/google/code-prettify/master/styles/index.html

* 打开以上链接后，点击具体主题，引入此主题css样式即可。
