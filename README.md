# Erxl的简易AI考试 v0
内含 常识与能力级（150分）、创造与研究级（240分）、超前沿研究级（400分） 三级的约20个题目，难度越高的题分数越高。满分790分。

为了节约时间，大部分测试仅测试单次，所以最终得分可能存在正负10%的误差

未答分代表AI无法输出完整内容，因此实际水平可能高于分数
| AI                          | 厂商             | 参数   | 激活   | 分数   | 未答分 | 评价                                                     |
|-----------------------------|------------------|--------|--------|--------|--------|----------------------------------------------------------|
| Grok 4                      | xAI              |        |        | 83.5   |        | 只擅长干活，日常对话水平极差。无审查                     |
| Claude 4 Sonnet             | Anthropic        |        |        | 69     |        | 回复太短；擅长代理编程；比别的模型更会创作               |
| Claude 4 Opus               | Anthropic        |        |        | 68     |        | 回复太短；擅长代理编程；比别的模型更会创作               |
| O3 Pro                      | OpenAI           |        |        | 65     |        |                                                          |
| Horizon Beta                | OpenAI           |        |        | 60     |        | 疑似GPT 5 Nano Coder。日常对话很差。编程能力很强         |
| **Qwen 3 235B A22B 2507**   | 阿里巴巴         | 235B   | A22B   | 56.33  |        | 开源之王。但代理编程能力比qwen3 coder差一些              |
| Gemini 2.5 Pro              | 谷歌             |        |        | 55     |        | 擅长在知识库内部展露惊人智慧，创造能力极差               |
| GPT 4.1                     | OpenAI           |        |        | 55     |        |                                                          |
| Horizon Alpha               | OpenAI           |        |        | 54     |        | 疑似GPT 5 Nano Coder。日常对话很差。编程能力很强         |
| **Qwen 3 235B A22B thinking 2507** | 阿里巴巴  | 235B   | A22B   | 51.33  |        |                                                          |
| **Qwen 3 Coder**            | 阿里巴巴         | 480B   | A35B   | 47.67  |        | 擅长代理编程，次于claude；其他水平不如235B的qwen         |
| GPT 4.1 Mini                | OpenAI           |        |        | 47     |        | 并没有那么mini，应该是中模                               |
| O4 Mini                     | OpenAI           |        |        | 46     |        | 推理不行，日常对话更不行                                 |
| **Deepseek Chat V3 0324**   | DeepSeek         | 685B   | A37B   | 46     |        |                                                          |
| Grok 3                      | xAI              |        |        | 46     |        | 无审查                                                   |
| O3                          | OpenAI           |        |        | 43     |        | 被整天AGI AGI地炒作，实际上就个垃圾                      |
| **Intern S1**               | 上海人工智能实验室 | 235B | A22B   | 42     |        | 很差劲，远次于deepseek、qwen                             |
| **Deepseek R1 0528**        | DeepSeek         | 685B   | A37B   | 40     |        |                                                          |
| **Kimi K2**                 | 月之暗面         | 1040B  | A32B   | 40     |        | 擅长作为代理编程，但不如qwen3 coder                      |
| **XBai O4**                 | 原石科技         | 32B    |        | 33     |        | 相比其基模Qwen3 32B，编码更强，常识更弱                  |
| **Ernie 4.5 300B A47B**     | 百度             | 300B   | A47B   | 32     |        |                                                          |
| Grok 3 Mini                 | xAI              |        |        | 30     |        |                                                          |
| **GLM 4.5**                 | 智谱             | 355B   | A32B   | 29.33  |        | 很差劲，远次于deepseek、qwen                             |
| **Llama 4 Maverick**        | Meta             | 109B   | A17B   | 26     |        | meta的巨大失败                                           |
| **GLM 4.5 Air**             | 智谱             | 106B   | A12B   | 25.66  |        | 很差劲，远次于deepseek、qwen                             |
| **Qwen 3 32B**              | 阿里巴巴         | 32B    |        | 21     |        |                                                          |
| **Qwen 3 30B A3B 2507**     | 阿里巴巴         | 30B    | A3B    | 21     |        | 以3B激活参数达到gpt4水平的夸张存在，开源小模王           |
| GPT 4                       | OpenAI           |        |        | 21     |        | 曾经的王，现在沦落到这个地步，感慨万千                   |
| Gemini 2.5 Flash            | 谷歌             |        |        | 20     |        |                                                          |
| **Qwen 3 32B /nothink**     | 阿里巴巴         | 32B    |        | 19.67  |        |                                                          |
| **Minimax M1**              | Minimax          | 456B   | A46B   | 16     |        | 很差劲，远次于deepseek、qwen                             |
| **MindLink 72B 0801**       | 昆仑万维         | 72B    |        | 14     |        | 很差劲，远次于deepseek、qwen                             |
| GPT 4.1 Nano                | OpenAI           |        |        | 13     |        |                                                          |
| **Qwen 2.5 72B**            | 阿里巴巴         | 72B    |        | 9      |        |                                                          |
| **Hunyuan A13B**            | 腾讯             | 80B    | A13B   | 6      |        | 很差劲，远次于deepseek、qwen                             |
| **GLM 4 32B**               | 智谱             | 32B    |        | 3      |        | 很差劲，远次于deepseek、qwen                             |
| GPT 3.5 Turbo               | OpenAI           |        |        | 3      |        | 一切的起源                                               |

只有Grok 4能在“创造与研究级”里拿到至少一分！


