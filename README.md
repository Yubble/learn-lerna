<!--
 * @Name: 
 * @Description: 
 * @Author: 刘燕保
 * @Date: 2021-08-31 21:36:37
-->

用来学习以及练习lerna的项目

packages 文件夹用于存放相互有依赖的项目，可用git 将代码拉取下来

常用命令：
lerna init // 初始化命令，只需要使用一次
lerna add // 为每个项目添加依赖
lerna add module-1 --scope=module-2 // 为module-2项目增加module-1依赖
lerna bootstrap // 为每个项目安装node_modules，等价于npm i
lerna clean // 删除每个项目中的node_modules