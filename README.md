Hi, all, 这是我根据 DlHighlight 的源代慢慢修改的一个代码高亮的项目。主要提供wordpress 代码高亮插件，普通的网页代码高亮方法和各种代码高亮配色方案。

###Usage
1.  引用 ColorCode.js
2.  通过下面的方法调用显示你要高亮的 html 代码:

    <script type="text/javascript">
        window.onload = function() {
            DlHighlight.HELPERS.highlightByName('colorcode', 'pre', '', false );
        }
    </script>

3. HTML 代码需要显示的地方加上 pre 标签

    <pre name="ColorCode" class="css">
        .colorcode {
            font-size: 12px;
            color: #fefefe;
        }
    </pre>

###Change Log

* Project Create:          2011-11-29
* Wordpress Plugin:        2011-12-06
* Change Project File:     2011-12-07
* Add HTML Style :         2011-12-20

###Project Tree

    |--ColorCode
        |--wp-colorcode //wordpress plugin's php files
            |--colorcode.php
            |--colorcode_amdin.php
        |--html-colorcode //html demo
        |--css //base css , four color themes
            |--knight.css
            |--moonfang.css
            |--nortrom.css
            |--yurnero.css
        |--js //base js


###Contact Me

* website: www.pizn.net or www.pizn.me
* email: pizner@gmail.com
