最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计序列化性能选型对比
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.nc0xew.asia/arts/229871.Doc

原标题：集成测试业务流程编写示例
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.nc0xew.asia/arts/422707.Doc

原标题：nodejs 数据库连接池配置调优
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://wiki.nc0xew.asia/arts/081660.Doc

原标题：数据库排序规则统一结果一致
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://wiki.nc0xew.asia/arts/711032.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.nc0xew.asia/arts/188691.Doc

原标题：Git 分支管理多人协作实战教程
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.nc0xew.asia/arts/617465.Doc

原标题：golang 单元测试 mock http 请求
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.nc0xew.asia/arts/532207.Doc

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.nc0xew.asia/arts/150918.Doc

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.nc0xew.asia/arts/441900.Doc

原标题：数据库 utf8mb4 支持 emoji 存储
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.nc0xew.asia/arts/341020.Doc

原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.nc0xew.asia/arts/304643.Doc

原标题：golang ci 流水线单元测试集成测试
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.nc0xew.asia/arts/270926.Doc

原标题：新手指南：本地防火墙端口访问失败排查
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.nc0xew.asia/arts/314141.Doc

原标题：golang 分布式锁防死锁处理
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.nc0xew.asia/arts/459500.Doc

原标题：线程池拒绝策略任务丢失防护
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.nc0xew.asia/arts/600991.Doc

原标题：golang redis set 集合去重业务
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.nc0xew.asia/arts/306574.Doc

原标题：前端错误监控上报系统搭建
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.nc0xew.asia/arts/090547.Doc

原标题：快速入门GraphQL基础查询语法示例
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.nc0xew.asia/arts/896770.Doc

原标题：golang 系统设计重试退避策略业务落地
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.nc0xew.asia/arts/412958.Doc

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.nc0xew.asia/arts/010640.Doc

原标题：golang 分布式锁防死锁处理
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.nc0xew.asia/arts/891435.Doc

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.nc0xew.asia/arts/086930.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://wiki.nc0xew.asia/arts/519932.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.nc0xew.asia/arts/754452.Doc

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.nc0xew.asia/arts/556232.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.nc0xew.asia/arts/550436.Doc

原标题：开发复盘：分布式会话共享多种方案实践
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.nc0xew.asia/arts/331980.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.nc0xew.asia/arts/251722.Doc

原标题：golang 系统设计内网外网服务隔离方案
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.nc0xew.asia/arts/200136.Doc

原标题：零基础理解幂等性基础概念与场景
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.nc0xew.asia/arts/664938.Doc

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.nc0xew.asia/arts/170704.Doc

原标题：golang ip 限流黑名单实现方案
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.nc0xew.asia/arts/015032.Doc

原标题：golang docker 部署 kafka 本地调试
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.nc0xew.asia/arts/569447.Doc

原标题：多操作系统开发兼容处理
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.nc0xew.asia/arts/689465.Doc

原标题：golang 系统设计 csrf 接口防护实现
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.nc0xew.asia/arts/792470.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.nc0xew.asia/arts/667252.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.nc0xew.asia/arts/785785.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.nc0xew.asia/arts/718506.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.nc0xew.asia/arts/260283.Doc

原标题：新手指南：项目本地编译输出产物解析
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.nc0xew.asia/arts/521392.Doc


二、踩坑排错｜Troubleshooting
原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.nc0xew.asia/arts/488192.Doc

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.nc0xew.asia/arts/788162.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.nc0xew.asia/arts/381502.Doc

原标题：排错：前端缓存304异常更新不及时
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://wiki.nc0xew.asia/arts/631601.Doc

原标题：Nginx 透传真实客户端 IP 配置
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.nc0xew.asia/arts/960594.Doc

原标题：golang 系统设计网关性能压测优化简单思路
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://wiki.nc0xew.asia/arts/043573.Doc

原标题：golang mysql 主从同步延迟兼容
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.nc0xew.asia/arts/315736.Doc

原标题：性能复盘：网络IO优化减少接口等待时间
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.nc0xew.asia/arts/716060.Doc

