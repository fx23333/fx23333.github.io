---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<style>class='newfont'</style>


<span class='anchor' id='about-me'></span>
<link rel="stylesheet" type="text/css" href="../assets/css/newfont.css">

# 🏫 Background
- **专业排名**：前四学期：5/144（3.4%），其中第二学年在年级中成绩排名：1/144，并获**国家奖学金**
- **语言能力**：以良好成绩通过CET4(639)；本科阶段所有英语课程均获满绩(4.0)，其中《英国社会与文化》课程获97分，(根据公共课成绩分析系统)卷面成绩排名全校第一；常在codeforces上刷题，长时间面对英文题面，具备良好英语文献阅读能力
- **核心课程**：高等数学（97，94）、概率论与数理统计（97）、信息安全数学基础（96）、离散数学（92）、计算机组成原理（95，96）、算法设计与分析（94）、数字逻辑与EDA（98，95）、数据库系统（95）、操作系统原理（92）、编译原理（92）
- **编程能力**：编程常用语言为C++、Python、Go、Verilog；熟悉算法与数据结构，抽象能力强，代码风格良好；熟悉Linux系统如Ubuntu，Kali的使用；熟悉IDA、OllyDebug等工具的使用；熟悉x86汇编语言；熟悉计算机体系结构、操作系统相关知识；熟悉分布式系统基础（分布式计算框架-如MapReduce/Spark；分布式存储/文件系统-如GFS/Frangipani；分布式事务/数据库-如2PC/Spanner/FaRM/Aurora；分布式中间件-如：Memcached/ZooKeeper；一致性算法-如Raft/CRAQ）
- **开发工具**：VS Code，PyCharm，Clion，Vivado，LaTeX(Overleaf)，Git
- **在校荣誉**：曾获**2022年度国家奖学金（该年度年级成绩排名为：1/144）**、武汉大学甲等奖学金（5%）、武汉大学三好学生、武汉大学优秀学生、武汉大学优秀共青团员及多项竞赛奖金，在校累计获奖金额逾30000元

# 🔥 News
- *2023.10*: &nbsp;🎉🎉 我在2022-2023学年年度综合素质测评中取得了1/144的成绩排名，并获**国家奖学金**、武汉大学优秀学生甲等奖学金以及武汉大学三好学生. 
- *2023.10*: &nbsp;🎉🎉 《慧音Guardian-物联网语音安全领航者》在2023年全国高校商业经营挑战赛创新创业竞赛创业计划赛道全国总决赛中荣获**一等奖**.
- *2023.06*: &nbsp;🎉🎉 《基于在线学习的异常流量实施分析系统》在中国大学生计算机设计大赛中南赛区中荣获**二等奖**.
- *2023.06*: &nbsp;🎉🎉 《从“堆盒子”到“动态规划”》在中国大学生计算机设计大赛中南赛区中荣获**三等奖**.
- *...*

