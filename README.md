# Sumiya

Engineering manager at Nike. Eighteen years building backend systems, currently leading Store Integrations.

---

## What I'm building now

**[Neo: An Experiment in Calibrating Agentic Trust](https://sumiya.page/2026/July/neo-an-experiment-in-calibrating-agentic-trust.html)**

An issue-to-production pipeline that labels a GitHub issue, generates and tests a PR, classifies its risk as GREEN/YELLOW/RED, and auto-merges the safe ones while holding risky changes for review.

---

## Things I've shipped

**[AI Intelligence Brief](https://sumiya.page/brief/index.html)**

Keeping up with AI research is a full-time job: arXiv drops every morning, YouTube deep-dives, newsletters, three-hour podcasts. This is a single daily read that cuts across all of it, fully automated. A Python pipeline pulls RSS feeds, YouTube channels, and arXiv each day, runs everything through Gemini 2.5 Flash, and publishes a structured digest to a static site on S3 and CloudFront.

**[CampaignLens](https://sumiya.page/campaign-lens.html)**

An AI agent that audits an email campaign across multiple dimensions, scoring content quality, deliverability risk, compliance, and accessibility. Serverless on AWS: Browser to API Gateway to Lambda, which verifies a Cloudflare Turnstile token before invoking Bedrock and Claude Sonnet. Turnstile keeps bot traffic from running up the inference bill on a public LLM endpoint.

**[OctaneLog](https://github.com/psumiya/octanelog)** *(public hackathon project)*

An iOS app that narrates your drives using the on-device Vision framework plus cloud Gemini. It records continuously, analyzes scenery in real time, and generates narrative summaries of where you've been. Two-model architecture: Gemini Flash for high-frequency video analysis, Gemini Pro for season-long story memory. Raw GPS and generated narratives stay on device.

**[option-insights](https://github.com/psumiya/option-insights)** *(public hackathon project)*

A charting tool for retail options traders. Takes a CSV of option trades and renders charts and graphs for analysis. Static site, no backend, runs entirely in the browser.

**[jcli](https://github.com/psumiya/jcli)**

A CLI tool that lets you invoke utility Java methods from your terminal without needing a JDK or JRE.

**[amazon-or-aws](https://amazonoraws.com)**

An AWS news aggregator and comprehensive product reference, so you can finally stop second-guessing whether it's "Amazon S3" or "AWS S3".

**[jpath](https://sumiya.page/jpath.html)**

A web UI for the Jayway JsonPath implementation. Built when the official site went down after the Heroku free tier was discontinued by Salesforce, and kept alive since, because validating a path expression shouldn't require writing test code. Was picked up by the JsonPath community as a stop-gap back in the day.

---

## TIL

I keep a [running log](https://github.com/psumiya/til) of things I learn as I work. Short-form, no fluff, mostly backend, AWS, and whatever I'm tinkering with.

---

## Day job

- I lead backend engineering at **Nike Stores**, the infrastructure connecting over a thousand retail stores worldwide to Nike's digital ecosystem.
- Previously led a team for the **Nike Communications Platform**, the infrastructure behind every cross-channel consumer communication Nike sends globally across email, push, SMS, and inbox, with tens of millions of messages a day.
- Before Nike, I built features for a public-service Affordable Care Act compliant product deployed in 4 US states.
