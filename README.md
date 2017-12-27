# meetingSystem
会议管理系统
Struts2.3+Spring4.0+Hibernate4.3
老师：
1、查看所有学生
	点击查看工作汇报可以看到学生历次的工作汇报（只有老师可见），点击答复可以进行回复
	点击查看工作代码可以看到历史上传的工作代码（可以设置所有人可见或者只有自己可见）
	点击查看会议汇报可以看到该同学的历次公开汇报记录
2、查看工作汇报
	可以按时间排序查看学生的工作汇报，点击答复可以进行回复
3、创建会议
	可以创建会议，设置开始时间和截止时间，（可选择指定的同学，通知该同学进行汇报）。会议内可以看到同学的公开汇报，点击进入讨论可以在会议下边进行讨论，可以看到哪个同学回复了哪个同学，按时间排序
4、我的消息
	可以看到学生的汇报，回复，我创建的会议的讨论情况
5、历史会议
	可以看到按照时间排序的会议，包括会议名称，会议备注，汇报人员。点击会议可以看到汇报和讨论记录
6、处理其他请求
	包括请假请求的回复等。

学生
1、查看所有同学
	点击查看会议汇报可以看到该同学的历次公开汇报记录
	点击查看公开代码可以看到该同学上传的公开代码
2、查看正在进行中的会议
	如果当前时间内有截止时间之前的会议，则可以点击进入讨论
3、历史会议
	可以看到按照时间排序的会议，包括会议名称，会议备注，汇报人员。点击会议可以看到汇报和讨论记录
4、创建我的项目
	可以创建一个新的项目，填写项目名称和项目描述，设置项目是否所有人可见。我上传的代码可以属于这个项目中。
5、查看我的项目
	可以查看我创建的项目，点击可以看到项目的名称，描述，代码，代码上传日期，及是否公开。
6、汇报工作
	可以向老师汇报本周工作情况，并上传相关PPT等
7、查看消息
	可以查看其它同学对我的回复，对我的代码的评价等