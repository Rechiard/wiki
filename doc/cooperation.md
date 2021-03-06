# 协作开发须知
技术是为了让业务更加流畅和高效。

所以在设计方案和开发之前，一定要对需要解决的实际问题来龙去脉了解清楚，做这个问题的“主人”。

## 一、原则
开源项目的开发不要做成和工作时候一样，接需求。要自己去找需要优化的点、认同需要解决的问题，这样要做的东西才是自己想做的，才能感受到做开源的乐趣：写自己感兴趣的代码，用自己觉得酷的技术。

因为开源是多人协作开发的形式，所以流程很重要否则会很乱无法跟踪进度和管理。下面是 HG 的协作开发流程，需要各位参与开发的小伙伴认证阅读并遵守。

大体上分为：
- 任务管理：创建任务、任务模版、管理同步项目进度
- 开发流程：Git 工作流、遵守参与项目的代码规范

## 二、流程（概述流程，详尽步骤请阅读项目的 README）
为了方便跟踪记录做的事情，我们一定要按照流程走，这样才不会丢掉任务、让任务停滞。

1. 参与到某个项目后，找对应的项目负责人申请 GitHub 项目权限、官网后台权限、Token 等。
2. 确定要做的功能后，在参与项目的 project 中创建任务，并放到对应的状态列下。内容模版如下：
    ```
    #### 任务名称：
    - [ ]拆分任务1
    - [ ] ...
    ---
    （分割线下是 Bug、问题修复、优化任务的记录）
    - [ ]修复 xxx 问题
    
    Begin：2019-11-20（开始时间）
    End：？（完成时间，自行安排，如有延期在群里说一下，然后再加一行新的 End：时间）
    @GitHub用户名（开发者）
    ```
3. 开发时具体到某个项目，会有对应的依赖库、技术栈、代码规范、安装环境流程，请自行认真阅读，如遇问题找 Team 中人员请教。
4. 写代码的第一步请基于 dev 分支创建：feature_功能描述 分支，进行开发。
5. 开发过程中，可自行思考需要加入的功能（前提是正确理解要解决的问题），有新的想法可以找最初问题的提出者讨论，达成一致后，搞就完事儿了。
6. 提交代码前，请自行测试完成后。提交 feature 合并到 dev 分支的 PR，并分配给其他项目成员和项目负责人进行 review。（可在群里提示）
7. 请大家积极、及时参与 review 中，同时管理上述创建的任务状态。

**注意**：写代码不要图一时之快，做到可维护、可阅读、有理可依、对应文档和注释及时更新和同步。工作中写的坑还不够多吗？做自己的项目，需要对自己要求高一点、再高一点。

## 三、写给项目负责人
一个人的代码威力有限，创建维护优秀的项目，凝聚更多优秀的人，让一切变得顺理成章。

让项目内的人开心的协同开发、积极的讨论，是一个项目负责人最应该做的事情。所以需要保证项目有意思、代码质量优秀、标准的规范、协作流程简单但不简陋，最后要保证项目持续推进。

只要项目足够优秀，优秀的人自然是会欣然加入的。

