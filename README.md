

# Comparing AI Coding Tools

AI-powered coding assistants have gained significant traction in recent years, aiming to enhance developer productivity and accelerate the software development process. In this README, we'll take a closer look at some prominent AI coding tools like: GitHub Copilot and Amazon Q (ex-AWS CodeWhisperer), as well as Open Source alternatives and compare their key features and capabilities. Feel free to share your ideas by raising an issue or doing a Pull Request.

|             | Github Copilot              | Amazon Q for Developers| Continue           | FauxPilot      | Privy      |
| -------- | --------- | ----------------- | ------------- | ------------ | -------- |
| Commercial tool             | x           | x      |    ||            |
| Opensource  |             |        | x  | x              | x          |
| Service type| SaaS        | SaaS   | Extension          | Hosted         | Hosted     |
|             |             |        |    ||            |
| Features    |             |        |    ||            |
| Code completion             | x           | x      | x  | x              | x          |
| Chat        | x           | x      | x  || x          |
| Assess/Document/Create code | x           | x      | x  | x              | x          |
| Models      | GPT4 for chat, GPT 3.5 for autocomplete        | Undisclosed            | Virtually all. OpenAI or local models consumed by API [link](https://docs.continue.dev/setup/select-provider)| Salesforce CodeGen | Ollama         |
|  |   |  |    | | |
| Availability| Global      | Global | Local              | Local          | Local      |
| Hosted regions              | Github US | AWS US |    | | |
| IDE's supported             | Visual Studio Code, Visual Studio, Vim, Neovim, the JetBrains suite, CLI    | Visual Studio Code, JetBrains, AWS Toolkit for Visual Studio, CLI, Chatbot MS Teams and Slack      | Visual Studio Code and JetBrains   | Visual Studio Code             | Visual Studio Code         |
|             |             |        |    ||            |
| Cost        | Free: 30 day trial<br>Paid: Individual 10 USD/month 100 USD/year<br>          Enterprise 39 USD/month Business 19 USD/month | Free: Limited requests per month<br>Paid: 19 USD/Dev/Month             | Free + pay for model consumption   | Free           | Free       |
| Demo        | [Demo](https://www.youtube.com/playlist?list=PL0lo9MOBetEHEHi9h0k_lPn0XZdEeYZDS)    | [Amazon Q Developer - Your generative AI-powered assistant for work](https://www.youtube.com/watch?v=_1HbJeoij6g) | [Demo](https://www.youtube.com/watch?v=V3Yq6w9QaxI) | [FauxPilot](https://www.youtube.com/watch?v=Juyl1v5nZK8) | [Demo](https://github.com/srikanth235/privy)
| Community support           | +++         | +++    | +++| +++            | ++         |
| URL         | [GitHub Copilot - GitHub Docs](https://docs.github.com/en/copilot/about-github-copilot)               | [What is Amazon Q Developer](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/what-is.html)              | [Continue](https://github.com/continuedev/continue)            | [FauxPilot](https://github.com/fauxpilot/fauxpilot) | [Privy](https://github.com/srikanth235/privy) |

Let's deep dive on the commercial tools!

## GitHub Copilot
GitHub Copilot is an AI-powered coding assistant developed by GitHub in collaboration with OpenAI. It is designed to help developers write code more efficiently by providing intelligent code suggestions and completions based on the context of the code being written. It is one of the most used tools on AI Coding domain.

### Key Features
2. Language Support: [Most current languages](https://docs.github.com/en/enterprise-cloud@latest/get-started/learning-about-github/github-language-support)
1. Tight integration with GitHub and popular code editors (e.g., Visual Studio Code)
1. Requires a paid subscription for individual developers


## Amazon Q for Developers (ex-CodeWhisperer)
An AI-powered coding assistant offered by Amazon Web Services (AWS). It is designed to help developers write code faster by providing intelligent code suggestions and completions based on the context of the code being written, similar to GitHub Copilot.

### Key Features

1. Language Support: [Most current languages](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/q-language-ide-support.html)
1. Tight integration with AWS services and IDEs like AWS Cloud9
1. Limited integration with non-AWS tools and IDEs

# Common on AI Coding tools
1. Code Completion, Code Generation, Documentation Generation
1. Potential for generating insecure or incorrect code
1. Limited support for complex or domain-specific codebases
1. Trained on a vast corpus of open-source code, enabling accurate code suggestions
1. Supports a wide range of programming languages
1. Continuously improving through feedback and fine-tuning
   
#  Research studies on AI Coding & Developer Productivity
1. [Research: quantifying GitHub Copilot’s impact on developer productivity and happiness](https://github.blog/2022-09-07-research-quantifying-github-copilots-impact-on-developer-productivity-and-happiness/)
1. [Unleashing developer productivity with generative AI](https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/unleashing-developer-productivity-with-generative-ai#:~:text=A%20McKinsey%20study%20shows%20that,maximize%20productivity%20and%20minimize%20risks.&text=Technology%20leaders%20aiming%20to%20accelerate,time%20savings%20with%20generative%20AI.)
