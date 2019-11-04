# 目录
* [brpc使用的线程模型](docs/thread_model.md)
* [M:N线程库]
  * [bthread原理]()
  * [pthread调度执行bthread]
  * [pthread线程间的Futex同步](docs/futex.md)
  * [Butex机制：bthread级别的挂起与唤醒](docs/bthread_sync_strategy.md)
* 网络数据IO的处理方法
  * [protobuf编程模式](docs/io_protobuf.md)
  * [多线程向同一TCP连接写入数据](docs/io_write.md)
  * [从TCP连接读取数据](docs/io_read.md)
* Client端执行流程
  * [无异常状态下的一次完整RPC请求过程](docs/client_rpc_normal.md)
  * 重试策略
  * Backup Request
  * [同一RPC过程中各个bthread间的同步](docs/client_bthread_sync.md)
* Server端执行流程
  * 处理一次请求的完整过程
  * 服务限流
  * 防雪崩
* 性能监控
* 基础工具库
  * 对象池
  * 定时器
  * 多线程环境下的计数器
  * 侵入式双向链表
