# Style Guide

## linkedin-article

Use:

- first person for experience, second person for the reader's situation,
- contractions ("you're", "it's", "don't"),
- varied paragraph length; an occasional one-sentence paragraph for a turn in the argument,
- concrete verbs and named subjects ("the deploy failed" not "issues were encountered"),
- a stated opinion where the draft has one ("I think this is the wrong default"),
- exact technical terms; conversational prose around them, not inside them.

Examples:

- "I spent two years telling teams to write more docs. I was solving the wrong problem."
- "Kafka isn't slow here. Your consumer group is rebalancing every 30 seconds, and that's a config choice."

Avoid:

- "In this article, I will..." table-of-contents openers,
- hedging stacks ("it could perhaps be argued that"),
- LinkedIn-guru cadence (every line its own paragraph for a full article),
- deleting a qualifier that marks a real limit of the evidence.

## linkedin-post

Use:

- a first line that works as a standalone preview,
- one idea per post; the article carries the rest,
- short lines and deliberate white space,
- a CTA that names what the reader gets ("The full breakdown is in the article"), keeping the CTA's original intent.

Example:

> We cut our streaming bill 40% without touching throughput.
>
> The fix wasn't clever. It was reading the retention config everyone assumed someone else had set.
>
> Full write-up in the article: what we checked, in order.

Avoid:

- engagement-bait questions bolted onto the end,
- restating the article's every point,
- hashtag walls,
- emoji bullets unless the author already uses them.

## video-script

Use:

- spoken rhythm: clauses a breath long,
- "you" early and often; talk to one viewer,
- verbal signposts instead of visual ones ("here's the part nobody checks"),
- numbers as said aloud ("forty percent", "three things"),
- the hook in the first two lines for short-form.

Example:

> Your Kafka bill doubled and your traffic didn't. Here's where that money actually goes. Three settings. The first one is retention...

Avoid:

- sentences with nested clauses or parentheticals,
- written-English connectors ("furthermore", "aforementioned"),
- reading a paragraph that was shaped for the page,
- hype phrasing the body cannot pay off.

## neutral professional

Use:

- plain, direct English with contractions,
- active voice by default,
- clear meaning over polish.

Example:

> I checked the file. The pricing section still needs a revision, then it's ready to send.
