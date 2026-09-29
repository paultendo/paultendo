### Paul Wood FRSA

I build legal technology, at [Fifty Six Law](https://fiftysixlaw.co.uk) and independently, and I research characters that pass for one another. I've been accepted into Anthropic's Cyber Verification Program and OpenAI's Daybreak, which let security researchers use their models for work like vulnerability research and bug bounties. I write about the work at [paultendo.github.io](https://paultendo.github.io).

**[confusable-vision](https://github.com/paultendo/confusable-vision)** is the world's first font-by-font confusables dataset: which Unicode characters look alike, measured from the outlines of 322 fonts at the size people read them. Its data is used in [Mozilla's add-on name checks](https://github.com/mozilla/addons-server/blob/master/src/olympia/amo/confusables.py#L4-L6), [disarm](https://disarm.dev/) and [SilverSpeak](https://acmcmc.github.io/silverspeak/).

**[namespace-guard](https://paultendo.github.io/namespace-guard/)** checks whether a username or slug is really free: across your users, organisations and reserved routes, and against names made to pass for one you protect, like `rnicrosoft`. On npm, with no dependencies. [agent-sanitizer](https://github.com/AlexanderMattTurner/agent-sanitizer) uses it to fold lookalike characters in AI agents' tool calls back to ASCII.

**[d0ma1n](https://d0ma1n.app)** finds the lookalikes of a domain that someone has already registered, and what each one is set up to do.

**[skills](https://github.com/paultendo/skills)** teach Claude Code and Codex to use namespace-guard and d0ma1n when a task calls for them. namespace-guard is in Anthropic's plugin directory and d0ma1n is awaiting approval. Both can be added with `claude plugin marketplace add paultendo/skills`.

**[tothepenny](https://paultendo.github.io/tothepenny/)** turns bank statement PDFs into a spreadsheet, checked against the balances the bank printed. It runs in your browser, so the statements stay on your computer.

**[agent-notify](https://github.com/paultendo/agent-notify)** sends a desktop notification when Codex, Claude Code or Gemini CLI finishes, needs an approval or hits an error.

[Blog](https://paultendo.github.io) · [Substack](https://paultendo.substack.com) · [LinkedIn](https://www.linkedin.com/in/p-wood/)
