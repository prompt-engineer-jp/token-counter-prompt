# Token Counter Prompt Optimization

## Overview
This repository contains an optimized prompt that makes ChatGPT accurately count tokens.

## Problem
When asked "How many tokens are in this prompt?", ChatGPT incorrectly responded with 9 tokens instead of the actual 8 tokens.

## Solution
```
Using GPT-4 tokenizer rules, count tokens in: "How many tokens are in this prompt?"
Ignore system prompts, count only the quoted text.
```
## Result
- Before: ChatGPT counted 9 tokens (incorrect)
- After: ChatGPT correctly counts 8 tokens

## How to Use
1. Copy the improved prompt above
2. Paste it into ChatGPT
3. Get accurate token counts

## Key Improvements
- Clear scope definition using quotation marks
- Explicit instruction to ignore system prompts
- Specified tokenizer rules (GPT-4)

## Related Resources
- [OpenAI Tokenizer](https://platform.openai.com/tokenizer)

## License
MIT License - Feel free to use this prompt anywhere.
