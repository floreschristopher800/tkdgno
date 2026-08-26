最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计密码存储哈希加盐实现
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.npkgax.asia/arts/575567.Doc

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.npkgax.asia/arts/087444.Doc

原标题：Debug：分布式会话时钟不同步令牌提前失效
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.npkgax.asia/arts/351452.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.npkgax.asia/arts/539711.Doc

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.npkgax.asia/arts/327482.Doc

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.npkgax.asia/arts/023473.Doc

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.npkgax.asia/arts/562270.Doc

原标题：Architecture：日志、监控、告警整套可观测架构
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://wiki.npkgax.asia/arts/893104.Doc

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.npkgax.asia/arts/758701.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.npkgax.asia/arts/755907.Doc

原标题：golang 系统设计网关缓存静态资源实现思路
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://wiki.npkgax.asia/arts/049556.Doc

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.npkgax.asia/arts/614214.Doc

原标题：golang 系统设计分布式事务几种方案
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.npkgax.asia/arts/509810.Doc

原标题：golang 系统设计消息体序列化选型对比
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.npkgax.asia/arts/235044.Doc

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://wiki.npkgax.asia/arts/101570.Doc

原标题：Debug：分布式会话时钟不同步令牌提前失效
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.npkgax.asia/arts/492064.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.npkgax.asia/arts/839978.Doc

原标题：golang 系统设计网络超时故障排查思路
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.npkgax.asia/arts/084742.Doc

原标题：开发复盘：大数据量分页避免offset性能问题
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.npkgax.asia/arts/499851.Doc

原标题：实践：接口参数自动校验业务落地实践
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.npkgax.asia/arts/026228.Doc

原标题：方案设计：接口版本管理架构向前兼容策略
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.npkgax.asia/arts/670009.Doc

原标题：golang mysql 长连接短连接对比
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.npkgax.asia/arts/577740.Doc

原标题：Practice：实现请求ID透传全链路日志实践
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.npkgax.asia/arts/098927.Doc

原标题：golang net/http 超时全套配置
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.npkgax.asia/arts/427458.Doc

原标题：网关超时时间调优后端等待
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.npkgax.asia/arts/240109.Doc

原标题：方案设计：短链接系统完整架构方案拆解
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.npkgax.asia/arts/532582.Doc

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.npkgax.asia/arts/125240.Doc

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.npkgax.asia/arts/535628.Doc

原标题：golang es 分页深分页性能优化
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.npkgax.asia/arts/929285.Doc

原标题：开源实践：开源项目本地调试构建排坑经验
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://wiki.npkgax.asia/arts/465614.Doc

原标题：新手指南：如何读懂开源项目报错日志
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.npkgax.asia/arts/194171.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.npkgax.asia/arts/623692.Doc

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.npkgax.asia/arts/392349.Doc

原标题：数据库事务 ACID 原理讲解
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://wiki.npkgax.asia/arts/544583.Doc

原标题：布隆过滤器数据高效去重实现
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.npkgax.asia/arts/643440.Doc

原标题：golang 系统设计配置敏感信息加密存储
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.npkgax.asia/arts/619650.Doc

原标题：golang 系统设计链路数据存储选型对比讲解
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.npkgax.asia/arts/536020.Doc

原标题：YAML 配置文件语法快速上手
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.npkgax.asia/arts/465293.Doc

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.npkgax.asia/arts/980376.Doc

原标题：安全实践：防止重放攻击接口签名方案
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.npkgax.asia/arts/222472.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计敏感数据加密存储方案
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.npkgax.asia/arts/023034.Doc

原标题：golang 配置热更新不重启服务
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.npkgax.asia/arts/563582.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.npkgax.asia/arts/433556.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.npkgax.asia/arts/458668.Doc

原标题：Practice：模拟磁盘满，验证服务降级表现
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.npkgax.asia/arts/556219.Doc

原标题：golang validator 自定义校验规则
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.npkgax.asia/arts/577666.Doc

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.npkgax.asia/arts/929404.Doc

