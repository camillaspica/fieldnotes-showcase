<picture>
  <source media="(prefers-color-scheme: dark)" srcset="images/logo-reversed.png">
  <img src="images/logo.png" alt="fieldnotes" width="330">
</picture>

**An AI research assistant for social listening.** Ask what people are saying about a topic. Fieldnotes
helps you design the study, finds and saves the conversation, codes every post with AI, and writes a
research summary with content recommendations. It can then keep watching the question for new posts.

> **[Try the demo → fieldnotes.streamlit.app](https://fieldnotes.streamlit.app)**. The demo uses made-up posts,
> and live searches and AI are switched off. If it has been asleep, press the wake-up button and give it
> about a minute. The source code is private.

![My studies](images/home.png)

## What it does

| Step | What happens |
| --- | --- |
| **Design** | Type a rough question. AI drafts a research design: a precise question, the decision it informs, whose conversations count, the period, places and languages, and the kind of study. You check it and approve it. |
| **Refine** | AI suggests sharper research questions and search terms within the design; you approve them. |
| **Sources** | Search YouTube, Bluesky and the web, collect from RSS and Atom feeds, Hacker News and Stack Exchange, or import exports from listening tools such as Brandwatch, Talkwalker, Meltwater and Sprout Social. |
| **Overview** | A free first look: volume over time, platforms, most-used words, example posts, and whether the data fits your design. |
| **Codebook** | AI drafts a codebook (themes, sentiment, relevance) that follows the design; you check and approve it. |
| **Code** | Every post is coded by AI against the approved codebook, with a cost estimate first and live progress. |
| **Review** | Check the posts the AI was unsure about, plus a spot check, one at a time. |
| **Report** | A research summary with findings, what it means for your decision, audience needs and content ideas, downloadable as Word, PDF or Markdown. |

## Start with a research design

Fieldnotes turns a rough question into a study you can defend. It marks what it assumed so you can check it,
asks a few quick questions to sharpen the draft, and saves your work as you go. Choose from four kinds of
study: **exploratory**, **descriptive**, **comparative** (two or more groups, side by side) and
**longitudinal** (change over time). Research templates and advanced designs are there when you need them.
Searching, coding and the report all follow the approved design, and if the design changes after coding,
every later step says so.

![Research design](images/design.png)

<img src="images/phone-design.png" alt="Research design on a phone" width="320">

## More places to listen

Alongside YouTube, Bluesky and web search, Fieldnotes can collect from public RSS and Atom feeds, Hacker
News and Stack Exchange. It suggests feeds that match your research question. Every collection is planned
and approved first, and each source states exactly what it can and can't filter, so nothing is implied that
didn't happen.

![Feed recommendations](images/sources.png)

## See the data before you spend anything

![Overview](images/overview.png)

## A research summary you can trust

The app calculates every figure and picks every quotation from the coded data itself. The AI writes only
the prose: the headline, findings, what this means for your decision, what the audience wants to know and
what content to make. Any figure the AI states that the data doesn't back up is flagged.

![Research summary](images/report-summary.png)

Comparative studies show each group side by side, including posts that belong to more than one group.

![Content recommendations and groups compared](images/content-ideas.png)

Longitudinal studies chart how often each theme comes up, month by month.

![Change over time](images/change-over-time.png)

## Keeps watching the question

Turn on watching and Fieldnotes checks your sources on a schedule. Each check saves only posts that are
new to the study, codes them with the approved codebook, and shows what changed. Nothing runs, and nothing
is spent, until you allow it.

![Keep watching this question](images/watching.png)

## People stay in charge

The AI's codes are checked where it was unsure, and every check is recorded. The report says exactly how
much was reviewed by a person.

![Review](images/review.png)

## Tools for detailed analysis

For deeper qualitative work, an optional analysis workspace adds passage coding, themes with the evidence
for and against them, a framework matrix, a hypotheses notebook, research cases and team coding with
agreement scores. Each keeps its own review steps and audit trail.

![Analysis workspace](images/workspace.png)

## Works on a phone

<img src="images/phone-report.png" alt="Research summary on a phone" width="320">

## Built with

Python and Streamlit. Coding and summaries use OpenAI, with strict structured outputs checked against
the codebook. Sources come from the YouTube Data API, Bluesky, Brave Search, public RSS and Atom feeds,
Hacker News and Stack Exchange. Data is stored in SQLite, with a compressed safe copy in Neon Postgres.
Finished reports can also be published, after you approve them, in a structured format that other tools
can read. Fieldnotes runs on Replit; the demo runs on Streamlit Community Cloud.

## About this repository

This repository only showcases Fieldnotes. It contains no source code, and the screenshots show
made-up example data. © 2026 camillaspica. All rights reserved.
