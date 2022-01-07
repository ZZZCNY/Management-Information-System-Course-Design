 
**《管理信息系统》课程实践任务书**
**一、专周性质与目标、要求：**
**1、性质**
《管理信息系统》课程实践专周是计算机信息管理与信息系统专业学生熟悉软件开发的过程和组织的综合实践课。它既是让学生训练程序设计语言的实践环节，也是让学生熟悉和体会软件的开发过程，同时在实践的过程中还需要学生熟悉如何与其他的团队成员共同协作开发软件。
本实践训练环节由需求分析实践和系统设计实现两部分组成。
**2、目的**
管理信息系统课程实践通过学生对一个项目进行分析设计，综合各种知识，通过专周实践熟练掌握管理信息系统的需求分析、系统设计的方法和技术； 熟悉如何获取应用系统的需求，能够正确区分用户的需求；熟悉管理信息系统的系统分析与设计的工具软件的使用，熟练使用这些软件对应用系统进行建模，为后续课程的学习和工作奠定基础。
**3、要求**
本专周实践需要分析设计一个图书馆图书管理系统。如图1所示，通过这个应用系统，教师和学生可以进行书籍的借阅和预约等操作。相关要求如下：
1） 基础信息维护：管理员可批量导入师生、专业和学院信息，导入的文件格式不限；此外，还可以重置系统内各个用户的密码。
2） 图书信息管理：管理员可对图书的基本信息（书名、ISBN、价格等）进行管理，也可完成图书批量或逐个的增删操作；此外，管理员可对图书进行批量的上下架，只有上架的图书才可被预约或借阅。
3） 荐购审核：可对师生提交的荐购图书进行审核，审核通过的图书将进入待购清单，以备之后采购。需要注意的是，不可通过图书馆已存在或在待购清单的图书，以避免重复购买。
4） 赔书申请审核：可对师生提交的赔书申请进行审核。
5） 规则修订：管理员可对借阅规则和罚金规则进行修订。其中，借阅规则对可借阅的书籍数量、借阅的每个周期长度进行修改。例如：老师最多可以同时借30本书，学生只能借10本；老师每个借书周期为90天，学生为30天；老师可借阅出版日期距今在20年以内的书籍，学生只可借阅出版日期在20年以内的书籍等。罚金规则可根据书籍的出版时间等基本信息自动计算书籍丢失应缴纳的罚金，例如：赔书罚金=（出版年份-当前年份）/10 * 书籍售价，滞纳罚金=（实际还书日期-最晚应还日期）*0.5等。
6） 数据可视化与汇总：提供针对个人、专业、学院、书籍等不同角度的数据可视化与汇总信息。
7） 书籍借阅：师生在系统中进行书籍借阅，只能借阅在架的图书。若该图书被多人预约，则根据一定规则计算优先级，只有当自己优先级最高才可借阅。
8） 书籍预约：师生可通过系统预约书籍，要求不可超出可借阅数量，且当前账户不存在过期未还书籍。同时，可以查看该书的所有预约记录，以了解当前自己的排位。
9） 个人信息查看：查看个人账户信息，同时也查看到与自身角色（教师或学生）对应的借阅规则。
10） 借阅历史查看：查看个人借阅历史记录。
11） 读者荐购：师生可在系统上填写荐购书籍的信息，推荐图书馆进行采购。
12）书籍遗失或滞纳处理：当书籍丢失时，可通过两种方案进行赔偿。一是在系统上支付根据规则计算出的罚金；二是购置相同书籍归还图书馆，但需发起赔书申请，并由管理员进行审核。当书籍过晚归还图书馆时，需要缴交滞纳金，否则不可再进行预约或借阅书籍。
![](https://cdn.nlark.com/yuque/0/2021/png/23075474/1639438996557-255a2693-a9c7-4fe9-ad9f-572ca621a0e3.png#height=404&width=415)
图1 系统功能导图
在图1中，标为1的是必须完成的基本功能；2和3属扩展功能，完成才可得到良及以上成绩。
 
本专周实践要求如下：
⑴ 了解和熟悉管理信息系统开发的过程。
(2) 熟悉建模工具软件的使用。
(3) 掌握应用系统分析与设计的基本原理、过程及方法。
(4) 熟悉和掌握软件文档的编写。
(5) 掌握信息系统开发规范。
(6) 掌握代码调试技术。
(7) 在开发的过程中要注意团队协作。
**二、时间、地点及任务安排**
**1、    时间： 19～20周**
2、**地点：** C**2-520**
**3、具体安排：**
**（一）第一阶段：（1周）**
（1）收集整理项目的需求，编写软件开发计划和软件需求说明文档。
（2）在需求分析的基础上利用收集的需求进行概要设计和详细设计，编写概要设计说明书和详细设计说明书。
（3）进行软件的数据库设计和软件的用户界面的设计。
**（二）第二阶段：（1周）**
（1）根据系统的设计编写相应代码。
（2）根据测试用例进行软件测试。
（3）编写软件项目开发总结。
（4）完成实习实践总结报告。
**四、人员安排**
人员小组合作，每组4～5人。
**五、实习纪律及成绩评定标准**
1、遵守学校有关学生专周实习的规章制度及所在实验室的规章制度。
2、实习过程中有较强的时间观念，不迟到、不早退。
3、服从指导教师和组长的指挥。
4、认真完成专周实习总结报告。
5、考核内容及评分采用多项综合评定方法，具体内容及所占比例如下表，成绩评定分为五等：优、良、中、及格、不及格。

| 考核项目 | 成绩比例% | 备注 |
| --- | --- | --- |
| 考勤、纪律、学风 | 15 | 个人 |
|  系统分析、设计 | 15 | 小组 |
|  系统实现 | 20 | 小组 |
| 测试计划 | 10 | 小组 |
| 文档写作 | 20 | 小组 |
| 专周实习总结报告 | 20 | 小组、个人 |

6、  扣分项目：有以下情况需要酌情扣分
（1） 不服从组长的安排，不与团队其他成员合作
 
 
