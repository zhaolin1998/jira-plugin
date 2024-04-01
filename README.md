Source code for:

https://developer.atlassian.com/display/DOCS/Set+up+the+Atlassian+Plugin+SDK+and+Build+a+Project

The files we looked at in this tutorial were:

- pom.xml
- /src/main/resources/atlassian-plugin.xml

-------------------------------------------------------------------------------------
Here are the SDK commands you'll use immediately:

* atlas-run   -- installs this plugin into the product and starts it on localhost
* atlas-debug -- same as atlas-run, but allows a debugger to attach at port 5005
* atlas-cli   -- after atlas-run or atlas-debug, opens a Maven command line window:
                 - 'pi' reinstalls the plugin into the running product instance
* atlas-help  -- prints description for all commands in the SDK
* atlas-run -- product jira --version 6.1 -- 运行在指定版本

Full documentation is always available at:

https://developer.atlassian.com/display/DOCS/Introduction+to+the+Atlassian+Plugin+SDK

pom文件配置<enableQuickReload>true</enableQuickReload>，在插件运行时，可直接修改代码，运行atlas-mvn package即可部署

![插件运行效果图](img_v3_029h_802d2a13-7137-46b3-866e-78842a3588bg.jpg)