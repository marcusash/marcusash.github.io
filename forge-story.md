# Forge

## The thing nobody's building for

Everyone's talking about agents. What they'll do. What they'll replace. How fast they're getting. And it's real — the speed is staggering, the capability is expanding weekly, and the tools are genuinely useful in ways they weren't six months ago.

But here's what I keep noticing. I manage 220 designers. I watch them react to every new AI demo. And nobody's anxious about the technology. They're anxious about themselves. About what it means for their craft. About whether the instincts they built over decades still matter. About the gap between reviewing other people's work and actually making something yourself.

That anxiety lives in three places. Your inner world: the thoughts you haven't processed, the stress you carry, the reflection you never make time for. Your communication: the messages you send that don't land, the ideas you can't articulate fast enough, the disconnect between what you think and what comes out. And your tools: the agents and systems you're supposed to be commanding but mostly just react to.

Nobody is building for any of that. We have a thousand ways to make agents smarter. We have zero terminal-native tools that make the humans more grounded while they use them.

## The system

Forge is three concentric circles.

**The inner circle: Inkwell.** Private daily writing. A journaling app that lives in your terminal, encrypts everything locally, and uses 14 years of your own writing to generate prompts that actually know you. Not "what are you grateful for." More like: "In 2013 you wrote about being the first person in the office and the last to leave. You don't believe that anymore. What changed?" One per day. Never repeated. The best part of the app is the part that already knows your story.

**The outer circle: Dispatch.** Voice and text shaped into polished communication. You record your thoughts or type some bullets. AI shapes it into something clear: a status update, a team message, a note to your manager. Voice shapes down (raw and verbose becomes tight). Text shapes up (bullets become prose). Capture first, then pick the format. Because you don't always know what you're writing until you've said it.

**The command layer: Forge.** The agent dashboard. A single terminal view of every agent working across your projects. What shipped overnight, what's blocked, what needs a decision. You type a command and it routes to the right agent. No more opening six separate windows to manage six separate AI teammates.

Each circle serves a different need. Together they're a system that helps you think clearly, communicate effectively, and stay in command of the tools that are supposed to work for you. All terminal-native. All model-driven. All built by a design team that cares about craft in a place nobody expects it.

## How it started

Last Saturday at 9pm I opened a terminal and typed `npm init`. By Sunday morning I had a working app.

I didn't write the code. I talked to 6 AI agents the way I talk to my design team. Clear ownership: every agent knows which files they own. A shared status board everyone reads before starting. Direct feedback with no hedging. And an overnight brief so detailed the team shipped while I slept.

All my instincts about quality, about pace, about when something's almost right, they just worked. And they worked faster than they ever have in a traditional review cycle.

The first thing I built was the inner circle. Inkwell. Because that's where everything starts: with your own thinking. I imported 14 years of journal entries. 352 of them. 210,000 words spanning my career from IC designer to CVP. And then I mined those entries for writing prompts using the same LLMs that power the agents.

The result is a terminal app that doesn't look like a terminal app. Choreographed animations. A breathing pace indicator. 72 achievement badges. Sixel image rendering. Confetti when you hit your word goal. 19 design specs written before a single line of code. 642 tests. 294 commits. Zero words lost.

It's the smallest piece of the Forge vision. But it shipped. And it's the most personal piece, the one that proves the whole idea works. If you can build something this polished in a terminal, with AI agents, using design instincts instead of engineering skills, then the rest of the system is just a matter of time and taste.

## Where we are

Inkwell is real. 642 tests passing. Running in my terminal every morning. The prompts are genuinely good. The kind that make you stop and think before you start typing.

Dispatch has a complete design spec. 960 lines. Seven screens. A voice pipeline using native Node bindings and local Whisper transcription. It's the next thing we build.

Forge command center has a spec too. Four screens. AI-generated overnight summaries. Multi-repo agent management from one terminal. It's the thing that ties everything together.

And separately, because learning is a different kind of personal, we're building Grind. Personalized study tools for my son's Algebra II class. Same agents. Same craft. Different mission. A dad helping his kid the way Detroit treats basketball: seriously, with grit, and with zero excuses.

The tools are ready. The question is whether we give ourselves permission to build something instead of just reviewing what others build.

Your words. Your hands. Go make something.
