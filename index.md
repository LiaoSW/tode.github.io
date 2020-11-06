---
layout: home
header:
  title: 全球领先的数字能源技术提供商
  text: >
    帮助用户实现数字能源转型，为用户在电力市场中掌握主动！
  action: # action button is optional
    label: 了解更多
    url: '#about'


sections:
  - type: call-to-action.html
    section_id: about
    background_style: bg-primary
    title: 企业介绍
    text: >-
      南京图德科技有限公司坐落于南京市栖霞区紫东国际创意园，成立于2020年4月，注册资本1250万元，是一家致力于提供能源电力领域人工智能解决方案的科技型企业。公司与华中科技大学SGO实验室产学研深度合作，与广东、湖北、江苏等省份建立合作关系。
      2015年国务院9号文颁布以来，我国已经在广东、浙江等8省份启动电力现货试点工作。自2019年下半年以来，能源局更是连续5次密集出台电改相关政策，电力市场建设工作加速推进。预计到2025年，我国电力市场年交易规模将超过10万亿千瓦时。其催生出的电力交易信息化市场需求，每年空间达到50亿元。
      目前国内电力市场经济优化问题求解都依赖美国公司商业求解器，售价昂贵且存在技术封锁风险。公司研发了现货电力市场领域最先进的出清求解引擎，可以有效解决目前电力市场模拟平台效率低，成本高的问题，能够全面替代国外求解器，同时速度提高近30倍，填补了相关领域空白，突破核心技术非自主研发的“卡脖子”问题。中国科学院院士程时杰评价本项目产品在电力现货交易细分行业具有革命性的核心技术。
      公司开发电力市场交易及智能决策成套软件，针对各省实际情况及客户实际需求，在自主研发核心算法基础上做定制化服务。该软件能够作为各省电力交易中心的平台软件。同时能够为电厂、售电公司等客户提供市场模拟及交易辅助决策，帮助客户获得更大竞争收益。此外，能够为市场组织机构、电网调度与规划部门、投资机构、科研院所等提供交易模拟、收益分析、规划方案、竞价策略等深度解决方案，并提供软件开发、人员培训及相关咨询服务。

    infos:
    - title: 企业愿景
      text: 争做能源行业数字化、智能化发展的信息技术一流供应商
    - title: 企业文化 
      text: 精益求精 不断创新
    - title:  企业使命
      text: 服务客户需求  推动行业发展  奉献社会进步
