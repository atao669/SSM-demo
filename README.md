# SSM-demo
本项目是一个企业员工信息管理系统，前端使用LigerUI框架，后端使用SpringBoot，实现了员工信息的增删改查，同时还可以通过Excel文件对员工信息进行增量更新或全局替换和从数据库中导出数据功能，后台是通过开启一个异步任务进行Excel文件的读入，并开启定时任务完成向数据库导入数据的，每次的文件导入操作都保留了文件导入文件的时间、导入类型，执行状态和结果信息并可以下载获取导入结果的文件，文件导出会记录导出实现、导出条件，同时也可以下载对应的导出结果文件。