原标题：golang k8s 网络策略网络隔离设置
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://wiki.nc0xew.asia/arts/348935.Doc

原标题：golang 系统设计线上故障排查完整流程
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.nc0xew.asia/arts/438890.Doc

原标题：日志输出规范防止磁盘爆满
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.nc0xew.asia/arts/121766.Doc

原标题：golang 系统设计网关错误重试超时处理策略
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://wiki.nc0xew.asia/arts/861052.Doc

原标题：golang 数据库慢查询监控实现
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://wiki.nc0xew.asia/arts/399977.Doc

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.nc0xew.asia/arts/263438.Doc

原标题：Practice：简易限流器分布式版本Redis实现
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.nc0xew.asia/arts/882611.Doc

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.nc0xew.asia/arts/014990.Doc

原标题：系统时间同步定时任务偏移
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.nc0xew.asia/arts/617528.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://wiki.nc0xew.asia/arts/890961.Doc

原标题：golang kafka 消费者组原理讲解
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.nc0xew.asia/arts/820957.Doc

原标题：浏览器内存泄漏排查前端页面
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.nc0xew.asia/arts/863649.Doc

原标题：Architecture：事件溯源架构模式适用业务场景
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.nc0xew.asia/arts/853345.Doc

原标题：golang 参数校验业务接口处理
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.nc0xew.asia/arts/018386.Doc

原标题：nodejs 中间件模式原理剖析
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.nc0xew.asia/arts/204658.Doc

原标题：程序信号中断退出处理逻辑
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.nc0xew.asia/arts/052715.Doc

原标题：golang kafka 消费者偏移量管理
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://wiki.nc0xew.asia/arts/495396.Doc

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.nc0xew.asia/arts/691001.Doc

原标题：限流组件计数器令牌桶模式实现
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.nc0xew.asia/arts/309193.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.nc0xew.asia/arts/006954.Doc

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.nc0xew.asia/arts/653746.Doc

原标题：线程调度优化减少上下文切换
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.nc0xew.asia/arts/530405.Doc

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://wiki.nc0xew.asia/arts/127797.Doc

原标题：golang 告警推送钉钉机器人实现
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.nc0xew.asia/arts/130761.Doc

原标题：Cookie 跨环境登录配置调整
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.nc0xew.asia/arts/893502.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.nc0xew.asia/arts/111967.Doc

原标题：golang url 参数编码处理方案
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.nc0xew.asia/arts/952723.Doc

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.nc0xew.asia/arts/769765.Doc

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.nc0xew.asia/arts/707058.Doc

原标题：安全实践：接口错误信息不要暴露内部细节
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.nc0xew.asia/arts/952005.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.nc0xew.asia/arts/920341.Doc

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://wiki.nc0xew.asia/arts/296281.Doc

三、实战开发｜Practice
原标题：golang 系统设计监控告警体系搭建思路
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.nc0xew.asia/arts/050557.Doc

原标题：读懂开源项目 README 实用技巧
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://wiki.nc0xew.asia/arts/152401.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.nc0xew.asia/arts/422647.Doc

原标题：Redis 分布式锁高并发安全实现
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://wiki.nc0xew.asia/arts/553207.Doc

原标题：golang 系统设计缓存一致性方案对比
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.nc0xew.asia/arts/611964.Doc

原标题：新手指南：本地防火墙端口访问失败排查
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.nc0xew.asia/arts/826527.Doc

原标题：golang kafka 核心概念分区副本
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://wiki.nc0xew.asia/arts/556833.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://wiki.nc0xew.asia/arts/152455.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.nc0xew.asia/arts/966406.Doc

原标题：Git 子模块更新代码不全修复
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.nc0xew.asia/arts/265842.Doc

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.nc0xew.asia/arts/043552.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.nc0xew.asia/arts/566942.Doc

原标题：golang redis 位图用户签到统计
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://wiki.nc0xew.asia/arts/828165.Doc

原标题：golang docker 容器资源限制设置
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.nc0xew.asia/arts/262667.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.nc0xew.asia/arts/189266.Doc

原标题：golang 系统设计 rest http 方法使用原则
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://wiki.nc0xew.asia/arts/798176.Doc

