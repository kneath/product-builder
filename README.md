# Product Builder

This is how I've been building new things with LLMs. I start with this structure here. I fill in my [idea](shaping/idea.md), and then I start figuring it out. **I call this process _shaping_** — an idea I learned from [Ryan Singer](https://www.ryansinger.co/). Ryan's process is extremely rigorous and specific — mine is extremely lightweight and fungible.

I ask the LLMs: what do you think of my idea? I have a discussion and try to flesh out the unknowns. What's possible? What have I missed? Does this make sense?

Then I come up with some [Design Priorities](shaping/design-priorities.md). What are the guiding priciples of this product? Does it need to be fast and optimized for slow internet connections? Built for an expert audience? Always have a light/dark mode? Designed to scale to hundreds of millions of users?

Then I ask the LLMs to guide me on a [Stack](shaping/stack.md) for the product. You can tell it what your [technical preferences](https://github.com/kneath/knyle-share/blob/main/TECHNICAL_PREFERENCES.md) are, and with the context of the idea and the design priorities, it can suggest a good stack.

Finally: [The Plan](shaping/the-plan.md). With an idea, design priorities, and stack, the LLM can now make a plan to build the product. I like to start with a few prototypes, those tend to help shape the plan in a better direction.
