# 软件工程概述

- 软件工程是一门工程学科，涉及软件生产的各个方面，从最初的系统描述一直到投入使用后的系统维护，都属于其学科范畴。软件工程不仅涉及软件开发的技术过程，也涉及诸如软件项目管理以及对那些支持软件生产的工具、方法和理论的开发等活动。软件工程离不开工程人员，他们既拥有一定的理论、方法和工具，又能有选择地利用它们，即使在没有可用的理论和方法的情况下，也能够力求解决问题的方法。软件工程之所以重要有两方面的原因1️⃣个人和社会越来越多地依赖先进的软件系统。这就需要我们能够既经济又快速地生产出可依赖和值得信赖的系统2️⃣从长远来看，运用软件工程方法和技术去开发软件系统比单纯为个人程序项目写程序更加便宜。对大多数类型的系统来说，绝大多数的钱都花费<font color="red">在软件投入使用后对软件的变更上</font>。

- 我们通常使用<font color="red">软件过程模型</font>来表现软件开发过程。软件过程模型是对软件开发过程的一种有用的抽象。下述是常见的三种软件过程模型：1️⃣瀑布式：将基本的开发活动划分为界限分明的独立过程，后续过程总是依赖之前的过程结果。2️⃣增量式：听取用户的使用意见和建议，将基本的开发活动交织在一起，通过一系列的版本（增量）发布来实现系统的开发。3️⃣复用式：通过集成大量可复用的组件到新系统中而非从头开发。

- 当前的业务都处于全球性、快速变化的环境中，新的软件要迅速地开发出来以抓住新的机遇。建立在传统需求描述，然后进行设计和实现，最终再进行测试的完整计划上的软件开发过程是不适应快速软件开发的。当需求发生改变，或者是当需求出现问题时，系统设计和实现不得不返工和重新进行测试。其结果是，传统的瀑布模型或基于描述的过程总是拖延，最后软件交付的时间远远晚于最初的规定。最终对这种重量级过程模型的不满引发了众多开发人员提出了基于增量式开发概念的<font color="red">敏捷开发方法</font>。其中最流行的敏捷方法包含：<font color="orange">极限编程</font>：1️⃣增量规划2️⃣为此版本选择用户故事情节3️⃣将故事情节分解成任务4️⃣规划下一个增量5️⃣开发/集成/测试软件6️⃣发布软件7️⃣开始下一个增量。 <font color="orange">Scrum管理</font>：1️⃣规划纲要2️⃣建立增量冲刺循环3️⃣总结项目

> 个体和交互胜过过程和工具；编写软件胜过书写详尽的文档；
>
> 用户合作胜过合同谈判；响应变更胜过遵循计划。 —— 敏捷宣言