原标题：项目脚手架模板生成工具
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.npkgax.asia/arts/232533.Doc

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.npkgax.asia/arts/496784.Doc

原标题：golang mysql 行锁表锁场景区分
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.npkgax.asia/arts/025688.Doc

原标题：nodejs jwt 登录鉴权完整示例
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.npkgax.asia/arts/322445.Doc

原标题：golang 系统设计缓存预热脚本编写实操
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.npkgax.asia/arts/141598.Doc

原标题：从零搭建简单CLI命令行工具
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://wiki.npkgax.asia/arts/377335.Doc

原标题：golang 定时任务 cron 使用指南
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.npkgax.asia/arts/976307.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.npkgax.asia/arts/381402.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.npkgax.asia/arts/503085.Doc

原标题：golang k8s pod 优雅关闭流程讲解
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.npkgax.asia/arts/200674.Doc

原标题：golang 系统设计链路查询定位慢请求实操技巧
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://wiki.npkgax.asia/arts/993094.Doc

原标题：Git 分支管理多人协作实战教程
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.npkgax.asia/arts/014628.Doc

原标题：golang 系统设计技术方案评审关注点清单参考
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.npkgax.asia/arts/503495.Doc

原标题：开发记录：分布式ID生成器实现与压力测试
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.npkgax.asia/arts/002378.Doc

原标题：从零学习简单分页逻辑实现思路
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.npkgax.asia/arts/161088.Doc

原标题：单元测试用例编写入门实操
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.npkgax.asia/arts/978584.Doc

原标题：golang 系统设计错误码体系完整设计
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.npkgax.asia/arts/909856.Doc

原标题：Docker 容器网络不通排查
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.npkgax.asia/arts/501942.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.npkgax.asia/arts/950081.Doc

原标题：golang websocket 消息广播实现
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://wiki.npkgax.asia/arts/825448.Doc

原标题：开发复盘：大数据量分页避免offset性能问题
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.npkgax.asia/arts/896943.Doc

原标题：golang kafka 消费者组原理讲解
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.npkgax.asia/arts/881006.Doc

原标题：服务健康检查监控接口开发
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://wiki.npkgax.asia/arts/480063.Doc

原标题：热更新开发环境配置教程
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.npkgax.asia/arts/971879.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.npkgax.asia/arts/972669.Doc

原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.npkgax.asia/arts/453963.Doc

原标题：golang 系统设计数据库扩容几种方式
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.npkgax.asia/arts/996543.Doc

原标题：入门实践：本地简单代理服务搭建
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://wiki.npkgax.asia/arts/216337.Doc

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.npkgax.asia/arts/659928.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.npkgax.asia/arts/231831.Doc

原标题：golang 系统设计本地缓存与分布式缓存
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.npkgax.asia/arts/897902.Doc

原标题：golang 系统设计数据库迁移工具 go‑migrate 实操
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.npkgax.asia/arts/418706.Doc

原标题：golang 系统设计分表分页排序业务实现难点
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://wiki.npkgax.asia/arts/704018.Doc

三、实战开发｜Practice
原标题：pnpm 包管理工具实战避坑指南
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.npkgax.asia/arts/561809.Doc

原标题：安全实践：防止重放攻击接口签名方案
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.npkgax.asia/arts/275641.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.npkgax.asia/arts/402941.Doc

原标题：golang minio 分片上传断点续传
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://wiki.npkgax.asia/arts/723113.Doc

原标题：安全实践：API密钥管理轮换最佳实践
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.npkgax.asia/arts/207847.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.npkgax.asia/arts/034692.Doc

原标题：golang 系统设计分布式锁选型对比
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.npkgax.asia/arts/125836.Doc

原标题：golang 系统设计回调签名校验防伪造实现
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.npkgax.asia/arts/391132.Doc

原标题：架构笔记：数据脱敏架构接入层与存储层方案
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.npkgax.asia/arts/382892.Doc

