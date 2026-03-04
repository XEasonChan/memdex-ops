---
# ─── Page Metadata ────────────────────────────────────────────────────────────
title: "How to Transfer Memory from ChatGPT to Claude (2026 Guide)"
slug: "how-to-transfer-memory-from-chatgpt-to-claude"
description: "Step-by-step guide to importing your ChatGPT memory into Claude using Anthropic's official tool. Learn what transfers, what doesn't, and how to keep your AI memory portable long-term."
canonical: "https://memdex.ai/blog/how-to-transfer-memory-from-chatgpt-to-claude"

# ─── Open Graph ───────────────────────────────────────────────────────────────
og_title: "How to Transfer Memory from ChatGPT to Claude (2026)"
og_description: "Anthropic launched an official memory import tool in March 2026. Here's exactly how it works, what it transfers, and what it misses."
og_image: "https://memdex.ai/blog/og-transfer-memory.png"
og_type: "article"
og_url: "https://memdex.ai/blog/how-to-transfer-memory-from-chatgpt-to-claude"

# ─── Twitter Card ─────────────────────────────────────────────────────────────
twitter_card: "summary_large_image"
twitter_title: "How to Transfer Memory from ChatGPT to Claude"
twitter_description: "Official tool, step-by-step. Takes 5 minutes. Here's what it actually migrates — and the gap it leaves."
twitter_image: "https://memdex.ai/blog/og-transfer-memory.png"
twitter_site: "@memdex_ai"

# ─── Article Metadata ─────────────────────────────────────────────────────────
author: "Memdex Team"
published_date: "2026-03-04"
modified_date: "2026-03-04"
category: "AI Tools"
tags:
  - ChatGPT
  - Claude
  - AI memory
  - memory migration
  - Anthropic
  - AI portability
reading_time: "5 min"

# ─── SEO ──────────────────────────────────────────────────────────────────────
robots: "index, follow"
keywords: "transfer memory ChatGPT Claude, import ChatGPT memory Claude, switch ChatGPT to Claude, claude.com/import-memory, ChatGPT memory migration 2026, AI memory portability"
---

<!--
  ┌─────────────────────────────────────────────────────────┐
  │  JSON-LD Structured Data — paste into <head> of page   │
  └─────────────────────────────────────────────────────────┘