- 软件工程必须具有 4 种基本的软件生产活动，这些活动可能是像使用 Java 和 C 这样的标准编程语言从头开始的一步步的软件开发，通常也会是通过扩展和修改现有的系统、或通过配置和集成商业现货软件或系统组件而获得。
  - [需求工程](#需求工程)
  - [软件设计与实现](#软件设计与实现)
  - [软件有效性验证](#软件有效性验证)
  - [软件进化](#软件进化)
  - [参考书籍](#参考书籍)

# 需求工程

- <font color="orange">极限编程</font>中，需求工程往往在（1️⃣增量规划2️⃣选择故事情节4️⃣规划下一个增量7️⃣开始下一个增量）中完成。<font color="orange">Scrum管理</font>中，需求工程往往在（1️⃣规划纲要3️⃣总结项目）中完成。

- 软件描述或需求工程是理解和定义系统需要提供哪些服务，以及找出开发和运行中收到哪些约束。需求工程是软件开发过程中一个特别关键的阶段，这个阶段的错误将不可避免地带来系统设计和实现阶段的后续问题。需求工程目标是生产一个达成一致意见的需求文档，定义能满足信息持有者需求的系统。通常文档中又两个层次表述。最终用户需要高层的需求描述，而系统开发人员需要比较详细的系统描述。需求工程有四个主要的阶段：1️⃣技术可行性研究2️⃣客户诉求导出和分析3️⃣需求文档化4️⃣需求有效性验证。

- Domain Driven Design

   DDD 是指你在软件中模拟如何在现实世界中解决问题，这部分现实世界就是业务领域，它包含多个业务上下文，每个上下文都有最适合自己的架构。

   DDD 的核心就是消化特定领域知识，并创建忠实反映它的软件模型。

[返回首页](#软件工程概述)

# 软件设计与实现

- <font color="orange">极限编程</font>中，软件设计与实现往往在（3️⃣将故事情节分解成任务5️⃣开发/集成/测试软件6️⃣发布软件）中完成。<font color="orange">Scrum管理</font>中，软件设计与实现往往在（2️⃣增量冲刺循环）中完成。

- 软件开发的实现阶段是把系统描述转换成一个可运行的系统的过程，它总是包含涉及和编程。这个过程描述了软件的结构、系统的数据、系统组件间的接口以及所用的算法的描述。设计者不可能一次就能完成一个完整的涉及，这是一个反复多次的过程。在设计过程中要不断添加设计要素和设计细节，并对先前的设计方案进行修正。软件设计因人而异，通常没有统一的模式。一些程序设计者从已经理解得很好的组件开始做起，然后再做不太熟悉的组件。其他人可能会采取相反的方案，把熟悉的组件留到最后，因为他们已经知道该如何开发这些组件。一些开发者喜欢先定义过程中要用到的数据，然后使用这些数据来驱动程序的开发。而另外一些人则是对数据现用现定义。设计过程一般包含：
  - [对需求文档进行系统建模](#系统建模)
  - [系统体系结构设计](#体系结构设计)
  - [系统实现](#系统实现)

## 系统建模

- 我们一般通过系统建模来更好的理解需求文档。系统建模就是建立系统抽象模型的过程，每一个模型表示一个系统不同的角度或者方面。其包含1️⃣上下文模型：确定需求中较大颗粒度功能的数量和边界。2️⃣交互模型：有助于我们分析所提出的系统结构是否能实现需求文档所提及的功能及其可靠性。3️⃣结构模型：即系统体系结构设计，表示为组件构成的系统及组件之间的关系。4️⃣行为模型：描述系统运行时的动态行为。如数据输入，事件触发。

## 体系结构设计

- 体系结构设计关心的是理解如何组织一个系统和设计系统的整体结构，用于识别系统的主要结构组件以及它们之间的关系。<font color="red">体系结构设计过程的输出是体系结构设计模型，它描述系统是如何由一组互相交互的组件组成的。</font>我们可以把体系结构看作是对好的系统实践所做的格式化的抽象描述，它们已经在不同的系统和环境中多次尝试和测试过。其中包含：
  - 着重GUI流程的 Model View Controller 结构，常用于浏览器应用中。
  - 着重职责分明的 分层结构，其包含界面层 User Interface layer 业务逻辑层 Business Logic Layer 数据访问层 Data access layer。
  - 着重数据共享的 容器结构，如基于 Inversion of Control 思想的工厂模式。
  - 着重输入输出的 管道/过滤器结构。

## 系统实现

- 软件设计和实现是软件工程过程中的一个阶段，在此阶段开发出可执行的软件系统。对简单系统来说，软件设计和实现就是软件工程的全部，其他所有活动都融汇在这个过程中。但是对于大型系统，软件设计和实现只是一系列软件工程过程中的一个。从很长的一段时间里首先，典型的开发方案差不多就是下面这样：
  - 首先，你收集需求，通过一些分析找出相关的业务实体，如用户、订单等；
  - 接着，带着这些理解，你尝试推导能够支撑流程的页面状态设计或是数据表设计，通常是关系型；
  - 接下来你组织页面交互或是编写接口，基于先前的状态/数据表设计来组织这些业务实体来完成业务流程，如用户登录，创建订单等；最后在表现层上，展现你的工作成果；

  ✅ 软件系统的代码结构，往往高度反映企业的组织结构 —— Melvin Conway (1967)

[返回首页](#软件工程概述)

# 软件有效性验证

​		<font color="orange">极限编程</font>中，软件有效性验证往往在（3️⃣将故事情节分解成任务5️⃣开发/集成/测试软件）中完成。<font color="orange">Scrum管理</font>中，软件有效性验证往往在（2️⃣增量冲刺循环）中完成。

​		软件有效性验证是要看系统是否符合它的描述以及系统是否满足客户的预期。测试过程中的阶段包括1️⃣单元测试：由开发系统的人员对组成系统的组件进行测试。组件可能是简单的实体，如一个函数或者对象类。2️⃣系统测试：集成组件形成完整的系统。这个过程主要是关注无法预测的组件间交互和组件界面问题引发的错误。也关注系统是否满足了功能上和非功能上的需求，并测试系统的总体特性。3️⃣接收测试：这是系统在接受并运行之前进行的最后阶段测试。这个阶段不再使用模拟数据来测试系统，而是用客户提供的真实数据测试系统。

> 如果没经过测试，那么它就是坏的。

[返回首页](#软件工程概述)

# 软件进化

​		<font color="orange">极限编程</font>中，软件进化往往在（3️⃣将故事情节分解成任务5️⃣开发/集成/测试软件6️⃣发布软件）中完成。<font color="orange">Scrum管理</font>中，软件进化往往在（2️⃣增量冲刺循环3️⃣总结项目）中完成。

​		软件进化是修改已存在的软件系统以适应用户新的需求的过程。变更是一个持续的过程，软件必须在变更过程中保持可用。

[返回首页](#软件工程概述)

# 参考书籍

-   《Microsoft .NET 企业级应用架构设计（第二版）》
-   《软件工程》Ian Sommerville

[返回首页](#软件工程概述)
