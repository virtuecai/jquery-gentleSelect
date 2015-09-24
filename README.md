# 更新支持bootstrap/性能体验优化, 修复部分bug, 请使用trunk代码

# jQuery plugin: gentleSelect

gentleSelect is a jQuery plugin for transfoming select boxes into
a skinnable alternative. The selection list can be rendered with
multiple columns/rows to present larger datasets in a more 
manageable format.


There is much to be done on the flexibility and robustness front, 
and we welcome contributions and bug fixes. Feel free to fork 
and send us pull requests!


## Usage

To use this plugin, one simply needs to load jQuery and the 
JS/CSS scripts for gentleSelect, then attach it to your
select boxes on DOM ready:

    <link type="text/css" src="dist/jquery-gentleSelect.min.css" />
    <script type="text/javascript" src="libs/jquery.min.js"></script>
    <script type="text/javascript" src="dist/jquery-gentleSelect.min.js"></script>
    <script type="text/javascript">
    $(document).ready(function() {
        $('select').gentleSelect();
    });
    </script>

For more options, see the [gentleSelect website].


## Others

Copyright (c) 2010, Shawn Chin.

This project is licensed under the [MIT license].


 [gentleSelect website]: http://shawnchin.github.com/jquery-gentleSelect "gentleSelect Website"
 [MIT License]: http://www.opensource.org/licenses/mit-license.php "MIT License"
