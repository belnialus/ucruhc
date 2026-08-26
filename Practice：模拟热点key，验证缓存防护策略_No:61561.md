最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Practice：模拟热点key，验证缓存防护策略
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.b2hisu.asia/arts/189356.Doc

原标题：golang 项目目录分层规范设计
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.b2hisu.asia/arts/383475.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.b2hisu.asia/arts/607840.Doc

原标题：序列化版本不一致解析失败
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.b2hisu.asia/arts/330676.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.b2hisu.asia/arts/312037.Doc

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://wiki.b2hisu.asia/arts/203568.Doc

原标题：golang mysql 连接泄漏检测方法
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://wiki.b2hisu.asia/arts/649192.Doc

原标题：编译打包产物依赖分析解读
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.b2hisu.asia/arts/822693.Doc

原标题：Practice：实现请求ID透传全链路日志实践
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.b2hisu.asia/arts/163380.Doc

原标题：DNS TTL 配置域名切换生效
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.b2hisu.asia/arts/718193.Doc

原标题：golang 错误包装 errors.wrap 用法
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://wiki.b2hisu.asia/arts/907646.Doc

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://wiki.b2hisu.asia/arts/936300.Doc

原标题：golang 系统设计故障止损降级回滚执行原则
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.b2hisu.asia/arts/506190.Doc

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.b2hisu.asia/arts/942132.Doc

原标题：golang 系统设计多级缓存更新策略
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.b2hisu.asia/arts/978506.Doc

原标题：golang ci 流水线制品仓库上传下载
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.b2hisu.asia/arts/691938.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.b2hisu.asia/arts/194301.Doc

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://wiki.b2hisu.asia/arts/967373.Doc

原标题：golang redis 缓存雪崩完整处理
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.b2hisu.asia/arts/311965.Doc

原标题：golang redis 持久化 RDB AOF 对比
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.b2hisu.asia/arts/326118.Doc

原标题：线上接口超时故障排查思路
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.b2hisu.asia/arts/607540.Doc

原标题：设计思考：分布式会话架构选型对比
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://wiki.b2hisu.asia/arts/947933.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.b2hisu.asia/arts/607118.Doc

原标题：golang 系统设计分布式会话方案对比
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.b2hisu.asia/arts/786100.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.b2hisu.asia/arts/785954.Doc

原标题：golang 系统设计消息体序列化选型对比
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://wiki.b2hisu.asia/arts/542402.Doc

原标题：JSON XML 数据解析处理示例
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.b2hisu.asia/arts/220117.Doc

原标题：设计思考：系统限流熔断降级完整防护体系
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.b2hisu.asia/arts/731361.Doc

原标题：golang 系统设计配置多环境隔离方案落地
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.b2hisu.asia/arts/906540.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.b2hisu.asia/arts/197258.Doc

原标题：golang mysql 事务回滚异常处理
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.b2hisu.asia/arts/567844.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.b2hisu.asia/arts/315777.Doc

原标题：golang 系统设计读写分离延迟业务兼容
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://wiki.b2hisu.asia/arts/271077.Doc

原标题：golang proto 默认值坑点梳理
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.b2hisu.asia/arts/521962.Doc

原标题：Nginx 缓冲区调优大文件上传
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.b2hisu.asia/arts/892958.Doc

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.b2hisu.asia/arts/421270.Doc

原标题：日志敏感信息脱敏泄露防护
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.b2hisu.asia/arts/823932.Doc

原标题：golang 系统设计 http3 quic 简单原理了解
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.b2hisu.asia/arts/048477.Doc

原标题：golang 系统设计大事务拆分实战思路
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.b2hisu.asia/arts/570511.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.b2hisu.asia/arts/487928.Doc


二、踩坑排错｜Troubleshooting
原标题：从零搭建简单CLI命令行工具
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.b2hisu.asia/arts/785621.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.b2hisu.asia/arts/088695.Doc

原标题：golang gorm 预加载关联查询优化
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.b2hisu.asia/arts/468373.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.b2hisu.asia/arts/566265.Doc

原标题：monorepo 项目多包管理最佳实践
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://wiki.b2hisu.asia/arts/370629.Doc

