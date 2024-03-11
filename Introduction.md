## Broken Access Control 访问控制失效

例子： 应用程序可以更改数据库主键，在此主键更改为另一个用户的记录时， 可以查看或修改用户的账户

## Cryptographic Failures 加密失效

加密失效实际上指的是机构或公司对于数据的保护不当导致的破坏或者泄露，而加密失效是指出了造成这个局面的根本原因

## injuction 注入

例子：后端在进行数据库操作的时候会拼接字符串数据，导致数据库操作语句被字符串等方式注入

## insecure Design
主要是考虑与设计逻辑的安全漏洞

## Security Misconfiguration
安全配置问题，主要在于用户或企业对于安全配置的疏忽造成的安全问题
例子：使用默认的用户名密码

## Vulnerable and Outdated Components 易受攻击和过时的组件
在大量应用不关心底层组件实现的情况下，可能造成因为组件漏洞或者过时产生的安全问题

## identifications and Authentication Failures 识别和认证失效
与身份验证和会话管理相关的安全问题，如果实现不当，会允许攻击者破环密码，关键字和会话
例子：允许使用弱密码或不设置多次验证失败的限制导致被暴力破解

## Software and Data integrity Failures 软件和数据安全性故障
关注于软件更新和关键数据的使用和软件完整性的验证，也包含了不安全的反序列化

## Security logging and Monitoring Failures 安全日志和监视故障

因为对于安全日志的监视和分析不足，导致了严重的安全事故

## 服务器请求伪造
例子：在server没有验证网络包的URL的情况下被请求远程资源，就有可能发生信息的泄露
