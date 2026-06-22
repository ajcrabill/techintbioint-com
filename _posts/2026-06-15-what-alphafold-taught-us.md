---
layout: post
title: "What AlphaFold Actually Taught Us"
date: 2026-06-15
author: AJ Crabill
reading_time: 6
excerpt: "The protein-folding story isn't about AI being impressive. It's about what happens the day after a capability threshold is crossed."
---

The protein-folding problem had resisted solution for fifty years when DeepMind ended it in 2020.

The problem: a protein is a chain of amino acids, and the sequence is encoded in your DNA. But knowing the sequence tells you almost nothing about the protein's shape, and the shape is everything. It determines what the protein does — whether it fights disease or causes it, whether a drug can target it or not. A single protein might fold into one of 10^300 possible configurations. It settles on its actual shape in milliseconds.

For decades, scientists used experimental methods — X-ray crystallography, cryo-electron microscopy — to determine protein structures one at a time. By 2020, after half a century of collective effort, the field had catalogued roughly 170,000 structures. There are more than 200 million known protein sequences. At that pace, complete coverage would have taken centuries.

AlphaFold predicted 200 million structures in two years. The cost per structure dropped from tens of thousands of dollars to nearly zero. The time dropped from months to seconds.

This is the story everyone knows. But I think we're drawing the wrong lessons from it.

## The lesson everyone draws

The popular version of the AlphaFold story is a story about AI capability: look how powerful these systems are, look how fast they learned, look what they can do. It's told as a triumph of machine learning, an impressive demonstration of what's possible.

That framing treats AlphaFold as a proof of concept. See what technology can do. Isn't that remarkable.

But AlphaFold isn't a proof of concept. It's a template. And the lesson isn't about what AI can do in principle — it's about what happens to a domain when a threshold gets crossed.

## What actually happened

Before AlphaFold, structural biology had an internal economy. There was specialized expertise (mastery of crystallography techniques), expensive equipment (synchrotrons, cryo-EM machines), long timelines, and a career track built around incrementally adding to the database of known structures.

After AlphaFold, that economy was restructured. The bottleneck shifted. Mastery of crystallography didn't disappear from value, but it stopped being the limiting factor in answering most questions about protein structure. The new bottleneck is knowing how to use AlphaFold's predictions intelligently — how to identify where they're likely to be wrong, how to design experiments that test and extend them, how to ask the next question that the system can't answer.

The structural biologists who thrived were the ones who moved toward the new bottleneck. The ones who doubled down on the old expertise found the field had partly moved on without them.

> The AlphaFold transition didn't happen over decades. It happened in a research cycle or two. There was no slow fade that let everyone adjust — there was a threshold crossing, and then the economics of the domain were different.

This is the template. Not "AI gradually improves until it's competitive." A specific capability crosses a threshold, the economics of a domain reorganize, and the people in that domain have a choice to make.

## Where is your AlphaFold?

The protein-folding case is unusually clean — a precise problem, a quantitative benchmark, a measurable before and after. Most domain shifts are messier. They happen unevenly, with contested timelines and unclear winners.

But the same basic structure is present in a growing number of fields.

Legal document review: already past the threshold in most e-discovery applications. The billable hour for junior associate document review is under pressure in ways that will not reverse.

Radiology: AI systems now match or outperform radiologists on specific diagnostic tasks — detecting certain cancers, flagging anomalies, screening chest X-rays. The transition is slower because medical credentialing is slower, but the threshold has been crossed in several subdomains.

Code generation: the threshold crossed somewhere around 2024. What changed wasn't that AI could write perfect code — it can't. What changed was that the bottleneck in many software tasks stopped being "can someone write this code" and became "can someone specify clearly what code to write and then verify the output."

Financial analysis: first-pass analysis, earnings summaries, market screening. The threshold crossed at the entry level of the job years ago. The firms that didn't adjust have higher costs for work that's now commoditized.

The uncomfortable question isn't whether AlphaFold-scale shifts are coming to your field. They're already here in some fields and visibly approaching in others. The question is: what are you currently doing that is, in five years, going to be on the other side of a threshold crossing?

## What this is not

This is not an argument that the work disappears. The structural biologists aren't unemployed. The junior associates aren't unemployed. The radiologists aren't unemployed.

This is an argument that the work shifts — and the people who thrive in the shift are not the ones who wait to see what happens. They're the ones who ask, in advance, what the new bottleneck will be, and start moving toward it.

The AlphaFold researchers didn't fold proteins themselves. They understood machine learning, and they understood how to frame the problem so a system could learn the patterns. The structural biologists using AlphaFold today don't need to master crystallography. They need to know how to interrogate a prediction — where to trust it, where to push back, what question to ask next.

That's a different skill set. It requires understanding the old domain well enough to know when the system's answer doesn't make biological sense. It requires knowing what the system was trained on and where its training is likely to have gaps.

The people who have this are not the ones who abandoned their domain expertise. They're the ones who added a new layer on top of it: an understanding of what the tool can and can't do, and the judgment to close the gap.

That's what a threshold crossing actually demands. And it demands it faster than most institutions update.