原标题：端口占用释放资源重启服务
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.b2hisu.asia/arts/495955.Doc

原标题：快速入门YAML配置文件语法与示例
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.b2hisu.asia/arts/084141.Doc

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.b2hisu.asia/arts/941184.Doc

原标题：nodejs http 服务性能调优实战
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.b2hisu.asia/arts/807688.Doc

原标题：数值类型溢出错乱问题修复
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.b2hisu.asia/arts/148390.Doc

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://wiki.b2hisu.asia/arts/651817.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.b2hisu.asia/arts/535768.Doc

原标题：golang 系统设计排行榜几种实现
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.b2hisu.asia/arts/843292.Doc

原标题：实战项目：百万日志文件解析处理脚本实践
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://wiki.b2hisu.asia/arts/716848.Doc

原标题：golang redis lua 脚本开发调试
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://wiki.b2hisu.asia/arts/193926.Doc

原标题：nodejs 中间件模式原理剖析
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.b2hisu.asia/arts/459607.Doc

原标题：golang redis stream 消息队列实践
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.b2hisu.asia/arts/904712.Doc

原标题：网关超时时间调优后端等待
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.b2hisu.asia/arts/446140.Doc

原标题：Docker 容器时区错误修复方案
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.b2hisu.asia/arts/457603.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.b2hisu.asia/arts/973968.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.b2hisu.asia/arts/226254.Doc

原标题：OpenSource：开源项目README高质量编写指南
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://wiki.b2hisu.asia/arts/344626.Doc

原标题：优化实践：预加载与懒加载业务场景取舍
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.b2hisu.asia/arts/461085.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://wiki.b2hisu.asia/arts/074077.Doc

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.b2hisu.asia/arts/897958.Doc

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.b2hisu.asia/arts/947487.Doc

原标题：前后端会话登录状态持久化
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.b2hisu.asia/arts/636604.Doc

原标题：记一次第三方SDK版本兼容引发线上故障
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://wiki.b2hisu.asia/arts/188704.Doc

原标题：nodejs 读取大文件 csv 处理方案
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.b2hisu.asia/arts/126358.Doc

原标题：golang 告警推送钉钉机器人实现
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.b2hisu.asia/arts/980275.Doc

原标题：golang 系统设计 csrf 接口防护实现
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.b2hisu.asia/arts/258011.Doc

原标题：golang 系统设计索引设计通用方法论汇总
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://wiki.b2hisu.asia/arts/714223.Doc

原标题：用户敏感数据脱敏代码实现
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.b2hisu.asia/arts/282201.Doc

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://wiki.b2hisu.asia/arts/948858.Doc

原标题：golang mysql 避免 select * 查询
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.b2hisu.asia/arts/688832.Doc

原标题：容器内存扩容 OOM 被杀死修复
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.b2hisu.asia/arts/747480.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.b2hisu.asia/arts/375279.Doc

原标题：golang 系统设计文件存储选型对比
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://wiki.b2hisu.asia/arts/710328.Doc

原标题：golang pprof 线上采集性能数据
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.b2hisu.asia/arts/877853.Doc

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.b2hisu.asia/arts/607675.Doc

三、实战开发｜Practice
原标题：golang 系统设计分布式锁不同场景选型对比
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.b2hisu.asia/arts/354463.Doc

原标题：序列化版本不一致解析失败
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.b2hisu.asia/arts/429448.Doc

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://wiki.b2hisu.asia/arts/318381.Doc

原标题：golang redis 限流几种实现方案
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.b2hisu.asia/arts/089133.Doc

原标题：API 接口调试与异常处理实战
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.b2hisu.asia/arts/662445.Doc

原标题：golang prometheus histogram 指标
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.b2hisu.asia/arts/307926.Doc

原标题：新手指南：项目本地编译输出产物解析
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.b2hisu.asia/arts/524926.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.b2hisu.asia/arts/716966.Doc

原标题：本地简易配置中心动态管理
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.b2hisu.asia/arts/319818.Doc

原标题：golang 系统设计故障止损降级回滚执行原则
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.b2hisu.asia/arts/746400.Doc

