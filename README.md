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
5. 实例上的方法 
 - $mount 	vm.$mount("#app")  ->el:'#app'
 - $nextTick 确保获取更新后的dom元素
 - $watch  监听数据变化  两个参数oldval newval   
 - $options  用户输入所有参数 
- $data _data  
- vm.$set vm.$delete    
6. 指令 v-once v-html  v-if v-else v-else-if  v-show  

   