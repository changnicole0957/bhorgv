最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Architecture：静态资源分发CDN整体架构思路
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.x9ogth.asia/arts/472449.Doc

原标题：主干开发团队代码合并策略
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.x9ogth.asia/arts/541102.Doc

原标题：golang redis 事务 multi exec 使用
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.x9ogth.asia/arts/301216.Doc

原标题：golang websocket 消息广播实现
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.x9ogth.asia/arts/538102.Doc

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.x9ogth.asia/arts/333235.Doc

原标题：golang 系统设计本地缓存与分布式缓存
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://wiki.x9ogth.asia/arts/316572.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.x9ogth.asia/arts/665454.Doc

原标题：开发记录：接口请求日志记录完整中间件实现
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://wiki.x9ogth.asia/arts/685876.Doc

原标题：前端图片懒加载性能优化
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.x9ogth.asia/arts/916264.Doc

原标题：golang 互斥锁读写锁并发安全
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.x9ogth.asia/arts/505886.Doc

原标题：安全实践：备份文件访问权限安全管控
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.x9ogth.asia/arts/781854.Doc

原标题：快速上手搭建简易内网测试服务
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.x9ogth.asia/arts/261023.Doc

原标题：golang k8s ingress 路由域名转发
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.x9ogth.asia/arts/619656.Doc

原标题：文件监控服务自动重启开发
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.x9ogth.asia/arts/149415.Doc

原标题：CPU 亲和性配置负载均衡调度
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.x9ogth.asia/arts/510150.Doc

原标题：大事务拆分防止连接池耗尽
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.x9ogth.asia/arts/089193.Doc

原标题：架构复盘：多实例部署业务状态无状态改造
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://wiki.x9ogth.asia/arts/852254.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.x9ogth.asia/arts/163713.Doc

原标题：性能复盘：内存泄漏定位，内存持续上涨优化
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.x9ogth.asia/arts/295566.Doc

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.x9ogth.asia/arts/304734.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.x9ogth.asia/arts/048203.Doc

原标题：golang 系统设计内存高占用排查思路
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.x9ogth.asia/arts/243915.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://wiki.x9ogth.asia/arts/381314.Doc

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.x9ogth.asia/arts/462102.Doc

原标题：网关集成鉴权限流日志一体化
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.x9ogth.asia/arts/227002.Doc

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.x9ogth.asia/arts/566623.Doc

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.x9ogth.asia/arts/233833.Doc

原标题：方案对比：定时任务框架选型与架构对比
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.x9ogth.asia/arts/036360.Doc

原标题：快速入门消息通知简单实现方案
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.x9ogth.asia/arts/719477.Doc

原标题：方案对比：同步事务vs事务消息最终一致性
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.x9ogth.asia/arts/485263.Doc

原标题：golang docker compose 环境变量
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.x9ogth.asia/arts/764906.Doc

原标题：架构笔记：高并发系统核心设计思路总结
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.x9ogth.asia/arts/888740.Doc

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.x9ogth.asia/arts/781207.Doc

原标题：golang 系统设计状态字段枚举约束设计思路
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.x9ogth.asia/arts/991113.Doc

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.x9ogth.asia/arts/820711.Doc

原标题：golang 系统设计重试退避策略业务落地
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.x9ogth.asia/arts/415433.Doc

原标题：快速入门容器基础概念，理解镜像与容器
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://wiki.x9ogth.asia/arts/309515.Doc

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.x9ogth.asia/arts/675627.Doc

原标题：pnpm 包管理工具实战避坑指南
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.x9ogth.asia/arts/485978.Doc

原标题：MySQL 慢查询索引优化实战
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.x9ogth.asia/arts/073139.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计配置多环境本地开发适配方案
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.x9ogth.asia/arts/890403.Doc

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.x9ogth.asia/arts/422541.Doc

原标题：磁盘 inode 耗尽文件创建失败
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.x9ogth.asia/arts/353216.Doc

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.x9ogth.asia/arts/529244.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.x9ogth.asia/arts/605940.Doc

