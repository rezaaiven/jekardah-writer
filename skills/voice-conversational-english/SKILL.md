---
name: voice-conversational-english
description: Produce, adapt, or review conversational professional English for LinkedIn articles, LinkedIn posts, video scripts, and long-form blog or newsletter writing, keeping the register human and direct without corporate hedging, forced slang, or factual drift.
---

# Voice Conversational English

## Overview

Use this skill to write or review English prose that is professional in substance but conversational in delivery: long-form articles, the short social posts that promote them, and spoken scripts for short or long video. It is the English sibling of `tutur-jabodetabek-urban`: a style layer only, never a license to change meaning.

This is a register skill, not a personality transplant. It adjusts diction, rhythm, address, and cadence; it preserves the author's stance, facts, structure, and certainty ceiling.

## Search And Discovery

Relevant searches: conversational English, humanize English article, LinkedIn article voice, LinkedIn post tone, thought leadership voice, casual professional English, video script voice, spoken-word script, newsletter voice, plain English rewrite.

## Supported registers

1. **`linkedin-article`** (also fits blog/newsletter long-form)
   - Written to be read, at length. First and second person. Contractions. Paragraphs that vary in length, including one-sentence paragraphs used sparingly for emphasis.
   - Thought-leadership drafts: keep a visible point of view; an opinion stated as an opinion beats a hedge. Technical drafts: keep established technical terms exact; be conversational around the terminology, never inside it.
2. **`linkedin-post`** (short companion post for an article or standalone)
   - Very short lines, front-loaded first sentence (it is the preview text), one idea per post, white space is deliberate. A pointer to the article is a CTA whose intent must be preserved, not decorated.
3. **`video-script`** (short-form social or long-form YouTube)
   - Written to be spoken. Read-aloud rhythm: shorter clauses, no nested subordinate clauses, no parentheticals the voice cannot perform. Numbers and names spelled the way they are said. Mark beats or pauses only if the user asks for production notes.
4. **`neutral professional`** (default when no register is named)
   - Clean conversational English that works in docs, emails, and general web writing without platform-specific shape.

## Workflow

1. Identify the target register above. If the requested register is not one of these, report it as unsupported instead of improvising.
2. Identify audience and stakes. Peer practitioners tolerate more informality than prospects or executives; adjust warmth, not clarity.
3. Adapt with restraint.
   - Prefer the words the author would say out loud: contractions, active verbs, concrete nouns, direct address.
   - Remove corporate hedging ("it's worth noting", "arguably", "in today's landscape", "leverage", "utilize") unless the hedge is a genuine certainty limit — never delete a calibrated qualifier that protects accuracy.
   - Do not perform casualness: no forced slang, no emoji unless the source or user already uses them, no exclamation marks doing enthusiasm's job.
   - Keep technical terms, product names, numbers, quotes, and attributions exactly as given.
4. For spoken registers, read the result aloud mentally; any sentence you would restart mid-breath gets split.

## Output Style

- For direct requests, return the adapted text first.
- For review, flag stiff constructions, hedging, robotic cadence, performed casualness, and register mismatch for the stated platform.
- For variants, label `linkedin-article`, `linkedin-post`, `video-script`, or `neutral professional`.

## Composition contract

When orchestrated by `review-rewrite-content`, this skill owns diction, rhythm, sentence shape, address (I/you/we), and platform cadence for supported English registers. It must not change defensible propositions, evidence or certainty ceiling, attribution, quoted meaning, selected hook angle, payoff obligation, CTA intent, headings, links, lists, or structure. It may not raise certainty or add claims to sound confident.

## Resources

- `references/style-guide.md`: per-register rules with use/avoid lists.
- `references/examples.md`: before/after examples per register.
- `references/usage-patterns.md`: task patterns and review checklist.
