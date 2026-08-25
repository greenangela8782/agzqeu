最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计数据库版本迁移回滚方案
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.afedlm.asia/blog/8653615.sHtML

原标题：坑点：环境配置写死代码，上线忘记修改
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://book.afedlm.asia/blog/7871996.sHtML

原标题：golang k8s cronjob 定时任务配置
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://book.afedlm.asia/blog/3734029.sHtML

原标题：golang 系统设计分布式事务几种方案
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://book.afedlm.asia/blog/4494064.sHtML

原标题：golang 数据库批量更新性能优化
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://book.afedlm.asia/blog/6109237.sHtML

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://book.afedlm.asia/blog/0106217.sHtML

原标题：开源项目构建失败排查步骤
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.afedlm.asia/blog/9655698.sHtML

原标题：部署实践：服务器时间同步chrony配置
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://book.afedlm.asia/blog/4135230.sHtML

原标题：无用对象回收抑制内存上涨
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.afedlm.asia/blog/5986366.sHtML

原标题：golang k8s 基础概念 pod deployment
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.afedlm.asia/blog/4728658.sHtML

原标题：golang 日志与链路 ID 关联打印
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://book.afedlm.asia/blog/1912610.sHtML

原标题：缓存穿透防护保护数据库
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://book.afedlm.asia/blog/1254009.sHtML

原标题：golang 系统设计容量评估简单方法论
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://book.afedlm.asia/blog/5126010.sHtML

原标题：坑点：软链接权限问题容器读取文件失败
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://book.afedlm.asia/blog/6105425.sHtML

原标题：golang 系统设计用户签到统计方案
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.afedlm.asia/blog/5283804.sHtML

原标题：golang 系统设计测试环境预发环境生产环境隔离
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://book.afedlm.asia/blog/4874673.sHtML

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://book.afedlm.asia/blog/9392708.sHtML

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://book.afedlm.asia/blog/7439195.sHtML

原标题：golang 系统设计故障预案编写模板参考示例
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://book.afedlm.asia/blog/4259574.sHtML

原标题：服务熔断防止故障级联传播
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://book.afedlm.asia/blog/2655688.sHtML

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://book.afedlm.asia/blog/1822504.sHtML

原标题：golang 系统设计创建更新时间自动维护方案
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://book.afedlm.asia/blog/6489198.sHtML

原标题：序列化版本不一致解析失败
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://book.afedlm.asia/blog/1720232.sHtML

原标题：Redis 内存淘汰策略数据防丢失
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://book.afedlm.asia/blog/3863168.sHtML

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://book.afedlm.asia/blog/3769726.sHtML

原标题：golang 系统设计配置多环境本地开发适配方案
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://book.afedlm.asia/blog/3436576.sHtML

原标题：消息队列消费堆积扩容处理
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.afedlm.asia/blog/7153284.sHtML

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://book.afedlm.asia/blog/9356576.sHtML

原标题：入门实践：实现简单文件读写功能
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://book.afedlm.asia/blog/9738804.sHtML

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://book.afedlm.asia/blog/3763672.sHtML

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://book.afedlm.asia/blog/9308256.sHtML

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://book.afedlm.asia/blog/2769359.sHtML

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://book.afedlm.asia/blog/6124610.sHtML

原标题：零基础理解模块化与组件化基础思想
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://book.afedlm.asia/blog/3754312.sHtML

原标题：golang 分布式锁防死锁处理
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://book.afedlm.asia/blog/4221464.sHtML

原标题：依赖版本冲突兼容修复方案
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://book.afedlm.asia/blog/8697272.sHtML

原标题：golang 系统设计配置灰度下发简单实现思路
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://book.afedlm.asia/blog/4501779.sHtML

原标题：CI/CD 流水线自动构建部署落地
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://book.afedlm.asia/blog/7649865.sHtML

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://book.afedlm.asia/blog/5315900.sHtML

原标题：大事务拆分回滚日志暴涨解决
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.afedlm.asia/blog/0841794.sHtML


二、踩坑排错｜Troubleshooting
原标题：golang cron 定时任务防并发执行
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://book.afedlm.asia/blog/0727438.sHtML

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://book.afedlm.asia/blog/7435570.sHtML

原标题：避坑：请求未设置read超时无限挂起连接
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://book.afedlm.asia/blog/4819403.sHtML

原标题：react hooks 常见陷阱避坑指南
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://book.afedlm.asia/blog/5061164.sHtML

原标题：Hands‑on：简易速率限制中间件完整实现
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.afedlm.asia/blog/7575107.sHtML

原标题：AI实践：大模型生成测试用例实践与校验
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://book.afedlm.asia/blog/9467006.sHtML

原标题：golang 批量任务协程控制防雪崩
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://book.afedlm.asia/blog/2513133.sHtML