原标题：实践：API版本控制多种策略落地对比实践
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://wiki.nc0xew.asia/arts/128243.Doc

原标题：Practice：实现业务唯一流水号生成组件实践
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.nc0xew.asia/arts/104148.Doc

原标题：SDK 版本兼容线上崩溃修复
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://wiki.nc0xew.asia/arts/868974.Doc

原标题：golang 系统设计 api 接口兼容性设计原则
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.nc0xew.asia/arts/769556.Doc

原标题：golang 系统设计性能优化通用思路方法论
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.nc0xew.asia/arts/457345.Doc

原标题：golang 系统设计链路查询定位慢请求实操技巧
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.nc0xew.asia/arts/922444.Doc

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.nc0xew.asia/arts/647183.Doc

原标题：golang ci 流水线自动部署 k8s 示例
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.nc0xew.asia/arts/023249.Doc

原标题：Hands‑on：简易配置中心本地原型实现
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://wiki.nc0xew.asia/arts/603289.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.nc0xew.asia/arts/160994.Doc

原标题：安全复盘：Redis未授权访问漏洞防护
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.nc0xew.asia/arts/374347.Doc

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://wiki.nc0xew.asia/arts/851949.Doc

原标题：一次JWT令牌过期时间异常问题复盘
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.nc0xew.asia/arts/909774.Doc

原标题：golang mysql 时间类型选型避坑
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.nc0xew.asia/arts/166145.Doc

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.nc0xew.asia/arts/922631.Doc

原标题：golang aes 对称加密解密示例
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.nc0xew.asia/arts/781625.Doc

原标题：golang 链路 traceId 透传中间件
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.nc0xew.asia/arts/804702.Doc

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.nc0xew.asia/arts/456950.Doc

原标题：golang 系统设计唯一索引业务使用场景
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.nc0xew.asia/arts/743013.Doc

原标题：踩坑：大事务引发数据库连接池耗尽
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://wiki.nc0xew.asia/arts/525033.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://wiki.nc0xew.asia/arts/294256.Doc

原标题：golang gitlab runner 部署与注册实操
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://wiki.nc0xew.asia/arts/638464.Doc

原标题：SSH 密钥配置 GitHub 免密登录
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.nc0xew.asia/arts/077537.Doc

原标题：项目依赖安全扫描漏洞防范
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.nc0xew.asia/arts/474664.Doc

四、架构设计｜Architecture
原标题：数据库连接及时关闭连接泄漏
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.nc0xew.asia/arts/361997.Doc

原标题：运维笔记：服务器Swap分区调优生产实践
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.nc0xew.asia/arts/020922.Doc

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.nc0xew.asia/arts/451395.Doc

原标题：Architecture：静态配置与动态配置架构分离
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.nc0xew.asia/arts/481528.Doc

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.nc0xew.asia/arts/508957.Doc

原标题：Architecture：监控告警架构避免告警风暴设计
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://wiki.nc0xew.asia/arts/233658.Doc

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.nc0xew.asia/arts/260333.Doc

原标题：Security：接口鉴权越权漏洞检测与修复
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.nc0xew.asia/arts/535625.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://wiki.nc0xew.asia/arts/070227.Doc

原标题：golang http 服务性能优化调参
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.nc0xew.asia/arts/092607.Doc

原标题：线上异常：线程池队列拒绝策略配置错误丢任务
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.nc0xew.asia/arts/045047.Doc

原标题：接口签名校验防篡改实现
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.nc0xew.asia/arts/565313.Doc

原标题：跨平台换行符统一异常修复
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.nc0xew.asia/arts/454475.Doc

原标题：golang 分布式锁 redis 实现
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.nc0xew.asia/arts/826201.Doc

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.nc0xew.asia/arts/552297.Doc

原标题：golang 系统设计限流熔断降级组合使用
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.nc0xew.asia/arts/271419.Doc

原标题：golang 系统设计故障预案编写模板参考示例
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.nc0xew.asia/arts/123207.Doc

原标题：golang redis 过期 key 监听业务
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.nc0xew.asia/arts/693901.Doc

?
