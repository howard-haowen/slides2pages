---
marp: true
lang: en-US
title: 中山大學演講2024
description: AI, LLM & Prompt Engineering
theme: graph_paper
transition: fade
paginate: true
_paginate: false
style: |
    section {
      font-size: 35px;
    }
header: |
    [Haowen Jiang](https://bit.ly/4fL1hX0)
footer: |
    *AI, LLM & Prompt Engineering*
_header: ""
_footer: ""
---

<!-- _backgroundImage: "" -->
<!-- _footer: "" -->

# AI, LLM & Prompt Engineering

-   Speaker: <br>Dr. [Haowen Jiang](https://bit.ly/4fL1hX0)
-   Date: <br> Oct 24th, 2024

![bg right:60%](https://content-management-files.canva.com/cdn-cgi/image/f=auto,q=70/ed385524-58a0-4503-9934-e5909d1ec600/ai-portrait-generator_promo-showcase_012x.png)

<!-- This is presenter note. You can write down notes through HTML comment. -->

---

## Outline

-   My background
-   Intro to AI
-   Large Language Models (LLMs)
-   Prompt Engineering
-   Q & A

---

<!-- _header: "" -->
<!-- _footer: "" -->
<!-- _paginate: "" -->
<!-- _color: white -->

## <!-- fit --> My background

![bg](https://habitatbroward.org/wp-content/uploads/2020/01/10-Benefits-Showing-Why-Education-Is-Important-to-Our-Society.jpg)

---

## Education

![bg right:65% saturate:3.0 fit](https://github.com/howard-haowen/NLP-demos/raw/main/img/education_blue.png)

---

## Experience

-   :teacher: English lecturer at _Nat'l Taipei University of Technology_

![bg right:65% saturate:3.0 90%](https://4.bp.blogspot.com/-lvpwx0NvAHE/WfkiITI5OEI/AAAAAAAAAFE/98Wtc8AuUkAL41mK9U4t-MVW8rSUTSBPwCLcBGAs/s1600/g1377083943860215164.jpg)

---

## Experience

-   :scientist: Postdoc researcher at _Peking University_

![bg right:65% fit](https://www.memecreator.org/static/images/memes/3950560.jpg)

---

## Experience

-   :technologist: AI engineer at [IBM](https://www.ibm.com/us-en) (my 5th industry job)

![bg right:60% 70%](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F489ea0af-4ef1-4af3-919e-be486597e278_1080x1080.jpeg)

---

## IBM Business Divisions

[>> source](https://www.trefis.com/stock/ibm/articles/546402/forecast-of-the-day-ibm-infrastructure-revenues/2023-01-05)

![bg right:65% fit](https://s3.amazonaws.com/wp-uploads-trefis/articles/wp-content/uploads/2023/01/05021808/Screenshot-2023-01-05-at-12.47.51-PM.png)

---

<!-- _header: "" -->
<!-- _footer: "" -->
<!-- _paginate: "" -->
<!-- _color: white -->

## <!-- fit --> Intro to AI

![bg](https://theblue.ai/wp-content/uploads/2023/06/GenAI-models-Generative-AI-Hamburg.png)

---

<!-- _header: "" -->
<!-- _footer: "" -->

## Q1: What is AI? Or what counts as AI?

## Q2: Do you think AI thinks as humans do?

![bg](https://c4.wallpaperflare.com/wallpaper/829/1010/472/cloud-tip-paper-board-wallpaper-preview.jpg)

---

<!-- _header: "" -->
<!-- _footer: "" -->

![bg contain](https://assets-global.website-files.com/6344c9cef89d6f2270a38908/644c1fe29b0887661966d9cd_d0051e24.png)

---

## Searching for a function

-   The goal of ML/DL is to search for a _function_ that takes some input and then produces some output in a way that humans would normally do.

![h:250 center](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQD9L2Who0uL21le4IhuRZ78UdmWb3Vq3KFrTl5FguXzDFCpLSoRJqPL4vNL-LX1M7OLU8&usqp=CAU)

---

## Function

> -   Natural Language
>     `We like languages` >>> LIKE(We, languages)

> -   Programming
>
> ```python
> def like(subj, obj):
>    print(f"{subj} like {obj}.")
>
> like("We", "languages")
> ```
>
> Try it out [>> here](https://www.programiz.com/online-compiler/5eYYlPCRJ8OJ8)!

---

## Data-driven AI

<!-- _footer: "" -->

> A data-driven model
> is trained on data points instead of being coded upfront.
>
> ```python
> inputs = [0, 1, 2] # the x variable
> outputs = [1, 4, 7] # the y variable
> ```
>
> Random: y = 0.1x + 0.5
> Trained: y = 3x + 1

![bg right:45% fit](https://www.varsitytutors.com/assets/vt-hotmath-legacy/hotmath_help/topics/graphing-linear-equations/graphing-linear-equations2.gif)

---

## How do machines learn?

> Machines learn by **trial and error**, just as humans do.

![bg right](https://pbs.twimg.com/media/EtRGq93UUAIG7Du.jpg)

---

## Machine Guessing

![bg right:70% fit](https://dataedo.com/asset/img/cartoon/machine_guessing.png)

---

## Why is machine learning powerful?

The true power of ML/DL lies in the fact that

-   humans only need to provide input and output
-   computers are in charge of figuring out the right process, which is called a **model**

![h:200 center](https://av-eks-lekhak.s3.amazonaws.com/media/__sized__/article_images/494205_1_En_7_Fig1_HTML-thumbnail_webp-600x300.webp)

---

-   2 types of AI

![bg right:65% fit](https://dce0qyjkutl4h.cloudfront.net/wp-content/uploads/2023/06/generative-ai-benefits.png)

---

-   2 types of discriminative models

![bg right:65% 110%](https://media.licdn.com/dms/image/D5612AQHleCueKC_lww/article-cover_image-shrink_600_2000/0/1677785069046?e=2147483647&v=beta&t=C6GRtT_VWW1c-WkYggBLllLx6Zxor1sSrM9lMW9FGdA)

---

-   4 types of generative models

![bg right:65% 110%](https://research.aimultiple.com/wp-content/uploads/2022/11/Tools-612x459.png.webp)

---

-   Traditional AI vs Generative AI

![](https://dataplatform.cloud.ibm.com/docs/api/content/wsj/analyze-data/images/fm-overview-diagram.svg?context=wx&locale=en)
[>> source](https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/fm-overview.html?context=wx)

---

![bg 85%](https://www.aiprm.com/generative-ai-statistics/Generative-AI-HRP-18_hu188251e92af378d8fe14163ebe148231_186318_1600x0_resize_q95_h2_box_3.webp)

---

![bg 85%](https://appinventiv.com/wp-content/uploads/2023/04/How-Generative-AI-for-Business-is-Shaping-the-Industries_info-2-scaled.webp)

---

![bg fit](https://www.xenonstack.com/hs-fs/hubfs/Applications-of-GenAI-in-education-industry.png?width=1281&height=1030&name=Applications-of-GenAI-in-education-industry.png)
[>> source](https://www.xenonstack.com/blog/generative-ai-education)

---

![bg 80%](https://www.aiprm.com/generative-ai-statistics/Generative-AI-HRP-10_hu1af2d1ab3485629f04de35d9acb9e671_369875_1600x0_resize_q95_h2_box_3.webp)
[>> source](https://www.aiprm.com/generative-ai-statistics/)

---

![bg fit](https://www.aiprm.com/generative-ai-statistics/Generative-AI-HRP-8_hua10b28ff11d64d80ef58b13cb396e10f_205567_1600x0_resize_q95_h2_box_3.webp)
[>> source](https://www.aiprm.com/generative-ai-statistics/)

---

![bg fit](https://www.aiprm.com/generative-ai-statistics/Generative-AI-HRP-3_hu712fc34baa99fe749eacae4470c2cae2_150823_1600x0_resize_q95_h2_box_3.webp)
[>> source](https://www.aiprm.com/generative-ai-statistics/)

---

![bg 80%](https://market.us/wp-content/uploads/2024/03/Generative-AI-in-Edtech-Market-2.jpg)
[>> source](https://market.us/report/generative-ai-in-edtech-market/)

---

<!-- _header: "" -->
<!-- _footer: "" -->
<!-- _paginate: "" -->
<!-- _color: white -->

## <!-- fit --> Large Language Models (LLMs)

![bg](https://media.licdn.com/dms/image/D4D12AQEMLCtqvbBAKQ/article-cover_image-shrink_720_1280/0/1707217131110?e=2147483647&v=beta&t=ef1xjQ2h-zTAFU5RJ-3Tqx0rDRpC883UrCFhuPWA55o)

---

<!-- _header: "" -->
<!-- _footer: "" -->

## Q1: What LLM APPs (ChatGPT, Bing Chat, Google Gemini) have you ever used?

## Q2: What're some of the challenges you face when interacting with them?

![bg](https://c4.wallpaperflare.com/wallpaper/829/1010/472/cloud-tip-paper-board-wallpaper-preview.jpg)

---

## <!-- fit --> ChatGPT's significance

<!-- _paginate: "" -->

> [>> TechGoing](https://www.techgoing.com/bill-gates-chatgpts-history-is-as-significant-as-the-birth-of-the-pc-or-the-internet/)
>
> ChatGPT’s history is as significant as the birth of **the PC or the Internet**.
> ~ Bill Gates

![bg right](https://i.insider.com/63dbc9bc0a08ae0018a67757?width=1300&format=jpeg&auto=webp)

---

## ChatGPT's model

> ChatGPT is powered by a large language model (LLM) called **Generative Pre-trained Transformer** (GPT).

![bg right fit](https://apacentrepreneur.com/wp-content/uploads/2023/07/ChatGPT-will-Impact-Digital-Marketing.jpg)

---

## The LLM family

![h:400](https://arxiv.org/html/2402.06196v2/x3.png)

---

## What makes LLM large?

> LLM is large because of the size of its **parameters**.

![bg right:65% h:550](https://www.marktechpost.com/wp-content/uploads/2023/10/Screenshot-2023-10-15-at-4.25.57-PM.png)

---

## What is a language model?

-   A language model predicts the next word based on conditional probability.

![h:300 center](https://static.wixstatic.com/media/3eee0b_2ba9521e928e4a1ab8328fbc34170542~mv2.png)

---

## A language model has some world knowledge.

-   Given a huge corpus of texts, a language model can acquire some basic world knowledge.

![bg right fit](https://miro.medium.com/v2/resize:fit:1400/format:webp/0*FQOc2s9cdQSVqAJJ.png)

---

<!-- _header: "" -->
<!-- _footer: "" -->

![bg fit](<https://www.investopedia.com/thmb/ulGrKT5WnVclGMOgQQVe65OtmeI=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/large-language-model-7563532-final-9e350e9fa02d4685887aa061af7a2de2.png>)

---

### Closed-source LLMs

### Open-source LLMs

![bg right:70% fit](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F6bca1171-adab-4c13-92f9-d5e0cf45f044_940x788.png)

---

## Using closed-source LLMs

![h:440 center](https://dynatechconsultancy.com/hs-fs/hubfs/Microsoft%20Copilot%20vs%20ChatGPT%20vs%20Gemini-02.jpg?width=6948&height=3917&name=Microsoft%20Copilot%20vs%20ChatGPT%20vs%20Gemini-02.jpg)

---

## Using open-source LLMs

-   [gpt4all](https://www.nomic.ai/gpt4all)
-   [LM Studio](https://lmstudio.ai/)
-   [Ollama](https://ollama.com/)

[>> source](https://getstream.io/blog/best-local-llm-tools/)

![bg right:65% fit](https://stream-blog-v2.imgix.net/blog/wp-content/uploads/25b33a8a582c43c4ed91140f85491218/localLLMsHeader.jpg?auto=format&auto=compress&w=1600&fit=max)

---

## Popular open-source LLMs

![bg right:70% fit](https://www.inspirisys.com/uploads/blog_image/Most-Popular-Open-Source-LLMs.png)
[>> source](https://www.inspirisys.com/blog-details/Top-10-Open%CB%97Source-LLMs-of-2024-A-Complete-Guide/175)

---

## Benefits of open-source LLMs

![bg right:70% fit](https://datasciencedojo.com/wp-content/uploads/LinkedIn-Newsletr-Infographics-71-scaled.jpg)
[>> source](https://datasciencedojo.com/blog/open-source-llms-for-enterprises-benefits/)

---

-   [IBM](https://www.ibm.com/products/watsonx-ai/foundation-models)
-   [Perplexity](https://www.perplexity.ai/discover)

[>> source](https://datasciencedojo.com/blog/open-source-llms-for-enterprises-benefits/)

![bg right:70% fit](https://datasciencedojo.com/wp-content/uploads/LinkedIn-Newsletr-Infographics-73-scaled.jpg)

---

<!-- _header: "" -->
<!-- _footer: "" -->
<!-- _paginate: "" -->
<!-- _color: white -->

## <!-- fit --> Prompt Engineering

![bg fit](https://images.spiceworks.com/wp-content/uploads/2024/04/19183329/prompt-engineering-in-programming.jpg)

---

<!-- _header: "" -->
<!-- _footer: "" -->

## Q1: How do you design prompts to effectively elicit the desired responses?

## Q2: How can humans and AI work together to create more effective and creative outcomes?

![bg](https://c4.wallpaperflare.com/wallpaper/829/1010/472/cloud-tip-paper-board-wallpaper-preview.jpg)

---

## Prompt on the terminal

![h:500 center](https://res.cloudinary.com/practicaldev/image/fetch/s--WoTmwWJC--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/z7v1jxp2pr7z0d3lqqxv.png)

---

## Prompt in GenAI

-   a specific instruction or input given to the AI model to generate a desired output

![bg right:65% fit](https://d3lkc3n5th01x7.cloudfront.net/wp-content/uploads/2023/05/29032214/Bridging-the-AI-human-communication-gap-A-comprehensive-guide-to-prompt-engineering-Feature.svg)

---

## What makes a good prompt?

![h:500 center](https://assets-global.website-files.com/651599053c664397a48c84cd/652555f8ade90301ee2a8bc5_BOOKS.webp)

---

<!-- _header: "" -->
<!-- _footer: "" -->

# Elements of a good prompt

![bg](https://slidechef.net/wp-content/uploads/2021/11/Real-Classroom-Background.jpg)

---

## Checklist

![bg right:70% fit](https://pbs.twimg.com/media/GAwsIY6XEAAkBPW.jpg)
[>> source](https://chat-gpt-5.ai/chatgpt-prompt-formula/)

---

## 01: <br>Task

![bg right:70% fit](https://chat-gpt-5.ai/wp-content/uploads/2023/12/Task.jpeg)
[>> source](https://chat-gpt-5.ai/chatgpt-prompt-formula/)

---

## 02: Context

![bg right:70% fit](https://chat-gpt-5.ai/wp-content/uploads/2023/12/Context.jpeg)
[>> source](https://chat-gpt-5.ai/chatgpt-prompt-formula/)

---

## 03: Examples

![bg right:70% fit](https://chat-gpt-5.ai/wp-content/uploads/2023/12/Examples.jpeg)
[>> source](https://chat-gpt-5.ai/chatgpt-prompt-formula/)

---

## 04: Persona

![bg right:70% fit](https://chat-gpt-5.ai/wp-content/uploads/2023/12/Persona.jpeg)
[>> source](https://chat-gpt-5.ai/chatgpt-prompt-formula/)

---

## 05: Format

![bg right:70% fit](https://chat-gpt-5.ai/wp-content/uploads/2023/12/Format.jpeg)
[>> source](https://chat-gpt-5.ai/chatgpt-prompt-formula/)

---

## 06: <br>Tone

![bg right:70% fit](https://chat-gpt-5.ai/wp-content/uploads/2023/12/Tone.jpeg)
[>> source](https://chat-gpt-5.ai/chatgpt-prompt-formula/)

---

## Perfect prompt

![bg right:70% fit](https://chat-gpt-5.ai/wp-content/uploads/2023/12/perfect-prompt.jpeg)
[>> source](https://chat-gpt-5.ai/chatgpt-prompt-formula/)

---

<!-- _header: "" -->
<!-- _footer: "" -->

![bg contain](https://i0.wp.com/fourweekmba.com/wp-content/uploads/2023/01/prompt-engineering.png)

---

## Skills

![bg right:75% fit](https://gsdcdata.s3.amazonaws.com/gsdc/image/prompt-engineer-skills-a-step-by-step-learning-path.jpg)
[>> source](https://www.gsdcouncil.org/blogs/prompt-engineer-skills)

---

## Salary

![bg right:75% fit](https://lh7-us.googleusercontent.com/vb5y8PZ35_sDzdvcrHPzPqPl-ZV_5Cp64hPfHSqxMsqRBWzwOJZKt8AdHIDvpsst1214BCku5cqcimoZ1-Usju69EPRsP3YEVPCo5okPZeIWsuAn9jjWpwRKt7yPfgxbm1wv7eOLC0oO3B--i3H6r2c)
[>> source](https://dataengineeracademy.com/blog/what-is-prompt-engineering-trend-in-2024/)

---

## Prompt engineers are in high demand.

![h:500 center](https://media.licdn.com/dms/image/D5612AQGb_dVDFI5GoA/article-cover_image-shrink_720_1280/0/1684218148948?e=2147483647&v=beta&t=2h2bBdCmPcwcJA5fxVbYoqhbclYK7RtYt9oR48XpIWE)

---

## Soft skills for prompt engineering

![bg right:65% fit 90%](https://images.ctfassets.net/lzny33ho1g45/7CNpHEDpS10XH6Vj0VF4u5/c9f8303b813b64145a55858eeb4dfa16/Group_12494.jpg?w=1400&fm=avif)

---

## Technical skills for prompt engineering

![bg right:65% fit 90%](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*C5zRyXyvcgvsn_aoFBR7sg.png)

---

### Start with Python 🐍 if you want to try programming.

![bg right:65% fit](https://cdn.kobo.com/book-images/82012983-1b89-46f7-9986-00404214f15f/1200/1200/False/python-for-kids-for-dummies.jpg)
![bg fit](https://cf-assets2.tenlong.com.tw/ig/027/229/466/9781119907947.jpg?1704156714)

---

![h:500 center](https://i.imgur.com/DuUmNoP.png)

[>> source](https://santiagof.medium.com/english-is-the-most-powerful-programing-language-even-for-data-science-introduction-to-prompt-998406a499be)

---

### With LLMs, everyone can be a developer, even if you're just 9 years old.

![bg right:65% fit](https://cdn.ftvnews.com.tw/engnews/images/2024/cfd1b651-48d8-4e6f-8dfb-49da3f76cc13.jpg)
[>> source](https://english.ftvnews.com.tw/news/2024919W01EA)

---

## GenAI's impact on future jobs

[>> source](https://www.cogentinfo.com/resources/genai-how-will-it-impact-future-jobs-and-workflows)
![bg right:65% fit](https://cdn.prod.website-files.com/651e8862627bb76b91f2a4e6/65ddd5d3c620763dfddc1317_growth%2030%20jan-02.jpg)

---

<!-- _header: "" -->
<!-- _footer: "" -->

# Prompting techniques

![bg](https://slidechef.net/wp-content/uploads/2021/11/Real-Classroom-Background.jpg)

---

![bg invert 80%](https://miro.medium.com/v2/resize:fit:1400/1*Mq65ILt6P0p8n_ylGtkm1A.png)
[>> source](https://medium.com/the-modern-scientist/prompt-engineering-classification-of-techniques-and-prompt-tuning-6d4247b9b64c)

---

-   Zero-shot prompting

![h:400](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*qy3a2I6tPEbR3ASaM4z4vw.png)
[>> source](https://medium.com/the-modern-scientist/prompt-engineering-classification-of-techniques-and-prompt-tuning-6d4247b9b64c)

---

-   Few-shot prompting

![h:400](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*4gE37XARckC1j_h9ldc2Bw.png)
[>> source](https://medium.com/the-modern-scientist/prompt-engineering-classification-of-techniques-and-prompt-tuning-6d4247b9b64c)

---

-   Generated knowledge prompting: Idea

![h:400](https://miro.medium.com/v2/resize:fit:1334/format:webp/1*yle11EBNK9SIntuAN0sgUw.png)
[>> source](https://medium.com/the-modern-scientist/prompt-engineering-classification-of-techniques-and-prompt-tuning-6d4247b9b64c)

---

-   Generated knowledge prompting: Example

![h:430 center](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*DQJ8bj0WlEPywSS7wjdLww.png)
[>> source](https://medium.com/the-modern-scientist/prompt-engineering-classification-of-techniques-and-prompt-tuning-6d4247b9b64c)

---

-   Chain-of-thought (CoT) prompting

![](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*ZeCxbNj-VXyG9El5pwSjZQ.png)
[>> source](https://medium.com/the-modern-scientist/prompt-engineering-classification-of-techniques-and-prompt-tuning-6d4247b9b64c)

---

-   Program-aided lanaguage (PAL) prompting

![](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*cKINqTfoTPjIOdu6CnRLVA.png)
[>> source](https://medium.com/the-modern-scientist/prompt-engineering-classification-of-techniques-and-prompt-tuning-6d4247b9b64c)

---

-   Putting it all together

![h:420 center](https://static.wixstatic.com/media/b45b25_2742fe86a5bd495dadc3de0e77512b6b~mv2.png/v1/fill/w_1480,h_786,al_c,q_90,usm_0.66_1.00_0.01,enc_auto/b45b25_2742fe86a5bd495dadc3de0e77512b6b~mv2.png)
[>> source](https://www.tensorops.ai/post/prompt-eng-vs-rag-vs-fine-tuning-what-do-you-need)

---

## Prompt generator

[>> try it out here](https://www.feedough.com/ai-prompt-generator/)
![bg right fit](https://m.media-amazon.com/images/I/61PrMQDOGwL._AC_UF1000,1000_QL80_.jpg)

---

## Code demo

-   [Basic Text Classification](https://github.com/google-gemini/cookbook/blob/main/examples/prompting/Basic_Classification.ipynb)
-   [Text Classification with a Schema](https://github.com/google-gemini/cookbook/blob/main/examples/json_capabilities/Text_Classification.ipynb)
-   [Sentiment Analysis with scores](https://github.com/google-gemini/cookbook/blob/main/examples/json_capabilities/Sentiment_Analysis.ipynb)
-   [Basic Information Extraction](https://github.com/google-gemini/cookbook/blob/main/examples/prompting/Basic_Information_Extraction.ipynb)
-   [Information Extraction with a Schema](https://github.com/google-gemini/cookbook/blob/main/examples/json_capabilities/Entity_Extraction_JSON.ipynb)

---

<!-- _header: "" -->
<!-- _footer: "" -->

## Q1: What are the things that you didn't know but learned from this talk?

## Q2: What are the things that you'll start doing after listening to this talk?

![bg](https://c4.wallpaperflare.com/wallpaper/829/1010/472/cloud-tip-paper-board-wallpaper-preview.jpg)

---

## Take-away messages - 1/3

-   **Interdisciplinary integration**: Generative AI and prompt engineering are not just for tech enthusiasts or computer science majors. They can be incredibly useful tools for humanities majors as well.

![bg](https://static.vecteezy.com/system/resources/thumbnails/047/443/431/small/quote-speech-text-free-png.png)

---

## Take-away messages - 2/3

-   **Creativity amplified**: Generative AI can be seen as a tool to amplify human creativity, not replace it. Remember, the AI is just a tool, the real creativity comes from you.

![bg](https://static.vecteezy.com/system/resources/thumbnails/047/443/431/small/quote-speech-text-free-png.png)

---

## Take-away messages - 3/3

-   **Doing by saying**: The field of generative AI heavily relies on understanding and manipulating language. This is where knowledge of language comes in. Understanding how language works can help you better utilize and even improve these tools.

![bg](https://static.vecteezy.com/system/resources/thumbnails/047/443/431/small/quote-speech-text-free-png.png)

---

<!-- _header: "" -->
<!-- _footer: "" -->
<!-- _paginate: "" -->
<!-- _color: black -->

## Any questions:question:

![bg](https://insight.ieeeusa.org/wp-content/uploads/sites/2/2021/12/questions-1200.jpg)
![bg](https://i.pinimg.com/736x/b5/ed/ce/b5edce1292f23e30781b6d2ba487f39c.jpg)

---

## How to reach me

-   Email:
    `howard.haowen@gmail.com`
-   Portfolio:
    [https://howard-haowen.github.io](https://bit.ly/4fL1hX0)

![bg left:40%](https://raw.githubusercontent.com/howard-haowen/blog.ai/master/images/profile-removebg.png)
