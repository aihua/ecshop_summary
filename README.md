#### ECShop、ECMall相关资料总结

- [ECShop数据表](https://github.com/Richardphp/ecshop_summary/blob/master/_posts/ecshop.sql)
- [ECMall数据表](http://www.360sdn.com/Php/2013/0911/858.html)
- [ECMall的模板解析语法介绍](http://www.nowamagic.net/librarys/veda/detail/1482)
- [ECShop的帮助系统-ECShop后台使用说明](http://help.ecshop.com/index.php)
- [数据导出xls表格](https://github.com/Richardphp/ecshop_summary/blob/master/_posts/export_excel.php)
- [ecshop中ajax的调用原理](http://www.68ecshop.com/article-870.html)
- [欢迎来到ECSHOP知识堂](http://help.ecmoban.com/)
- [Smarty变量调节器的使用](http://blog.csdn.net/chuangrain/article/details/7499680)
- [ECSHOP访问首页一直跳转到安装目录解决方案](https://github.com/Richardphp/ecshop_summary/blob/master/_posts/ecshop_skip_to_install.md)
- [ecshop函数列表大全](http://bbs.ecshop.com/thread-95500-1-1.html) 
- [ecshop全局变量的设置和加载](http://www.360doc.com/content/14/0504/11/9200790_374437952.shtml) 


-------

###ECShop开发随手记

- 在模型里边如果用错getOne/getRow等方法获取数据 处理不当的时候，管理后台页面可能会出现空白 或者服务器无法完成请求的情况 

- 我还发现如果控制器中的sql语句写错，也是会影响整个程序，什么都不显示 

- 写前台控制器 mobile/include/apps/defalut/controller/ 路径，里边数据表前缀：$this->model->pre 才能直接访问到，总共有3中访问方法.还有数据库取数据：$this->model->getRow()

- 访问私有变量用关键字 self::privatefunction() 的方法，用了$this->调了半天