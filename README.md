# Fieldnotes

**An AI research assistant for social listening.** Ask what people are saying about a topic. Fieldnotes
finds and saves the conversation, codes every post with AI, and writes a research summary with content
recommendations. It can then keep watching the question for new posts.

> **[Try the demo → fieldnotes.streamlit.app](https://fieldnotes.streamlit.app)**. The demo uses made-up posts,
> and live searches and AI are switched off. If it has been asleep, press the wake-up button and give it
> about a minute. The source code is private.

![My studies](images/home.png)

## What it does

| Step | What happens |
| --- | --- |
| **Ask** | Type a research question in your own words. |
| **Refine** | AI suggests sharper research questions and search terms; you approve them. |
| **Sources** | Search YouTube, Bluesky and the web, or import exports from listening tools such as Brandwatch, Talkwalker, Meltwater and Sprout Social. |
| **Overview** | A free first look: volume over time, platforms, most-used words and example posts. |
| **Codebook** | AI drafts a codebook (themes, sentiment, relevance) that you check and approve. |
| **Code** | Every post is coded by AI against the approved codebook, with a cost estimate first and live progress. |
| **Review** | Check the posts the AI was unsure about, plus a spot check, one at a time. |
| **Report** | A research summary with findings, audience needs and content ideas, downloadable as Word, PDF or Markdown. |

## A research summary you can trust

The app calculates every figure and picks every quotation from the coded data itself. The AI writes only
the prose: the headline, findings, what the audience wants to know and what content to make. Any figure
the AI states that the data doesn't back up is flagged.

![Research summary](images/report-summary.png)

![Content recommendations](images/content-ideas.png)

## Keeps watching the question

Turn on watching and Fieldnotes checks your sources on a schedule. Each check saves only posts that are
new to the study, codes them with the approved codebook, and shows what changed, marking themes that
weren't in the last summary.

![Keep watching this question](images/watching.png)

## See the data before you spend anything

![Overview](images/overview.png)

## People stay in charge

The AI's codes are checked where it was unsure, and every check is recorded. The report says exactly how
much was reviewed by a person.

![Review](images/review.png)

## Works on a phone

<img src="images/phone-report.png" alt="Research summary on a phone" width="320">

## Built with

Python and Streamlit. Coding and summaries use OpenAI, with strict structured outputs checked against
the codebook. Sources come from the YouTube Data API, Bluesky and Brave Search. Data is stored in SQLite,
with a compressed safe copy in Neon Postgres. Fieldnotes runs on Replit; the demo runs on Streamlit
Community Cloud.

## About this repository

This repository only showcases Fieldnotes. It contains no source code, and the screenshots show
made-up example data. © 2026 camillaspica. All rights reserved.
