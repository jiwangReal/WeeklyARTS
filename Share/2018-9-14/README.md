## 做游戏服务器端开发时的一些收获与总结  
由于在写游戏服逻辑时踩了一些坑，在此记录如下  

#### 一、理论知识储备  
服务端属于后端开发，因此比较注重底层架构。  

- 把《深入理解计算机系统》好好看看，以后做开发接触到越底层的东西这个就越有用，知其然并知其所以然，这样提升空间会很大，也很快；  
- 把《UNIX网络编程卷一二》好好看看，因为涉及通信，通过这本书可以把最基础的概念完整的建立起来；  
- 把Linux基本操作命令和简单的shell脚本，以及makefile好好学一下，因为虽然开发时我们可以在windows下编程，但最后项目的落地部署还是得在Linux环境下。因此建议去下载一个Linux Server版的系统装在虚拟机里。  


#### 二、编程能力提升  
有了理论知识作为支撑后，还应该注重编程技能。  

在此我的想法是在LeetCode上刷标签为哈希表（hashtable）、排序（sort）和搜索（search）的题型，同时还可以在HankerRank和LeetCode上刷SQL专题类型的题作为编程能力的提升。  



#### 三、综合能力提升  
综合能力的提升就是多做一些小demo，多尝试犯错。  

- 入门级：写一个多人在线聊天室；  
- 中级：在聊天室的基础上添加注册登录选房间部分；或者自己尝试把redis+mysql数据库添加进来，完成一个简单的游戏注册登录选服选角的逻辑；或者可以开始尝试把别人写的战斗服务端逻辑用自己的想法写出来  


#### 四、小结  
以上就是我这段时间的收获，高级阶段我没有写，因为我现在确实很菜，也不知道高级阶段是什么样子的。  