# ids4
 identity server 4 是asp.net core 的openid connect 和oauth2框架<br>	
可以提供的功能：<br>
1.认证即服务<br>
2.适用于所有应用程序的集中登录逻辑和工作流程，idetity server是openid connect 的官方认证实现<br>
3.单点登录/注销<br>
4.多个类型的应用程序在一个点进行登录和注销操作<br>
5.api访问控制<br>
6/为各种类型的客户端颁发API的令牌，例如服务器到服务器，Web应用程序，SPA,本地应用和移动应用程序<br>
7.联合网关<br>
8.支持Azure Active Directory，Google，Facebook等外部身份提供商。这可以保护您的应用程序免受如何连接到这些外部提供商的详细信息的影响<br>

Oauth2协议，它允许应用程序从一个安全令牌服务要求访问令牌，使用这个访问令牌来访问API。这个机制降低了客户机应用程序和API的复杂性，因为身份验证和授权是可以集中式的

OpenId connect 式OAuth的扩展。它将两个基本安全，认证和api的访问，被组合成单个协议，通常只需要一次往返安全令牌服务

Identity Server 是将规范兼容的Oauth2和openid connect 端点添加到.net core任意中间件。

identity server 中间件会向其添加必要的协议头

