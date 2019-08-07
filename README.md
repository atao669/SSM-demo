# SSM-demo
本项目是一个企业员工信息管理系统，前端使用LigerUI框架，后端使用SpringBoot，实现了员工信息的增删改查，同时还可以通过Excel文件对员工信息进行增量更新或全局替换和从数据库中导出功能，文件导入通过开启一个异步任务进行Excel文件的读入，并开启定时任务实现向数据库导入记录，每次的文件导入操作都保留了导入时间、导入类型，执行状态和结果信息并可以下载获取导入结果的文件，文件导出会记录导出时间、导出条件，同时也可以下载对应的导出结果文件。
本人正在对该项目改进中，还添加了籍贯地人数的统计功能，利用ECharts完成每个地区的出生人数的柱状图显示。
