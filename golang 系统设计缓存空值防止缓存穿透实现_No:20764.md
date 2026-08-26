最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/33246.sHtML

原标题：Practice：实现限流之后友好业务返回处理
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/45828.sHtML

原标题：golang 系统设计分布式会话方案对比
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/00696.sHtML

原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/70618.sHtML

原标题：DevOps：环境配置管理区分开发测试生产
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/11992.sHtML

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/82322.sHtML

原标题：Architecture：API网关核心能力与组件拆分
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/72918.sHtML

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/92846.sHtML

原标题：设计思考：业务系统如何设计优雅失败架构
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/81075.sHtML

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/92502.sHtML

原标题：Security：RPC调用身份认证安全加固
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/09476.sHtML

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/51402.sHtML

原标题：nodejs 集成测试业务流程编写
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/00361.sHtML

原标题：排错：多实例部署session共享失效登录失效
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/01880.sHtML

原标题：业务错误码体系设计方案
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/07758.sHtML

原标题：端口占用释放资源重启服务
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/63732.sHtML

原标题：Architecture：服务注册发现架构原理与选型
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/19282.sHtML

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/94296.sHtML

原标题：golang docker 镜像体积优化技巧
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/68655.sHtML

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/48246.sHtML

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/52470.sHtML

原标题：快速入门WebSocket，实现简易双向通信demo
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/77616.sHtML

原标题：golang 系统设计开源项目 release 发布流程
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/67869.sHtML

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/48051.sHtML

原标题：golang 系统设计分库分表 id 全局生成策略
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/66295.sHtML

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/40721.sHtML

原标题：项目实践：分布式会话Redis存储落地实践
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/88766.sHtML

原标题：正则表达式文本处理实战案例
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/17499.sHtML

原标题：定时任务周期调度 demo 开发
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/51495.sHtML

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/85250.sHtML

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/33262.sHtML

原标题：数据库读写分离性能优化
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/55776.sHtML

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/69246.sHtML

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/62134.sHtML

原标题：手写简易 RPC 服务通信原型
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/47724.sHtML

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/65977.sHtML

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/01164.sHtML

原标题：golang excel 简单读写操作示例
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/22912.sHtML

原标题：Practice：实现请求ID透传全链路日志实践
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/41431.sHtML

原标题：golang redis 分布式计数器开发
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/82633.sHtML


二、踩坑排错｜Troubleshooting
原标题：架构复盘：服务优雅停机架构设计资源释放
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/77858.sHtML

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/81522.sHtML

原标题：实践：实现Redis分布式锁完整可运行代码
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/04284.sHtML

原标题：调优方案：CDN优化静态资源访问延迟
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/17087.sHtML

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/81061.sHtML

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/36976.sHtML

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/92960.sHtML

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/10780.sHtML

原标题：文件锁正确使用避免死锁
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/60302.sHtML

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/53015.sHtML

原标题：架构复盘：热点数据防护架构防止节点过载
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/77054.sHtML

原标题：golang 系统设计大表加索引线上执行方案
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/30956.sHtML

原标题：Practice：实现限流之后友好业务返回处理
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/02101.sHtML

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/93894.sHtML

原标题：golang 信号量控制并发数量
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/06382.sHtML

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/30855.sHtML

原标题：golang redis set 集合去重业务
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/40295.sHtML

原标题：golang 接口返回统一封装工具
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/70309.sHtML

原标题：golang alertmanager 钉钉告警推送
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/73761.sHtML

原标题：golang 系统设计定时任务分布式锁
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/32187.sHtML

原标题：避坑：版本升级之后项目直接无法启动
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/56607.sHtML

原标题：Nginx 静态代理负载均衡全套配置
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/73581.sHtML

原标题：golang 系统设计高可用服务架构梳理
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/52573.sHtML

原标题：golang 系统设计内部服务契约测试简单思路
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/08040.sHtML

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/52232.sHtML

原标题：golang 系统设计 git 分支流程 gitflow 实操
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/01692.sHtML

原标题：golang ci 流水线环境变量管理方案
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/18168.sHtML

原标题：Architecture：对象存储接入业务整体架构
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/92142.sHtML

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/61480.sHtML

原标题：程序日志分级输出规范实践
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/63689.sHtML

原标题：golang 系统设计网关请求日志 traceId 透传实现
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/31122.sHtML

原标题：Architecture：配置中心架构，动态配置设计思路
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/81294.sHtML

原标题：入门实践：使用模板快速生成项目脚手架
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/77419.sHtML

