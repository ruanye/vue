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
3. {{}} 小胡子语法 -> Mustache(发音：ˈmʌstæʃ')
4. vue  模板渲染顺序 
	- 如果有render 会优先查找render 
	- 如果没有render 会找template
	- 如果没有temlate 会找el元素进行渲染  
5. 实例上的方法 
 - $mount 	vm.$mount("#app")  ->el:'#app'
 - $nextTick 确保获取更新后的dom元素
 - $watch  监听数据变化  两个参数 newval  oldval  
 - $options  用户输入所有参数 
- $data _data  
- vm.$set vm.$delete   后添加的属性无法被劫持  需要使用$set   
6. 指令 v-once v-html  v-if v-else v-else-if  v-show   v-for(数组、对象、数字 不要和v-if连用 key尽量不要使用索引)
7. 计算属性computed和watch的区别 

*  指令和过滤器里面this是 window 

8. 过滤器  filter  全局 局部  Vue.filter(名字,function(){})  局部的在组件里面定义  
filters  作用 不改变原数据的基础上对数据进行格式化(1592878371058=>2020-6-23  100=>100元/$  16.1333->16.13 )   方法/计算属性可以代替过滤器 
9.自定义指令 dircetive(指令)  操作dom   Vue.directive   局部directives 
   