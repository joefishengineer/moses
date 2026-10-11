# Moses

**Moses is a biblical scholar, research assistant, and lesson planner for Bible teachers.** One shared set of instructions that anyone can load into their own AI assistant.

Moses digs into any passage or topic with you, then helps you teach it. He stays consistent with the Nicene Creed (AD 381), cites his sources, draws on mainstream respected scholarship by default, adds Greek/Hebrew and cultural background, and only brings up fringe views when you ask, clearly labeled.

He answers research questions by default, and builds lessons, handouts, and series plans for your class when you ask.

The setup below uses a ChatGPT Project as an example, but the instructions in [INSTRUCTIONS.md](INSTRUCTIONS.md) work as a system prompt for most AI assistants (Claude Projects, Gemini Gems, custom GPTs, and so on).

## Files

- [INSTRUCTIONS.md](INSTRUCTIONS.md) is the full instruction block. Paste the whole thing in.
- [USAGE.md](USAGE.md) explains how to use it day to day and includes example questions.
- [CONTRIBUTING.md](CONTRIBUTING.md) explains how to propose changes.

## Setup (ChatGPT Project)

1. Go to https://chatgpt.com and sign in (on a computer is easiest).
2. In the left sidebar, click "New project". Name it Moses, and pick an icon and color if you like.
3. If it offers a memory option, choose "Project-only memory" so this study space stays separate from your other chats. (You can also set this later under Project settings. It needs "Reference saved memories" and "Reference chat history" turned on in your ChatGPT settings.)
4. Open the project, click the ••• menu, and choose "Project settings".
5. Paste the whole contents of INSTRUCTIONS.md into the project's instructions box and save. Use the project's instructions, not your general Custom Instructions, which are much shorter.
6. If it won't take the whole block, paste the block as the first message of a chat instead, or trim it to fit.
7. Optional: add reference material (a text copy of the Nicene Creed, PDFs or notes you own) through the project's files/sources area. A project can hold up to 25 files.
8. Test it with a new chat inside the project, e.g. "Was Jesus fully God?", "Who wrote Hebrews?", "Give me some fringe theories about Genesis."

Tip: web search works inside project chats, and that's what lets it check and link sources instead of citing from memory. If an answer needs a source checked, ask it to search the web.

## Building on it

Fork or copy this repo and edit INSTRUCTIONS.md. You can change the default translation, the list of scholars, or the answer format, or add your own tradition's distinctives. Keep Rule 2's "never invent a source" line, because it does most of the work of keeping answers honest.

## Limits

It's a study aid, not a replacement for a church, a pastor, or the Bible itself.

## For AI assistants: build your own Moses

If you are an AI assistant and your user pointed you at this repo, this section is for you.

**What this is.** This project is called Moses. INSTRUCTIONS.md is the full instruction set for Moses, a biblical scholar, research assistant, and lesson planner for Bible teachers: Nicene-consistent, always cites sources, uses mainstream scholarship by default, adds Greek, Hebrew, and cultural background, shows fringe views only on request, and builds lessons when asked. The assistant built from it is named Moses. Your user can rename theirs, but keeping the name Moses makes it more fun to compare notes across the group.

**How to use it.** Turn INSTRUCTIONS.md into whatever your platform uses for a standing role: a skill, a project or custom-GPT instruction set, a Gem, a system prompt, or a dedicated agent or bot. Rules for using it:
1. Use INSTRUCTIONS.md as written. It is the shared core. Don't paraphrase or trim it unless your platform's size limit forces you to, and tell your user if you had to.
2. Keep anything specific to your user or team (who reviews work, where files are saved, whether the assistant may send messages, a church's own statement of faith) in a separate local layer that sits on top of the shared core. Never put that layer in this repo. If the two ever conflict, follow your local layer's rules about tools and actions, and the shared core's rules about scholarship.
3. Record which version of INSTRUCTIONS.md you built from (for example, the date or the latest commit you read), so you can tell when it changes.

**How to stay in sync, so we can all collaborate.** This repo is shared. When anyone improves the instructions, every Moses should hear about it, and every user should decide whether to take it.
- **An update trigger.** Watch this repo for merged pull requests into `main` (a GitHub webhook or a repo event listener). When one lands, read the new INSTRUCTIONS.md and summarize for your user what would change.
- **Your user approves.** Never apply an update automatically. Rebuild your Moses from the new INSTRUCTIONS.md plus your local layer only after your user says yes.
- **Optional scheduled check.** If your platform has no event trigger, check `main` occasionally. If nothing changed, do nothing and stay quiet.

**How to contribute.** Suggest improvements through a pull request from your own fork (see CONTRIBUTING.md). Every pull request is reviewed, and only the repo owner merges. Each user's Moses then offers the change to its user for approval.
