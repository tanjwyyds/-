# -1. 搭建一个包含以下模块的开发环境
• Git代码仓库（如Github
、Gitee、本地Gitlab等）
• Jenkins或其它持续集成与测试工具
• issue tracking模块（例如Github
、JIRA
、MentisBT等）
2. 采用Ant
、Maven等配置工具配置软件项目，项目中必须包含
build
和test两个目标，build用来导出程序的完整jar包，test用来
对程序进行测试。
3. 在持续集成（如Jenkins）中应用项目配置中设定的test任务，完
成冒烟测试。（Jenkins日志中可以看到执行测试用例的提示
）
4. 调研缺陷提交的一般性流程和格式要求，在缺陷管理工具中登记
发现的bug，填写缺陷信息。
5. 按项目将要给其它人接手的角度，为其编写一个简要的
README.md来说明项目开发、测试与缺陷提交步骤、方法（应
具体化，长度不限，交代清晰即可
）
