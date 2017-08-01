主要实现一个评论系统
只实现了发表功能
weibo.html为主页面
weibo.php是用于交互的后端文件
css存放所用到的css文件
js存放所用的js文件
数据库暂无导出
需要运行请自行建立,数据库名称zns_ajax
数据库用户为root 无密码
字段
`ID` INT NOT NULL AUTO_INCREMENT PRIMARY KEY ,
`content` TEXT NOT NULL ,
`time` INT NOT NULL ,
`acc` INT NOT NULL ,
`ref` INT NOT NULL
