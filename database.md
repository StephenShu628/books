database consistency





---------------------------
DynamoDB  :The DynamoDB Book

CAP定理：
表示在分布式系统中三个指标相互制约，不可能三个都达到的理论；

C--- consistency 一致性 指的是读某个数据是返回的是最后写的值；这个指标和复制有关；
A--- availability 可用性 指的是每次从节点查询都会返回正确的值； 这个和可读取有关；
P--- partition tolerence 分区兼容性 指的是网络问题导致节点不能通信但是不影响系统运行；这个和容错有关；
