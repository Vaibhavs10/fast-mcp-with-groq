# Blazingly fast MCP with *Groq* 💥

Hugging Face makes it easy to use powerful AI models without needing to build everything from scratch. Groq is great at running these models super fast, which means your AI applications can respond quickly. The Model Control Protocol (MCP) ties everything together by letting different AI tools work together smoothly. This combination means you can build AI applications that are both powerful and easy to use.

In this post we will take an applied overview of MCP and how you can build some really cool workflows with blazingly fast inference from Groq.

We'll use tiny MCP clients from Hugging Face to showcase what's possible:

1. `@huggingface/tiny-agents` (for TS fans)
2. `huggingface_hub[mcp]` (for python fans)

Let's get started:

Step 1: Clone this repo

```bash
git clone https://github.com/Vaibhavs10/fast-mcp-with-groq && cd fast-mcp-with-groq
```

Step 2 (TS): Try any of the examples

For example you can run the image-gen example like this:

```bash
npx @huggingface/tiny-agents run ./image-gen
```

Step 2 (Python):

```bash
uv pip install "huggingface_hub[mcp]>=0.32.0"
```

```bash
tiny-agents run ./image-gen
```