原标题：安全实践：敏感信息加密存储传输完整方案
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://book.afedlm.asia/blog/4493793.sHtML

原标题：golang 系统设计故障预案编写模板参考示例
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.afedlm.asia/blog/2116047.sHtML

原标题：Git 代码冲突正确处理方式
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://book.afedlm.asia/blog/1510198.sHtML

原标题：golang 系统设计架构图绘图工具选型对比
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.afedlm.asia/blog/9368027.sHtML

原标题：项目脚手架模板生成工具
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.afedlm.asia/blog/2036483.sHtML

原标题：golang 系统设计多级缓存更新策略
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://book.afedlm.asia/blog/6634597.sHtML

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://book.afedlm.asia/blog/1321689.sHtML

原标题：项目实践：灰度发布简易方案落地实践
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://book.afedlm.asia/blog/2370491.sHtML

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://book.afedlm.asia/blog/8842277.sHtML

原标题：golang 优雅处理 http 超时设置
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://book.afedlm.asia/blog/5702254.sHtML

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.afedlm.asia/blog/1948706.sHtML

原标题：golang pprof 线上采集性能数据
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://book.afedlm.asia/blog/4547317.sHtML

原标题：golang github actions 缓存依赖提速
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://book.afedlm.asia/blog/9797629.sHtML

原标题：实战项目：GitHubAction自动测试构建实践
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://book.afedlm.asia/blog/3985051.sHtML

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://book.afedlm.asia/blog/8058460.sHtML

原标题：nodejs redis 缓存业务实战
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://book.afedlm.asia/blog/4588728.sHtML

原标题：安全复盘：定时任务权限过大风险管控
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.afedlm.asia/blog/8930252.sHtML

原标题：安全笔记：CORS跨域配置错误安全风险
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.afedlm.asia/blog/9658627.sHtML

原标题：Architecture：事件溯源架构模式适用业务场景
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://book.afedlm.asia/blog/3599445.sHtML

原标题：前端水印防信息泄露实现
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.afedlm.asia/blog/9032255.sHtML

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://book.afedlm.asia/blog/3869318.sHtML

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.afedlm.asia/blog/7171502.sHtML

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.afedlm.asia/blog/8094724.sHtML

原标题：开发记录：容器日志标准输出采集实践方案
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://book.afedlm.asia/blog/2624357.sHtML

原标题：Debug：网关超时时间小于后端接口超时设置
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://book.afedlm.asia/blog/0930946.sHtML

原标题：排错：打包后资源路径，开发生产行为不一致
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.afedlm.asia/blog/3832249.sHtML

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.afedlm.asia/blog/9389595.sHtML

原标题：AI实践：大模型生成测试用例实践与校验
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://book.afedlm.asia/blog/0490983.sHtML

原标题：实战：Docker资源监控查看容器状态实操
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://book.afedlm.asia/blog/0885595.sHtML

原标题：golang 消息队列 kafka 消费开发
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://book.afedlm.asia/blog/6344521.sHtML

原标题：主干开发团队代码合并策略
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://book.afedlm.asia/blog/4384135.sHtML

原标题：定时任务重复执行分布式锁
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://book.afedlm.asia/blog/8800831.sHtML

原标题：golang 系统设计创建更新时间自动维护方案
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://book.afedlm.asia/blog/1000178.sHtML

三、实战开发｜Practice
原标题：Redis 热点 key 拆分降低集群压力
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://book.afedlm.asia/blog/0849863.sHtML

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://book.afedlm.asia/blog/4466088.sHtML

原标题：新手指南：如何读懂开源项目报错日志
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.afedlm.asia/blog/5258595.sHtML

原标题：前端大文件分片上传完整方案
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.afedlm.asia/blog/6371955.sHtML

原标题：从零学习简单分页逻辑实现思路
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://book.afedlm.asia/blog/4971382.sHtML

原标题：零基础理解读写分离基础思想
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.afedlm.asia/blog/2354273.sHtML

原标题：golang 系统设计开源项目协作流程梳理
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://book.afedlm.asia/blog/0010447.sHtML

原标题：避坑：正则回溯引发CPU占满DoS风险
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://book.afedlm.asia/blog/9349321.sHtML

原标题：实践：消息队列死信处理业务落地实践
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://book.afedlm.asia/blog/1107796.sHtML

原标题：Performance：JSON序列化性能优化实践
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://book.afedlm.asia/blog/4521721.sHtML

原标题：Practice：模拟热点key，验证缓存防护策略
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://book.afedlm.asia/blog/2448721.sHtML

原标题：用户敏感数据脱敏代码实现
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.afedlm.asia/blog/8972860.sHtML

原标题：安全实践：API密钥管理轮换最佳实践
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.afedlm.asia/blog/6426894.sHtML

