最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Practice：实现异步回调处理通用组件封装
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://book.nrwoja.asia/blog/9539919.sHtMl

原标题：golang 系统设计代码评审高效沟通原则思路
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://book.nrwoja.asia/blog/5783673.sHtMl

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://book.nrwoja.asia/blog/1204830.sHtMl

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://book.nrwoja.asia/blog/1904308.sHtMl

原标题：golang 项目 docker compose 本地调试
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://book.nrwoja.asia/blog/8375298.sHtMl

原标题：golang 系统设计密钥轮换安全实践思路
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://book.nrwoja.asia/blog/9942753.sHtMl

原标题：一次数据库死锁现场分析与解决方案记录
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://book.nrwoja.asia/blog/1388905.sHtMl

原标题：golang 系统设计读写分离架构示例
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://book.nrwoja.asia/blog/9382260.sHtMl

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.nrwoja.asia/blog/4669053.sHtMl

原标题：开源项目本地运行排错完整清单
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://book.nrwoja.asia/blog/5610288.sHtMl

原标题：golang 系统设计回调重试幂等完整处理
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://book.nrwoja.asia/blog/9238647.sHtMl

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://book.nrwoja.asia/blog/9042790.sHtMl

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://book.nrwoja.asia/blog/1318720.sHtMl

原标题：golang http client 连接池调优
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://book.nrwoja.asia/blog/0703182.sHtMl

原标题：golang 系统设计内存高占用排查思路
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://book.nrwoja.asia/blog/8206984.sHtMl

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.nrwoja.asia/blog/3909030.sHtMl

原标题：文件监控服务自动重启开发
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://book.nrwoja.asia/blog/1289282.sHtMl

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://book.nrwoja.asia/blog/7082712.sHtMl

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://book.nrwoja.asia/blog/4283836.sHtMl

原标题：golang docker compose 本地开发最佳实践
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://book.nrwoja.asia/blog/8299682.sHtMl

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://book.nrwoja.asia/blog/6663317.sHtMl

原标题：缓存穿透防护保护数据库
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://book.nrwoja.asia/blog/2934258.sHtMl

原标题：golang md5 sha 加密工具实现
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://book.nrwoja.asia/blog/1267685.sHtMl

原标题：包管理器依赖冲突解决方案
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://book.nrwoja.asia/blog/3089568.sHtMl

原标题：golang 系统设计接口返回格式统一规范
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://book.nrwoja.asia/blog/3226372.sHtMl

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://book.nrwoja.asia/blog/3065905.sHtMl

原标题：业务错误码完整落地实践
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.nrwoja.asia/blog/0893580.sHtMl

原标题：实践：实现Redis分布式锁完整可运行代码
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://book.nrwoja.asia/blog/5969981.sHtMl

原标题：部署实践：容器优雅停机配置处理信号
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://book.nrwoja.asia/blog/7465648.sHtMl

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://book.nrwoja.asia/blog/5558660.sHtMl

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://book.nrwoja.asia/blog/4645500.sHtMl

原标题：golang 系统设计消息体序列化选型对比
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://book.nrwoja.asia/blog/9794483.sHtMl

原标题：ServiceWorker 缓存页面更新清理
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.nrwoja.asia/blog/7726830.sHtMl

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://book.nrwoja.asia/blog/5244580.sHtMl

原标题：golang 系统设计大表结构变更不停机方案
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://book.nrwoja.asia/blog/5667657.sHtMl

原标题：快速入门WebSocket，实现简易双向通信demo
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://book.nrwoja.asia/blog/5341394.sHtMl

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://book.nrwoja.asia/blog/2763837.sHtMl

原标题：开发测试生产多环境配置区分
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://book.nrwoja.asia/blog/0151613.sHtMl

原标题：golang websocket 消息广播实现
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.nrwoja.asia/blog/8687222.sHtMl

原标题：golang es 映射 mapping 设计避坑
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.nrwoja.asia/blog/7499079.sHtMl


二、踩坑排错｜Troubleshooting
原标题：Hands‑on：简易速率限制中间件完整实现
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://book.nrwoja.asia/blog/9615017.sHtMl

原标题：golang 系统设计技术文档编写最佳实践
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://book.nrwoja.asia/blog/5695618.sHtMl

原标题：5分钟快速搭建个人技术文档站点
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://book.nrwoja.asia/blog/8120832.sHtMl

原标题：golang 系统设计回调重试幂等完整处理
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://book.nrwoja.asia/blog/5352869.sHtMl

原标题：golang 系统设计网关鉴权鉴权转发流程讲解
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://book.nrwoja.asia/blog/6781238.sHtMl

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.nrwoja.asia/blog/6953150.sHtMl

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://book.nrwoja.asia/blog/2013557.sHtMl

原标题：全局异常处理器接口返回统一
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://book.nrwoja.asia/blog/3971278.sHtMl

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://book.nrwoja.asia/blog/1420273.sHtMl

