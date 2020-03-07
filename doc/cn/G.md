附件G(信息)
将软件生命周期过程应用于系统中的系统
G.1Introduction
一个系统的系统(SoS)是一个系统‐‐利益(SOI)，其元素本身就是系统。SoS集合了一组系统来完成一项任务，而这些任务是任何系统都无法单独完成的。每个组成系统保持自己的管理、目标和资源，同时在SoS内部协调和适应以满足SoS的目标。在5.2中讨论的术语上下文中。3(如图3所示)，包含原始SOI、启用系统和交互系统的复合系统集构成一个SoS。当存在影响组合集的问题时，系统的系统就成为了SOI, SOI被认为是用来满足单个组成系统不能满足的业务或任务目标，或者理解组合的紧急行为。

本附件阐述了系统生命周期过程在此类SoS的应用。它描述了一般特征，SoS的常见类型，以及贯穿生命周期的含义。
G。2SoS特征和类型
紧急呼救系统的特点是组成系统的管理和操作独立性，在许多情况下，这些系统是与紧急呼救系统的用户同时开发和继续支持最初确定的用户。在其他上下文中，每个组成系统本身是一个SOI;它的存在往往早于SoS，而它的特性最初是为了满足最初用户的需求而设计的。作为SoS的成员，他们的考虑范围扩展到SoS的更大需求。这意味着增加了复杂性，特别是当系统继续独立于SoS时。组成系统通常还保留其原始的涉众和治理机制，这限制了解决SoS需求的备选方案。

根据组成系统和SoS之间的治理关系，SoS被描述为四种类型(表G.1)。最强的治理关系适用于系统的定向系统，其中SoS组织对组成系统具有权威，尽管组成系统最初并没有被设计来支持SoS。对公认的SoS的控制要少一些，因为在组成系统和系统的系统之间分配的权限会影响一些系统工程过程的应用。在缺乏系统权威的协同体系中，系统工程的应用依赖于各组成系统之间的协作。系统的虚拟系统在很大程度上是自组织的，限制了SoS系统工程的机会。

表G。1 -系统类型的系统

类型
特征
虚拟
[ ]
分散的管理权力没有明确的、集中一致的目的——新兴的行为依赖于相对不可见的持续机制
协作
 
组成系统自愿地相互作用，以实现共同商定的目的，共同决定如何互操作、执行和维护标准
承认
 
公认的目标，一个指定的管理者和资源为SoS组成系统保留其独立的所有权，管理和资源
导演
   
建立和管理的综合紧急救援系统，以实现特定的目的，集中管理和演变的组成系统，保持独立运作的能力，正常的运作模式，服从于中心的目的

123
©ISO/IEC 2017 -保留所有权利
ISO / IEC / IEEE 12207:2017 (E)
紧急状态的一个关键特征是紧急状态的出现——由于组成系统的复杂的相互作用动力学而在紧急状态级别产生的未预料到的影响。然而，在SoS中，在组合时有意考虑组成系统，从而获得和分析仅使用系统无法获得的结果。组成系统的复杂性，以及它们可能在设计时没有考虑它们在SoS中的作用，可能会导致新的、意想不到的行为。识别和处理意外紧急结果是工程SoS面临的一个特殊挑战。
请注意，一些最大的软件SoS，如Internet，是虚拟SoS，其中的组成系统被设计成遵循通用的建议和通信协议。虚拟SoS可以表现出有益的新兴行为，如冗余、动态重构、协作和弹性。

G。3SE过程应用于系统G.3的系统。1一般
SoS的上述特性对这四种系统生命周期过程的应用都有影响。
G.3。2协议流程
协议过程对SoS至关重要，因为它们在负责SoS的组织和通常独立的组成系统之间建立了发展和操作控制模式。由不同组织获取和管理的组成系统，有时具有与SoS不一致的原始目标。除了在有向SoS的情况下，SoS组织没有他们的合作不能任务一个组成的系统组织。在公认的或协作的SoS中，这些任务与组成系统本身作为SOI的任务相平衡。对于虚拟SoS，协议过程可能是非正式的，或者仅用于分析目的。

即使在组成系统的所有者之间的协议中，仍然有一个收购者和一个供应商。系统所有者可以是另一个组成系统的收购者和供应商。
G.3。组织项目实施过程
在一个典型的系统‐‐利益，组织项目启动过程建立的环境中进行的项目。组织建立项目使用的过程和生命周期模型;建立、重定向或取消项目;提供所需资源，包括人力和财政资源;并设置和监视项目为内部和外部客户开发的系统和其他交付物的质量度量(6.2)。

在SoS中，组成系统的所有者通常保留对其系统进行工程设计的责任，他们每个人都有自己的组织项目授权流程。根据紧急救援系统的类型，紧急救援系统还应用这些组织项目启动流程来满足紧急救援系统的特殊考虑:计划、分析、组织和将现有系统和新系统的功能集成到紧急救援系统中。

因此，在SoS中，这些组织项目实施过程是在两个层面上进行的。负责组成系统的组织为其SOI独立于SoS实现这些过程。SoS组织(或通过SoS协议在系统的协作系统中)为SoS实施这些过程，以实现适用于整个SoS的那些考虑。例如，人力资源管理是由每个组成系统组织为其系统的工程所处理的。SoS组织只针对跨组成系统应用于SoS的系统工程活动的人力资源管理。