原标题：优化实践：读写分离分担主库查询压力
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/32223.sHtML

原标题：开发记录：容器日志标准输出采集实践方案
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/85594.sHtML

原标题：DevOps：CI构建产物缓存复用加速编译
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/51162.sHtML

原标题：golang k8s cronjob 定时任务配置
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/94854.sHtML

原标题：包管理器依赖冲突解决方案
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/02521.sHtML

原标题：golang k8s 网络策略网络隔离设置
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/48314.sHtML

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/85673.sHtML

三、实战开发｜Practice
原标题：golang defer panic 异常处理
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/85783.sHtML

原标题：CLI 工具进度条交互效果开发
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/08728.sHtML

原标题：golang 单元测试 table‑driven
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/80722.sHtML

原标题：CI 持续集成自动构建流程
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/85006.sHtML

原标题：golang jaeger 链路追踪 go 接入
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/82717.sHtML

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/65923.sHtML

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/30272.sHtML

原标题：golang k8s cronjob 定时任务配置
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/00299.sHtML

原标题：优化实践：预加载与懒加载业务场景取舍
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/03198.sHtML

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/76989.sHtML

原标题：调优方案：服务实例扩容，水平扩展性能
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/73753.sHtML

原标题：nestjs 拦截器过滤器管道实战
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/81180.sHtML

原标题：零基础理解HTTP常用请求头与状态码
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/63970.sHtML

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/01753.sHtML

原标题：golang k8s 网络策略网络隔离设置
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/68792.sHtML

原标题：golang 系统设计 mq 消息积压解决方案
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/77382.sHtML

原标题：Security：Docker镜像安全扫描漏洞修复
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/62104.sHtML

原标题：内网 DNS 不稳定随机报错排查
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/06726.sHtML

原标题：调优方案：Nginx性能参数调优高并发配置
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/07027.sHtML

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/41574.sHtML

原标题：golang 系统设计缓存预热脚本编写实操
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/52727.sHtML

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/42511.sHtML

原标题：数据库分表存储大表优化方案
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/33312.sHtML

原标题：vite 项目配置与构建提速技巧
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/67459.sHtML

原标题：golang redis 大 key 识别处理方案
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/66859.sHtML

原标题：golang 系统设计缓存预热缓存降级实现
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/52170.sHtML

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/41394.sHtML

原标题：安全组端口开放网络访问
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/48321.sHtML

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/28567.sHtML

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/58180.sHtML

原标题：接口签名校验防篡改实现
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/75468.sHtML

原标题：HelloShell：入门常用shell脚本编写
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/25066.sHtML

原标题：实战：基于DockerCompose搭建本地开发栈
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/88274.sHtML

原标题：golang kafka 消息顺序性保证方案
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/28453.sHtML

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/79986.sHtML

原标题：Redis 内存淘汰策略数据防丢失
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/95446.sHtML

原标题：Hands‑on：模板渲染引擎最小原型实现
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/14231.sHtML

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/52860.sHtML

原标题：快速入门日志打印与日志分级基础用法
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/25792.sHtML

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/36412.sHtML

四、架构设计｜Architecture
原标题：Performance：避免大报文，减少内存占用优化
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/40325.sHtML

原标题：快速上手简单信号处理脚本编写
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/70145.sHtML

原标题：golang gorm 批量插入性能调优
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/73681.sHtML

原标题：golang 数据库批量更新性能优化
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/74093.sHtML

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/83871.sHtML

原标题：golang 系统设计代码安全审计简单思路
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/99113.sHtML

原标题：Redis 分布式锁高并发安全实现
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/58007.sHtML

原标题：golang 系统设计数据库查询优化完整流程
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/65260.sHtML

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/83689.sHtML

原标题：安全实践：备份文件访问权限安全管控
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/02924.sHtML

原标题：架构笔记：分库分表中间件选型业务约束
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/01096.sHtML

原标题：golang k8s job 一次性任务执行
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/18945.sHtML

原标题：golang 系统设计开源项目维护简单经验分享
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/71795.sHtML

原标题：golang 系统设计内部服务熔断降级配置思路
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/25540.sHtML

原标题：安全复盘：Redis命令注入风险防护手段
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/26421.sHtML

原标题：设计思考：系统容量评估架构前期估算思路
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/74177.sHtML

原标题：golang mysql 行锁表锁场景区分
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/47207.sHtML

原标题：golang 系统设计 canary 金丝雀部署实操
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://baoma.fzzhiyan.cn/Article/details/21052.sHtML

?
