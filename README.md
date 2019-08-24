
# 一、目的
## 现实中的痛点
  现在周围的人都在做微商，如果每天订单量大的话，大量的时间会花费在给顾客快递单号的事情上。
## 解决问题
    1. 我们在系统录入发货信息：收件人姓名，收件人电话，订单编号
    2. 用户可电话号码查询自己的订单；
    3. 点击订单编号，可跳转到快递详细物流信息页面。(https://q.kuaidi100.cn/auto.php)

# 二、使用的技术
  1. **SpringBoot** ：Spring boot是Spring家族中的一个全新的框架，它用来简化Spring应用程序的创建和开发过程，也可以说Spring boot能简化我们之前采用SpringMVC+Spring+Mybatis框架进行开发的过程。
  2. **Bootstrap-Table**：Bootstrap table是国人开发的一款基于 Bootstrap 的 jQuery 表格插件，通过简单的设置，就可以拥有强大的单选、多选、排序、分页，以及编辑、导出、过滤（扩展）等等的功能。
  3. **Mysql**：MySQL是一个轻量级关系型数据库管理系统，由瑞典MySQL AB公司开发，目前属于Oracle公司。 MySQL是一个关系型数据库管理系统，MySQL是一种关联数据库管理系统，关联数据库将数据保存在不同的表中，而不是将所有数据放在一个大仓库内，就增加了速度并提高了灵活性。
  4. **jQuery**：jQuery是一个开源免费的优秀JavaScript库，它能使用户更加方便地处理HTML文档、事件等等。jQuery由约翰·雷西格（John Resig）于2006年创建，从最初的增强CSS选择器功能，发展至今，功能超级丰富。
# 三、操作步骤
## 1. 快递单号查询页面
- 用户查询页面 http://mhtclub.com/kuaidi/index.html

  ![](https://github.com/hellowHuaairen/kuaidi/blob/master/doc/1.png)

- 管理员操作页面：http://mhtclub.com/kuaidi/admin.html

  ![](https://github.com/hellowHuaairen/kuaidi/blob/master/doc/2.png)
  
 
## 2. 点击快递单号，直接查看详情
    
  方便用户的使用，直接点击订单编号，就可以跳转到快递的查询页面，支持所有快递订单的查询。
  
## 3. 快捷访问
  扫描下面的二维，即可快捷访问网站，完成对数据的查询，修改，新增操作
  
  ![](https://github.com/hellowHuaairen/kuaidi/blob/master/doc/3.png)
  
  ![](https://github.com/hellowHuaairen/kuaidi/blob/master/doc/4.png)
  

# 四、持续更新
  1. 快递信息批量导入功能；
  2. 快递信息批量导出功能；
  3. ...

