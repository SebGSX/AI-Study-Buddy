# Overview
> Please be aware that AI changes rapidly and that the information contained in this and related files may quickly become out-of-date. Be sure to always check.

Generative AI such as services provided by OpenAI's ChatGPT are exceptional resources for learning. Some AIs are really smart (see below) and they're constantly getting smarter. Given the breadth and depth of their training data, AIs know more in total than any human could ever hope to remember. Even in specific fields like law, AIs can outperform experts (see below). While AI is not a panacea, it offers something compelling from a personalised tutoring standpoint. It's smart, always available, cost-effective, and knows a whole lot.

According to Benjamin Bloom's oft cited research from 1984 [The 2 Sigma Problem](https://web.mit.edu/5.95/readings/bloom-two-sigma.pdf), those of us fortunate enough to receive personalised tutoring can in the best cases achieve a 2 standard deviation (2 sigma) improvement in learning outcomes. It is vital to remember that AI can make mistakes and can even invent things that aren't true (known as hallucinations), so it is important to verify just like you would with a human tutor. Using AI as your study buddy thus opens a compelling opportunity to excel in your studies in a convenient and cost-effective manner.

That said, AI is not a silver bullet. The quality of your questions directly impact the quality of the output. Essentially, what you put in is what you get out. Thus, the harder you work at your studies, the better the support AI can give you. The more precise and domain-specific your language, the higher chance of the AI working out where you've made an error. AI can lack nuance and does not necessarily have the kind of insight stemming from experiential learning, so don't forget to work with humans too.

> Key points: AIs are very helpful, but be careful to check for hallucinations and be mindful to do your part. AI can lack nuance and may not necessarily have deep insight.

> Disclaimer: Be sure at all times to check that your use of AI does not break any data privacy, protection, or confidentiality rules and that copyright as well as intellectual property rights are respected. The information contained in this and any related files is provided for information purposes only. The author cannot be held liable for any loss whatsoever for your use of any system including but not limited to artificial intelligence. Your use of the information contained herein is solely at your own discretion and risk. The information provided in this and any related files is provided "AS-IS" with no warranty express or otherwise implied.

