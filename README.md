# AI Study Buddy

[![GitHub tag](https://img.shields.io/github/tag/SebGSX/AI-Study-Buddy?include_prereleases=&sort=semver&color=blue)](https://github.com/SebGSX/AI-Study-Buddy/releases/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)
[![issues - AI-Study-Buddy](https://img.shields.io/github/issues/SebGSX/AI-Study-Buddy)](https://github.com/SebGSX/AI-Study-Buddy/issues)

## Overview

This project provides several AI tutoring prompts designed to assist students at all levels with their learning activities. The motivation for this project stems from a paper written in 1984 by Benjamin Bloom and published by MIT Press. Bloom's paper, [The 2 Sigma Problem](https://web.mit.edu/5.95/readings/bloom-two-sigma.pdf), explains how those of us fortunate enough to receive personalised tutoring can in the best cases achieve a two standard deviation (2 sigma) improvement in learning outcomes. Using my own learning journey as well as those of friends and colleagues for testing and verification, the prompts built have been exhaustively developed and tested over a period of about nine months.

> **Disclaimer:** Be sure at all times to check that your use of AI does not break any data privacy, protection, or confidentiality rules, regulations, laws, or contractual obligations, and that copyright as well as intellectual property rights are respected. The information contained in this and any related files is provided for information purposes only. The author cannot be held liable for any loss whatsoever for your use of any system including but not limited to artificial intelligence. Your use of the information contained herein is solely at your own discretion and risk. The information provided in this and any related files is provided "AS-IS" with no warranty express or otherwise implied.

## Objective

The objective of this project is to democratise access to the kind of personal, individualised tutoring that until quite recently was the preserve of the affluent. Generative AI while not perfect and must be checked--in much the same way one checks guidance from tutors or other sources--it does provide an on-demand and both highly intelligent and knowledgeable resource.

> Please be aware that AI changes rapidly and that the information contained in this project and related projects may quickly become out-of-date. While I do endeavour to keep projects updated, I may not always be able to do so.

## Ethics

For reasons of integrity and good ethics, we must not use AI to complete assessments and assignments unless such use is authorised and disclosed appropriately. Misuse of AI not only deprives us of meaningful learning and skill development, but discovery of such misuse is also  a simple matter of an in-person test or interview.

> **Note to tutors, course conveners, and professors:** Adding an oral component to all assessments to check for genuine insight is highly recommended to protect academic integrity. In addition, it is prudent to look for generic, inauthentic voicing in assessments and assignments. Such voicing is typically an indicator of copying AI responses. Essentially, the same checks used for determining if a student has copied from forums, assignment sites, paid tutors, etc. are effective with some modification.

## Supervision for Minors

For parents wishing to use the content of this repository to assist children with their schoolwork, please ensure that any such use is appropriately supervised.

## Why Generative AI?

### Generative AI is Smart

According to an article in [Scientific American](https://www.scientificamerican.com/article/i-gave-chatgpt-an-iq-test-heres-what-i-discovered/), ChatGPT was given an IQ test some time around March of 2023. The AI scored **155**, which is, according to the article, "superior to 99.9 percent of the test takers who make up the American WAIS III standardization sample of 2,450 people. As the chatbot lacks the requisite eyes, ears and hands, it is not able to take WAIS’s nonverbal subtests. But the Verbal IQ and Full-Scale IQ scales are highly correlated in the standardization sample, so ChatGPT appears to be very intelligent by any human standards."

### Generative AI has Expertise

According to an article in the [American Bar Association (ABA) Journal](https://www.abajournal.com/web/article/latest-version-of-chatgpt-aces-the-bar-exam-with-score-in-90th-percentile), ChatGPT passed the latest bar exam with a score in the 90th percentile some time around March 2023. That is not to say that ChatGPT is a licensed attorney or should be counted on for legal; however, it does show the depth of AI expertise.

## Why is a Generative AI Tutor is Effective?

### Master Coaching with Deliberate Practice

Perhaps the most powerful aspect of AI is its ability to act as a master coach by correcting us as we discuss ideas with it. Making lots of mistakes with immediate feedback and correction rapidly improves skill. For detailed insight into why, please see Daniel Coyle's book entitled *The Talent Code*. Similarly, the book entitled *Peak* by Anders Ericsson and Robert Pool contemplates the notion of "deliberate practice" that is fostered using AI as a tutor.

## Getting the Most from Generative AI

AI is not a silver bullet. The quality of your questions directly impacts the quality of the output. Generative AI is a system of probabilities. Thus, if it has been trained on many conversations such as those between experts and layfolk alike, it will respond like an expert if addressed as one and a lay person if addressed as such. Essentially, what we put in is what we get out. Thus, the harder we work at your studies, the better the support AI can provide. The more precise and domain-specific the language, the higher the chance of the AI working out where we've made an error. AI can lack nuance and does not necessarily have the kind of insight stemming from experiential learning, so we must not forget to work with humans too. While AI is not a panacea, it offers something compelling from a personalised tutoring standpoint. It's smart, always available, cost-effective, and knows a whole lot.

> **Key points:** AIs are very helpful, but we must be careful to check for hallucinations (the AI inventing things that aren't real) and we must be mindful to do our part. AI can lack nuance and may not have deep insight. That said, the technology is improving and evolving constantly.

### AI Custom Instructions (Standing Instructions)

An often overlooked component of the use of generative AI is custom instructions. Custom instructions are standing instructions that guide how the AI should respond in all instances. Given that large language models (LLMs) are probabilistic systems trained on vast amounts of data, it behoves the user to limit the AI's domain so that more accurate and in-depth responses are generated.

The author has experimented with a variety of custom instructions over the past year to 18 months and has found that the set provided within the [AI Custom Instructions](https://github.com/SebGSX/AI-Custom-Instructions) repository is the most effective.

> **Note:** The custom instructions do evolve and are thus subject to change. Given the experimental nature of the work the custom instructions are sometimes suboptimal and may contain errors or out-of-the-box thinking.

## How to Create an AI Study Buddy

### First, Choose an AI Service

There are many AI services to choose from; however, I use OpenAI's ChatGPT. You can find ChatGPT [here](https://chatgpt.com/). There is a free version of ChatGPT using the GPT-3.5 model; however, GPT-4 is the model that passed the IQ test and bar exam, which is why I use the paid version and the latest stable (non-preview) model.

At minimum, you'll need [ChatGPT Plus](https://openai.com/blog/chatgpt-plus) if you want the paid version. I use [ChatGPT Team](https://openai.com/chatgpt/team) because of its enhanced data protection support, which I need.

> Please be sure to check data privacy concerns when using any service including but not limited to generative AI services.

### Second, Create Your Study Buddy

To proceed, you'll need the [Tutor Prompt for AI](https://github.com/SebGSX/AI-Study-Buddy/blob/main/tutor-prompt-for-AI.md) prompt. Prompt engineering is the careful process of explaining to a generative AI system exactly what you want it to do for you. While it may look simple enough, quite a lot goes into structuring an effective prompt. OpenAI has some guidance [here](https://platform.openai.com/docs/guides/prompt-engineering) whereas general guidance can be found [here](https://www.promptingguide.ai/).

#### Preparing the Prompt

The prompt I've prepared uses a format called [Markdown](https://www.markdownguide.org/) to annotate the text in a simple way that indicates layout. Please copy the text I've provided verbatim including the Markdown. When viewing the prompt on GitHub by following the link above, you will notice 3 buttons above the content: `Preview`, `Code`, and `Blame`. Choose `Code` to see the Markdown.

At the top of the prompt is a section with variables that you will need to update with your information. The information helps the AI understand what is expected. Within the text of the prompt you'll see the variables enclosed in double-braces `{{VARIABLE-NAME}}`. The most important are the `SKILL-LEVEL` and `LANGUAGE-SKILL-LEVEL` variables. Those variables should contain one of `Novice`, `Advanced Beginner`, `Competent`, `Proficient`, and `Expert` as defined within the highly regarded and well-understood Dreyfus Model of Skill Acquisition. The skill level variables help the AI to provide the most appropriate level of tutoring.

```Markdown
---
COURSE: Pure Mathematics (M208)
DOMAIN: Pure Mathematics
EDUCATION-LEVEL: undergraduate (stage 2)
COUNTRY: United Kingdom
QUALIFICATION: BSc in Mathematics and Statistics
CURRENT-SKILL-LEVEL: Proficient
TARGET-SKILL-LEVEL: Expert
LANGUAGE: English (UK)
LANGUAGE-SKILL-LEVEL: Expert
---
```

> **Important:** Please remember to be careful with your personal information and that of others. The AI does not need anyone's personal identifiable information (PII) to be effective.

Please feel free to adjust the text of the prompt to suit your needs.

> *Please note:* Even if you're an expert in prompt engineering, it is unlikely that your changes to the prompt will be perfect on the first attempt. Pay attention to the AI's responses and adjust the prompt as needed. Prompt engineering is a highly iterative process.

#### The Casual Study Buddy

Once you have your prompt, simply copy and paste it into the first message of a new session with an AI service, then proceed to ask the AI for help in any domain you need. Remember, the better your questions, the better the answers.

#### The Formal Study Buddy

If you'd like a dedicated AI that you can configure once and use repeatedly, ChatGPT provides [custom GPTs](https://help.openai.com/en/articles/8554397-creating-a-gpt). Once you've created your custom GPT, replace the text in the "Instructions" box with the prompt you've created.

> Please be extremely careful when saving the custom GPT because it is possible to make custom GPTs public. A public GPT can be disastrous for reasons of data privacy, protection, and confidentiality not to mention copyright as well as intellectual property rights. As such, it is strongly recommended to keep custom GPTs strictly private unless you know exactly what you're doing. See disclaimer above.

## Using the AI Study Buddy

AIs are great with concepts but can struggle when performing logic, maths, and stats tasks, or anything the like where precise, step-by-step work is required. Accordingly, it is strongly recommended that all output is checked carefully and continually.

The types of interactions that work best with generative AI include discussing concepts, asking for explanations, and exploring hypothetical scenarios. AI is also very good at providing concrete examples across domains such as explaining how integration in calculus can be used to calculate power usage over time in our homes.

> Generative AI is not perfect and is not infallible. Similar to checking guidance from tutors or fellow students in study groups, be sure to check responses and guidance from generative AI carefully.

## Talking to the AI Study Buddy

If using the OpenAI app for mobile devices, we can talk to our AI Study Buddies like we would a human albeit with some changes in how we approach the conversation.

## Contributing

Contributions are welcome as are corrections. The author follows Crocker's Rules. Direct, honest, and constructive feedback is appreciated. Please submit a pull request with your changes or an issue with your feedback.

## License

Released under [MIT](/LICENSE) by [@SebGSX](https://github.com/SebGSX) (Seb Garrioch).
