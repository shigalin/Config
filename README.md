# Config
* 无聊建了个频道 https://t.me/useConfig
* 收集并修改的配置文件
* Quantumult.conf：主要是同步https://github.com/lhie1/Surge/blob/master/Shadowrocket.conf 配置，根据Filter Action添加相关服务服务器选择，如Apple，Netflix
* https://raw.githubusercontent.com/shigalin/Config/master/Quantumult.conf 等同于 https://raw.githubusercontent.com/lhie1/Surge/master/Quantumult.conf 
* https://raw.githubusercontent.com/shigalin/Config/master/Quantumult_URL.conf 等同于 https://raw.githubusercontent.com/lhie1/Surge/master/Quantumult_URL.conf 

# Quantumult规则使用：
1. 进入Settings — Favorites
2. 选择右上角添加，Server（服务器订阅），Filter（TCP规则订阅），Rejection（URL规则订阅）
3. 选择 Filter ，Name随意，URL填入 https://raw.githubusercontent.com/shigalin/Config/master/Quantumult.conf ，勾选Filter Action
4. 如果开启了HTTPS解密进入第5步
5. 选择 Rejection ，Name随意 ，URL填入 https://raw.githubusercontent.com/shigalin/Config/master/Quantumult_URL.conf , 勾选Including Host Names
6. 在Favorites的Filter订阅和Rejection订阅多了订阅的选项，左滑选项，选择Replace替换规则
7. 在Filter替换过程中，注意选择Apple服务是选择直连或者代理，包含iCloud服务和App Store下载等。其他如果不需要默认选项即可

