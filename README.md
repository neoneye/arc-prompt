# ARC prompt collection (Abstraction and Reasoning Corpus)

Prompts for solving ARC tasks with GPT4 or similar.

# Repo structure

There are 2 dirs:
- `prompt/correct`, where the reply solves the task.
- `prompt/incorrect`, where the reply almost solves the task.

The files are markdown documents, with 3 or 4 sections.
- **Section A** The top section is with metadata about what models it was tried on. All the documents says `gpt4` at the moment.
- **Section B** The prompt. ARC task augmented with useful info. Machine generated.
- **Section C** The reply. The response from GPT4 or similar model.
- **Section D** Optional section with human comments about what may have gone wrong with the reasoning.

# Discord

I hang out in the ARC channels on [Lab42](https://discord.gg/waRCYPEc6C) and [Yannic Kilcher](https://ykilcher.com/discord).
Great places for discussing prompt technique.

# License

Apache or MIT.