原标题：复盘总结：技术选型对比文档模板实践
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.x9ogth.asia/arts/205865.Doc

原标题：记一次本地运行正常，线上环境报错诡异问题
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.x9ogth.asia/arts/028754.Doc

原标题：新手指南：本地防火墙端口访问失败排查
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://wiki.x9ogth.asia/arts/622848.Doc

原标题：新手向：配置项目eslint/prettier代码格式化
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.x9ogth.asia/arts/682882.Doc

原标题：vue pinia 状态管理实战教程
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://wiki.x9ogth.asia/arts/088036.Doc

原标题：golang mysql 防止 sql 注入实践
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.x9ogth.asia/arts/596928.Doc

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.x9ogth.asia/arts/047134.Doc

原标题：快速上手搭建简易内网测试服务
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.x9ogth.asia/arts/891560.Doc

原标题：开发复盘：分布式会话共享多种方案实践
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://wiki.x9ogth.asia/arts/411774.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.x9ogth.asia/arts/942034.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.x9ogth.asia/arts/592929.Doc

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.x9ogth.asia/arts/192826.Doc

原标题：Git 仓库瘦身加快克隆下载速度
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.x9ogth.asia/arts/216487.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.x9ogth.asia/arts/087055.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://wiki.x9ogth.asia/arts/538227.Doc

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.x9ogth.asia/arts/920850.Doc

原标题：开发生产环境资源路径统一
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.x9ogth.asia/arts/398444.Doc

原标题：部署复盘：数据库主从备份恢复演练实践
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.x9ogth.asia/arts/477775.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.x9ogth.asia/arts/865435.Doc

原标题：Nginx 反向代理路由配置实战
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.x9ogth.asia/arts/545173.Doc

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.x9ogth.asia/arts/264048.Doc

原标题：webpack chunk 分包策略详解
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.x9ogth.asia/arts/089415.Doc

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.x9ogth.asia/arts/382717.Doc

原标题：接口签名验签完整安全方案
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.x9ogth.asia/arts/450325.Doc

原标题：Performance：避免循环查询N+1问题完整优化
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.x9ogth.asia/arts/397577.Doc

原标题：golang 系统设计 changelog 变更日志维护
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://wiki.x9ogth.asia/arts/607813.Doc

原标题：从零学习简单分布式ID生成思路
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.x9ogth.asia/arts/512558.Doc

原标题：golang 工具函数库封装思路
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.x9ogth.asia/arts/144286.Doc

原标题：nodejs 定时任务生产环境避坑
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://wiki.x9ogth.asia/arts/573856.Doc

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.x9ogth.asia/arts/334836.Doc

原标题：排错：CI流水线构建失败，日志无明确报错
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://wiki.x9ogth.asia/arts/573763.Doc

原标题：缓存穿透击穿雪崩全套防护
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.x9ogth.asia/arts/768832.Doc

原标题：golang 系统设计限流熔断降级组合使用
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://wiki.x9ogth.asia/arts/896623.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.x9ogth.asia/arts/126803.Doc

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://wiki.x9ogth.asia/arts/459210.Doc

三、实战开发｜Practice
原标题：日志驱动异常日志不输出修复
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.x9ogth.asia/arts/712988.Doc

原标题：Practice：模拟热点key，验证缓存防护策略
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.x9ogth.asia/arts/945876.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.x9ogth.asia/arts/905020.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.x9ogth.asia/arts/015497.Doc

原标题：Git 误提交撤销回退实操教程
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.x9ogth.asia/arts/718761.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.x9ogth.asia/arts/084550.Doc

原标题：golang 系统设计 git 工作流本地开发提交流程
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.x9ogth.asia/arts/455563.Doc

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.x9ogth.asia/arts/913446.Doc

原标题：golang 系统设计 mq 故障降级业务策略
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://wiki.x9ogth.asia/arts/975259.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.x9ogth.asia/arts/771576.Doc