<script type="application/ld+json">
[
  {
    "@context": "https://schema.org",
    "@type": "HowTo",
    "name": "How to Transfer Memory from ChatGPT to Claude",
    "description": "Step-by-step guide to importing your ChatGPT memory into Claude using Anthropic's official import tool at claude.com/import-memory.",
    "totalTime": "PT5M",
    "estimatedCost": { "@type": "MonetaryAmount", "currency": "USD", "value": "0" },
    "tool": [
      { "@type": "HowToTool", "name": "Claude account (free or paid)" },
      { "@type": "HowToTool", "name": "ChatGPT account with Memory enabled" }
    ],
    "step": [
      {
        "@type": "HowToStep",
        "position": 1,
        "name": "Open the Claude import page",
        "text": "Go to claude.com/import-memory in your browser. You'll see a pre-written export prompt ready to copy.",
        "url": "https://memdex.ai/blog/how-to-transfer-memory-from-chatgpt-to-claude#step-1"
      },
      {
        "@type": "HowToStep",
        "position": 2,
        "name": "Copy the export prompt",
        "text": "Click 'Copy prompt' on the Claude import page. This prompt instructs ChatGPT to generate a structured summary of everything it has saved about you.",
        "url": "https://memdex.ai/blog/how-to-transfer-memory-from-chatgpt-to-claude#step-2"
      },
      {
        "@type": "HowToStep",
        "position": 3,
        "name": "Paste the prompt into ChatGPT",
        "text": "Open a new ChatGPT conversation, paste the copied prompt, and send it. ChatGPT will respond with a structured block of your saved memories.",
        "url": "https://memdex.ai/blog/how-to-transfer-memory-from-chatgpt-to-claude#step-3"
      },
      {
        "@type": "HowToStep",
        "position": 4,
        "name": "Copy ChatGPT's output",
        "text": "Copy the entire structured memory block from ChatGPT's response.",
        "url": "https://memdex.ai/blog/how-to-transfer-memory-from-chatgpt-to-claude#step-4"
      },
      {
        "@type": "HowToStep",
        "position": 5,
        "name": "Paste into Claude's memory settings",
        "text": "In Claude, go to Settings > Capabilities > Memory, then paste the block into the import field and confirm.",
        "url": "https://memdex.ai/blog/how-to-transfer-memory-from-chatgpt-to-claude#step-5"
      },
      {
        "@type": "HowToStep",
        "position": 6,
        "name": "Wait for processing",
        "text": "Claude processes memory imports in daily cycles. Your imported memories will appear within 24 hours. Review them in Settings > Memory to verify accuracy.",
        "url": "https://memdex.ai/blog/how-to-transfer-memory-from-chatgpt-to-claude#step-6"
      }
    ]
  },
  {
    "@context": "https://schema.org",
    "@type": "Article",
    "headline": "How to Transfer Memory from ChatGPT to Claude (2026 Guide)",
    "description": "Step-by-step guide to importing your ChatGPT memory into Claude using Anthropic's official import tool.",
    "image": "https://memdex.ai/blog/og-transfer-memory.png",
    "author": { "@type": "Organization", "name": "Memdex", "url": "https://memdex.ai" },
    "publisher": {
      "@type": "Organization",
      "name": "Memdex",
      "logo": { "@type": "ImageObject", "url": "https://memdex.ai/logo.png" }
    },
    "datePublished": "2026-03-04",
    "dateModified": "2026-03-04",
    "mainEntityOfPage": "https://memdex.ai/blog/how-to-transfer-memory-from-chatgpt-to-claude"
  },
  {
    "@context": "https://schema.org",
    "@type": "FAQPage",
    "mainEntity": [
      {
        "@type": "Question",
        "name": "Does the ChatGPT to Claude memory transfer work for free users?",
        "acceptedAnswer": {
          "@type": "Answer",
          "text": "Yes. Anthropic made Memory free for all Claude users when it launched the import tool in March 2026. You do not need a Claude Pro subscription."
        }
      },
      {
        "@type": "Question",
        "name": "How long does it take to transfer memory from ChatGPT to Claude?",
        "acceptedAnswer": {
          "@type": "Answer",
          "text": "The copy-paste process takes under 5 minutes. However, Claude processes imported memories in daily cycles, so the context may take up to 24 hours to fully appear in your conversations."
        }
      },
      {
        "@type": "Question",
        "name": "Does the transfer include my full ChatGPT conversation history?",
        "acceptedAnswer": {
          "@type": "Answer",
          "text": "No. The tool only imports stored memory snippets — the preferences and facts ChatGPT had explicitly saved about you. Full conversation history does not transfer."
        }
      },
      {
        "@type": "Question",
        "name": "Why did ChatGPT export almost nothing when I used the prompt?",
        "acceptedAnswer": {
          "@type": "Answer",
          "text": "ChatGPT appears to limit how much it exports through this workflow. If your ChatGPT Memory feature has saved little, or if privacy settings restrict exports, the output may be minimal. Check your ChatGPT Memory settings at chatgpt.com/settings/memory to see what has actually been saved."
        }
      },
      {
        "@type": "Question",
        "name": "Is the transferred memory permanent in Claude?",
        "acceptedAnswer": {
          "@type": "Answer",
          "text": "It persists in Claude's memory until you delete it. However, the import is a one-time snapshot — it does not stay in sync with ChatGPT. Any new context you build in ChatGPT after the import will not automatically update in Claude."
        }
      }
    ]
  }
]
</script>
-->

---

# How to Transfer Memory from ChatGPT to Claude (2026)

*Updated March 4, 2026 · 5 min read*

---

In early March 2026, millions of users started switching from ChatGPT to Claude — driven by OpenAI's Pentagon deal and policy controversies. Demand was so high that Claude.ai crashed twice in 24 hours. Anthropic called it "unprecedented demand."

Whether you're switching permanently or just testing Claude, the first question is the same: **do you have to start over?**

The short answer: not entirely. Anthropic launched an official memory import tool on March 2, 2026 that lets you bring your saved ChatGPT preferences into Claude in about five minutes. Here's exactly how to use it — and what to expect.

---

## What You'll Need

- A Claude account (free works — Memory is now free for all users)
- A ChatGPT account with Memory enabled
- About 5 minutes

