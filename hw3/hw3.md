1、简单题

- 简述瀑布模型、增量模型、螺旋模型（含原型方法），并分析优缺点
  - 从项目特点、风险特征、人力资源利用角度思考
- 简述统一过程三大特点，与面向对象的方法有什么关系？
- 简述统一过程四个阶段的划分准则是什么？每个阶段关键的里程碑是什么？
- 软件企业为什么能按固定节奏生产、固定周期发布软件产品？它给企业项目管理带来哪些好处？

**瀑布模型**

- 优点
  - 有利于大型软件开发过程中人员的组织、管理，有利于软件开发方法和工具的研究，从而提高了大型软件项目开发的质量和效率。
  - 需求是明确的，在短期内可获取每个阶段是无差错的
  - 可以应用在迭代模型中
- 缺点
  - 强调过程活动的线性顺序
  - 缺乏灵活性，尤其是无法解决软件需求不明确或不准确的问题
  - 瀑布模型的软件活动是文档驱动的，当阶段之间规定过多的文档时，会极大地增加系统的工作量
  - 管理人员如果仅仅以文档的完成情况来评估进度，往往会产生错误的结论。

**增量模型**

- 优点
  - 人员分配灵活，刚开始不用投入大量人力资源
  - 如果核心产品很受欢迎，则可增加人力实现下一个增量
  - 可先发布部分功能给客户
- 缺点
  - 并行开发构件有可能遇到不能集成的风险，软件必须具备开放式的体系结构
  - 增量模型的灵活性可以使其适应这种变化的能力大大优于瀑布模型和快速原型模型，但也很容易退化为边做边改模型，从而使软件过程的控制失去整体性

**螺旋模型**

- 优点
  - 设计上的灵活性，可以在项目的各个阶段进行变更
  - 以小的分段来构建大型系统，使成本计算变得简单容易
  - 客户始终参与每个阶段的开发，保证了项目不偏离正确方向以及项目的可控性
  - 随着项目推进，客户始终掌握项目的最新信息，从而他或她能够和管理层有效地交互
- 缺点
  - 采用螺旋模型需要具有相当丰富的风险评估经验和专门知识，在风险较大的项目开发中，如果未能够及时标识风险，势必造成重大损失
  - 过多的迭代次数会增加开发成本，延迟提交时间

**2.简述统一过程三大特点，与面向对象的方法有什么关系？**

- 软件开发是一个迭代过程
- 软件开发是由Use Case驱动的
- 软件开发是以架构设计为中心的

**3.简述统一过程四个阶段的划分准则是什么？每个阶段关键的里程碑是什么？**

统一过程中的软件生命周期在时间上被分解为四个顺序的阶段，在每个阶段的结尾执行一次评估以确定这个阶段的目标是否已经满足。 里程碑： 初始阶段：生命周期目标（Lifecycle Objective）里程碑 精化阶段：生命周期体系结构 (Lifecycle Architecture) 里程碑 构建阶段：初始运行能力 (Initial Operational Capability) 里程碑。 移交阶段：产品发布 (Product Release) 里程碑。

**4.软件企业为什么能按固定节奏生产、固定周期发布软件产品？它给企业项目管理带来哪些好处?**

UP的每个阶段都由一个或多个迭代组成。每个迭代都要针对不同的业务用例或系统用例进行细化和实现。每个阶段开始时都有特定的目标，结束时有里程碑。在每个阶段中存在一个或多个迭代，在每个迭代中，可以有多个工作流，企业只需要完成该阶段性的小目标即可。 因此企业在企业在使用UP时依据各个迭代过程可以有固定的节奏生产、固定时间发布软件产品。