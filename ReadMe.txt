这是我的一个JavaScript学习记录的项目，虽然我有过三年的C#开发，
并且我有过js的基础，但是我决心要冲头好好学习一下。
加油吧，沉浸在着知识的海洋中。。。

2018-05-06
js对象居然可以删除属性
delete obj.name 就可已删除一个对象的属性
判断一个对象是否包含某个属性，就用In 例如：判断student对象中是否有name属性   'name' in student // true or false
不过要考虑到这个属性是否通过继承获得的
如果想判断一个属性是否只属于这个对象本身，就使用hasOwnProperty()方法 例如 : student.hasOwnProperty();