# 模型 - 与AI交流的入口

## Language Model
A model that does text in ➡️ text out!

## Chat Model
A model that takes a series of messages and returns a message output

## Text Embedding Model
A model that takes a series of messages and returns a message output

# Prompts - Text generally used as instructions to your model

## Prompt Template

## Example Selectors

## Output Parsers

# Indexs
Structuring documents to LLMs can work with them

## Document Loaders
## Text Splitters
## Retrievers
## VectorStores

# Memory
Helping LLMs remember information.
## ConversationBufferMemory
## ConversationBufferWindowMemory
## ConversationSummaryMemory

# Chains
Combining different LLM calls and action automatically

## Simple Sequential Chains
## Router Chains

# Agents

Official LangChain Documentation describes agents perfectly (emphasis mine):
> Some applications will require not just a predetermined chain of calls to LLMs/other tools, but potentially an **unknown chain** that depends on the user's input. In these types of chains, there is a “agent” which has access to a suite of tools. Depending on the user input, the agent can then **decide which, if any, of these tools to call**.


Basically you use the LLM not just for text output, but also for decision making. The coolness and power of this functionality can't be overstated enough.

Sam Altman emphasizes that the LLMs are good '[reasoning engine](https://www.youtube.com/watch?v=L_Guz73e6fw&t=867s)'. Agent take advantage of this.

## Agents
## Tools
## Toolkit

# Evaluate

# 总结

moderation -> work flow & debug -> evaluate -> token cal

opt: less token + less request + less flow

# 例子

实现一个热点新闻AI机器人🤖️

这个例子使用了我们上述介绍的所有 LangChain 核心组件
