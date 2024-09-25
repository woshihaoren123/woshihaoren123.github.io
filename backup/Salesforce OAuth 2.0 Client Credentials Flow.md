描述：在Salesforce和第三方服务器中共享用户信息，而无需用户参与
文档：https://help.salesforce.com/s/articleView?id=sf.remoteaccess_oauth_client_credentials_flow.htm&type=5&language=en_US
使用方案：
1. 创建Integration Profile
2. 创建Integration User
3. 创建Connected App, Run As Integration User
4. 调用API测试，是否返回Access Token
5. 调用API测试，是否返回权限允许内相关记录信息