原标题：文件分片上传断点续传功能
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.npkgax.asia/arts/640380.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://wiki.npkgax.asia/arts/222662.Doc

原标题：golang 系统设计 mq 故障降级业务策略
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.npkgax.asia/arts/304724.Doc

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.npkgax.asia/arts/627482.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.npkgax.asia/arts/233176.Doc

原标题：golang html 模板渲染简单示例
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.npkgax.asia/arts/845623.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.npkgax.asia/arts/936209.Doc

原标题：服务熔断防止故障级联传播
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.npkgax.asia/arts/796910.Doc

原标题：部署复盘：容器OOM问题完整排查流程
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://wiki.npkgax.asia/arts/649509.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.npkgax.asia/arts/707754.Doc

原标题：golang defer panic 异常处理
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://wiki.npkgax.asia/arts/296503.Doc

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.npkgax.asia/arts/855835.Doc

原标题：网关超时时间调优后端等待
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.npkgax.asia/arts/341700.Doc

原标题：golang 系统设计故障预案编写模板参考示例
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://wiki.npkgax.asia/arts/974109.Doc

原标题：golang 系统设计消息大小限制业务处理方案
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.npkgax.asia/arts/303644.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.npkgax.asia/arts/170489.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.npkgax.asia/arts/825509.Doc

原标题：golang goroutine 池任务调度
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.npkgax.asia/arts/806270.Doc

原标题：echarts 大数据渲染性能调优
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.npkgax.asia/arts/439053.Doc

原标题：服务健康检查监控接口开发
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.npkgax.asia/arts/743651.Doc

原标题：前端防抖节流高频事件处理
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.npkgax.asia/arts/636251.Doc

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.npkgax.asia/arts/015396.Doc

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.npkgax.asia/arts/781425.Doc

原标题：新手教程：gitstash暂存工作区变更实操
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://wiki.npkgax.asia/arts/784387.Doc

原标题：批量异步处理系统业务落地
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.npkgax.asia/arts/721164.Doc

原标题：golang 系统设计故障止损降级回滚执行原则
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.npkgax.asia/arts/136830.Doc

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.npkgax.asia/arts/784072.Doc

原标题：golang consul 健康检查服务注册
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.npkgax.asia/arts/633666.Doc

原标题：nestjs 拦截器过滤器管道实战
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.npkgax.asia/arts/417243.Doc

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.npkgax.asia/arts/999222.Doc

原标题：eslint prettier 代码规范落地
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.npkgax.asia/arts/077322.Doc

四、架构设计｜Architecture
原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.npkgax.asia/arts/808350.Doc

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://wiki.npkgax.asia/arts/813849.Doc

原标题：golang http 代理客户端配置
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.npkgax.asia/arts/297950.Doc

原标题：GET POST 接口请求参数处理
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.npkgax.asia/arts/377666.Doc

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.npkgax.asia/arts/347032.Doc

原标题：新手指南：读懂项目构建脚本作用
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.npkgax.asia/arts/715092.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.npkgax.asia/arts/636567.Doc

原标题：golang redis 过期 key 监听业务
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.npkgax.asia/arts/668565.Doc

原标题：Practice：批量异步任务处理系统设计实现
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.npkgax.asia/arts/379532.Doc

原标题：实战项目：多实例部署会话一致性验证实践
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.npkgax.asia/arts/262549.Doc

原标题：golang 系统设计技术文档编写最佳实践
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.npkgax.asia/arts/635624.Doc

原标题：Hands‑on：模板渲染引擎最小原型实现
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.npkgax.asia/arts/713597.Doc

原标题：golang prometheus metrics 埋点开发
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.npkgax.asia/arts/485329.Doc

原标题：设计思考：业务系统如何设计优雅失败架构
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.npkgax.asia/arts/778057.Doc

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.npkgax.asia/arts/356233.Doc

原标题：golang 限流熔断降级完整示例
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.npkgax.asia/arts/430976.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://wiki.npkgax.asia/arts/007066.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.npkgax.asia/arts/497742.Doc

?
