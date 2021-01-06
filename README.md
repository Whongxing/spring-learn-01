# spring-learn-01
Sping学习，最简单的Spring空项目(多模块)创建，引入maven依赖
- 先新建一个普通的Project,删除src目录
- 在项目中新建一个Moudle——maven项目，此项目也是父项目，此时默认项目的pom.xml文件为下图
![](https://github.com/Whongxing/spring-learn-01/blob/master/image/maven%E6%A8%A1%E5%9D%97%E5%88%9D%E5%A7%8B%E5%8C%96pom%E6%96%87%E4%BB%B6.PNG)
- 接下来还需要为父项目进行pom打包，这样就可以删除父项目中的src：

打包方式：添加  <packaging>pom</packaging>
