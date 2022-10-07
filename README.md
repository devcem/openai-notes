# OpenAI Notes

This repo will contain my personal notes about OpenAI, GPT-3, and other related topics. The main objective is to have a place to store my notes and to share them with the community. But also creating a "useful" tool that I can use my daily life. Codename is this tool is "Nerd" a discord bot that can write new features, fix bugs and deploy/maintain the codebase.

## Definitions
- I will use the term "AI" to refer to any kind of artificial intelligence, including machine learning, deep learning, and other related topics.
- In order to create a useful tool, I'll need certain algorithms, data structures. And notes will be about them.

## Templates
- File list search https://github.com/devcem/openai-notes/blob/main/file-list.md
- File and route method https://github.com/devcem/openai-notes/blob/main/file-route-method.md
- Find missing/newly added code piece https://github.com/devcem/openai-notes/blob/main/find-missing.md

## Best Prompt Settings
- Temperature, 0.37 works better with zonf's prompt. When temperature is 0, there is no creativity, use 0 only in the case where you have at least 2-3 lines of code.
- Use """ to seperate questions from code.
- code-davinci 002

## Read
- Self-asking algorithm : https://twitter.com/OfirPress/status/1577302733383925762
- Self-asking algorithm : https://twitter.com/kojima_tks/status/1577502622226862080
- https://artifact-research.com/artificial-intelligence/talking-to-machines-prompt-engineering-injection/
- Injection : https://twitter.com/goodside/status/1578278974526222336
- A potential project that is planning to cut costs of GPT : https://twitter.com/humanloop/status/1577655572559630336

## Update Log
- First version of Nerd bot created at "09/30/2022". This version can modify simple parts of any code on PHP backend. It works with this method: Find related file -> Find related route -> Modify it with OpenAI's edit function and show changes with diff function.