## AI is Smart
According to an article in [Scientific American](https://www.scientificamerican.com/article/i-gave-chatgpt-an-iq-test-heres-what-i-discovered/), ChatGPT was given an IQ test some time around March of 2023. The AI scored **155**, which is "superior to 99.9 percent of the test takers who make up the American WAIS III standardization sample of 2,450 people. As the chatbot lacks the requisite eyes, ears and hands, it is not able to take WAIS’s nonverbal subtests. But the Verbal IQ and Full Scale IQ scales are highly correlated in the standardization sample, so ChatGPT appears to be very intelligent by any human standards."

## AI has Expertise
According to an article in the [American Bar Association (ABA) Journal](https://www.abajournal.com/web/article/latest-version-of-chatgpt-aces-the-bar-exam-with-score-in-90th-percentile), ChatGPT passed the latest bar exam with a score in the 90th percentile some time around March 2023. That is not to say that ChatGPT is a licensed attorney or should be counted on for legal; however, it does show the depth of AI expertise.

# How to Create an AI Study Buddy
## First, Choose an AI Service
There are many AI services to choose from; however, I use OpenAI's ChatGPT. You can find ChatGPT [here](https://chat.openai.com/). There is a free version of ChatGPT using the GPT-3.5 model; however, GPT-4 is the model that passed the IQ test and bar exam, which is why I use the paid version.

At minimum, you'll need [ChatGPT Plus](https://openai.com/blog/chatgpt-plus) if you want the paid version. I use [ChatGPT Team](https://openai.com/chatgpt/team) because of its enhanced data protection support, which I need.

> As at the time of writing, enabling chat history in "Settings > Data Controls" when using ChatGPT (free) or ChatGPT Plus allows OpenAI to use chat history data to train their AI models. Doing so can create a data privacy issue. Please be sure to check both your settings and your obligations.

## Second, Create Your Study Buddy
No matter how you choose to proceed, you'll need [this](https://github.com/SebGSX/AI-Study-Buddy/blob/main/tutor-prompt-for-AI.md) prompt. Prompt engineering is the careful process of explaining to a generative AI system exactly what you want it to do for you. While it may look simple enough, quite a lot goes into structuring an effective prompt. OpenAI has some guidance [here](https://platform.openai.com/docs/guides/prompt-engineering) whereas general guidance can be found [here](https://www.promptingguide.ai/).

### Preparing Your Prompt
The prompt I've prepared uses a format called [markdown](https://www.markdownguide.org/) to annotate the text in a simple way that indicates layout. You must copy the text I've provided verbatim including the markdown. When viewing the prompt on GitHub by following the link above, you will notice 3 buttons above the content: Preview, Code, and Blame. Choose Code to see the source.

At the top of the prompt is a section with variables that you will need to update with your information. The information helps the AI understand what is expected. Within the text of the prompt you'll see the variables enclosed in double-braces `{{VARIABLE-NAME}}`.

```
---
COURSE: Essential Mathematics 2 (MST125)
DOMAIN: Mathematics & Statistics
LEVEL: undergraduate
QUALIFICATION: BSc(Honours) in Mathematics and Statistics
---
```

At the end of the prompt, you'll find a section called "Your Student" that you will need to complete. In that section, replace the ellipses "..." with information about yourself as a student. Be sure that the information you provide aligns with the headings that precede the ellipses. Providing such information helps the AI to understand you as a student. Accordingly, only provide the information that would help the AI tailor its responses such as a need to understand the "why" before the "how" or "what".

> Please remember to be careful with your personal information and that of others. The AI does not need anyone's personally identifiable information (PII) to be effective.

> Even if you're an expert in prompt engineering, it is unlikely that your changes to the prompt will be perfect on the first attempt. Pay attention to the AI's responses and adjust the prompt as needed. Prompt engineering is a highly iterative process.

### The Casual Study Buddy
Once you have your prompt, simply copy and paste it into the first message of a new session with an AI service, then proceed to ask the AI for help in any domain you need. Remember, the better your questions, the better the answers.

### The Formal Study Buddy
If you'd like a dedicated AI that you can configure once and use repeatedly, ChatGPT has you covered with [custom GPTs](https://help.openai.com/en/articles/8554397-creating-a-gpt). Once you've created your custom GPT, replace the text in the "Instructions" box with the prompt you've created.

> Please be extremely careful when saving the custom GPT because it is possible to make custom GPTs public. A public GPT can be disastrous for reasons of data privacy, protection, and confidentiality not to mention copyright as well as intellectual property rights. As such, the author strongly recommends keeping custom GPTs strictly private unless you know exactly what you're doing. See disclaimer above.

# Using Your Study Buddy
AIs are great with concepts but can struggle when doing maths and stats or anything the like where precise, step-by-step work is required. Accordingly, it is better to use the AI for learning and revision of concepts.

The types of interactions that work best with AI include discussing concepts, asking for explanations, and exploring hypothetical scenarios. AI is also very good at providing concrete examples across domains such as explaining how integration in calculus can be used to calculate power usage over time in our homes.

> AIs are not perfect and they're not infallible. Just like you'd check guidance from your personal tutor or your fellow students in study groups, check your AI's responses and guidance for things like hallucinations.

## Master Coaching
Perhaps the most powerful aspect of AI is its ability to act as a master coach by correcting you as you discuss ideas with it. Making lots of mistakes with immediate feedback and correction rapidly improves skill. For detailed insight into why, please see Daniel Coyle's book entitled *The Talent Code*.

## Talking to Your Study Buddy
If you download the OpenAI app for your mobile device, you can talk to your AI Study Buddy like you would a human albeit with some changes in how you approach the conversation.

> The author has a visual disability and quite specific learning needs, being able to talk to the AI has been an incredibly beneficial feature.

## AI Ethics
Do not use AI to complete assessments and assignments for you. Not only will the AI get things wrong, a quick on-the-spot oral exam will reveal the plagarism and cheating.

> Note to tutors, course conveners, and professors: Adding an oral component to all assessments to check for genuine insight is highly recommended to protect academic integrity. Also, keep an eye out for generic, inauthentic voicing in assessments and assignments, it's typically an indicator of copying AI responses. Essentially, the same checks you use for figuring out if someone has copied from forums, sites, etc. are effective.
