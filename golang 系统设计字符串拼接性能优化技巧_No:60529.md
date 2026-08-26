最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计字符串拼接性能优化技巧
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://book.36n932.asia/blog/929589.Doc

原标题：Practice：实现业务id生成不连续有序ID方案
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.36n932.asia/blog/460146.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.36n932.asia/blog/961425.Doc

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://book.36n932.asia/blog/789653.Doc

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://book.36n932.asia/blog/318474.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://book.36n932.asia/blog/060187.Doc

原标题：golang 系统设计 rest http 方法使用原则
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://book.36n932.asia/blog/609670.Doc

原标题：业务错误码体系设计方案
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.36n932.asia/blog/334011.Doc

原标题：排错：前端sourcemap错误线上无法定位报错
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://book.36n932.asia/blog/466304.Doc

原标题：服务健康检查监控接口开发
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.36n932.asia/blog/685433.Doc

原标题：手写简易 MQ 理解消息存储消费
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://book.36n932.asia/blog/236200.Doc

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://book.36n932.asia/blog/829757.Doc

原标题：golang 系统设计防爬虫简单策略
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://book.36n932.asia/blog/295625.Doc

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://book.36n932.asia/blog/538871.Doc

原标题：项目实践：数据库慢日志采集分析落地实践
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://book.36n932.asia/blog/814725.Doc

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://book.36n932.asia/blog/520185.Doc

原标题：Debug：序列化反序列化版本不一致解析失败
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://book.36n932.asia/blog/753998.Doc

原标题：golang 系统设计告警升级通知策略配置思路
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.36n932.asia/blog/358829.Doc

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.36n932.asia/blog/387332.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://book.36n932.asia/blog/704831.Doc

原标题：依赖安装失败全方位排错
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://book.36n932.asia/blog/534937.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://book.36n932.asia/blog/093248.Doc

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.36n932.asia/blog/206614.Doc

原标题：golang 系统设计日志系统架构思路
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://book.36n932.asia/blog/619903.Doc

原标题：golang 系统设计读写分离架构示例
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.36n932.asia/blog/095234.Doc

原标题：快速入门环境区分：开发、测试、生产环境
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://book.36n932.asia/blog/832133.Doc

原标题：nodejs jwt 登录鉴权完整示例
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://book.36n932.asia/blog/626847.Doc

原标题：golang 系统设计监控告警体系搭建思路
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.36n932.asia/blog/721767.Doc

原标题：golang 令牌桶限流中间件 gin
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://book.36n932.asia/blog/213775.Doc

原标题：Practice：实现数据库连接池简易模拟实现
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.36n932.asia/blog/412632.Doc

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://book.36n932.asia/blog/947329.Doc

原标题：golang 系统设计雪花算法 id 原理剖析
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://book.36n932.asia/blog/520444.Doc

原标题：文件描述符优化进程卡死修复
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.36n932.asia/blog/087037.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://book.36n932.asia/blog/537998.Doc

原标题：golang 系统设计技术文档维护更新最佳实践
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.36n932.asia/blog/152413.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.36n932.asia/blog/393936.Doc

原标题：golang 系统设计链路追踪架构简单讲解
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://book.36n932.asia/blog/930545.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://book.36n932.asia/blog/638071.Doc

原标题：实战：多版本SDK兼容业务改造实践
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://book.36n932.asia/blog/666070.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.36n932.asia/blog/832836.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计监控大盘故障快速定位思路
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://book.36n932.asia/blog/022173.Doc

原标题：布隆过滤器数据高效去重实现
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://book.36n932.asia/blog/012838.Doc

原标题：golang 参数校验业务接口处理
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.36n932.asia/blog/934765.Doc

原标题：golang 系统设计熔断降级架构讲解
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://book.36n932.asia/blog/904470.Doc

原标题：新手指南：本地多版本环境共存配置
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.36n932.asia/blog/752366.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.36n932.asia/blog/900520.Doc

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://book.36n932.asia/blog/188285.Doc

原标题：防火墙 IP 白名单回调接口放行
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://book.36n932.asia/blog/111858.Doc

