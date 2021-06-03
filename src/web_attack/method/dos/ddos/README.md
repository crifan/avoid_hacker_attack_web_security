# DDoS

* `DDos`=`Distributed DoS`=`Distributed Denial Of Service`=`分布式拒绝服务攻击`
  * 是什么：当黑客使用网络上两个或以上(被攻陷的)电脑(作为`僵尸`)向特定的目标发动`拒绝服务`式攻击
    * 重点：DoS攻击不是来自一个地方，而是来自四面八方
  * 相关名词
    * 攻
        * `DDoS攻击`
    * 防
        * `DDoS防护` = `防DDoS`(攻击) = `DDoS治理`
  * 特点
    * 很难防得住
    * 一般被DDoS攻击的都是重要服务、知名网站
      * 比如银行、信用卡支付网关、甚至根域名服务器等
  * (被攻击的)结果=现象
    * 网络异常缓慢（打开文件或访问网站）
    * 特定网站无法访问
    * 无法访问任何网站
    * 垃圾邮件的数量急剧增加
    * 无线或有线网络连接异常断开
    * 长时间尝试访问网站或任何互联网服务时被拒绝
    * 服务器容易断线、卡顿、lag
  * DDoS攻击形式
    * 攻击形式
      * 带宽消耗型
        * `UDP洪水攻击`=`User Datagram Protocol Floods`
        * `ICMP洪水攻击`=`ICMP Floods`
        * `死亡之Ping`=`Ping of death`
        * `泪滴攻击`
      * 资源消耗型
        * `协议分析攻击`=`SYN flood`=`SYN洪水`
        * `LAND攻击`
        * `CC攻击`=`Distributed HTTP flood`=`分布式HTTP洪水攻击`
        * `僵尸网络攻击`
        * `应用程序级洪水攻击`=`Application level floods`
  * 防御=对策
    * 防御方式
      * 入侵检测
      * 流量过滤
      * 多重验证
    * 防御工具
      * 防火墙
      * 交换机
      * 路由器