#    actions:
#      - title: Get Started!
#        url: '#page-top'
#       class: btn-light

  - type: services.html
    section_id: services
    #background_style: bg-info
    title: 产品和服务
    services:
      - title: 软件开发、销售、租赁
        icon: fa-gem text-info
      - title: 现货市场相关资讯、培训
        icon: fa-paper-plane
      - title: 求解器定制开发
        icon: fa-laptop-code
      - title: 市场主体报价方案制定
        icon: fa-heart

  - type: software.html
    section_id: software
    #background_style: bg-info
    background_style: bg-info text-white
    title: 软件平台开发
    services:
      - title: 电力市场快速出清仿真系统
        text: 为客户提供100%自定义边界条件下的市场快速出清，模拟反演电力现货市场日前交易出清结果，并实现结果快速复现仿真。.
        icon: fa-gem text-info
        # url: https://startbootstrap.com/
      - title: 电力现货市场迭代预测系统
        text: 基于电力市场快速仿真模块，实现对电力现货市场日前交易的快速迭代预测，从而批量比对不同交易方案结果，形成最大交易报价方案。
        icon: fa-paper-plane
      - title: 发电现货交易辅助系统
        text: 针对发电企业定制化开发现货交易辅助系统，为企业提供现货交易管理、报价方案决策、历史决策分析、报价策略纠偏、出清结果展示等功能，支撑企业更好参与现货交易。.
        icon: fa-laptop-code
      - title: 售电现货交易辅助系统
        text: 针对售电企业定制化开发现货交易辅助系统，为企业提供套餐方案制定分析、交易策略方案订制等，实现售电企业在现货市场中收益最大化。.
        icon: fa-heart
      - title: 售电长协现货协同交易辅助决策系统
        text: 针对发电企业和售电企业，解决中长期电力市场与现货市场衔接的关键问题，提供中长期交易长协电量优化分解工具，实现市场交易年度优化。
        icon: fa-heart

  - type: engine.html
    section_id: engine
    #background_style: bg-info
    title: 引擎内核租赁
    services:
      - title: 电力市场快速出清引擎
        text: 现有普遍采用的基于混整线性规划的电力现货市场出清模型以及商业求解器，用于我国省级电网时存在求解速度瓶颈问题，单次求解时间过长，且求解器商业授权价格高、存在技术封锁风险。公司研发结合新一代求解技术的快速出清算法，实现了快速的市场出清推理，可以有效替代Cplex等商业求解器，同等规模电网下的求解速度达到传统方法的近30倍。
        icon: fa-gem text-info
        # url: https://startbootstrap.com/
      - title: 中长期交易优化引擎
        text: 该引擎有效模拟市场参与者不同市场行为、市场投资在电力市场中的中长期收益情况，大幅提高了市场中长期收益模拟的速度，实现了对市场中长期收益的预测，目前已经开发完成。同时能有效避免无解的问题，并大幅提高求解效率，相较于目前同等模型颗粒度的运行模拟软件，计算速度提高近3倍。
        icon: fa-paper-plane
      - title: 大电网中长期节点组合优化引擎
        text: 该引擎基于机组聚合的机组组合算法，该算法通过机组聚合以及变量连续化等处理，能够一次求解全年或多年机组组合问题，将中长期交易长协电量最优分解到月和日，可应用于可再生能源消纳配额、最优电源配比、跨区输电计划制定等，是目前国内唯一能够集中求解全年最优机组组合的算法。
        icon: fa-laptop-code
    
  - type: training.html
    section_id: training
    #background_style: bg-info
    background_style: bg-dark text-primary
    title: 培训
    services:
      - title: 交易员培训
        icon: fa-gem text-info
        # url: https://startbootstrap.com/
      - title: 电力市场知识培训
        icon: fa-paper-plane
      - title: 软件开发培训
        icon: fa-laptop-code

 # - type: portfolio.html
    # this section has always ID 'portfolio'
    #section_id: portfolio
    #background_style: bg-dark
  #  projects:
  #    - title: Project 1
  #      text: This is a very short project description.
  #      # the images are located in:
  #      # img/portfolio/fullsize
  #      # img/portfolio/thumbnails
  #      icon: 1.jpg
  #      url: '#'
  #    - title: Project 2
  #      text: This is a very short project description.
  #      icon: 2.jpg
  #      url: '#'
  #    - title: Project 3
  #      text: This is a very short project description.
  #      icon: 3.jpg
  #      url: '#'
  #    - title: Project 4
  #      text: This is a very short project description.
  #      icon: 4.jpg
  #      url: '#'
  #    - title: Project 5
  #      text: This is a very short project description.
  #      icon: 5.jpg
  #      url: '#'
  #    - title: Project 6
  #      text: This is a very short project description.
  #      icon: 6.jpg
  #      url: '#'

  # - type: aside.html
  #   section_id: aside
  #   title: Free Download at Start Bootstrap!
  #   actions:
  #     - title: Download Now!
  #       url: https://startbootstrap.com/themes/creative/
  #       class: btn-light

 #  - type: members.html
#    section_id: members
#    title: 团队成员
#    background_style: bg-info text-white
#    members:
#     - title: Christina M. Aponte
#        text: CEO
#        image: assets/img/members/person1.jpg
#       url: '#'
#      - title: Gary D. Stevens
#        text: CTO
#        image: assets/img/members/person2.jpg
#        url: '#'
#      - title: Devon J. Fletcher
#       text: CFO
#        image: assets/img/members/person3.jpg
#        url: '#'
#      - title: Todd E. Anderson
#        text: COO
#        image: assets/img/members/person5.jpg
#        url: '#'
#      - title: Daniel T. Riley
#        text: Chief Scientist
#        image: assets/img/members/person6.jpg
#        url: '#'
#      - title: Ella P. Walter
#        text: Chief Architect
#        image: assets/img/members/person7.jpg
#        url: '#'

  - type: trends.html
    section_id: trends
    title: 公司动态
    honor: 
      title: 获得荣誉
      image: assets/img/trends/honor.jpg
    coorperation: 
      title: 战略合作
      images: 
        - image: assets/img/trends/hehai.jpg
        - image: assets/img/trends/hust.jpg
    intellectual_property: 
        - image: assets/img/trends/1.jpg
        - image: assets/img/trends/2.jpg
        - image: assets/img/trends/3.jpg
        - image: assets/img/trends/4.jpg
        - image: assets/img/trends/5.jpg
        - image: assets/img/trends/6.jpg
        - image: assets/img/trends/7.png
        - image: assets/img/trends/8.png
        - image: assets/img/trends/9.png
        - image: assets/img/trends/10.png
        - image: assets/img/trends/11.png
        - image: assets/img/trends/12.png

  - type: contact.html
    section_id: contacts
    background_style: bg-light
    title: 联系我们
    image: assets/img/wxqrcode.jpg
    text: >-
      有商业合作需求？ 想要加入我们？ 欢迎给我们来电或发送邮件
      我们会尽快与您取得联系！
    infos:
    - title: 企业邮箱：business@tode.ltd
      icon: fa-phone
      url: mailto:business@tode.ltd
    - title: 网址：www.tode.ltd
      icon: fa-envelope
    - title: 地址：南京市栖霞区马群街道紫东路2号C11-101室（210046）
      icon: fa-weibo
      icon_type: fab


---
