======
apg
======
全名为app webpage generator，作用是以studio为单位，自动生成静态的网站。

http://www.applabsinc.net/

需求
=======
目前公司有多个studio，每个studio对应一系列的app。项目的需求是以studio为单位，建立网站。这样可以提高SEO排名，也可以作为展示studio的一个平台。

.. image:: /_static/apg_01.png

自己的进步
===========
1. 实践了supervisor进程管理工具。
2. 将celery的定时任务和异步任务功能应用到静态网站的生成和自动部署上。
3. 使用了新的前端框架Vuejs，封装了html的各种input元素，能够对应django model自动生成表单。
4. 获得前端对ajax消息处理的一些宝贵经验。

完成过程
==========
制作这个系统的时间大概是在2016年6月份。为了和其他系统保持外观一致，总体框架仍然采用了django-suit。但是主要页面完全是前后端分离的。在PTS中，我大量使用了angularjs，经过对比，我发觉Vuejs比angularjs更加的优秀。所以在APG中，我改为使用Vuejs。

由于时间相对比较充裕，所以进行了较多的重构。将Vuejs与django结合得比较好。