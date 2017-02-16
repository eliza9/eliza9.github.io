整理一个售前项目的案例，重新绘制了36个原型页面，1张思维导图，3张流程图，2张对比图，1张结构图，介绍一家百货购物中心微信服务号改版的设计。



#一、用户体验五要素

###1.战略层：
这其实是甲方公司的考虑，可以理解为大多数百货行业都在通过移动端提供用户更好服务，所以我们的甲方也在其中。

###2.范围层：
移动端是设计包括App和移动网页端，包括各类新媒体，目前要解决的问题是，打通微信公众服务号、App以及商城线下，为用户提供全角度的服务。

###3.结构层：
微信公众服务号的功能点，既要配合了其他服务渠道，也需要实现其自身的价值。在结构设置上可以分为（1）配合线下的活动页面（2）微信独有的功能页面（3）背靠完整的会员服务体系。核心是服务，对象是用户，也就是会员。重点就是会员服务。

###4.框架层：
目前的交互设计主要围绕这个层次，要保证每个链接到页面的跳转逻辑时顺畅的，且对应结构层来说是完整的，每个页面的设计符合用户的心理模型，且保留一定的再开发性，为日后的拓展铺垫更多。

###5.表现层：
微信公众号的设计不同于App，所以就本项目的表现层基本在框架层上进一步优化，本文就省略了。



#二、竞品分析
###1.选择竞品：
找对竞品很重要，同行业或者同用户群，功能类似或者定位类似，都是需要考虑的，找了以下五个（横向思考）：
①大悦城：年轻时尚，相同的用户群。
②大丸百货：外资百货，高大上，相同的服务品质。
③K11：含艺术气息的商业百货。
④万达：全国覆盖面较广的集团公司。
⑤银泰：浙江省较早开发互联网的零售业百货公司。

###2.对比分析类型百货类公众号的概括：
如图：

可以得出每个竞品的侧重点不一，而结合起来反而是甲方所需要的部分。

总体看一共可参考的也只有三大功能点：会员、APP引流、商城，以及各自的特色服务，会根据商场的营销活动而变动。考虑到线上商城并不是甲方本次改版微信公众号的的服务目的，就是省略了该部分的设计。

横向的竞品只需要概括到结构层就可以了，框架层可以参考的竞品是纵向的，各类可以实现该功能的App页面的设计版式都是可以对比参考的，不需要只在同行业的限制内。

需求分析思维导图：

本案例的结构设置如图：



#三、解决方案及设计图

###1.流程设计
既然结构已设定，那流程必须走通才能绘制页面。分别从菜单的每一栏绘制流程，并考虑栏目之间的联系。
A．菜单1（图）
B．菜单2（图）
C．菜单3（图）

###2.用户体验设计

**亮点一：**
（图）
“会员中心”和“我的实体卡”之间，是可以通过手指向下滑和向上推来实现的。（如果没有绑定实体卡，会有绑定弹窗的，绑定后是顺滑的手势操作）是轻度滑动，不是长按哦！

【解说】会员中心页是会员体系的核心，实体卡是商城服务的基础，所以这个手势设计把实体卡“埋”在信息结构的下一层，像是揭开了遮罩，通过手势的下滑和上滑来查阅信息。既方便又眼前一亮。（灵感来源：material design的层级设计）。

**亮点二：**
（图）
弹窗比较多。

【解说】其实算不上亮点，弹出的好处在于不需要单独做状态页面，而且不需要返回，直接右上角的叉叉就可以关闭，进行其他操作，这样做可以稍微减少页面的跳转，这样减少加载页面的时间，而且把是不是进行下一步操作的权力还给用户，部分的弹窗上还有交互功能。（发现自己大概是弹窗爱好者）



#四、设计说明

1.  微信最多3个一级菜单、5个子菜单条目。

2.  最左的第一个栏目，也就是菜单1，一般是刚关注公众号后的点击率最高的菜单栏目，适合根据具体商城线下营销活动，通过更灵活的变动，来呼应和烘托线下活动的氛围。同时配上微信图文宣传，是可以达到良好的用户交流的效果的。

3.  最右第三个的栏目，是最靠近右手触控的范围的，最容易响应的会员体系，通过这个位置实现其服务是恰到好处的。

4.  负责引导App下载的栏目位于第二栏居中，相对来说，中间点开的随机可能性是三栏最小的，站在用户的角度，我们需要考虑到这样一种心理状态：**“我都已经关注你公众号了，还要特地去下一个App看在你的商城里买东西，我又不是没有淘宝或者其他购物软件，除非我是脑残粉，或者积分利益驱动，不然我懒得下载。”**所以我的解决方案就是“万达式”的，**任务模式+利益驱动**，栏目设置成“微信福利”，同时在App内同步打卡数据，一方面促进用户使用App，一方面让用户看到栏目能实现的价值。当然甲方还可以配上线上活动优惠券等营销手法，比如设置H5抽奖、游戏等活动，来突出“下载App”可以的到百盛更好的服务等，空出这个位置待后期。

5.  可以通过原型图边上的备注看出，菜单1、2都是可以引导到菜单3的，同时菜单3也等于是个流程的总和，达到了设计的核心。

    ​

# 五、项目后续

你真的想知道吗？

哈哈！**未被采用！**因为当年我在公司的时候，负责这个项目的人不是我，而且我们是乙方公司，甲方想换乙方是分分钟的事情。

当时看到这个项目的时候，是售前项目，也就是说，就算我们给甲方公司做好了竞品和原型，甲方也可以不用，找别的公司开发，其中的原因有四个：a.我们做得不得甲方所愿，b.价格问题；c.甲方负责人有多个，并且是竞争关系；d.甲方领导已承诺了其他合作公司，借我们的成品拿去给其他公司实现。

事实上具体什么情况我也不知道，因为后来我辞职自学UX设计了，我纯粹是对这个项目感兴趣而做的设计方案。分享给各位。 因为之前的工作是做新媒体运营和文案的工作，交互设计，用户体验设计都是自学的，所以就拿来实践一下。以上，仅供参考，我非常想从事UX/UE/交互工作，学了各种书和软件。本文只是个人小见，如果不符合的地方请指出！与君共勉！