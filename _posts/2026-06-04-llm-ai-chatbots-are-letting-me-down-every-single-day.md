---
layout: post
comments: true
title: LLM AI Chatbots are letting me down every single day 
---

*by a human - no AI was used*

[View Post](https://umrashrf.github.io/llm-ai-chatbots-are-letting-me-down-every-single-day/)

LLM Chatbots are definitely an innovation to where we have come with AI. I remember almost signing up for a project in early 2017 at my postgrad university with a professor working in Natural Language Processing (NLP) and making something like LLM. But it felt too complex and ambitious requiring a lot of time, so I picked another project and moved on.

Fast-forward today I use LLM every day to speed up my work and focus on what's more important than coding, the business. To improve the user experience and value for their time and money. As many others have said that now the distribution and sales matter even more and I agree with that.

But LLM can't handle complex tasks like I can. All their answers are half-baked, and I have to do the heavy lifting of getting them to the finish line.

You should be surprised to know that now open-weights local models are good enough for simple coding questions and answers to avoid hitting search engines, StackOverflow or LLMs. Download and install *ollama* in your computer and run *gemma3* or *gemma4* basic models, and you can ask things like:

```
>>> you are a javascript es6 programmer, 
...only output valid js es6 code and nothing else. 
...do not explain or write comments or docs. 
...Write js code to get today's date with utc offset 
...which will print in this format: "Thu Jun 4, 2026 10:53 AM"
```

> *Is there a way to prefix "you are a javascript es6 programmer, only output valid js es6 code and nothing else. do not explain or write comments or docs." forever? Please let me know in the comments below.*

and the answer will be:

```javascript
const today = new Date();
const options = {
  year: 'numeric',
  month: '2-digit',
  day: '2-digit',
  hour: '2-digit',
  minute: '2-digit',
  second: '2-digit',
  timeZoneName: 'short'
};
const formattedDate = today.toLocaleString('en-US', options);
console.log(formattedDate);
```

Exactly what you wanted. You just skipped search engines and paid LLMs. This is a big blow to search engines and LLMs and a big win for our privacy.

> *There is an open source *open-webui* project you can use to give you a feeling of popular chatbots out there but I found it to be a memory hog and slow.*

Large companies can add a local LLM filter layer for their employees to get answers from local LLM and fallback to external paid providers like Claude or OpenAI considerably reducing their AI costs.