原标题：项目依赖安全扫描漏洞防范
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://book.36n932.asia/blog/292001.Doc

原标题：golang 系统设计 mq 消息重复消费处理
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://book.36n932.asia/blog/074436.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://book.36n932.asia/blog/893261.Doc

原标题：golang k8s ingress 路由域名转发
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://book.36n932.asia/blog/572392.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://book.36n932.asia/blog/231955.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://book.36n932.asia/blog/174702.Doc

原标题：分页逻辑错误数据漏查修复
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://book.36n932.asia/blog/040143.Doc

原标题：配置外部化线上部署防错误
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.36n932.asia/blog/315476.Doc

原标题：入门实践：简单批量处理脚本编写
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://book.36n932.asia/blog/637633.Doc

原标题：网络读取超时设置连接挂起防护
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://book.36n932.asia/blog/153034.Doc

原标题：gRPC 服务端客户端入门示例
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://book.36n932.asia/blog/477633.Doc

原标题：golang etcd 分布式锁实现原理
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.36n932.asia/blog/438643.Doc

原标题：系统字符集统一乱码修复
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://book.36n932.asia/blog/679826.Doc

原标题：安全实践：API密钥管理轮换最佳实践
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://book.36n932.asia/blog/641398.Doc

原标题：golang redis 限流几种实现方案
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.36n932.asia/blog/785447.Doc

原标题：golang k8s 镜像拉取密钥配置
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.36n932.asia/blog/091366.Doc

原标题：react hooks 常见陷阱避坑指南
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://book.36n932.asia/blog/674034.Doc

原标题：golang 消息死信处理业务逻辑
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://book.36n932.asia/blog/975878.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://book.36n932.asia/blog/955407.Doc

原标题：WebSocket 双向通信 demo 开发
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://book.36n932.asia/blog/616696.Doc

原标题：批量数据处理脚本编写技巧
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.36n932.asia/blog/486572.Doc

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.36n932.asia/blog/979488.Doc

原标题：golang 系统设计 rest 资源命名规范汇总
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.36n932.asia/blog/498871.Doc

原标题：golang mysql 避免 select * 查询
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://book.36n932.asia/blog/486100.Doc

原标题：DevOps：CI构建产物缓存复用加速编译
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://book.36n932.asia/blog/496503.Doc

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.36n932.asia/blog/743952.Doc

原标题：golang redis lua 脚本开发调试
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://book.36n932.asia/blog/431302.Doc

原标题：效率笔记：终端开发工具提升日常调试效率
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.36n932.asia/blog/448071.Doc

原标题：golang 雪花 id 重复问题排查
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.36n932.asia/blog/746150.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://book.36n932.asia/blog/016131.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.36n932.asia/blog/967947.Doc

原标题：看懂报错日志快速定位问题
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.36n932.asia/blog/870527.Doc

三、实战开发｜Practice
原标题：模拟登录鉴权权限判断示例
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://book.36n932.asia/blog/159056.Doc

原标题：golang 系统设计数据库慢请求排查流程
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.36n932.asia/blog/059192.Doc

原标题：限流规则误拦截正常请求修复
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.36n932.asia/blog/336267.Doc

原标题：快速入门容器基础概念，理解镜像与容器
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.36n932.asia/blog/378366.Doc

原标题：效率笔记：调试网络请求curl命令高级用法
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.36n932.asia/blog/316875.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.36n932.asia/blog/129181.Doc

原标题：Git 混乱提交历史清理方法
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://book.36n932.asia/blog/276874.Doc

原标题：golang mysql json 字段查询使用
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://book.36n932.asia/blog/589147.Doc

原标题：golang 系统设计读写分离架构示例
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://book.36n932.asia/blog/189890.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://book.36n932.asia/blog/290667.Doc

原标题：nodejs redis 缓存业务实战
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://book.36n932.asia/blog/674877.Doc

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://book.36n932.asia/blog/716521.Doc

