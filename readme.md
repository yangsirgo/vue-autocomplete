#vue-autocomplete.vue
## 功能概述
####适合中文的autocomplete，适合vue.js1.0
##语法
#### 引入
    <autocomplete
    name="people"
    url="http://localhost:8080/HumanBasic/humanFulltimeUser/selectListByName"
    anchor="userName"
    label="userNumber"
    model="vModelLike"
    placeholder='请输入查询的'
    limit='2'>

###### limit
#######url中会增加limit参数，传给后台，确定每天返回的数据数量。
###### min
#######input中输入的字符个数。
###### anchor
#######anchor是下拉框显示的username。
###### label
#######username下面的员工编号。
###### name
#######name是组件的名字，便于多个antocomplete管理。

##应用技术
####基础的vue.js知识
####ES6的字符串模板语法