原标题：golang 系统设计创建更新时间自动维护方案
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.nrwoja.asia/blog/8937455.sHtMl

原标题：实践：消息队列死信处理业务落地实践
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://book.nrwoja.asia/blog/5330741.sHtMl

原标题：多操作系统开发兼容处理
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://book.nrwoja.asia/blog/7421712.sHtMl

原标题：Docker Compose 一键搭建本地栈
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://book.nrwoja.asia/blog/4566195.sHtMl

原标题：golang prometheus 告警规则编写
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.nrwoja.asia/blog/6042160.sHtMl

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://book.nrwoja.asia/blog/3072356.sHtMl

原标题：golang 系统设计接口参数防篡改校验
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://book.nrwoja.asia/blog/9249106.sHtMl

原标题：golang 系统设计技术方案评审关注点清单参考
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://book.nrwoja.asia/blog/1726763.sHtMl

原标题：安全笔记：文件下载接口路径校验安全
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.nrwoja.asia/blog/1273792.sHtMl

原标题：OOMKilled 容器被杀完整排查
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://book.nrwoja.asia/blog/4891731.sHtMl

原标题：golang 系统设计回调重试幂等完整处理
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://book.nrwoja.asia/blog/1946111.sHtMl

原标题：快速入门简单签名校验实现思路
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://book.nrwoja.asia/blog/1234228.sHtMl

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://book.nrwoja.asia/blog/2114942.sHtMl

原标题：安全复盘：定时任务权限过大风险管控
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://book.nrwoja.asia/blog/4762776.sHtMl

原标题：零基础理解会话、Cookie、Session基础
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://book.nrwoja.asia/blog/9297451.sHtMl

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.nrwoja.asia/blog/0495098.sHtMl

原标题：并发数据覆盖加锁安全处理
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://book.nrwoja.asia/blog/0758437.sHtMl

原标题：坑点：gitreset误删本地代码恢复方案
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://book.nrwoja.asia/blog/4034429.sHtMl

原标题：Nginx 静态代理负载均衡全套配置
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://book.nrwoja.asia/blog/3404354.sHtMl

原标题：接口签名验签完整安全方案
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.nrwoja.asia/blog/3350271.sHtMl

原标题：golang lru 缓存淘汰算法编写
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.nrwoja.asia/blog/0416904.sHtMl

原标题：JWT 令牌过期异常处理
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://book.nrwoja.asia/blog/7863688.sHtMl

原标题：vite 插件开发自定义构建逻辑
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.nrwoja.asia/blog/0144587.sHtMl

原标题：全局时间标准统一逻辑错乱修复
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://book.nrwoja.asia/blog/8603803.sHtMl

原标题：零基础理解数据库事务基础ACID概念
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.nrwoja.asia/blog/0521657.sHtMl

原标题：Cookie Session 会话状态管理
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.nrwoja.asia/blog/7309109.sHtMl

原标题：优化实践：读写分离分担主库查询压力
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://book.nrwoja.asia/blog/4656208.sHtMl

原标题：golang docker 部署 kafka 本地调试
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://book.nrwoja.asia/blog/0194125.sHtMl

原标题：golang 系统设计数据库索引设计方法论
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://book.nrwoja.asia/blog/9698055.sHtMl

原标题：提交第一个开源 PR 完整流程
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://book.nrwoja.asia/blog/7318192.sHtMl

原标题：AI实践：大模型生成代码后审查与重构实践
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://book.nrwoja.asia/blog/8272642.sHtMl

三、实战开发｜Practice
原标题：AI‑Dev：利用AI快速阅读陌生开源项目源码
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.nrwoja.asia/blog/8451507.sHtMl

原标题：运维笔记：备份策略数据库定时备份脚本
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://book.nrwoja.asia/blog/2059970.sHtMl

原标题：新手教程：gitrebase基础使用与风险提示
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://book.nrwoja.asia/blog/4830024.sHtMl

原标题：快速入门环境区分：开发、测试、生产环境
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://book.nrwoja.asia/blog/5362640.sHtMl

原标题：Performance：缓存策略优化，降低数据库压力
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://book.nrwoja.asia/blog/5842795.sHtMl

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://book.nrwoja.asia/blog/6169872.sHtMl

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.nrwoja.asia/blog/9097861.sHtMl

原标题：入门实践：简单图片上传预览本地demo
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://book.nrwoja.asia/blog/1734650.sHtMl

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.nrwoja.asia/blog/7150153.sHtMl

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://book.nrwoja.asia/blog/8543084.sHtMl

原标题：golang 系统设计代码安全审计简单思路
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.nrwoja.asia/blog/4024081.sHtMl

原标题：全局时间标准统一逻辑错乱修复
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://book.nrwoja.asia/blog/7081411.sHtMl

原标题：入门实践：简单错误码设计与使用规范
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://book.nrwoja.asia/blog/7288946.sHtMl

