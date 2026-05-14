# Product Builder

This is how I've been building new things with LLMs. I start with this structure here. There is a simple [Agents](AGENTS.md) file that points to the main [Shaping Approach](shaping/README.md). There isn't much infrastructure here — only about 500 words in total (outside of this README). I've found the less infrastructure I give to LLMs, the better they work for me.

## The Idea

I fill in my [Idea](shaping/Idea.md), and then I start figuring it out. **I call this process _shaping_** — an idea I learned from [Ryan Singer](https://www.ryansinger.co/). Ryan's process is extremely rigorous and specific — mine is extremely lightweight and fungible. [Here is an example Idea](https://github.com/kneath/knyle-share/blob/main/shaping/Idea.md) I wrote for one of my projects.

I ask the LLMs: what do you think of my idea? I have a discussion and try to flesh out the unknowns. What's possible? What have I missed? Does this make sense? If I want to take a deep dive into a question (e.g. what APIs exist for this data type?), I ask the agent to create a [report](reports/README.md).

## Design Priorities

Then I come up with some [Design Priorities](shaping/design-priorities.md). What are the guiding priciples of this product? Does it need to be fast and optimized for slow internet connections? Built for an expert audience? Always have a light/dark mode? Designed to scale to hundreds of millions of users?

## The Stack

Then I ask the LLMs to guide me on a [Stack](shaping/stack.md) for the product. You can tell it what your [technical preferences](https://github.com/kneath/knyle-share/blob/main/TECHNICAL_PREFERENCES.md) are, and with the context of the idea and the design priorities, it can suggest a good stack.

## The Plan

Finally: [The Plan](shaping/the-plan.md). With an idea, design priorities, and stack, the LLM can now make a plan to build the product. 

## Build It

I like to start with a few prototypes, they help shape the plan in a more useful direction. **LLMs are little context goblins.** This document structure and the prototypes — they serve as context fuel for it to build the real thing.
