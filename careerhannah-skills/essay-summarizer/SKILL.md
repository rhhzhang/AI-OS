---
name: essay-summarizer
description: Summarize essays or blog posts using a standard output format. Trigger whenever I submit a prompt that only includes a link to an essay, such as from Substack, X, or a personal blog.
---

# Essay Summarizer

## When to trigger

Activate whenever the user submits a prompt that is only a link (or a link with minimal context like "summarize this") pointing to an essay, blog post, Substack, X/Twitter thread, or personal blog.

## Instructions

Fetch the essay using WebFetch. Provide a summary in the following format. Keep it as brief and easy to read as possible, without losing important details.

### Output format

**Author:** 1-2 sentences on the author. Their name, background, and relevant expertise. Look them up on the web, LinkedIn, or other sources as needed.

**Thesis:** 1-2 sentences on the core thesis of the essay. What is the key point it is trying to make?

**Supporting Evidence:** Bullets with the key rationale or supporting evidence for the thesis. Be specific wherever possible, including data or quotes.

**Counter Argument:** 1-2 sentences on the best counter to the thesis of this essay. Research anything you can find that contradicts the argument in the essay in order to write this section.

**References:** A bulleted list of any relevant links for further research. This can include backup for evidence cited in the essay, other relevant works by the author, related pieces from other authors, or support for the counter argument.
