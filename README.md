# Sumiya

Engineering leader who builds. 18 years in building and running software systems.

---

## What I'm building now

**[Neo: An Experiment in Calibrating Agentic Trust](https://sumiya.page/2026/July/neo-an-experiment-in-calibrating-agentic-trust.html)**

I built Neo, an issue-to-production pipeline that labels a GitHub issue, generates and tests a PR, classifies its risk as GREEN/YELLOW/RED, and auto-merges the safe ones while holding risky changes for review.

**[AI Intelligence Brief](https://sumiya.page/brief/index.html)**

Keeping up with AI research is a full-time job. Papers drop on arXiv every morning, YouTube channels post deep-dives, newsletters land in your inbox, and podcasts stretch to three hours. I am wroking on a single daily read that cuts across all of it, all automated. I have built a Python pipeline that pulls from RSS feeds, YouTube channels, and arXiv each day, runs everything through Gemini 2.5 Flash, and publishes a structured intelligence digest to a static site on S3 and CloudFront.

---

## Things I've shipped

**[CampaignLens](https://sumiya.page/campaign-lens.html)**

An AI agent where you can audit an email campaign across multiple dimensions - scoring content quality, deliverability risk, compliance, and accessibility. Serverless on AWS using a simple flow: User (Browser) -> API Gateway -> Lambda -> Cloudflare then Bedrock -> Claude Sonnet.

**[OctaneLog](https://github.com/psumiya/octanelog)** *(public hackathon project)*  
An iOS app that narrates your drives using on-device Vision AI and Gemini. Continuously records, analyzes scenery in real-time, and generates narrative summaries of where you've been. Two-model architecture: Gemini Flash for high-frequency video analysis, Gemini Pro for season-long story memory. Privacy-first: raw GPS and generated narratives stay on device.

**[option-insights](https://github.com/psumiya/option-insights)** *(public hackathon project)*  
A charting tool for retail options traders — built at a public hackathon. Takes a CSV of option trades and renders charts and graphs for analysis. Static site, no backend, runs entirely in the browser.

**[jcli](https://github.com/psumiya/jcli)**  
A CLI tool that lets you invoke utility Java methods from your terminal without needing a JDK or JRE. 

**[amazon-or-aws](https://amazonoraws.com)**  
An AWS news aggregator and comprehensive product reference — so you can finally stop second-guessing whether it's "Amazon S3" or "AWS S3".

**[jpath](https://sumiya.page/jpath.html)**  
A web UI for the Jayway JsonPath implementation. Built when the official site went down after the Heroku acquisition - and kept alive since, because validating a path expression shouldn't require writing test code. Was picked up by the JsonPath community as a stop-gap back in the day. Might still be in use somewhere.

---

## TIL

I keep a [running log](https://github.com/psumiya/til) of things I learn as I work - short-form, no fluff. Mostly backend, AWS, and whatever I'm 
tinkering with.

---

## Impact (the day job)

- I currently lead backend engineering at **Nike Stores** - the infrastructure connecting Nike's retail stores worldwide to Nike's digital ecosystem.
- In the past I led a team for **Nike Communications Platform** - the infrastructure behind every cross-channel consumer communication Nike sends globally (email, push, SMS, inbox), and prior to that I built features for a public-service Affordable Care Act compliant product that was deployed in several US states.
