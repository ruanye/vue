## vue 基础
1. 库和框架 
框架framework  vue   库 libary  jquery loadash react  
react+react-router+redux =>框架 
框架和库的区别  
库 是我主动去调用库里面的方法 
框架 在固定的位置去写代码 框架会自动调用方法 
2. mvc 和mvvm  
m model 数据  v view 页面  c controll 控制器  backbone 
vue ->mvvm 框架 不完全遵循mvvm规则(ref 用户可以直接操作dom )
m model(js里面的数据)  v view 视图(页面)  vm   viewmodel 视图模型    
用户不需要操作dom     viewmodel  
3. {{}} 小胡子语法 -> Mustache 
4. vue  模板渲染顺序 
	- 如果有render 会优先查找render 
	- 如果没有render 会找template
	- 如果没有temlate 会找el元素进行渲染  

作业：周一上午11点交  线上能直接能看能用 npm run build 结束的页面 （自己录制演示的视频 ）     
前端加后端(不能多于3个人一组) 公司员工信息统计系统(移动端可以看,pc端也可以看，禁止使用bootsrap) 
登录 -> 注册  数据库   
1.  添加员工 ->  姓名 性别(男，女)  部门  年龄  居住地 
2.  员工健康状态  有无异常  体温 
3.  员工列表的页面    