原标题：本地运行正常线上报错排查
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://wiki.x9ogth.asia/arts/596985.Doc

原标题：golang k8s ingress 路由域名转发
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.x9ogth.asia/arts/895947.Doc

原标题：架构复盘：多实例部署业务状态无状态改造
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.x9ogth.asia/arts/284846.Doc

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.x9ogth.asia/arts/726033.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.x9ogth.asia/arts/607864.Doc

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.x9ogth.asia/arts/574473.Doc

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://wiki.x9ogth.asia/arts/372939.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.x9ogth.asia/arts/766066.Doc

原标题：前端打包分包加载提速方案
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.x9ogth.asia/arts/058122.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.x9ogth.asia/arts/868560.Doc

原标题：Debug：网关超时时间小于后端接口超时设置
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.x9ogth.asia/arts/138218.Doc

原标题：golang 系统设计容器镜像安全加固要点
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://wiki.x9ogth.asia/arts/511157.Doc

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.x9ogth.asia/arts/455338.Doc

原标题：日志敏感信息脱敏泄露防护
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.x9ogth.asia/arts/777690.Doc

原标题：新手指南：项目本地编译输出产物解析
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.x9ogth.asia/arts/444079.Doc

原标题：golang 系统设计压力测试性能测试执行流程
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.x9ogth.asia/arts/728149.Doc

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://wiki.x9ogth.asia/arts/423895.Doc

原标题：golang es 高亮搜索结果实现方案
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.x9ogth.asia/arts/802175.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.x9ogth.asia/arts/674149.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.x9ogth.asia/arts/760813.Doc

原标题：golang 系统设计 mq 消息丢失完整防护
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.x9ogth.asia/arts/867045.Doc

原标题：golang k8s helm chart 简单编写
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.x9ogth.asia/arts/684274.Doc

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.x9ogth.asia/arts/341304.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.x9ogth.asia/arts/134469.Doc

原标题：数据库 utf8mb4 支持 emoji 存储
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.x9ogth.asia/arts/647557.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.x9ogth.asia/arts/527106.Doc

原标题：golang mysql 分表 id 路由逻辑
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.x9ogth.asia/arts/497272.Doc

原标题：Hands‑on：简易配置中心本地原型实现
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.x9ogth.asia/arts/310017.Doc

原标题：开发复盘：超时参数统一治理线上服务实践
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.x9ogth.asia/arts/425056.Doc

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://wiki.x9ogth.asia/arts/086784.Doc

四、架构设计｜Architecture
原标题：磁盘占满服务不可用清理方案
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.x9ogth.asia/arts/646661.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.x9ogth.asia/arts/260075.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.x9ogth.asia/arts/275747.Doc

原标题：序列化版本不一致解析失败
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.x9ogth.asia/arts/293400.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://wiki.x9ogth.asia/arts/866640.Doc

原标题：实战项目：多实例部署会话一致性验证实践
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.x9ogth.asia/arts/617592.Doc

原标题：golang 系统设计异步化改造业务流程思路
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.x9ogth.asia/arts/419777.Doc

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.x9ogth.asia/arts/441735.Doc

原标题：复盘总结：线上故障完整复盘报告模板示例
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.x9ogth.asia/arts/660210.Doc

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.x9ogth.asia/arts/181083.Doc

原标题：快速上手单元测试，写出第一个测试用例
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.x9ogth.asia/arts/198565.Doc

原标题：百万数据 Excel 导出内存优化
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.x9ogth.asia/arts/737510.Doc

原标题：快速入门消息通知简单实现方案
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.x9ogth.asia/arts/855290.Doc

原标题：新手指南：看懂开源项目的Issue与PR
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.x9ogth.asia/arts/581907.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.x9ogth.asia/arts/937188.Doc

原标题：消息队列消费堆积扩容处理
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.x9ogth.asia/arts/007880.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.x9ogth.asia/arts/266749.Doc

原标题：golang docker 镜像安全扫描漏洞
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.x9ogth.asia/arts/914897.Doc

?