原标题：golang mysql innodb 事务隔离级别
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.b2hisu.asia/arts/400194.Doc

原标题：golang redis 连接池参数最佳值
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://wiki.b2hisu.asia/arts/618336.Doc

原标题：golang redis stream 消息队列实践
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://wiki.b2hisu.asia/arts/785227.Doc

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.b2hisu.asia/arts/713993.Doc

原标题：坑点：gitreset误删本地代码恢复方案
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.b2hisu.asia/arts/934390.Doc

原标题：方案设计：异步解耦业务架构边界识别
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.b2hisu.asia/arts/759560.Doc

原标题：golang 系统设计消息大小限制业务处理方案
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.b2hisu.asia/arts/578682.Doc

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.b2hisu.asia/arts/522335.Doc

原标题：golang 系统设计日志脱敏防止信息泄露
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.b2hisu.asia/arts/271516.Doc

原标题：nodejs 跨域中间件配置细节
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.b2hisu.asia/arts/607309.Doc

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.b2hisu.asia/arts/292776.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.b2hisu.asia/arts/401772.Doc

原标题：pnpm 包管理工具实战避坑指南
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.b2hisu.asia/arts/982461.Doc

原标题：Practice：批量异步任务处理系统设计实现
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.b2hisu.asia/arts/902808.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.b2hisu.asia/arts/201965.Doc

原标题：版本升级服务启动失败处理
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.b2hisu.asia/arts/897699.Doc

原标题：RPC 报文大小上限调优大请求
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.b2hisu.asia/arts/715797.Doc

原标题：golang 系统设计多租户数据隔离方案
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.b2hisu.asia/arts/185932.Doc

原标题：实战：Nginx实现文件限速下载配置实践
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.b2hisu.asia/arts/968626.Doc

原标题：容器内存扩容 OOM 被杀死修复
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://wiki.b2hisu.asia/arts/108284.Doc

原标题：golang 系统设计定时任务失败重试告警实现
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.b2hisu.asia/arts/193669.Doc

原标题：实战：基于内存实现简单消息广播组件
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.b2hisu.asia/arts/875814.Doc

原标题：文件分片上传断点续传功能
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.b2hisu.asia/arts/373517.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.b2hisu.asia/arts/087991.Doc

原标题：架构笔记：数据脱敏架构接入层与存储层方案
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.b2hisu.asia/arts/128473.Doc

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.b2hisu.asia/arts/094070.Doc

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.b2hisu.asia/arts/231333.Doc

原标题：系统时间同步定时任务偏移
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://wiki.b2hisu.asia/arts/760768.Doc

原标题：AI‑Dev：AI辅助编码高效使用提示词技巧
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.b2hisu.asia/arts/458707.Doc

原标题：Git 分支切换合并删除完整操作
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.b2hisu.asia/arts/042021.Doc

四、架构设计｜Architecture
原标题：golang docker compose 部署 minio
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.b2hisu.asia/arts/280460.Doc

原标题：nestjs 框架模块化项目搭建
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://wiki.b2hisu.asia/arts/613926.Doc

原标题：golang 系统设计告警升级通知策略配置思路
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.b2hisu.asia/arts/964137.Doc

原标题：前端防抖节流高频事件处理
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://wiki.b2hisu.asia/arts/846682.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.b2hisu.asia/arts/124451.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.b2hisu.asia/arts/972432.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.b2hisu.asia/arts/957362.Doc

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.b2hisu.asia/arts/646361.Doc

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.b2hisu.asia/arts/757390.Doc

原标题：百万数据 Excel 导出内存优化
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.b2hisu.asia/arts/651715.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.b2hisu.asia/arts/308249.Doc

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://wiki.b2hisu.asia/arts/827356.Doc

原标题：golang kafka 重试机制配置实操
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.b2hisu.asia/arts/043298.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.b2hisu.asia/arts/517404.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.b2hisu.asia/arts/986204.Doc

原标题：Debug：网关超时时间小于后端接口超时设置
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.b2hisu.asia/arts/204363.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.b2hisu.asia/arts/108384.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.b2hisu.asia/arts/273194.Doc

?
