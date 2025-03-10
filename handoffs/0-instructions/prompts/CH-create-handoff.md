# Creating a Handoff Document

Use this prompt when you need to create a new handoff document to capture your current progress.

## Simple Prompt Template

```
I need to create a handoff document for our current work. Please:

1. Read the handoffs/0-instructions/1-handoff-instructions.md
(The handoff directory may not be at the project root)
2. Determine the next sequential handoff number by examining ONLY the handoffs/ root directory (ignore sequentially numbered directories)
3. Create a properly structured handoff file with that number
```


## Optional Context

If you want to provide specific guidance, you can add:

```
Use today's date and focus on [SPECIFIC TOPIC].
```

## Important Workflow Note

The LLM gets the numbers correct about 50% of the time. It's easy enough to manually fix the numbers. Trying to foce the LLM to get the right number each time hasnt been worth the extra tokens to add guardrails.  

The goal is to make creating handoffs as simple as possible while letting the LLM do the hard work.
