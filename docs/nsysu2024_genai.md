---
marp: true
lang: en-US
title: 中山大學演講2024
description: AI, Prompt Engineering & Linguistics
theme: graph_paper
transition: fade
paginate: true
style: |
    section {
      font-size: 35px;
    }
header: |
    [Haowen Jiang](https://bit.ly/4fL1hX0)
footer: |
    *AI, Prompt Engineering & Linguistics*
_header: ""
_footer: ""
---

<!-- _backgroundImage: "" -->
<!-- _footer: "" -->

# AI, Prompt Engineering & Linguistics

Speaker: Dr. [Haowen Jiang](https://bit.ly/4fL1hX0)
Date: Sep 12th, 2024

![bg left](https://www.m3global.com/img/content/blog/ai-impact.jpg)

<!-- This is presenter note. You can write down notes through HTML comment. -->

---

## Outline

-   My background
-   Intro to AI
-   Large Language Models (LLMs)
-   Prompt Engineering & Linguisitcs
-   Q & A

---

<!-- _header: "" -->
<!-- _footer: "" -->
<!-- _paginate: "" -->
<!-- _color: blue -->

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

-   :technologist: AI engineer at [IBM](https://www.ibm.com/us-en)

![bg right:60% 70%](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F489ea0af-4ef1-4af3-919e-be486597e278_1080x1080.jpeg)

---

## IBM Business Divisions

[>> source](https://www.trefis.com/stock/ibm/articles/546402/forecast-of-the-day-ibm-infrastructure-revenues/2023-01-05)

![bg right:65% fit](https://s3.amazonaws.com/wp-uploads-trefis/articles/wp-content/uploads/2023/01/05021808/Screenshot-2023-01-05-at-12.47.51-PM.png)

---

<!-- _header: "" -->
<!-- _footer: "" -->
<!-- _paginate: "" -->
<!-- _color: blue -->

## <!-- fit --> Intro to AI

![bg](https://theblue.ai/wp-content/uploads/2023/06/GenAI-models-Generative-AI-Hamburg.png)

---

![](https://assets-global.website-files.com/6344c9cef89d6f2270a38908/644c1fe29b0887661966d9cd_d0051e24.png)

---

## Searching for a function

-   The goal of ML/DL is to search for a _function_ that takes some input and then produces some output in a way that humans would normally do.

![h:250](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQD9L2Who0uL21le4IhuRZ78UdmWb3Vq3KFrTl5FguXzDFCpLSoRJqPL4vNL-LX1M7OLU8&usqp=CAU)

---

## Function

> -   Linguistics
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
> Try it out [>> here](https://www.programiz.com/python-programming/online-compiler)!

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

![bg right:60% 80%](https://dataedo.com/asset/img/cartoon/machine_guessing.png)

---

## Why is machine learning powerful?

The true power of ML/DL lies in the fact that

-   humans only need to provide input and output
-   computers are in charge of figuring out the right process, which is called a **model**

![h:200](https://av-eks-lekhak.s3.amazonaws.com/media/__sized__/article_images/494205_1_En_7_Fig1_HTML-thumbnail_webp-600x300.webp)

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

![bg 90%](https://www.neebal.com/hs-fs/hubfs/Generative%20AI%20Applications-Infographic.jpg?width=1920&height=1080&name=Generative%20AI%20Applications-Infographic.jpg)

---

<!-- _footer: "" -->

![bg fit](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F70b2dc14-043d-4c4e-ab92-8a124e3ee1f7_1200x900.png)

---

<!-- _header: "" -->
<!-- _footer: "" -->
<!-- _paginate: "" -->
<!-- _color: blue -->

## <!-- fit --> Large Language Models

![bg](https://media.licdn.com/dms/image/D4D12AQEMLCtqvbBAKQ/article-cover_image-shrink_720_1280/0/1707217131110?e=2147483647&v=beta&t=ef1xjQ2h-zTAFU5RJ-3Tqx0rDRpC883UrCFhuPWA55o)

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

![h:300](https://static.wixstatic.com/media/3eee0b_2ba9521e928e4a1ab8328fbc34170542~mv2.png)

---

## A language model has some world knowledge.

-   Given a huge corpus of texts, a language model can acquire some basic world knowledge.

![bg right fit](https://miro.medium.com/v2/resize:fit:1400/format:webp/0*FQOc2s9cdQSVqAJJ.png)

---

![bg fit](<https://www.investopedia.com/thmb/ulGrKT5WnVclGMOgQQVe65OtmeI=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/large-language-model-7563532-final-9e350e9fa02d4685887aa061af7a2de2.png>)

---

-   Top AI chatbos in 2024 powered by LLM
    [>> source](https://www.forbes.com/sites/digital-assets/2023/12/19/top-ai-chatbots-in-2024-choosing-the-ideal-bot-for-your-business/?sh=70554a3541c2)

![bg right:65% fit](https://imageio.forbes.com/specials-images/imageserve/65820a6a9a59f0cda2f253c2/0x0.jpg?format=jpg&height=900&width=1600&fit=bounds)

---

<!-- _header: "" -->
<!-- _footer: "" -->
<!-- _paginate: "" -->
<!-- _color: blue -->

## <!-- fit --> Prompt Engineering & Linguistics

![bg fit](https://images.spiceworks.com/wp-content/uploads/2024/04/19183329/prompt-engineering-in-programming.jpg)

---

## Prompt on the terminal

![h:500](https://res.cloudinary.com/practicaldev/image/fetch/s--WoTmwWJC--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/z7v1jxp2pr7z0d3lqqxv.png)

---

## Prompt in GenAI

-   a specific instruction or input given to the AI model to generate a desired output

![bg right:65% fit](https://d3lkc3n5th01x7.cloudfront.net/wp-content/uploads/2023/05/29032214/Bridging-the-AI-human-communication-gap-A-comprehensive-guide-to-prompt-engineering-Feature.svg)

---

## What makes a good prompt?

![h:500](https://assets-global.website-files.com/651599053c664397a48c84cd/652555f8ade90301ee2a8bc5_BOOKS.webp)

---

<!-- _header: "" -->
<!-- _footer: "" -->

![bg contain](https://i0.wp.com/fourweekmba.com/wp-content/uploads/2023/01/prompt-engineering.png)

---

<!-- _header: "" -->
<!-- _footer: "" -->

![bg fit](https://lh5.googleusercontent.com/jxgG-AxD6QMQfYhNsHQghgl4jNRPY6yrH6gZn83bQBrkfwMn1bG_BbiPr6dwYqbw71u928vMTYBsrzUMit6Sc5TjViTjmpVSCgBPr3NoRbZUMeAaJbJVUjZUUCbczuZ5CGKac5VamvpcysFAI-1pu4A)

---

## Prompt engineers are in high demand.

![h:500](https://media.licdn.com/dms/image/D5612AQGb_dVDFI5GoA/article-cover_image-shrink_720_1280/0/1684218148948?e=2147483647&v=beta&t=2h2bBdCmPcwcJA5fxVbYoqhbclYK7RtYt9oR48XpIWE)

---

#### Prompt engineering requires soft skills.

![bg right:65% fit 90%](https://images.ctfassets.net/lzny33ho1g45/7CNpHEDpS10XH6Vj0VF4u5/c9f8303b813b64145a55858eeb4dfa16/Group_12494.jpg?w=1400&fm=avif)

---

## Prompt engineering skill - language

> Linguistics plays a vital role in prompt engineering.
>
> 1. **Language Structure**: Understanding of language structure helps in designing effective prompts.
> 2. **Semantic Analysis**: Understanding the meaning of words, phrases, and sentences helps in creating more precise prompts.
> 3. **Pragmatics**: Understanding the context in which language is used can lead to the creation of more effective prompts.

---

-   Elements of a good prompt

![h:500](https://pbs.twimg.com/media/GAwsIY6XEAAkBPW.jpg)

---

## Prompt engineering skill - critical thinking

![h:500](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*h_O3KFchZl_335WCMCr54A.png)

---

## Prompt engineering skill - coding

![h:500](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*C5zRyXyvcgvsn_aoFBR7sg.png)

---

Start with Python 🐍 if you want to try programming.

![bg right:65% fit](https://cdn.kobo.com/book-images/82012983-1b89-46f7-9986-00404214f15f/1200/1200/False/python-for-kids-for-dummies.jpg)
![bg fit](https://cf-assets2.tenlong.com.tw/ig/027/229/466/9781119907947.jpg?1704156714)

---

![h:500](https://i.imgur.com/DuUmNoP.png)

[>> source](https://santiagof.medium.com/english-is-the-most-powerful-programing-language-even-for-data-science-introduction-to-prompt-998406a499be)

---

## GenAI creates engineering paradigm shift.

![h:500](https://miro.medium.com/v2/resize:fit:2000/format:webp/1*oS8mcrCLMt57X6X6xMP8Iw.png)

---

## GenAI's impact on future jobs

[>> source](https://www.cogentinfo.com/resources/genai-how-will-it-impact-future-jobs-and-workflows)
![bg right:65% fit](https://cdn.prod.website-files.com/651e8862627bb76b91f2a4e6/65ddd5d3c620763dfddc1317_growth%2030%20jan-02.jpg)

---

<!-- _header: "" -->
<!-- _footer: "" -->
<!-- _paginate: "" -->

![bg contain](https://fourweekmba.com/wp-content/uploads/2019/03/ai-business-models.png)

---

## Example: extracting ordered items from a text

-   Online order

> Hey there! I’d like to make an order for pick-up. Could I get one large fries, two fish fillet sandwiches, three cheeseburgers with no onions, and four vanilla milkshakes? Oh, and could you also add five apple pies to that order? Thanks a lot!

---

## Example: extracting ordered items from a text

-   Using **knowledge of linguistics**

    > ```json
    > [
    > {'LIKE_NUM': True},
    > {'POS': 'ADJ', 'OP': '?'},
    > {'POS': 'NOUN', 'OP': '+'}
    > ]
    > ```

-   Try it out [>> here](https://demos.explosion.ai/matcher?text=Hey%20there!%20I%E2%80%99d%20like%20to%20make%20an%20order%20for%20pick-up.%20Could%20I%20get%20one%20large%20fries%2C%20two%20fish%20fillet%20sandwiches%2C%20three%20cheeseburgers%20with%20no%20onions%2C%20and%20four%20vanilla%20milkshakes%3F%20Oh%2C%20and%20could%20you%20also%20add%20five%20apple%20pies%20to%20that%20order%3F%20Thanks%20a%20lot!&model=en_core_web_sm&pattern=%5B%7B%22id%22%3A0%2C%22attrs%22%3A%5B%7B%22name%22%3A%22LIKE_NUM%22%2C%22value%22%3Atrue%7D%5D%7D%2C%7B%22id%22%3A1%2C%22attrs%22%3A%5B%7B%22name%22%3A%22POS%22%2C%22value%22%3A%22ADJ%22%7D%2C%7B%22name%22%3A%22OP%22%2C%22value%22%3A%22%3F%22%7D%5D%7D%2C%7B%22id%22%3A3%2C%22attrs%22%3A%5B%7B%22name%22%3A%22POS%22%2C%22value%22%3A%22NOUN%22%7D%2C%7B%22name%22%3A%22OP%22%2C%22value%22%3A%22%2B%22%7D%5D%7D%5D)!

---

## Outcome of the extraction

![h:500](https://i.imgur.com/5VSNHL1.png)

---

## Example: extracting ordered items from a text

-   Using a **prompt**

> You work at a fast food restaurant and are good at summarizing what a customer orders from a text. Extract ordered items from the following text. Use the json format, with two keys, quantity and item:
> Text: <Hey there! I’d like to make an order for pick-up. Could I get one large fries, two fish fillet sandwiches, three cheeseburgers with no onions, and four vanilla milkshakes? Oh, and could you also add five apple pies to that order? Thanks a lot!>

---

## Outcome of the extraction

```json
[
	{ "quantity": 1, "item": "large fries" },
	{ "quantity": 2, "item": "fish fillet sandwiches" },
	{ "quantity": 3, "item": "cheeseburgers with no onions" },
	{ "quantity": 4, "item": "vanilla milkshakes" },
	{ "quantity": 5, "item": "apple pies" }
]
```

See the conversation on [>> Bing Chat](https://sl.bing.net/M8YpgyiuI0)!

---

## Use case: Wendy's drive-thru

Wendy’s FreshAI uses generative AI to generate responses and adapt in real-time ... – it's a personalized, responsive experience for every customer. Considering **there are more than 200 billion ways to order a Dave’s Double®**, leveraging generative AI is a crucial piece of innovating the Wendy’s drive-thru experience for customers. [>> source](https://www.wendys.com/blog/drive-thru-innovation-wendys-freshai)

![bg right:30% 80%](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRNePvnAS_MYiMZtr4_f8mBEgrqnyX5WOURPCfC8shG4A&s)

---

## Take-away messages - 1/3

> -   **Interdisciplinary integration**: Generative AI and prompt engineering are not just for tech enthusiasts or computer science majors. They can be incredibly useful tools for humanities majors as well.

---

## Take-away messages - 2/3

> -   **Creativity amplified**: Generative AI can be seen as a tool to amplify human creativity, not replace it. Remember, the AI is just a tool, the real creativity comes from you.

---

## Take-away messages - 3/3

> -   **Doing by saying**: The field of generative AI heavily relies on understanding and manipulating language. This is where knowledge of linguistics comes in. Understanding how language works can help you better utilize and even improve these tools.

---

<!-- _header: "" -->
<!-- _footer: "" -->
<!-- _paginate: "" -->
<!-- _color: white -->

## Any questions:question:

![bg](https://t3.ftcdn.net/jpg/04/34/94/90/360_F_434949006_MtUycXdKs8P4Qg6ElGkuP9UdsEX012YE.jpg)
![bg](https://i.pinimg.com/736x/b5/ed/ce/b5edce1292f23e30781b6d2ba487f39c.jpg)

---

## How to reach me

-   Email:
    `howard.haowen@gmail.com`
-   Portfolio:
    [https://howard-haowen.github.io](https://bit.ly/4fL1hX0)

![bg left:40%](https://raw.githubusercontent.com/howard-haowen/blog.ai/master/images/profile-removebg.png)
