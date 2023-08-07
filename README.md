# 为什么有此清单？
* 以最小必要阅读资料为出发点，寻找了解chatgpt技术原理方向上最高质量阅读资料；


# 阅读目标拆解
## 搞清楚以下问题
* chatGPT的迭代史
* chatGPT的核心技术
* chatgpt跟传统的NLP技术相比，进步的地方是什么？
* chatgpt所带来的场景重构有哪些？产品的机会有哪些？
* chatGPT所带来的影响力？如何理解是所谓的iphone时刻？


# 资料筛选逻辑
* 以技术理解为主线；
* 第一手资料最重要；包括核心的论文以及openai老板们的分享；
* 其次是二手解读；
* 宏观论述+科普第三；
* **_资料会随着时间不断更新_**


# GPT资料列表
## 第一手资料
### Paper
* 2017 [Attention Is All You Need](https://arxiv.org/abs/1706.03762) - 这篇论文介绍了原始的 Transformer 的结构，是 Transformer 系列的基础。
* GPT1~GPT4 Openai
  * 2018 [Improving language understanding by generative pre-training](https://openai.com/research/language-unsupervised) - 这篇论文介绍了另一个流行的预训练模型，也就是被后人所熟知的 GPT-1。
  * 2019 [Language models are unsupervised multitask learners](https://www.semanticscholar.org/paper/Language-Models-are-Unsupervised-Multitask-Learners-Radford-Wu/9405cc0d6169988371b2755e573cc28650d14dfe) - 这篇论文引入了 GPT-2。
  * 2020 [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165) - 这篇论文引入了 GPT-3。
  * 2022 [Training lanquage models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155) - 这篇论文提出了一种 RLHF 的方式
  * 2023 [GPT-4 technical report](https://arxiv.org/abs/2303.08774)
* 2022 [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)

### Talks
* openai CEO
  * [Sam Altman: OpenAI CEO on GPT-4, ChatGPT, and the Future of AI | Lex Fridman Podcast](https://www.youtube.com/watch?v=L_Guz73e6fw)
  * [OpenAI CEO Sam Altman | AI for the Next Era](https://www.youtube.com/watch?v=WHoWGNQRXb0&t=2s)
* openai CTO
  * [Ilya Sutskever (OpenAI Chief Scientist) - Building AGI, Alignment, Spies, Microsoft, & Enlightenment](https://www.youtube.com/watch?v=Yf1o0TQzry8)
  * [GPT-4创造者：第二次改变AI浪潮的方向](https://mp.weixin.qq.com/s/rZBEDlxFVsVXoL5YUVU3XQ)
  * [黄仁勋与OpenAI首席科学家Ilya Sutskever的炉边谈话 4K 中文字幕](https://www.bilibili.com/video/BV1Tc411L7UA/?spm_id_from=333.337.search-card.all.click)
  * [Inside OpenAI [Entire Talk]](https://www.youtube.com/watch?v=Wmo2vR7U9ck)
* Andrej Karpathy
  * [微软2023年Build大会演讲：如何训练和应用GPT](https://www.youtube.com/watch?v=YrBJiy-V8MY)

## 第二手解读资料
### Course
* [李宏毅【機器學習 2023】(生成式 AI)](https://www.youtube.com/playlist?list=PLJV_el3uVTsOePyfmkfivYZ7Rqr2nMk3W)
* [RLChina 2023 ChatGPT 和大模型春季课程](http://rlchina.org/topic/652)

### paper
* [Sparks of Artificial General Intelligence: Early experiments with GPT-4](https://arxiv.org/abs/2303.12712)

### Talks
* [What is ChatGPT doing...and why does it work?](https://www.youtube.com/watch?v=flXrLGPY3SU)
* [GPT-4论文精读](https://www.youtube.com/watch?v=K0SZ9mdygTw)
* [GPT，GPT-2，GPT-3 论文精读](https://www.youtube.com/watch?v=t70Bl3w7bxY)
* [OpenAI Codex 论文精读【论文精读】](https://www.youtube.com/watch?v=oZriUGkQSNM)
* [Sparks of AGI: early experiments with GPT-4](https://www.youtube.com/watch?v=qbIk7-JPB2c)

### blog
* [理解大语言模型——10篇论文的简明清单](https://mp.weixin.qq.com/s/h7Pam1mepgd18aeqn7_3hw)
* [ChatGPT的各项超能力从哪儿来？万字拆解追溯技术路线图来了！](https://mp.weixin.qq.com/s/7N3HveaIfn2N-zKjBoRL1A)
* [通向AGI之路：大型语言模型（LLM）技术精要](https://zhuanlan.zhihu.com/p/597586623)
* Transformer
  * [What Are Transformer Models and How Do They Work?](https://txt.cohere.ai/what-are-transformer-models/)
  * [How Transformers Work](https://towardsdatascience.com/transformers-141e32e69591)
  * [小白看得懂的 Transformer (图解)](https://mp.weixin.qq.com/s/VrzkxEVBAO6abJcUsYGr0Q)
  * [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)
  * [为什么现在的大语言模型（LLM）都是Decoder-only的架构？](https://mp.weixin.qq.com/s/ZsHX-M9pisUvG9vqfzdzTQ)
* LLM大语言模型
  * [Compression for AGI](https://www.youtube.com/watch?v=dO4TPJkeaaU)
  * [压缩即泛化，泛化即智能](https://mp.weixin.qq.com/s/tSj9npIPg8IlYr2jbtg-Og)
* Prompt
  * [五万字综述！Prompt Tuning：深度解读一种新的微调范式](https://mp.weixin.qq.com/s/-lfq63NrsqUgmvYNzogCew)
* RLHF
  * [ChatGPT 背后的“功臣”——RLHF 技术详解 ](https://mp.weixin.qq.com/s/TLQ3TdrB5gLb697AFmjEYQ)
  * [ChatGPT (可能)是怎麼煉成的 - GPT 社會化的過程](https://www.youtube.com/watch?v=e0aKI2GGZNg)


## 第三手资料
* talks
  * [Foundation models and the next era of AI](https://www.youtube.com/watch?v=HQI6O5DlyFc)
  * [万字科普GPT4为何会颠覆现有工作流](https://www.bilibili.com/video/BV1MY4y1R7EN/)
  * [拾象科技 — OpenAI 闭门讨论会](https://mp.weixin.qq.com/s/AxX-Q7njegNTAxMkYFwsfA)
  * [ChatGPT技术分析](https://mp.weixin.qq.com/s/DdmAghMWHFq6kJldnbq37Q)
  * [详解现象级ChatGPT发展历程、原理、技术架构详解和产业未来](https://mp.weixin.qq.com/s/qVNsJRQXzBdctIp5RiSCRA)
* blog
  * [ChatGPT Is a Blurry JPEG of the Web ](https://www.newyorker.com/tech/annals-of-technology/chatgpt-is-a-blurry-jpeg-of-the-web)
  * [万字长文：一文看懂GPT风口，有哪些创业机会？](https://mp.weixin.qq.com/s/gPqOAzX4sWZtXDPFjc16Ow)
  * [这一轮AI会带来什么样的范式转移？](https://mp.weixin.qq.com/s/oXdIJ9hdSp7Ls4CuaNFiXw)
  * [理解 AI 驱动的软件 2.0 智能革命](https://www.indigox.me/the-evolution-of-machine-intelligence/)
  * [Does One Large Model Rule Them All?](https://maithraraghu.com/blog/2023/does-one-model-rule-them-all/)

