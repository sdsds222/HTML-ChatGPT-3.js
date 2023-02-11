# ChatGPT.js

#### 介绍
一个用原生JavaScript和编写的ChatGPT API接口使用聊天界面，基于openai的GPT-3技术，

并增加记忆对话上下文的功能，使AI对话更加自然，可实现与官网ChatGPT类似的持续性对话效果。

#### 软件架构
软件架构说明
Javascript HTML CSS

#### 安装教程

1.  将完整项目克隆到电脑
2.  双击index.html文件
3.  启动浏览器运行

#### 使用说明

1.  要使用该页面需要提前自备openai的apikey，否则将无法正常使用所有功能。
2.  基于原生Javascript，可直接部署到静态网页托管平台运行。
3.  在输入框输入“/help”即可查看支持的指令,可通过这些指令来更改发送请求的参数以调整AI的行为：
/help （用于查看帮助信息）
/apikey  (为每次发送的文本添加前置上下文)
/prompt  (为每次发送的文本添加前置上下文)
/maxtoken  (用于控制ChatGPT每次能生成的词数.)
/tpr (可以用来控制chatbot生成的话的多样性)
/top  (可以用来控制chatbot生成的话的质量)
/fp  (可以用来控制chatbot生成的话的“新颖程度”)
/pp  (用于控制bot产生的句子的长度)
/info  (用于显示当前各项参数的值)
/mode  (用于设置是否启用持续对话模式)


#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

