# ARC prompt collection (Abstraction and Reasoning Corpus)

Prompts for solving ARC tasks with GPT4 or similar.

Solves 39 of the public 800 tasks in the ARC 1 dataset.

Untested on the hidden 100 tasks, since GPT4 is closed source.

# Examples of incorrect predictions

IMO The incorrect predictions are more interesting than the correct predictions.
These predictions gets very close to the expected output.

<img src="documents/arc_fe9372f3_incorrect.jpg">

<img src="documents/arc_a406ac07_incorrect.jpg">

<img src="documents/arc_b7999b51_incorrect.jpg">

<img src="documents/arc_cd9d57f2_incorrect.jpg">

<img src="documents/arc_Center5_incorrect.jpg">

<img src="documents/arc_eb281b96_incorrect.jpg">


# Repo structure

There are 2 dirs:
- `prompt/correct` - Solves the task.
- `prompt/incorrect` - Almost solves the task.

The files are markdown documents, with 3 or 4 sections.
- Section A - **metadata** about what models it was tried on. All the documents says `gpt4` at the moment.
- Section B - The **prompt**. ARC task augmented with useful info. Machine generated.
- Section C - The **reply**. The response from GPT4 or similar model.
- Section D - Optional section with **human comments** about what may have gone wrong with the reasoning.

# Discord

I hang out in the ARC channels on [Lab42](https://discord.gg/waRCYPEc6C) and [Yannic Kilcher](https://ykilcher.com/discord).
Great places for discussing prompt technique.

# License

Apache or MIT.