原标题：优化实践：读写分离分担主库查询压力
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://book.nrwoja.asia/blog/7838078.sHtMl

原标题：项目实践：Docker多环境镜像构建策略实践
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.nrwoja.asia/blog/4835547.sHtMl

原标题：跨平台 uniapp 多端开发实操
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.nrwoja.asia/blog/8570828.sHtMl

原标题：新手教程：gitstash暂存工作区变更实操
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.nrwoja.asia/blog/7006415.sHtMl

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://book.nrwoja.asia/blog/8674387.sHtMl

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://book.nrwoja.asia/blog/2413551.sHtMl

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://book.nrwoja.asia/blog/2576560.sHtMl

原标题：复盘总结：系统压测报告模板与分析思路
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://book.nrwoja.asia/blog/9058040.sHtMl

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.nrwoja.asia/blog/2008744.sHtMl

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://book.nrwoja.asia/blog/3264355.sHtMl

原标题：golang 系统设计多租户数据隔离方案
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://book.nrwoja.asia/blog/7075137.sHtMl

原标题：golang docker 部署 es 本地开发
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://book.nrwoja.asia/blog/0549571.sHtMl

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://book.nrwoja.asia/blog/3164456.sHtMl

原标题：正则表达式优化 CPU 占满问题
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://book.nrwoja.asia/blog/2087356.sHtMl

原标题：golang channel 通道并发处理
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://book.nrwoja.asia/blog/5716525.sHtMl

原标题：golang 系统设计网络超时故障排查思路
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.nrwoja.asia/blog/1538725.sHtMl

原标题：Practice：实现业务操作日志记录中间件实践
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://book.nrwoja.asia/blog/8237842.sHtMl

原标题：golang docker 镜像构建最佳实践
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://book.nrwoja.asia/blog/8563191.sHtMl

原标题：Practice：实现接口签名、验签完整示例代码
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://book.nrwoja.asia/blog/4500416.sHtMl

原标题：golang 系统设计分布式任务调度
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://book.nrwoja.asia/blog/8611307.sHtMl

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.nrwoja.asia/blog/9049535.sHtMl

原标题：golang 系统设计结构化日志字段规范约定
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://book.nrwoja.asia/blog/0206947.sHtMl

原标题：数据库分表路由写入分片修正
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://book.nrwoja.asia/blog/0869839.sHtMl

原标题：WebSocket 断线重连稳定优化
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://book.nrwoja.asia/blog/7340728.sHtMl

原标题：入门实践：简单批量处理脚本编写
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://book.nrwoja.asia/blog/6697688.sHtMl

原标题：golang 分布式上下文传递方案
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://book.nrwoja.asia/blog/9310215.sHtMl

原标题：后端分页查询逻辑代码实现
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://book.nrwoja.asia/blog/2751456.sHtMl

四、架构设计｜Architecture
原标题：golang consul 健康检查服务注册
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://book.nrwoja.asia/blog/5092200.sHtMl

原标题：golang mysql 防止 sql 注入实践
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://book.nrwoja.asia/blog/4556791.sHtMl

原标题：golang 系统设计内存复用 sync.pool 使用
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://book.nrwoja.asia/blog/4573018.sHtMl

原标题：复盘总结：技术方案文档模板架构设计文档
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://book.nrwoja.asia/blog/1995345.sHtMl

原标题：TCP 长连接参数优化 TIME_WAIT
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://book.nrwoja.asia/blog/2661501.sHtMl

原标题：golang 系统设计线上故障排查完整流程
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.nrwoja.asia/blog/0132931.sHtMl

原标题：实战：单元测试+集成测试完整项目落地实践
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://book.nrwoja.asia/blog/2389658.sHtMl

原标题：实践：前后端分离项目登录状态保持完整方案
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://book.nrwoja.asia/blog/5639574.sHtMl

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://book.nrwoja.asia/blog/3081460.sHtMl

原标题：序列化版本不一致解析失败
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.nrwoja.asia/blog/2042213.sHtMl

原标题：内网测试服务搭建团队调试
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://book.nrwoja.asia/blog/8512986.sHtMl

原标题：快速上手搭建简易内网测试服务
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.nrwoja.asia/blog/1690242.sHtMl

原标题：GC 垃圾回收优化降低 CPU 占用
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.nrwoja.asia/blog/6938043.sHtMl

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://book.nrwoja.asia/blog/2912451.sHtMl

原标题：golang k8s 持久化 pv pvc 使用实操
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://book.nrwoja.asia/blog/7786971.sHtMl

原标题：入门实践：简易导出导入文件功能实现
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://book.nrwoja.asia/blog/9796749.sHtMl

原标题：golang 雪花 id 重复问题排查
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://book.nrwoja.asia/blog/5175689.sHtMl

原标题：灰度发布策略服务平滑升级
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://book.nrwoja.asia/blog/0524502.sHtMl

?
