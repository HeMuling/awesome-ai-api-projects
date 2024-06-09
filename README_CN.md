# Awesome AI Api Projects

|[English](README.md)|简体中文|

可以使用ai api（例如openai api，gemini api等）的各种项目列表。

- [ChatAI](# ChatAI)
  - [Web app](#Web-app)
  - [Desktop app](#Desktop app)
  - [Phone app](#Phone app)
  - [Bot](# Bot)
- [AI Agent](#AI Agent)
  - [Framework](#Framework)
  - [File](#File)
  - [Task](#Task)
  - [Research](# Research)
  - [Web crawler](# Web crawler)
- [Extension](#Extension)
  - [Browser](# Browser)
  - [IDE](# IDE)

## ChatAI

### Web app

| Name                                                         | Description                                                  | Open- or Close- source | Self-hosted or Local | Api supported                                                | Last update                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------- | -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [lobe-chat](https://github.com/lobehub/lobe-chat)            | LLMs 聊天应用与开发框架支持语音合成、多模态、可扩展的插件系统。支持社区助手、插件分享。 | open                   | Both, official       | 全能, 本地模型                                               | ![GitHub last commit](https://img.shields.io/github/last-commit/lobehub/lobe-chat?label=%20) |
| [Chuanhu Chat](https://github.com/GaiZhenbiao/ChuanhuChatGPT) | 为ChatGPT等多种LLM提供了一个轻快好用的Web图形界面和众多附加功能：支持 GPT-4 · 基于文件问答 · LLM本地部署 · 联网搜索 · Agent 助理 · 支持 Fine-tune | open                   | Both                 | [OpenAI](https://platform.openai.com/playground), [Google Gemini](https://ai.google.dev/gemini-api), [Claude](https://www.anthropic.com/), 本地模型 | ![GitHub last commit](https://img.shields.io/github/last-commit/GaiZhenbiao/ChuanhuChatGPT?label=%20) |
| [ChatGPT-PerfectUI](https://github.com/ConnectAI-E/ChatGPT-PerfectUI) | 基于Vue3 + Vite + Tailwindcss，复刻ChatGPT网页，体验一模一样的web-app！ | open                   | Local only           | [OpenAI](https://platform.openai.com/playground)             | ![GitHub last commit](https://img.shields.io/github/last-commit/ConnectAI-E/ChatGPT-PerfectUI?label=%20) |
| [ChatGPT-Next-Web](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web) | 一键免费部署你的跨平台私人 ChatGPT 应用，支持 GPT3, GPT4 & Gemini Pro 模型。 | open                   | Both                 | [OpenAI](https://platform.openai.com/playground), [Google Gemini](https://ai.google.dev/gemini-api), [Claude](https://www.anthropic.com/) | ![GitHub last commit](https://img.shields.io/github/last-commit/ChatGPTNextWeb/ChatGPT-Next-Web?label=%20) |
| [chatgpt-web](https://github.com/Chanzhaoyu/chatgpt-web)     | 用 Express 和 Vue3 搭建的 ChatGPT 演示网页                   | open                   | Local only           | [OpenAI](https://platform.openai.com/playground)             | ![GitHub last commit](https://img.shields.io/github/last-commit/Chanzhaoyu/chatgpt-web?label=%20) |
| [LibreChat](https://github.com/danny-avila/LibreChat)        | 一个UI配对ChatGPT，包括暗黑模式、流式传输和最新更新，兼容远程与本地AI服务，文件上传分析和高级代理等 | open                   | Local only           | [OpenAI](https://platform.openai.com/playground), [Google Gemini](https://ai.google.dev/gemini-api), [Claude](https://www.anthropic.com/), 本地模型 | ![GitHub last commit](https://img.shields.io/github/last-commit/danny-avila/LibreChat?label=%20) |
| [khoj](https://github.com/khoj-ai/khoj)                      | 通过整合笔记、文件和网络的实时信息，创建始终可用的个人 AI 代理，以扩展您的能力。 | open                   | Both+official        | [OpenAI](https://platform.openai.com/playground), [Claude](https://www.anthropic.com/), 本地模型 | ![GitHub last commit](https://img.shields.io/github/last-commit/khoj-ai/khoj?label=%20) |
| [h2ogpt](https://github.com/h2oai/h2ogpt)                    | 查询和总结您的文档，或者只是与本地私人 GPT LLMs 进行聊天     | open                   | Local only           | 本地模型                                                     | ![GitHub last commit](https://img.shields.io/github/last-commit/h2oai/h2ogpt?label=%20) |
| [quivr](https://github.com/QuivrHQ/quivr)                    | 创建 AI 助手，可以连接特定的数据源，或用工具处理特定输入以生成实用输出 | open                   | both                 | [OpenAI](https://platform.openai.com/playground), 本地模型   | ![GitHub last commit](https://img.shields.io/github/last-commit/QuivrHQ/quivr?label=%20) |

### Desktop app

| Name                                            | Description                                                  | Open- or Close- source | Platform              | Api supported                                                | Last update                                                  |
| ----------------------------------------------- | ------------------------------------------------------------ | ---------------------- | --------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [ChatALL](https://github.com/sunner/ChatALL)    | ChatALL可以把一条指令同时发给多个 AI，帮助您发现最好的回答。 | open                   | Windows, macOS, Linux | [OpenAI](https://platform.openai.com/playground), [Google Gemini](https://ai.google.dev/gemini-api), [Claude](https://www.anthropic.com/), 本地模型 | ![GitHub last commit](https://img.shields.io/github/last-commit/sunner/ChatALL?label=%20) |
| [chatbox](https://github.com/Bin-Huang/chatbox) | 你的终极桌面AI助手。 Chatbox是一个桌面客户端，支持ChatGPT、Claude和其他大型语言模型 | open                   | Windows, macOS, Linux | [OpenAI](https://platform.openai.com/playground), [Google Gemini](https://ai.google.dev/gemini-api), [Claude](https://www.anthropic.com/), 本地模型 | ![GitHub last commit](https://img.shields.io/github/last-commit/Bin-Huang/chatbox?label=%20) |
| [Noi](https://github.com/lencx/Noi)             | 可定制的AI增强浏览器，提供个性化浏览体验，具有强大的提示管理、批量AI消息功能、主题选择、无需标签的缓存模式以及多账户支持 | open                   | Windows, macOS, Linux | 全能                                                         | ![GitHub last commit](https://img.shields.io/github/last-commit/lencx/Noi?label=%20) |

### Phone app

| Name                                                         | Description                                                  | Open- or Close- source | Platform                                                     | Api supported                                                | Last update                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [chatbox](https://github.com/Bin-Huang/chatbox)              | 你的终极桌面AI助手。 Chatbox是一个桌面客户端，支持ChatGPT、Claude和其他大型语言模型，可在Windows、Mac和Linux平台上使用。 | open                   | [iOS](https://apps.apple.com/us/app/chatbox-ai/id6471368056), [Android](https://play.google.com/store/apps/details?id=xyz.chatboxapp.chatbox) | [OpenAI](https://platform.openai.com/playground), [Google Gemini](https://ai.google.dev/gemini-api), [Claude](https://www.anthropic.com/) | ![GitHub last commit](https://img.shields.io/github/last-commit/Bin-Huang/chatbox?label=%20) |
| [ChatX](https://apps.apple.com/cn/app/chatx-ai-chat-client/id6446304087?l=en-GB) | 小而轻的 AI 聊天客户端                                       | close                  | [iOS](https://apps.apple.com/cn/app/chatx-ai-chat-client/id6446304087?l=en-GB) | [OpenAI](https://platform.openai.com/playground), [Google Gemini](https://ai.google.dev/gemini-api), [Claude](https://www.anthropic.com/) | NA                                                           |

### Bot

| Name                                                         | Description                                                  | Open- or Close- source | Platform                             | Api supported                                    | Last update |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------- | ------------------------------------ | ------------------------------------------------ | ----------- |
| [chatgpt-on-wechat](https://github.com/zhayujie/chatgpt-on-wechat) | 基于LLM的对话机器人，支持私聊及群聊的消息智能回复，语音、图像、知识库，支持插件 | open                   | 微信公众号、企业微信应用、飞书、钉钉 | 全能                                             |![GitHub last commit](https://img.shields.io/github/last-commit/zhayujie/chatgpt-on-wechat?label=%20)|
| [gpt-ai-assistant](https://github.com/memochou1993/gpt-ai-assistant) | 使用 LINE 与专属 AI 助理聊天                                 | open                   | Line                                 | [OpenAI](https://platform.openai.com/playground) |![GitHub last commit](https://img.shields.io/github/last-commit/memochou1993/gpt-ai-assistant?label=%20)|

## AI Agent

### Framework

| Name                                                | Description                                                  | Open- or Close- source | Platform         | Self-hosted or Local | Api supported                                                | Last update                                                  |
| --------------------------------------------------- | ------------------------------------------------------------ | ---------------------- | ---------------- | -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [botpress](https://github.com/botpress/botpress)    | 对话机器人创建平台，提供拖放界面的可视化编程、多渠道支持、自然语言理解、消息API、多编程语言支持、丰富模块 | open                   | Web ui           | Loacl, offical       | [OpenAI](https://platform.openai.com/playground), [Google Gemini](https://ai.google.dev/gemini-api), [Claude](https://www.anthropic.com/), 本地模型 | ![GitHub last commit](https://img.shields.io/github/last-commit/botpress/botpress?label=%20) |
| [MetaGPT](https://github.com/geekan/MetaGPT)        | 内部包括产品经理 / 架构师 / 项目经理 / 工程师，通过模拟软件公司执行任务。 | open                   | CLI, pip package | Local                | 全能, 本地模型                                               | ![GitHub last commit](https://img.shields.io/github/last-commit/geekan/MetaGPT?label=%20) |
| [dify](https://github.com/langgenius/dify)          | LLM 应用开发平台。提供拖放界面的可视化编程、 AI 工作流、RAG 管道、Agent、模型管理、可观测性功能等 | open                   | Web ui           | Both, offical        | 全能, 本地模型                                               | ![GitHub last commit](https://img.shields.io/github/last-commit/langgenius/dify?label=%20) |
| [DB-GPT](https://github.com/eosphoros-ai/DB-GPT)    | 围绕数据库构建LLM应用的开发框架。支持多模型管理(SMMF)、Text2SQL效果优化、RAG框架以及优化、Multi-Agents框架协作、AWEL(智能体工作流编排)等多种技术能力 | open                   | Web ui           | Both                 | 全能, 本地模型                                               | ![GitHub last commit](https://img.shields.io/github/last-commit/eosphoros-ai/DB-GPT?label=%20) |
| [TaskingAI](https://github.com/TaskingAI/TaskingAI) | 基于LLM的代理开发和部署 的BaaS平台。提供直观的用户界面来管理LLM应用程序功能模块，包括工具、RAG系统、助手、对话历史等 | open                   | Web ui           | Local                | 全能, 本地                                                   | ![GitHub last commit](https://img.shields.io/github/last-commit/TaskingAI/TaskingAI?label=%20) |

### File

| Name                                                     | Description                                                  | Open- or Close- source | Self-hosted or Local | Api supported                                                | Last update                                                  |
| -------------------------------------------------------- | ------------------------------------------------------------ | ---------------------- | -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [h2ogpt](https://github.com/h2oai/h2ogpt)                | 查询和总结您的文档，或者只是与本地私人 GPT LLMs 进行聊天     | open                   | Local only           | 本地模型                                                     | ![GitHub last commit](https://img.shields.io/github/last-commit/h2oai/h2ogpt?label=%20) |
| [Chat2DB](https://github.com/chat2db/Chat2DB)            | 数据管理、开发和分析工具。可以将自然语言转换为 SQL，将 SQL 转换为自然语言，还可以自动生成报告。支持Mysql、Postgresql、SQLServer、DB2、Oracle、SQLServer、Oceanbase、Clickhouse、Redis、H2、SQLite、Dameng | open                   | Local+official       | [OpenAI](https://platform.openai.com/playground), [Google Gemini](https://ai.google.dev/gemini-api), [Claude](https://www.anthropic.com/) | ![GitHub last commit](https://img.shields.io/github/last-commit/chat2db/Chat2DB?label=%20) |
| [lollms-webui](https://github.com/ParisNeo/lollms-webui) | 该项目旨在提供一个用户友好的界面，以便访问和利用各种LLM和其他人工智能模型来执行各种任务。 | open                   | Local only           | [OpenAI](https://platform.openai.com/playground)             | ![GitHub last commit](https://img.shields.io/github/last-commit/ParisNeo/lollms-webui?label=%20) |
| [FastGPT](https://github.com/labring/FastGPT)            | 基于 LLM 大语言模型的知识库问答系统，提供开箱即用的数据处理、模型调用等能力。同时可以通过 Flow 可视化进行工作流编排，从而实现复杂的问答场景 | open                   | Both+official        | 全能, 本地模型                                               | ![GitHub last commit](https://img.shields.io/github/last-commit/labring/FastGPT?label=%20) |
| [DocsGPT](https://github.com/arc53/DocsGPT)              | 简化了在项目文档中查找信息的过程。通过集成强大的 GPT 模型，开发人员可以轻松提出关于项目的问题并获得准确的答案 | open                   | Both+official        | [OpenAI](https://platform.openai.com/playground), [Claude](https://www.anthropic.com/), 本地模型(特别训练的模型) | ![GitHub last commit](https://img.shields.io/github/last-commit/arc53/DocsGPT?label=%20) |
| [pdfGPT](https://github.com/bhaskatripathi/pdfGPT)       | 利用LLM阅读pdf                                               | open                   | Local only           | [OpenAI](https://platform.openai.com/playground)             | ![GitHub last commit](https://img.shields.io/github/last-commit/bhaskatripathi/pdfGPT?label=%20) |

### Task

| Name                                                         | Description                                                  | Task  kind                       | Open- or Close- source | Platform         | Self-hosted or Local | Api supported                                                | Last update                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------- | ---------------------- | ---------------- | -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)   | 利用人工智能进行建设、测试和委派任务，彻底改变创新和生产力。 | Code                             | open                   | CLI, Web ui      | Local                | [OpenAI](https://platform.openai.com/playground), [Claude](https://www.anthropic.com/), [Groq](https://console.groq.com/keys) | ![GitHub last commit](https://img.shields.io/github/last-commit/Significant-Gravitas/AutoGPT?label=%20) |
| [gpt-engineer](https://github.com/gpt-engineer-org/gpt-engineer) | 利用自然语言让AI编写并执行代码，要求AI实施改进               | Code                             | open                   | CLI              | Local                | [OpenAI](https://platform.openai.com/playground), [Claude](https://www.anthropic.com/), 本地模型 | ![GitHub last commit](https://img.shields.io/github/last-commit/gpt-engineer-org/gpt-engineer?label=%20) |
| [MetaGPT](https://github.com/geekan/MetaGPT)                 | 内部包括产品经理 / 架构师 / 项目经理 / 工程师，通过模拟软件公司执行任务。 | Code, Research, Data interpreter | open                   | CLI, pip package | Local                | 全能, 本地模型                                               | ![GitHub last commit](https://img.shields.io/github/last-commit/geekan/MetaGPT?label=%20) |
| [AgentGPT](https://github.com/reworkd/AgentGPT)              | 通过LLM与访问互联网实现用户指定的任务                        | Any                              | open                   | Web ui           | Local, official      | [OpenAI](https://platform.openai.com/playground)             | ![GitHub last commit](https://img.shields.io/github/last-commit/reworkd/AgentGPT?label=%20) |
| [SWE-agent](https://github.com/princeton-nlp/SWE-agent)      | 接收 GitHub 问题，并尝试使用LLM自动修复它                    | Debug                            | open                   | Web ui           | Local                | [OpenAI](https://platform.openai.com/playground), [Claude](https://www.anthropic.com/) | ![GitHub last commit](https://img.shields.io/github/last-commit/princeton-nlp/SWE-agent?label=%20) |
| [pandas-ai](https://github.com/Sinaptik-AI/pandas-ai)        | 用生成式人工智能来探索、清洗和分析数据。                     | Data analysis                    | open                   | pip package      | Local                | [OpenAI](https://platform.openai.com/playground), [some strange model](https://docs.pandas-ai.com/llms) | ![GitHub last commit](https://img.shields.io/github/last-commit/Sinaptik-AI/pandas-ai?label=%20) |
| [DevOpsGPT](https://github.com/kuafuai/DevOpsGPT)            | 利用LLM将自然语言需求转化为可工作的软件。根据多次问答确定开发细节。 | Code                             | open                   | Web ui           | Local                | [OpenAI](https://platform.openai.com/playground)             | ![GitHub last commit](https://img.shields.io/github/last-commit/kuafuai/DevOpsGPT?label=%20) |
| [gpt-computer-assistant](https://github.com/onuratakan/gpt-computer-assistant) | 通过读取屏幕，语音或文字输入帮助完成任务                     | Code                             | open                   | App, pip package | Local                | [OpenAI](https://platform.openai.com/playground)             | ![GitHub last commit](https://img.shields.io/github/last-commit/onuratakan/gpt-computer-assistant?label=%20) |

### Research

| Name                                                         | Description                                                  | Open- or Close- source | Platform            | Self-hosted or Local | Api supported | Last update                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------- | ------------------- | -------------------- | ------------- | ------------------------------------------------------------ |
| [gpt-researcher](https://github.com/assafelovic/gpt-researcher) | 可以生成详细、正式且客观的研究报告，通过联网搜索专注于相关资源、结构框架和经验报告。 | open                   | Web ui, pip package | Local                | 全能          | ![GitHub last commit](https://img.shields.io/github/last-commit/assafelovic/gpt-researcher?label=%20) |
| [gpt_academic](https://github.com/binary-husky/gpt_academic) | 论文阅读/润色/写作，Python和C++等项目剖析&自译解功能，PDF/LaTex论文翻译&总结 | open                   | Web ui              | Local                | 全能          | ![GitHub last commit](https://img.shields.io/github/last-commit/binary-husky/gpt_academic?label=%20) |

### Search

| Name                                                    | Description                                                  | Open- or Close- source | Platform | Self-hosted or Local | Api supported                                                | Last update                                                  |
| ------------------------------------------------------- | ------------------------------------------------------------ | ---------------------- | -------- | -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Perplexica](https://github.com/ItzCrazyKns/Perplexica) | AI 动力的搜索引擎，它深入互联网寻找答案。Perplexity AI 替代品 | open                   | Web ui   | Both                 | [OpenAI](https://platform.openai.com/playground),  [Groq](https://console.groq.com/keys), 本地模型 | ![GitHub last commit](https://img.shields.io/github/last-commit/ItzCrazyKns/Perplexica?label=%20) |

### Web crawler

| Name                                                         | Description                                                  | Open- or Close- source | Platform    | Self-hosted or Local | Api supported                                                | Last update                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------- | ----------- | -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Scrapegraph-ai](https://github.com/VinciGit00/Scrapegraph-ai) | 一个网络爬虫Python库，使用大型语言模型和直接图逻辑为网站和本地文档创建爬取管道 | open                   | pip package | Local                | [OpenAI](https://platform.openai.com/playground), [Google Gemini](https://ai.google.dev/gemini-api), [Claude](https://www.anthropic.com/), [Groq](https://console.groq.com/keys), 本地模型 | ![GitHub last commit](https://img.shields.io/github/last-commit/VinciGit00/Scrapegraph-ai?label=%20) |

## Extension

### Browser

| Name                                                  | Description                                                  | Open- or Close- source | Platform                                                     | Api supported                                                | Last update                                                  |
| ----------------------------------------------------- | ------------------------------------------------------------ | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [chatGPTBox](https://github.com/josStorer/chatGPTBox) | 随时在任何页面使用快捷键 呼出聊天对话框，多种网站集成，提供翻译、总结等多种工具等 | open                   | [Chrome](https://chromewebstore.google.com/detail/chatgptbox/eobbhoofkanlmddnplfhnmkfbnlhpbbo), [Edge](https://microsoftedge.microsoft.com/addons/detail/fission-chatbox-best/enjmfilpkbbabhgeoadmdpjjpnahkogf), [Firefox](https://addons.mozilla.org/firefox/addon/chatgptbox/), [Safari](https://apps.apple.com/app/fission-chatbox/id6446611121) | [OpenAI](https://platform.openai.com/playground), [Claude](https://www.anthropic.com/) | ![GitHub last commit](https://img.shields.io/github/last-commit/josStorer/chatGPTBox?label=%20) |
| [Sider](https://sider.ai/)                            | 在任何网页上辅助阅读和写作 直接和图片、网页链接、PDF、GPTs等聊天 | close                  | [Chrome](https://chromewebstore.google.com/detail/sider-chatgpt-%E4%BE%A7%E8%BE%B9%E6%A0%8F-+-gpt-4/difoiogjjojoaoomphldepapgpbgkhkb), [Edge](https://microsoftedge.microsoft.com/addons/detail/sider-chatgpt-%E4%BE%A7%E8%BE%B9%E6%A0%8F-gpt/dhoenijjpgpeimemopealfcbiecgceod) | [OpenAI](https://platform.openai.com/playground), [Google Gemini](https://ai.google.dev/gemini-api), [Claude](https://www.anthropic.com/) | NA                                                           |
| [沉浸式翻译](https://immersivetranslate.com/)         | 双语对照翻译                                                 | close                  | [Chrome](https://chromewebstore.google.com/detail/%E6%B2%89%E6%B5%B8%E5%BC%8F%E7%BF%BB%E8%AF%91-%E7%BD%91%E9%A1%B5%E7%BF%BB%E8%AF%91%E6%8F%92%E4%BB%B6-pdf%E7%BF%BB%E8%AF%91-%E5%85%8D%E8%B4%B9/bpoadfkcbjbfhfodiogcnhhhpibjhbnh?utm_source=official), [Edge](https://microsoftedge.microsoft.com/addons/detail/%E6%B2%89%E6%B5%B8%E5%BC%8F%E7%BF%BB%E8%AF%91-%E7%BD%91%E9%A1%B5%E7%BF%BB%E8%AF%91%E6%8F%92%E4%BB%B6-pdf%E7%BF%BB%E8%AF%91-/amkbmndfnliijdhojkpoglbnaaahippg?utm_source=official), [Firefox](https://addons.mozilla.org/zh-CN/firefox/addon/immersive-translate/), [Safari](https://apps.apple.com/us/app/immersive-translate-for-safari/id6447957425?utm_source=official), [Tampermonkey](https://download.immersivetranslate.com/immersive-translate.user.js) | [OpenAI](https://platform.openai.com/playground), [Google Gemini](https://ai.google.dev/gemini-api), [Claude](https://www.anthropic.com/) | NA                                                           |

### IDE

| Name                                                   | Description                                                  | Open- or Close- source | Platform     | Api supported                                                | Last update                                                  |
| ------------------------------------------------------ | ------------------------------------------------------------ | ---------------------- | ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [gpt-pilot](https://github.com/Pythagora-io/gpt-pilot) | 编写代码、调试代码，进行交流，并根据需求和指导从头开始构建完整的应用程序。 | open                   | major shells | [OpenAI](https://platform.openai.com/playground), [Claude](https://www.anthropic.com/), [Groq](https://console.groq.com/keys) | ![GitHub last commit](https://img.shields.io/github/last-commit/Pythagora-io/gpt-pilot?label=%20) |

### Terminal/Shell

| Name                                             | Description                                                  | Open- or Close- source | Platform | Api supported                                              | Last update                                                  |
| ------------------------------------------------ | ------------------------------------------------------------ | ---------------------- | -------- | ---------------------------------------------------------- | ------------------------------------------------------------ |
| [shell_gpt](https://github.com/TheR1D/shell_gpt) | LLM驱动的命令行生产力工具。该命令行工具提供了简化的 shell 命令、代码片段、文档的生成 | open                   | pip      | [OpenAI](https://platform.openai.com/playground), 本地模型 | ![GitHub last commit](https://img.shields.io/github/last-commit/TheR1D/shell_gpt?label=%20) |
