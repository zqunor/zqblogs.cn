## 基于TP5写简单的博客项目

进度记录--2018/4/8


1、设计数据库`db.sql`


进度记录--2018/4/18
1.设置布局显示模板页面
    
    index.html -- 首页
    about.html -- 关于
    detail.html -- 文章详情
    category.html -- 导航模块（按分类）
    archives.html -- 归档文章列表（按时间）
    liuyan.html -- 留言反馈

2.设置后台视图页面

    文章管理
    分类管理
    标签管理
    友情链接管理
    评论管理
    留言管理
    关于页面
    首页

进度记录--2018/4/25

1.修改后台模板布局

2.修改文章数据表结构
* 添加status字段，标注文章状态：
    * 0 - 草稿
    * 1 - 发布

3.文章添加页面功能修复
* UEditor富文本编辑器显示问题
    * 将相关js在使用前载入

* WdatePicker日历插件载入
    * My97DatePicker
    * 参数使用报错（删除第二个参数）
    * 设置皮肤颜色 为 twoer