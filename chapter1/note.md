2021-03-28  
**初识django**  
web开发，mtv架构  
应用场景：  
- django admin管理后台（内容管理、企业管理、运维管理） 
  
优点：  
- python实现，代码干净、整洁  
- 提供管理后台，能够快速开发  
- 服用度高，设计、使用上遵循dry原则  
- 易于扩展的中间件  
- 丰富的第三方类库  

缺点：  
- 单体应用，不易与并行并发，单点扩展  
- 不适合非常小的几行代码的项目  
- 不适合高并发的To C项目开发  

django的mtv架构三大核心：model,template,view  

django的设计思想：  
- dry(do not repeat yourself)：不重复造轮子  
- mvt  
- 快速开发  
- 灵活易于扩展  
- 松耦合  
- 显示优于隐式  

环境搭建：  
- anaconda  
- pycharm