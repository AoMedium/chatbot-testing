# MemGPT

## Using this directory

Agents and personas are accessed locally outside of this repository's directory.

You will need to add the agents and personas manually into your local memgpt folder (until MemGPT supports configurable data storage https://github.com/cpacker/MemGPT/issues/329)

- e.g: `/Users/user/.memgpt` on MacOS

## Notes

- MemGPT does not support removing data sources once added to an agent; need to create a new agent and readd the data sources (and "retrain" its memory)
  - Consider creating multiple agents for each data source for independence and utilise them with MemGPT + AutoGen (https://www.youtube.com/watch?v=bMWXXPoDnDs)