原标题：Security：服务器最小权限账号运维实践
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://book.afedlm.asia/blog/8756834.sHtML

原标题：开发复盘：批量任务进度持久化实现方案
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://book.afedlm.asia/blog/8536794.sHtML

原标题：Practice：简易限流器分布式版本Redis实现
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://book.afedlm.asia/blog/9325779.sHtML

原标题：golang 系统设计对象池复用减少内存分配
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://book.afedlm.asia/blog/6050028.sHtML

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://book.afedlm.asia/blog/9229531.sHtML

原标题：部署实践：告警收敛避免告警风暴配置
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.afedlm.asia/blog/1526131.sHtML

原标题：接口签名校验防篡改实现
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://book.afedlm.asia/blog/7967372.sHtML

原标题：golang 系统设计架构图绘制规范简单建议
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://book.afedlm.asia/blog/9331683.sHtML

原标题：golang 数据库连接泄露排查
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://book.afedlm.asia/blog/1595875.sHtML

原标题：golang minio 存储桶权限管控配置
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://book.afedlm.asia/blog/7494821.sHtML

原标题：WSL 搭建 Windows Linux 开发环境
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://book.afedlm.asia/blog/6067322.sHtML

原标题：Hands‑on：简易邮件发送服务封装实践
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.afedlm.asia/blog/4137080.sHtML

原标题：golang 系统设计避免索引失效书写 sql 原则
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://book.afedlm.asia/blog/6860902.sHtML

原标题：Fork 开源项目同步上游代码
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.afedlm.asia/blog/5663938.sHtML

原标题：Hands‑on：简易速率限制中间件完整实现
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://book.afedlm.asia/blog/0479932.sHtML

原标题：HelloTest：理解集成测试基础编写思路
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://book.afedlm.asia/blog/6196240.sHtML

原标题：Practice：实现异步回调处理通用组件封装
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://book.afedlm.asia/blog/4287877.sHtML

原标题：golang docker 部署 kafka 本地调试
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://book.afedlm.asia/blog/9761491.sHtML

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://book.afedlm.asia/blog/3432176.sHtML

原标题：新手向：开源项目依赖安装失败排查
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://book.afedlm.asia/blog/6400565.sHtML

原标题：系统文件描述符上限调大
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://book.afedlm.asia/blog/7064842.sHtML

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://book.afedlm.asia/blog/7109198.sHtML

原标题：WebSocket 断线重连稳定优化
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://book.afedlm.asia/blog/5806395.sHtML

原标题：数据库主从延迟业务兼容处理
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://book.afedlm.asia/blog/8390611.sHtML

原标题：golang 项目 go mod 依赖管理
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://book.afedlm.asia/blog/8979791.sHtML

原标题：后端登录鉴权模块完整开发
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://book.afedlm.asia/blog/2708765.sHtML

原标题：新手指南：如何读懂开源项目报错日志
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://book.afedlm.asia/blog/0542508.sHtML

四、架构设计｜Architecture
原标题：内存泄漏定位分析完整流程
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://book.afedlm.asia/blog/8928551.sHtML

原标题：实战项目：实现分布式任务调度最小原型
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.afedlm.asia/blog/2054042.sHtML

原标题：golang 简易埋点日志上报实现
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://book.afedlm.asia/blog/3917527.sHtML

原标题：开源项目构建失败排查步骤
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://book.afedlm.asia/blog/4129970.sHtML

原标题：golang 系统设计定时任务调度时间校准要点
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://book.afedlm.asia/blog/7894494.sHtML

原标题：golang 内存缓存简单实现方案
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://book.afedlm.asia/blog/5016350.sHtML

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://book.afedlm.asia/blog/1646313.sHtML

原标题：golang 灰度权重流量分发简单实现
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://book.afedlm.asia/blog/9721958.sHtML

原标题：架构复盘：多实例部署业务状态无状态改造
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://book.afedlm.asia/blog/0237584.sHtML

原标题：后端登录鉴权模块完整开发
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.afedlm.asia/blog/8403099.sHtML

原标题：零基础理解前后端简单交互流程
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://book.afedlm.asia/blog/8192670.sHtML

原标题：HelloTest：理解集成测试基础编写思路
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://book.afedlm.asia/blog/6767753.sHtML

原标题：从零搭建简单CLI命令行工具
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://book.afedlm.asia/blog/6745164.sHtML

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://book.afedlm.asia/blog/0561072.sHtML

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://book.afedlm.asia/blog/2628122.sHtML

原标题：架构复盘：热点数据防护架构防止节点过载
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://book.afedlm.asia/blog/1525199.sHtML

原标题：数据库连接池参数调优
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://book.afedlm.asia/blog/9016904.sHtML

原标题：golang 系统设计 git 工作流本地开发提交流程
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://book.afedlm.asia/blog/5166985.sHtML

?
