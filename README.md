A free, interactive study guide for AI271 Programming for Artificial Intelligence at SST, UMT.
.

Why I Made This
Exams sneak up on everyone. I made this so that no one in our batch has to sit in the exam hall staring blankly at a slicing question or mixing up loc and iloc just because they didn't have time to go through everything the night before.
This guide is everything you need — condensed, visual, and actually easy to read — so you can open it an hour before the paper and walk in feeling prepared. No scrolling through long notebooks. No hunting for that one line of code you half-remember. It's all here.

What's Inside
📖 Study Guide
Clean, topic-by-topic notes with colour-coded code examples and a key tip on every single section. Covers:
NotebookTopics1Variables, data types, type casting, operators, strings, f-strings, input/output2if/elif/else, for loops, range(), while, break & continue, functions, scope, lambda3Lists (indexing, slicing, methods, comprehensions), tuples, dictionaries, sets4NumPy arrays, 2D arrays, reshape, indexing & slicing, boolean & fancy indexing, math & stats5Pandas Series, DataFrames, column/row selection, .loc vs .iloc, boolean filtering, operations
⚡ Cheat Sheet
Every important method, operator, and pattern in one place — no fluff, just the stuff you actually need. Perfect when you want to quickly remind yourself of syntax without re-reading an entire section.
🧠 Practice Quiz
20 randomised multiple-choice questions covering all the concepts that love to show up in exams. Every wrong answer comes with an explanation so you actually understand where you went wrong, not just what the right answer was.

How It Helps You Actually Remember
Reading notes once doesn't make things stick. This guide is built around a simple loop:

Read the concept with a real code example right next to it
See the key note that tells you exactly what trips people up
Test yourself on the quiz immediately after
Understand why you got it wrong if you did

That cycle — read, see the trap, test, understand — is what moves something from "I've seen this before" to "I actually know this." Even 45 minutes with this guide before an exam makes a real difference.

The Things That Catch Everyone Out
These are the concepts where most marks get lost — pay extra attention:

Slicing stop is exclusive — lst[1:4] gives index 1, 2, 3. Never 4.
[::-1] reverses any list, string, or array instantly
loc vs iloc — loc uses labels with inclusive stop; iloc uses integer positions with exclusive stop. They look the same with a default index but behave differently.
NumPy 2D indexing — m[row, col] with a comma. m[:, 0] is the entire first column.
axis=0 vs axis=1 — axis=0 goes down rows (result is per column); axis=1 goes across columns (result is per row)
Pandas boolean filtering — always use & and | instead of and/or, and wrap every condition in parentheses
