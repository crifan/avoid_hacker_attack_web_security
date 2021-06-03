# WAF

TODO:

【整理】WAF 安全

---

* WAF
  * 历史
    * WAF产品
      * `Perfecto`的`AppShield`：主要用于电商
      * `ModSecurity`：开源项目
        * 先：基于`WAS TC`去制定保护规则
          * `WAS TC`=OASIS `Web Application Security Technical Committee`
        * 后：基于`OWASP`的Top10去制定规则
        * `OWASP`=`Open Web Application Security Project`
      * 侧重防信用卡诈骗
        * 相关标准
          * `PCI DSS`=`Payment Card Industry Data Security Standard`
  * 现状
    * Web应用已成攻击者首要目标
    * 以硬件设备形式实现的传统WAF不足以提供全面的应用控制和可见性
    * 基于云的新时代WAF可以提供足够的Web防护
      * 交付安全投资的真正价值
