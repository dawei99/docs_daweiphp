$project
========

$project will solve your problem of where to start with documentation,
by providing a basic explanation of how to do it easily.

Look how easy it is to use:

    import project
    # Get your stuff done
    project.do_stuff()

Features
--------

- Be awesome
- Make things faster

Installation
------------

Install $project by running:

    install project

Contribute
----------

- Issue Tracker: github.com/$project/$project/issues
- Source Code: github.com/$project/$project

Support
-------

If you are having issues, please let us know.
We have a mailing list located at: project@google-groups.com

License
-------

The project is licensed under the BSD license.

段落
####

普通的文本段落之间，还有块级元素之间，必须使用一个空行加以区分，否则会被
reStructuredText 折叠到上一行。

第二个段落，与上一段落分开了。

第三个段落，这个段落我换行但不空行，你将看到这个段落没有换行。
这是因为最初创建 reStructuredText
这个项目是为了写代码文档，而程序员都习惯硬换行，而为了区隔英语单词，
折叠上去的每一行前都加了一个空格。
如果希望硬断行且不自动添加空格（例如中文文章），在行尾添加一个反斜杠。\
折上去的部分就不会有空格。注意所有的硬换行都要对齐缩进。\

| 第四个段落，段内的换行。
| 用竖线和空格开头，之后的每一行
| 在渲染时都会单独成行。
| 这功能不常用，因为用列表会更美观。

看不懂也没关系，你只要记住一个段落就一直往下写，新段按两下回车。
