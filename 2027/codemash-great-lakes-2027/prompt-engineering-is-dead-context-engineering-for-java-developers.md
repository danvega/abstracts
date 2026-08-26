# Prompt Engineering Is Dead: Context Engineering for Java Developers

**Format:** Session

## Abstract

We spent the last few years obsessing over prompts: finding the perfect wording, adding magic phrases, tweaking instructions until the model behaved the way we wanted. But models got better, and the real bottleneck showed itself. The quality of an AI application depends not just on what you ask it, but on everything you put around the question.

Every request has a context budget. System instructions, conversation history, retrieved knowledge, tool definitions, and the user's question all compete for space and attention. Put too much in and costs climb, tool selection gets worse, and important information gets lost. Leave the wrong thing out and the model can't possibly give you the right answer. It's why your chatbot works in the demo and falls apart at turn forty.

In this live-coding session we'll build a Spring AI application from the context window out. We'll decide what belongs in the system prompt and what conversation memory should keep or forget. Then we'll retrieve only the knowledge needed for the current request and see what happens when dozens of tool schemas compete for the model's attention. We'll use Spring AI's Advisors and progressive tool discovery to assemble the right context at the right time instead of sending everything every time.

We'll flip the problem around and control what comes back using structured output, schema validation, and self-correction.

You'll leave with a practical mental model for building AI applications: what goes into the context, when it gets there, what stays out, and how to turn the model's response into something your Java application can actually trust.