# 💻 laboratory
- [MapReduce实现](https://github.com/fx23333/MapReduce)
- [Raft实现](https://github.com/fx23333/Raft)

# 📁 Research Experience

- <span class="xingkai" style="font-size: 30px;">分布式系统</span>
  - **<span class="youyuan">【分布式系统】</span>**<span class="fangsong">基础知识</span>
    - **【一致性算法】**为了实现各种一致性，需要使用一些一致性算法。尽管Paxos作为奠基者，其理解难度过大，并且现实世界中各方对Paxos的实现略有不同。而Raft则是一种更清晰、更易理解、更易部署的算法。**本人基于MIT6.824的Lab2，完成了一个Raft算法的实现**（为了实现Raft算法，本人还对Go的并发控制模型（[Go Concurrency Control Models](https://1drv.ms/b/s!AlxOiC78JsFshzmlIgVBPy5FLHwf?e=fWELY7)）、RPC等（[Go Basic](https://1drv.ms/b/s!AlxOiC78JsFshy-SkKhTkYJThoe1?e=CcZrWX)）知识做了一些了解）。除[Raft](https://1drv.ms/b/s!AlxOiC78JsFshzuYS6XiHRpToK2M?e=xlLGMC)外，本人还熟悉[CRAQ](https://1drv.ms/b/s!AlxOiC78JsFshz_7G171B1pCnimm?e=p8YcRV)
    - **【分布式计算】**本人对[MapReduce](https://1drv.ms/b/s!AlxOiC78JsFshx0JxilRuCR3BA3L?e=gcKofn)和[Spark](https://1drv.ms/b/s!AlxOiC78JsFshyZD71qUeBMombKR?e=WoWqhm)均比较熟悉。各类分布式文件系统/存储系统的设计，为分布式计算提供了基础设施。例如MapReduce建立在GFS之上，Spark以HDFS为依托。尽管前者作为Google三驾马车之二，但其类批处理的模式、单一的运算和较高的编程要求，使其正在逐渐淡出历史舞台；而Spark的RDD高级抽象，基于内存迭代的计算方式、基于DAG的任务调度等特性使得Spark在面临数据挖掘、机器学习等任务时具有更强的竞争力（尽管受到了Flink等框架的挑战）
    - **【分布式存储】**本人熟悉的分布式存储系统包括[Google File System](https://1drv.ms/b/s!AlxOiC78JsFshzQfDVS3oCI_8tH3?e=7Ejojc)、[Frangipani](https://1drv.ms/b/s!AlxOiC78JsFshx60xxiA__QylCER?e=BeK5CC)和[COPS](https://1drv.ms/b/s!AlxOiC78JsFshyowetpTrtzcIqw_?e=EcbRh5)。GFS作为Google三驾马车之一，具有其创新性。GFS相比以往的分布式文件系统，认为部分服务器的故障是一种常态。因此，将持续监测、错误检测、容错、自动恢复纳入GFS必不可少的重要功能，并且可以与MapReduce在同一集群上协作；Frangipani由于其针对Cache一致性的相关设计而独树一帜；相较之下，COPS则提出了因果一致性的相关设计方案
    - **【分布式中间件】**本人了解的分布式中间件包括[Zookeeper](https://1drv.ms/b/s!AlxOiC78JsFshzz47WBS-InTO8Z0?e=RDlAiZ)和[Memcached](https://1drv.ms/b/s!AlxOiC78JsFshyfS8kg25dJFlkFQ?e=5XzXJz)。ZooKeeper的设计为别的分布式系统提供了更简单的同步原语，例如FaRM就通过ZooKeeper来管理其Configuration信息；Memcached介于Server和DB之间，显著降低DB的负载且显著增大吞吐量
    - **【分布式数据库】**本人熟悉的分布式数据库包括[Aurora](https://1drv.ms/b/s!AlxOiC78JsFshxxUNsHA7Ykbw-VU?e=NBJBFf)、[Spanner](https://1drv.ms/b/s!AlxOiC78JsFshyIaFswhNN1lBj-D?e=YL7qDb)和[FaRM](https://1drv.ms/b/s!AlxOiC78JsFshyFtzeSmouGvy7uM?e=CNnPBK)。Aurora基于亚马逊开发的各类基础设施构建，包含一个多租横向存储服务，此存储服务抽象了一个虚拟化的分段redo log，并且和分布式数据库集群的实例（instance） 是松耦合的，Aurora通常被认为是一个CA系统；Spanner则利用Paxos机制配合2PC协议达到强一致性，根据谷歌CIO的说法，Spanner从技术上是一个CP系统，但仍然提供了非常高的可用性；FaRM则充分利用了硬件特性RDMA和内核旁路机制，然而正是由于RDMA的运用，使得其分布式事务协议显得更加复杂；同时，本人还了解分布式数据库经常使用的分布式事务协议（例如[2PC](https://1drv.ms/b/s!AlxOiC78JsFshyCylPPq58laeI5h?e=uM6RXV)）
    - **【区块链/去中心化】**本人对于这块内容主要了解[Bitcoin](https://1drv.ms/b/s!AlxOiC78JsFshy6gYf3LSlSwz_-9?e=Ifl8v9)、[BlockStack](https://1drv.ms/b/s!AlxOiC78JsFshzLuTLpsF6514n5k?e=6ja32l)和[Certificate Transparency](https://1drv.ms/b/s!AlxOiC78JsFshyzDkBlIQN3dOteW?e=eWjHmh)等知识。区块链充分利用了密码学哈希来实现Proof of Work来达成各个结点的共识，并且较为有效地解决了Fork Consistency的问题；而Blockstack则建立于比特币之上，试图构建一个去中心化应用架构；而证书透明度则利用一种审计的视角来提供网络站点证书的管理，可以防范并追踪中间人攻击

  - <span class="youyuan">【分布式系统】</span><span class="fangsong">分布式系统理解</span>
    - **【分布式系统部署的必然性】**分布式系统在计算机网络体系和理论逐渐完善、互联网数据膨胀导致需要兴建大量数据中心和云计算的兴起等多方面因素的共同作用下应运而生。在单结点性能不能满足庞大数据吞吐量的情况下，分布式系统的部署成为必然
    - **【分布式系统依赖底层基础设施】**绝大部分分布式系统架构的设计依赖于底层计算机网络、计算机体系结构和计算机操作系统的支持。例如VMWare FT的解决方案需要在Primary 向backup传送定时器中断后，在对应的指令处由backup的处理器也产生中断；在Memcached中，充分利用了TCP可靠性高和UDP传输效率高的特点，分别用于实现get和set操作；在GFS的设计中，其chunk只不过是Linux文件系统中的一个普通文件
    - **【复制和分片】**通常为了获得更好的性能，分布式系统会采复制/分片两种方案。复制能够有效地降低大吞吐量场景下单个结点的负载并且（部分分布式系统）允许读取本地replica，能有效降低传播时延；分片则提供了更好的拓展性，可以满足数据动态增长的需求。两种方式各有利弊，但并非对立。Memcached的实现就充分结合了两者的优点：在Region之间使用复制，在同一cluster内则利用一致性哈希协议，采用分片的方案，Frangipani亦是如此（个人愚见，对于分布式存储系统/文件系统而言，分片是根本要求，而复制则是可用性的必然保障，两者应该兼具）
    - **【可用性、一致性和分区容错性】**一个具有大规模结点的分布式系统必然会有容错的要求。容错通常使用非易失性内存和复制两种方式。FaRM就是使用非易失性内存的典范。对于复制而言，会额外产生一致性的问题。一致性可以简单分为强一致性/可线性化和弱一致性（最终一致性、因果一致性等）。CAP定理证明了一个分布式系统不可能同时兼具可用性、一致性和分区容错性。现实中，相当的设计舍弃了强一致性
    - **【作为上层应用的基础设施】**目前，深度学习迅速发展，而分布式系统的脚步也从未停歇。近来，本人接触到了网内计算的相关概念，其充分利用了各类网络设备，有效地提高了深度神经网络的计算性能

  - <span class="youyuan">【学习计划】</span>
    - 因为接触时间较短，我目前的知识水平可能还比较有限，但我具有足够的毅力决心以及对分布式系统领域十足的兴趣，所以会在未来进一步学习系统相关的知识。我计划继续完成MIT6.824的学习和Lab，剩余内容已经不多，相信很快就能完成；我还会再利用剩余时间，去完成高质量的操作系统lab（本校的操作系统实验使用ia32架构，并且对于多进程调度等内容涉及较少，但相应地收获了很多x86汇编的知识），例如MIT6.828等；同时我也将广泛涉猎编译原理、计算机体系结构等领域的相关知识并阅读近年来分布式系统领域的[经典论文](https://iswade.github.io/02_distributed_system_paper)
- <span class="xingkai" style="font-size: 30px;">人工智能安全</span>
  - <span class="youyuan">【人工智能-人工智能安全】</span> <span class="fangsong">对基于后门的深度神经网络水印的新型保护方法</span>
    - 针对痛点：（1）深度学习网络存在被窃取的风险，被窃取后无法证明归属权，现今常用用嵌入水印的方式来证明模型的归属权（IP）；（2）DNN水印鲁棒性较差，对fine-tune攻击防御能力差；（3）目前大多数研究都着眼于设计更鲁棒的水印方法，设计新型后门来让模型在被fine-tune之后水印仍然可以保留，而由于水印是基于神经网络后门的，水印的鲁棒性受限于后门技术的发展，很难做到在不影响原本神经网络功能的情况下去嵌入稳固的水印，此种旧思路目前暂时难获得较好的进展
    - 我们则使用了一种巧妙的“逆思维”解决思路完美地解决了这个问题




# 📚 Project
- <span class="youyuan">【人工智能-自然语言处理】</span><span class="fangsong">Kaggle：Feedback Prize-Evaluating Student Writing</span>
  - 访问了有史以来最大的学生写作数据集，对6至12年级学生撰写的论文中的文本进行分段，并对议论性和修辞性元素进行分类，帮助虚拟写作导师和自动写作系统利用这些算法减少评分时间，印证了自己在自然语言处理方面的优秀能力
  - **【比赛方案】**（1）数据方面首先对官方数据中一些不干净的原标签进行修复；（2）整体的方案采用了Longformer+Deberta的双模型融合；（3）为防止过拟合，尝试在模型头部位置加入Dropout层；（4）训练出了Longformer-base-4096和Deberta-large两个模型，并在模型预测出结果后，使用了后处理的方式来进一步筛选预测的实体，主要是对每种实体的最小长度和最小置信度做出限制，如果小于阈值则被后处理筛掉；（5）最后进行CV-10-Fold和简单的加权融合
  - **取得了的0.712的Final Score，最终摘得本次竞赛的银牌（88 / 2058）**，[Feedback Prize Leaderboard](https://www.kaggle.com/competitions/feedback-prize-2021/leaderboard)

- <span class="youyuan">【人工智能-自然语言处理】</span><span class="fangsong">实体-立场分析（数据集构建和模型微调）</span>
  - 针对实验所选择的“两岸关系”、“疫苗”话题领域，对一段输入文本，识别文本中的实体，并给出该实体对于话题的立场
  - 利用序列标注的方法来解决—解决的核心便是序列标签的设计：经典的序列标注任务中，标签只包含实体的边界信息和实体的类别信息。我们将实体的立场信息同样地通过标签表现出来，由于立场信息、边界信息和类别信息这三者并不相互包含和重叠，因此，我们直接将实体的立场信息直接附加在原有的标签之后，将实体立场分析创新地转化为“立场嵌入式实体识别”任务
  - <span class="kaishu">相关工作被评为课程Best Project</span>

- <span class="youyuan">【语音安全】</span> <span class="fangsong">Smart Music Guardian：智能语音攻击防御系统</span>
  - 伴随着智能语音市场的规模逐年递增和“语音控制”的普及，智能语音攻击也正逐渐兴起——它是指语音攻击是指恶意攻击者通过无声远程操控的方式，达到侵入智能设备语音控制系统的目的，并带来诸多隐患
  - 提出了一套系统的解决方案，立足于传统语音攻击【识别精度低】、【无法提供预警】、【难溯攻击源】的缺陷，分别针对性地提出并设计了【智能语音攻击检测模型】、【群智感知搜集监测平台】、【攻击态势识别预警提醒】，在终端设备物联网的语音安全效能方面实现了良好的改进
  - <span class="kaishu">相关作品获全国高校商业精英挑战赛创新创业竞赛国家级一等奖</span>


- <span class="youyuan">【网络安全】</span> <span class="fangsong">基于在线学习的异常流量实时分析系统</span>
  - 目前，各种类型的流量充满了网络空间，其中包含了正常上网业务，具有CVE编号的网络攻击、计算机病毒（邮件病毒、木马、蠕虫、勒索软件）等。如何开发出一个网络安全系统，能够有效地流量数据进行检测、分析与分类以及针对常见攻击的检测，并实时识别出网络上的恶意攻击行为成为现阶段面临的一个挑战
  - 在对网络流量分析的现有研究中，都面临了准确性和可靠性低的问题，而本项目使用模型融合的时空深度学习网络对不同类型的流量进行分类，取得了良好的效果
  - <span class="kaishu">相关作品获中国大学生计算机设计大赛中南地区赛二等奖</span>


- <span class="youyuan">【计算机基础教学】</span><span class="fangsong">从“堆盒子”到动态规划</span>
  - 算法自身的抽象性往往是同学们算法学习的最大阻碍，而“化抽象为具象”的最佳方法便是对算法进行“可视化”。
  - 本作品采用了与著名博主3Blue1Brown所同源的基于Python的数学动画制作引擎Manim来制作，自主编写3000余行代码，配合后期大量的代码微调、剪辑、配音、AI字幕搭配工作，最终得以完成本次作品
  - 将视频发布到了Manim爱好者的交流社群中，在本院同学之间进行测试反馈和迭代，再到各高中乃至高校进行应用推广，均收到了良好反馈
  - <span class="kaishu">相关作品获中国大学生计算机设计大赛中南地区赛三等奖</span>


- <span class="youyuan">【“互联网+”创新创业】</span> <span class="fangsong">启阳计划：教育、公益、就业有机结合平台</span>
  - 以自主研发的具有学员课程培训、企业人才遴选等多功能的集成性“启阳伴学”小程序为平台，前期独创“行教”模式与公益结合，致力于改变教育资源分配不均衡的问题，后期将业务范围扩充至多栖教育领域，通过独有的校园壁垒、完备的评价体系定向输送新生血液，为全教育行业提供接触优秀大学生的广阔平台
  - <span class="kaishu">项目于2022年上半年正式投入运营，团队创收10w+；并获马云主办的“善创未来·美好大会”全球青年社会创新大赛全国总决赛二等奖</span>


- <span class="youyuan">【数据库系统】</span><span class="fangsong">安全可信的数据库系统设计</span>
  - 在 Linux+MySQL+HTML/css/JavaScript+Flask下设计完成一个前端Web界面+后端数据库系统的网站
  - 主要实现任务有：数据库操作以及应用与数据库交互过程的编写、防止 SQL 注入的基本功能、数据库并发、数据备份与恢复、数据库完整性检查等功能的实现、不同类型的用户权限访问控制、简单的前端界面
  - <span class="kaishu">相关工作被评为Excellent Project（课程得分：95/100）</span>

- <span class="youyuan">【系统安全】</span><span class="fangsong">信息系统安全实践</span>
  - 依托OllyDebug和IDEA等工具对真实的恶意样本逻辑进行分析，使用AFL对恶意样本进行模糊测试、探索Selinux相关安全机制的原理与使用
  - 使用Kali和Metasploit对靶机进行渗透测试，深入了解经典漏洞ms08-067的原理和利用方法。此外，还使用永恒之黑在Windows 10平台下进行渗透测试，对永恒之黑漏洞进行详尽的原理分析，并且与永恒之蓝
  漏洞进行对比，获得老师的好评


# 📘 竞赛经历

|:------|:-------:|------:|
|全国高校商业精英挑战赛-创新创业竞赛：一等奖|团体|国家级|
|“善创未来·美好大会”全球青年社会创新大赛：二等奖|团体|国家级|
|“Kaggle：Feedback Prize - Evaluating Student Writing：88/2058（银牌）|团体|国家级|
|蓝桥杯全国软件和信息技术专业人才大赛（湖北赛区）：二等奖|个人|省部级|
|中国大学生计算机设计大赛（中南地区赛）：二等奖|团体|省部级|
|中国大学生计算机设计大赛（中南地区赛）：三等奖*2|团体|省部级| 
|“互联网+”大学生创新创业大赛（武汉大学校赛）：一等奖|团体|市校级|
|“互联网+”大学生创新创业大赛（武汉大学校赛）：二等奖|团体|市校级|



# 📖 Educations
- *2021.09 - 2023.11 (now)*, 武汉大学国家网络安全学院. 
- *2018.09 - 2021.06*, 上海市控江中学. 
- *2014.09 - 2018.06*, 上海市民办金盟中学. 


# 💻 Internships
- *2023.04 - 2023.09*, 武汉大学国家网络安全学院珞珈之戍实验室.