原标题：运维笔记：线上服务健康检查脚本编写
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.36n932.asia/blog/342840.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://book.36n932.asia/blog/625234.Doc

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.36n932.asia/blog/899953.Doc

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://book.36n932.asia/blog/269524.Doc

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://book.36n932.asia/blog/129392.Doc

原标题：golang 系统设计本地缓存更新失效方案实现
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://book.36n932.asia/blog/785792.Doc

原标题：架构笔记：OAuth2授权服务架构模式拆解
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://book.36n932.asia/blog/452622.Doc

原标题：部署复盘：服务启动顺序依赖处理方案
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://book.36n932.asia/blog/715222.Doc

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://book.36n932.asia/blog/615980.Doc

原标题：Git LFS 大文件推送失败解决
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://book.36n932.asia/blog/534795.Doc

原标题：golang k8s ingress 路由域名转发
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://book.36n932.asia/blog/316005.Doc

原标题：golang 系统设计熔断算法 hystrix 思路
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.36n932.asia/blog/279284.Doc

原标题：golang redis 缓存穿透解决方案
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://book.36n932.asia/blog/560003.Doc

原标题：GitHub Markdown 文档语法汇总
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://book.36n932.asia/blog/159989.Doc

原标题：Hands‑on：本地模拟分布式锁失效场景测试
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://book.36n932.asia/blog/749859.Doc

原标题：实战：容器内执行调试排错完整实操流程
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://book.36n932.asia/blog/888322.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://book.36n932.asia/blog/322115.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.36n932.asia/blog/048564.Doc

原标题：golang 系统设计唯一索引业务使用场景
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://book.36n932.asia/blog/358344.Doc

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.36n932.asia/blog/760282.Doc

原标题：golang 协程泄露问题排查方法
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://book.36n932.asia/blog/484430.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.36n932.asia/blog/166239.Doc

原标题：方案设计：短链接系统完整架构方案拆解
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.36n932.asia/blog/567512.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://book.36n932.asia/blog/919165.Doc

原标题：golang 系统设计消息队列解耦削峰
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://book.36n932.asia/blog/912856.Doc

原标题：实战：Nginx实现文件限速下载配置实践
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://book.36n932.asia/blog/261737.Doc

原标题：部署实践：DockerCompose管理多服务环境
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://book.36n932.asia/blog/154966.Doc

原标题：TCP 长连接参数优化 TIME_WAIT
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://book.36n932.asia/blog/304799.Doc

四、架构设计｜Architecture
原标题：css 变量主题切换方案实现
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://book.36n932.asia/blog/418376.Doc

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://book.36n932.asia/blog/016880.Doc

原标题：服务熔断防止故障级联传播
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://book.36n932.asia/blog/421006.Doc

原标题：内存溢出问题现象识别排查
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.36n932.asia/blog/987060.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://book.36n932.asia/blog/411992.Doc

原标题：系统时间同步定时任务偏移
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://book.36n932.asia/blog/671929.Doc

原标题：golang 系统设计 csrf 接口防护实现
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://book.36n932.asia/blog/878796.Doc

原标题：Practice：实现请求重试组件支持退避策略
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://book.36n932.asia/blog/973260.Doc

原标题：定时任务周期调度 demo 开发
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://book.36n932.asia/blog/375914.Doc

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://book.36n932.asia/blog/787281.Doc

原标题：golang minio 对象存储接口开发
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.36n932.asia/blog/449548.Doc

原标题：性能复盘：锁等待严重业务逻辑优化记录
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://book.36n932.asia/blog/573569.Doc

原标题：布隆过滤器数据高效去重实现
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://book.36n932.asia/blog/653225.Doc

原标题：golang 信号捕获程序退出处理
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.36n932.asia/blog/353343.Doc

原标题：部署复盘：数据库主从备份恢复演练实践
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://book.36n932.asia/blog/071852.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://book.36n932.asia/blog/137303.Doc

原标题：请求重试组件退避策略实现
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.36n932.asia/blog/918075.Doc

原标题：golang ci 流水线漏洞扫描依赖检查
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://book.36n932.asia/blog/545447.Doc

?
