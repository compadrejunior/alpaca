# Run Stanford Alpaca AI on your machine

## Overview

Stanford Alpaca is an open-source language model developed by computer scientists at Stanford University (**1**). It is a seven-billion parameter variant of Meta's LLaMA model (**2**), which has been fine-tuned using supervised learning on 52,000 instruction-following demonstrations (**3**). Alpaca is designed to be able to respond to instructions like ChatGPT (**4**), and it has been demonstrated to perform similarly to the ChatGPT model on many tasks but at a lower cost. The goal of the Alpaca project is to build and share an instruction-following language model with the research community, which can serve as a platform for further research and development.

## Requirements

- [Node.js](https://nodejs.org/en)
- [Download Python](https://www.python.org/downloads/)

## Installation

1. Install packages.
    ```bash
    npx dalai llama install 7B
    ```
2. Run the service.
    ```bash
    npx dalai serve 
    ```

## References

1. [Stanford takes costly, risky Alpaca AI model offline • The Register](https://www.theregister.com/2023/03/21/stanford_ai_alpaca_taken_offline/)
2. [Stanford's Alpaca shows that OpenAI may have a problem (the-decoder.com)](https://the-decoder.com/stanfords-alpaca-shows-that-openai-may-have-a-problem/)
3. [Stanford CRFM](https://crfm.stanford.edu/2023/03/13/alpaca.html)
4. [Train and run Stanford Alpaca on your own machine - Replicate – Replicate](https://replicate.com/blog/replicate-alpaca)
5. [tatsu-lab/stanford_alpaca: Code and documentation to train Stanford's Alpaca models, and generate the data. (github.com)](https://github.com/tatsu-lab/stanford_alpaca)
6. [cocktailpeanut/dalai: The simplest way to run LLaMA on your local machine (github.com)](https://github.com/cocktailpeanut/dalai)