---

## Step-by-Step: Transfer Your Memory

### Step 1 — Open Claude's import page {#step-1}

Go to **[claude.com/import-memory](https://claude.com/import-memory)**. You'll see a pre-written export prompt and an import text field.

### Step 2 — Copy the export prompt {#step-2}

Click **Copy prompt**. This is a special instruction that tells ChatGPT (or Gemini, Copilot, etc.) to generate a structured summary of everything it has saved about you.

### Step 3 — Paste into ChatGPT {#step-3}

Open a **new ChatGPT conversation**, paste the prompt, and send it. ChatGPT will respond with a formatted block containing your saved memories — your name, job, preferences, writing style, recurring projects, and any instructions you've given it over time.

> **Tip:** If ChatGPT returns very little, check your memory settings at **chatgpt.com → Settings → Personalization → Memory**. If Memory was disabled or lightly used, there may not be much to export.

### Step 4 — Copy ChatGPT's output {#step-4}

Select and copy the entire memory block from ChatGPT's response.

### Step 5 — Paste into Claude {#step-5}

Back on **claude.com/import-memory**, paste the block into the import field and click **Import**. Alternatively: **Claude Settings → Capabilities → Memory → Import**.

### Step 6 — Wait up to 24 hours {#step-6}

Claude processes memory updates in daily synthesis cycles, not in real time. Your imported context will take effect within 24 hours. Once it does, go to **Settings → Memory** to review what was imported — Anthropic recommends verifying accuracy before relying on it.

---

## What Gets Transferred

| Transfers | Doesn't Transfer |
|-----------|-----------------|
| Tone and format preferences | Full conversation history |
| Your name, job, industry | File attachments |
| Project names and goals | Custom GPT configurations |
| Recurring topics you've discussed | Context built after the import date |
| "Always / never" instructions you gave | Anything ChatGPT didn't save to Memory |

The tool moves your **saved memory snippets** — the explicit facts and preferences ChatGPT had noted. It does not move the implicit understanding that built up through months of actual conversation. That accumulated context stays on ChatGPT.

---

## Known Limitations

**ChatGPT may export very little.** Multiple users reported that the export prompt returned almost nothing from ChatGPT, even after months of use. ChatGPT appears to limit what it exports through this workflow.

**24-hour processing delay.** The import isn't instant. Plan accordingly if you need your context available immediately.

**It's a one-time snapshot.** There's no ongoing sync. New context you build in ChatGPT after the import won't automatically carry over to Claude.

**Claude may not fully apply imported memories.** Anthropic marks this feature as experimental. Some users found that Claude didn't consistently reflect imported preferences in conversations.

**Work-focused filter.** Claude's memory is designed for professional context. Imported personal details unrelated to work may be silently dropped.

---

## Frequently Asked Questions

**Is this free?**
Yes. Anthropic made Memory free for all Claude users on March 2, 2026, alongside launching the import tool.

**Does it work with Gemini or Copilot too?**
Yes — the same workflow works with any AI that has a memory feature. The export prompt is designed to be pasted into any assistant.

**What if I want to undo the import?**
Go to **Claude Settings → Memory** and delete the imported entries individually.

**Will my context stay current after I import?**
No. The import is a one-time migration. Any new context you build on ChatGPT after importing won't automatically appear in Claude.

---

## The Gap the Official Tool Leaves

The import tool solves the surface-level problem: your explicitly saved preferences travel with you. But most of the productive value you've built with ChatGPT isn't in the saved snippets — it's in the *continuous context* that accumulated through actual usage. How you frame problems. What level of detail you expect. The shorthand your AI learned from working with you.

That context doesn't export. It lives in conversation history.

For professionals who use AI daily, this matters every time a better model is released, every time a platform goes down (like Claude did on March 2-3), and especially when you change jobs and lose access to a company AI account entirely.

**[Memdex](https://memdex.ai)** is a browser extension that takes a different approach: rather than migrating at the end, it captures your AI collaboration context continuously — running in the background while you use ChatGPT, Claude, or Gemini, storing it in your personal account, not the platform's. When you switch models or change jobs, your full context travels with you. No import prompt required.

---

*[Install the Memdex browser extension →](https://memdex.ai)
Available for Chrome, Edge, and Firefox.*
