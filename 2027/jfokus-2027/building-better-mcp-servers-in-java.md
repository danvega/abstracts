# Building Better MCP Servers in Java

**Format:** Session

## Abstract

Building an MCP server is easy. Building one that is useful, secure, and easy for an AI model to understand is much harder.

We will start with a quick introduction to the Model Context Protocol. What is an MCP server? What is it not? How does MCP compare to agent skills, and why do people confuse them? When should you use MCP instead of a skill, a normal API, or a direct integration?

From there we will build an MCP server in Java with Spring AI and connect it to real clients like Claude and your IDE. Then comes the interesting part: what separates a good MCP server from a working one. We will look at tool names and descriptions, parameter design, response size, tool selection, and progressive tool discovery. Finally, we will cover security, including how to control access to your server and the tools it exposes.

You will leave knowing how to build and secure an MCP server in Java, how to design tools that models can use reliably, and how to decide between MCP, skills, or neither for your application.
