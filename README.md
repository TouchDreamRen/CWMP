# CWMP
CWMP：Course Work Manager Platform   课程作业管理平台 

基于Servlet和Jsp交互

一、项目的背景和意义

        1、背景
           Web课程设计要求，开发此系统。
           整体描述：
                管理员可添加学生、教师、课程，并指定授课的教师和教课的班级；
                教师可布置多次作业，设置作业的提交时间；
                学生完成作业后，将作业文件打包上传，可重新提交；
                教师可批改学生提交的作业，进行打分，并设置批阅意见。学生可查看作业的批阅情况；
                教师可统计学生作业的提交情况，班级作业的提交情况等；
                系统有三种角色登录：管理员、教师、学生。
                
        2、系统应用与意义
               该系统是在学习了java的基础上进行开发的。在需求上，充分考虑了具体用户的实际情况。
               本产品将主要适用于学校教师对班级课程作业的管理，方便教师在线批改作业、查看学生完
               成作业情况，方便学生向老师提交作业、以及查看老师批改情况。本系统为人们提供了一个
               方便学校中老师对学生日常作业的管理的系统，方便了老师和学生之间的互动，相对传统的
               学生代表收发作业、再提交给老师这种浪费人力物力的不便捷来说，该系统大大提高了老师
               对学生作业管理的效率，在学校中，该平台对老师和学生很实用。
          
	  
 二、项目需求
 
 	1、功能结构图：        
   ![image](https://github.com/TouchDreamRen/CWMP/raw/master/screenshots/FunctionalStructure.png)
	
	2、功能说明：
        管理员：
                1、教师、班级、课程管理功能：
                添加、删除、修改、查看（教师、学生和课程）
                2、授课管理：安排教师授课的班级和课程；
                课程和班级（学生）依附于教师；
        教  师：
                1、发布作业并设置提交时间；
                2、批改学生提交的作业，打分和设置批阅意见；
                3、统计学生作业的提交情况；
                4、统计班级作业的提交情况；
                5、个人设置：发布公告、个人信息修改
        学  生：
                1、查看教师发布的作业；
                2、上传自己的作业，可以重新提交；
                3、下载老师发布的作业；
                4、查看自己作业的批阅情况；
                5、个人设置：修改密码、查看个人信息；


   	3、用例图：
   ![image](https://github.com/TouchDreamRen/CWMP/raw/master/screenshots/UseCase.png)
   
	4、用例描述-管理员部分：
   ![image](https://github.com/TouchDreamRen/CWMP/raw/master/screenshots/UseCaseDescription.png)
   
   
三、数据库设计——数据库表关系
        ![image](https://github.com/TouchDreamRen/CWMP/raw/master/screenshots/DataBase.png)


四、架构设计——MVC架构
	![image](https://github.com/TouchDreamRen/CWMP/raw/master/screenshots/Framework.png)


五、开发技术和组件
        
        前台：   Bootstrap+Html5+CSS来显示页面    +    JavaScript+JQuery来控制页面
        后台：  SQLServer 2014数据库
        中间：  Servlet来处理前后台的交互

        系统开发环境和组件： 
	Windows 8操作系统 +  eclipse  +  JDK8.0  +  SQLserver 2014( DBMS ) + Tomcat 7.0 + Chrome浏览器 


六、界面设计

   	登录界面：
   ![image](https://github.com/TouchDreamRen/CWMP/raw/master/screenshots/login.png)
        
        管理员界面：
   ![image](https://github.com/TouchDreamRen/CWMP/raw/master/screenshots/manager.png)    
        
        教师界面：
   ![image](https://github.com/TouchDreamRen/CWMP/raw/master/screenshots/teacher.png)    
        
        学生界面：
   ![image](https://github.com/TouchDreamRen/CWMP/raw/master/screenshots/student.png)    
        
	
七、项目总结
        
        1、项目进度展示：
   ![image](https://github.com/TouchDreamRen/CWMP/raw/master/screenshots/GanttChart.png) 
   
        2、分析与总结：
	
           本课程作业管理系统实现了需求分析的基本功能，基本满足了三个功能角色的需求，开发过程中一开始一直在实
        现界面的优化，并且多次修改数据库。本系统实现了学生作业的上传与下载，及教师发布作业，批改作业打分，统
        计作业提交情况等。管理员对学生教师及课程的管理等功能，系统已经进行了测试，基本功能都成功了，但是因为
        初次开发，在系统中难免存在着各种问题，这些我们会在以后的时间进行更正。
           在开发本系统的过程中，要查询翻阅大量的参考文献以及网上搜索资料，培养了我们调查研究、查阅中外文献资
        料。通过对本系统的开发，提高了我们团队合作的意识、分析解决实际问题的能力。最主要的是提高了我们的自学
        能力，因为开发本系统中使用了Eclipse开发平台与Microsoft SQL Server工具进行数据库的设计，采用JSP语
        言进行开发，因此，通过这次实验，把所学的理论知识与实际应用联系了起来，为我们今后走向社会打下了坚实的
        基础。


   
