# AI & ChatGPT Shortlist

This repository is a curated list of interesting tools, plugins, and resources for working with OpenAI's ChatGPT and other AI. It also contains small tutorials to help you learn various aspects of using ChatGPT effectively.

## The story behind this repo
After using for several months ChatGPT 3.5 and ChatGPT 4 daily for various tasks, I decided to start an experiment:
**For 3 months, my boss will be ChatGPT.** In all the aspects of my life, ChatGPT will guide me to be a better parent, be better organize, eat better and even build a 10,000€/month business. I'll update this repo to share my learnings about this interesting experiment. Hopefully you can reproduice it yourself.

## Table of Contents

1. [Tools and Plugins](#tools-and-plugins)
   - [AI end-to-end solutions](#AI-end-to-end-solutions)
   - [Content Creation](#Content-Creation)
   - [AI Prompts Engineering](#AI-Prompts-Engineering)
   - [AI Deployment](#AI-Deployment)
3. [Tutorials](#tutorials)
   - [Loading Personalities](#loading-personalities)
   - [Creating Efficiency Prompts](#creating-efficiency-prompts)
   - [Using URLs and PDFs](#using-urls-and-pdfs)
4. [Contributing](#contributing)
5. [License](#license)

## Projets done with ChatGPT

1. [My personal website on github, 100% ChatGPT](https://lkorczowski.github.io/)

## Tools and Plugins

### AI end-to-end solutions

* [Manychat](manychat.com) - answer automatically to your clients
* [Unbounce](unbounce.com) - generate landingpage using AI
* [Tailorbrands](tailorbrands.com) - generate your graphical chart using AI
* [copy.ai](copy.ai) - the copy of your website in one click
* [adext.ai](adext.ai) - optimize your ads copy using AI for Google and Facebook ads
* [HuggingChat](https://huggingface.co/chat/) - the opensource alternative to ChatGPT by HuggingFace

### Content Creation
* [submagic](https://submagic.co/) -  AI-Powered Captions and Subtitles for short videos <90s (Tiktok, Reels, etc.)
* [Midjourney](https://www.midjourney.com/) - Do I need to present them? text-to-image generator specialized on digital art
* [D-ID](https://www.d-id.com/) - dubbing your video using immersive and human-like conversational AI

### AI-models

### AI Prompts Engineering
* [PromptPerfect](https://promptperfect.jina.ai/) - automatically optimizes your prompts for ChatGPT, MidJourney, StableDiffusion, Claude and many others.

### AI Deployment
* [🤖 AnythingLLM: A full-stack personalized AI assistant](https://github.com/Mintplex-Labs/anything-llm) - A full-stack application and tool suite that enables you to turn any document, resource, or piece of content into a piece of data that any LLM can use as reference during chatting.
* [PrivateGPT](https://github.com/imartinez/privateGPT) - Ask questions to your documents without an internet connection, using the power of LLMs. 100% private, no data leaves your execution environment at any point. You can ingest documents and ask questions without an internet connection!
* [LocalGPT](https://github.com/PromtEngineer/localGPT) -  Inspired by PrivateGPT: Chat with your documents on your local device using GPT models. No data leaves your device and 100% private. 
* [gpt4all](https://github.com/nomic-ai/gpt4all) - Open-source assistant-style large language models that run locally on your CPU

### Software
* [Mojo programming language](https://www.modular.com/) - Programming language for AI based on python. "The fastest unified AI inference engine in the world."
* [TensorFlow](https://www.tensorflow.org/) - end-to-end Python ML librairy and framework for training, testing and deploying AI models. Made in Google.
* [PyTorch](https://pytorch.org/) - Python ML librairy and framework for training, testing. Much easier to grasp than TensorFlow if you know python.
* [scikit-learn](https://scikit-learn.org/) - the easiest way to start building models and using ML for data science. 

## Tutorials

### PeTODI prompt Framework
I developed my own prompt Framework that I use in most of the simple tasks. It has a very high degree of success (95%+) with ChatGPT4 and doesn't require any plugin or internet. It also drastically improves any prompt of ChatGPT3.5 which is dumb in comparison (success rate 75%+).

1. Personality -> ask to load a personality for the agent.
2. Task -> ask the general goal of the agent for this entire conversation.
3. Output -> specify exactly what is the expected output (format, type, etc.)
4. Details -> give the details, context and data. If it require several prompts to feed data, you can use “Don’t start anything yet, you can acknowledge and I will feed you with more data in the next prompt” at the end of your prompt.
5. Iterate -> after the first output was given, you can iterate by giving feedback, pointing out errors and asking for feedback. When code is the output, you can copy/paste any error and ChatGPT will provide you with solutions.


### Loading Personalities

A brief overview of how to load a personality into ChatGPT. Include a link to the tutorial file (e.g., `loading_personalities.md`).

### Creating Efficiency Prompts

A brief overview of how to create efficiency prompts for ChatGPT. Include a link to the tutorial file (e.g., `creating_efficiency_prompts.md`).

### Using URLs and PDFs

A brief overview of how to use URLs and PDFs as input for ChatGPT. Include a link to the tutorial file (e.g., `using_urls_and_pdfs.md`).

## Contributing

We welcome contributions to this repository! If you have a tool, plugin, resource, or tutorial to add, please [create a pull request](https://github.com/yourusername/chatgpt-shortlist/pulls) or [open an issue](https://github.com/yourusername/chatgpt-shortlist/issues) for discussion.

## License

This repository is licensed under the [MIT License](LICENSE).
