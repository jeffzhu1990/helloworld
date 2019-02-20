# 将附件从文章中剥离
**太多的详细参数对文章的思路形成了干扰**

Overview of Power BI Gateway 将从以下5篇文章中汲取思路：
* 本地数据网关
* 本地数据网关 - 深入了解
* 本地数据网关（个人模型）
* 自定义连接器
* 本地数据网关故障排查
* 安装网关
* 管理网关

**整理过程中的规则**
<font color=#FF0000>使用醒目颜色标注重复内容</font>

## 本地数据网关
1. 附件一：可用数据源类型列表
2. 附件二：端口/网关使用的完全限定域名的列表

## 本地数据网关 - 深入了解
1. 附件一：可用数据源类型列表

## 本地数据网关故障排查
1. 附件一：性能计数器
    - 计数器的分组
    - 可用性能计数器的列表

#### 以下是对文章思路的厘定：
**本地数据网关**
* 操作系统及硬件要求
* 使用时注意事项
* Analysis Service 实时连接限制
* <font color=00FFFF>附件一</font>
* 下载并安装本地数据网关（本地数据网关&个人模式网关）
* 配置新网关（本地数据网关&个人模式网关）
* Tips：
    - 在云中存储加密凭据
    <font color=00FFFF>- 登录账户
    - Windows 服务账户
    - 强制HTTPS与Azure服务总线通信
    - 对TLS 1.2 的支持
* 如何重启网关</font>
* 网关的工作原理
    - 限制和注意事项
    - 租户级别管理
    - 启用出站Azure连接

**本地数据网关 - 深入了解**
* 介绍
* 网关的工作原理
* 附件一
* <font color=#FF0000>登录账户</font>
* 向本地数据源进行身份验证
* 向实时 Analysis Services 数据源进行身份验证
* 基于角色的安全性
* 行级别安全性
* Azure Active Directory 如何
* 如何辨别我的 UPN
* 映射 Analysis Services 数据源的用户名
* 将本地 Active Directory 与 Azure Active Directory 同步
* 现在，这就网关起作用的地方
* 接下来该怎么做
* 这时事情可能会出错
* <font color=#FF0000>登录帐户 (不用怀疑，就是第四个提到的一模一样的内容，微软就是这么任性，文档不是一般的烂)</font>
* <font color=#FF0000>Windows 服务帐户</font>
* <font color=#FF0000>附件二</font>
* <font color=#FF0000>强制HTTPS与Azure服务总线通信</font>
* <font color=#FF0000>对TLS 1.2 的支持</font>
* <font color=#FF0000>如何重启网关</font>