SoS工程中一个特别的挑战是，组成系统、组织项目授权过程和SoS的过程之间缺乏一致性。组成系统的过程是为了满足它们自己的结果而设计的，有时与SoS的结果不一致。例如，当组成系统组织完全控制其投资组合中的组成系统和其他系统和项目时，与SoS组织的投资组合管理不同，投资组合管理可以是一个组成系统职责。

124
©ISO/IEC 2017 -保留所有权利
ISO / IEC / IEEE 12207:2017 (E)
G.3。4技术管理流程
在一个典型的利益系统中，技术管理过程涉及管理组织管理层分配的资源和资产，并应用这些资源和资产来履行组织或组织签订的协议。它们涉及项目的管理，特别是在成本、时间尺度和成就方面的规划，对符合计划和业绩标准的行动进行检查，以及查明和选择纠正行动以弥补进展和成就方面的不足。它们用于建立和执行项目的技术计划，管理整个技术团队的信息，根据系统产品或服务的计划评估技术进展，控制技术任务直至完成，并在决策过程中提供帮助(6.3)。

技术管理过程也在SoS和组成系统的层面上实施。技术管理过程应用于SoS工程的特殊考虑——规划、分析、组织和将现有系统和新系统的混合能力集成到一个系统中的系统能力。与此同时，组成系统的组织保留对其系统的工程设计和自己的技术管理过程的责任。

SoS组织处理技术管理过程，因为它们适用于整个SoS，而这些过程也在组成系统组织中独立实现。例如，对于配置管理，组成系统管理它们自己的配置，而SoS处理配置管理，因为它适用于SoS中的系统组合。风险是由组成系统管理的，基于风险的评估，因为它适用于其结果，而SoS风险管理着眼于SoS的风险。

规划、评估和控制(6.3)是所有管理实践的关键;SoS工程中的一个关键挑战是SoS组织对组成系统的过程缺乏控制(特别是对于公认的和协作的SoS)。在其自身组织需求的驱动下，每个组成系统都可以处于不同于其他组成系统的开发或升级计划中。SoS组织计划了一个集成的生命周期，除了SoS启动的生命周期中的变化(将SoS视为SOI)之外，该生命周期还识别组成系统中的独立变化。这通常涉及到稳定的中间形式的定义，这些形式通过在组成系统之间添加增量功能来强调SoS的发展。

G.3。5技术流程
技术过程涉及整个生命周期中的技术操作。他们首先将涉众的需求转化为产品，然后通过应用该产品，在需要的时候和地方提供可持续的服务，以实现客户满意度。技术过程的应用是为了创建和使用一个系统，无论它是以模型的形式还是一个成品，它们适用于系统结构层次中的任何层次(6.4)。

与应用于紧急救援系统的其他程序一样，紧急救援系统和组成系统的技术程序均已执行;在某些情况下，SoS的实施是通过执行组成系统的过程，而不是针对整个SoS。

业务或使命分析为一个SoS看看整个SoS业务和使命环境。当组成系统被开发到在那个空间中运作的程度时，系统和组成系统的系统的业务或任务分析将在很大程度上被共享。目标是确定提供所需能力的最佳方法。

涉众需求和需求定义关注于顶层SoS，但也考虑涉众对单个系统的不同需求如何导致对SoS的约束。
SoS的系统/软件需求定义往往是在满足涉众需求和任务目标所需的层次上定义的，并将其转换为构成系统的需求，而SoS则是构成系统新需求的“涉众”。

SoS的体系结构是一个框架，用于将现有系统和新系统的混合功能组织和集成到SoS功能中，将组成系统的体系结构留给它们的组织。由于SoS中的组成系统通常早于SoS，所以SoS体系结构的定义通常从SoS的实际体系结构开始。然后检查架构备选方案，以确定涉众

125
©ISO/IEC 2017 -保留所有权利
ISO / IEC / IEEE 12207:2017 (E)
关注并满足顶级SoS需求，并认识到对组成系统的新需求的影响，并适应组成系统体系结构的约束。
设计定义过程提供了足够详细的数据和信息来支持SoS实现。这涉及到与组成系统组织的协作，这些组织将进行他们自己的设计交易，以确定当他们应用于他们的系统时处理SoS需求的方法。这些是组成系统组织的责任。实施工作由组成系统完成，而SoS组织则担当监察的角色。

集成、验证、转换和验证由组成系统完成，以支持它们实现的更改以支持SoS生成的需求。这些过程也适用于SoS，当升级后的组成系统集成到SoS中，性能得到验证和验证时。SoS中组成系统的独立性和异步性对在传统SOI中实现这些流程的有效实现提出了挑战。在某些情况下，SoS级别的评估只能在运行环境中进行，在这种情况下，应考虑预防措施以避免SoS不良行为。

最后，由于操作、维护和处置过程的管理和操作独立性，它们往往由组成系统来执行。SoS级交互可以促进互操作性，减少这些过程的重复工作。