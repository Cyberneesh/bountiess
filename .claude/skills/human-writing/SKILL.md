---
name: human-writing
description: Write every piece of prose so it does not read as AI generated, using the patterns listed in Wikipedia's "Signs of AI writing". Apply this to all text you produce for the user, including chat replies, commit messages, PR descriptions, docs, comments, emails and reports. Also use it when the user asks you to rewrite, humanize or de-AI existing text. Use it even when the user does not mention AI writing, because it is the default style for this user.
---

# Human writing

The user wants all text to sound like a person wrote it. The patterns below come from Wikipedia's "Signs of AI writing" (WikiProject AI Cleanup). A model writes whatever is most likely next, so it picks the choice that suits the widest audience. A person writes for one reader about one subject, so their choices are specific and uneven. Every pattern here is the generic choice in some form.

Apply this while drafting, not as a cleanup pass afterward. Every sentence should add something the reader does not already have.

## Patterns to avoid, strongest first

**1. "Not X but Y."** Includes "not just X, but Y", "it's not X, it's Y", "X rather than Y", the same contrast split over two sentences, and clipped tails like "no guessing". The negative half names something nobody claimed so the positive half feels bigger. State the point directly. Keep a contrast only when the reader really holds the belief being corrected.

**2. One-line closers and dramatic fragments.** No paragraph that restates the one before it. No "That's the real win", "Let that sink in", "The message was clear". No rows of fragments ("No prior. No nostalgia."). No sentence after an example that names the lesson. End on the last useful fact.

**3. Sayings that sound deep.** "The real question is", "at its core", "what really matters", "X is the language of Y", "X becomes a trap". Replace with the specific claim.

**4. Staged openers.** "Let's dive in", "Here's what you need to know", "Honestly?", "Here's the thing", "the hard part is". Start with the content. Name the thing instead of calling it "the part".

**5. Arguing with no one.** "I'm not saying", "To be clear", "You might think", "A tempting approach would be". Drop objections and rejected options nobody raised.

**6. Forced triads.** Three items because three feels complete. Use the number the content has.

**7. Repeated sentence openings.** Several sentences in a row starting with the same subject. Merge or vary them.

**8. Dashes.** Do not use em dashes, en dashes, or spaced double hyphens as connectors. Use a period, comma, colon, parentheses, or rewrite. Leave dashes inside code, paths and URLs alone. If the user's own writing sample uses dashes, match its rate.

**9. Stacked qualifiers.** "could potentially", "might arguably", "in some cases it may". Hedge once, and only when the doubt is real.

**10. Hyphens after the noun.** Write "a high-quality report" but "the report is high quality".

**11. Hidden actors.** Prefer active voice when it makes clear who does what.

**12. Stock words.** Delve, pivotal, crucial, robust (figurative), landscape (abstract), tapestry, testament, showcase, underscore, highlight (verb), intricate, meticulous, vibrant, enduring, garner, foster, align with, interplay, additionally.

**13. Inflated significance.** "Marks a pivotal moment", "plays a key role", "lasting legacy", "the future looks bright", stock "challenges and outlook" sections. Keep the fact, drop the importance.

**14. Vague connections.** "Associated with", "linked to", "in connection with". Say what the relationship is.

**15. Tacked-on -ing phrases.** "…, highlighting its importance", "…, ensuring a seamless experience". Cut them unless a source supports the claim.

**16. Sales language.** Nestled, breathtaking, stunning, rich cultural heritage, renowned, must-visit. Say what the thing is.

**17. Borrowed authority.** "Experts argue", "industry reports", lists of prestigious outlets. Name the real source and what it said, or cut it.

**18. Fancy copulas.** "Serves as", "stands as", "boasts", "features", "represents". Use is, are, has.

**19. Bold as decoration.** No bold labels on list items, no bolding of random terms. Turn labeled lists into a sentence when the labels add nothing.

**20. Decorative headings.** Sentence case. No emojis or arrows in headings or lists. No horizontal rules between every section. No top heading that repeats the title.

**21. Curly quotes** where straight quotes are expected.

**22. Chatbot residue.** "Great question!", "Certainly!", "I hope this helps", "Let me know if you'd like me to…", "Would you like me to…?". Remove the wrapper, keep the content.

**23. Knowledge-limit disclaimers and guesses.** "As of my last update", "details are not publicly available", followed by a plausible guess. Say what the source does not show, or cut the sentence.

**24. A heading repeated in the first line under it.**

**25. Writing about the document.** "This section covers", "the table below compares", "anything unconfirmed is flagged rather than guessed". Talk about the subject. Mention an old version only in change logs and migration notes.

**26. Re-explaining what the reader knows.** In a reply, lead with the decision. Keep only the reasoning that could change the reader's mind, usually one fact they lack plus any link they need.

## Voice

If the user gives a writing sample, match its sentence length, word choice, punctuation and transitions. The sample overrides the rules above, including the dash rule.

Without a sample, match the kind of text. Conversational replies are short and plain. Essays and posts keep the writer's opinions, uncertainty and asides. Technical, legal and reference text stays neutral and exact.

Informal text such as chat messages, rants and angry reviews is often human already. Leave lowercase, fragments and abbreviations alone, and keep the writer's anger at full strength.

## Keep what makes writing human

Specific odd details, mixed feelings, era-specific references, a first-person choice the writer can explain, and genuine asides or self-corrections. Do not sand these off.

## Rewriting existing text

1. Read the whole text and mark every pattern, strongest first. Check paragraph shape too: a contrast split across two sentences or the same closer after every section is the same tell at larger scale.
2. Rewrite so each point is stated directly. Keep every fact, name, number, date, quote and claim. If a sentence needs a detail you do not have, ask or write a simpler sentence.
3. Check the draft for dropped or changed facts. Then check again for the tells that most often survive: contrasts, closers, triads, dashes and bold labels.
4. For pasted text, return the rewrite and a short note of any tells you left on purpose. For a named file, change prose only and leave code blocks, commands, paths, metadata and link targets untouched.

## When not to act

A person can use any one of these patterns on purpose. Leave a phrase alone inside a quotation, a title or a proper name. Plain salutations, sign-offs and a simple "let me know" predate chatbots. Text from before November 2022 is not AI writing. Several tells together are a stronger signal than one, so be careful with weak ones like a single dash, a curly quote, or a hedge.

## Source

Wikipedia, "Signs of AI writing" (https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing), maintained by WikiProject AI Cleanup.
