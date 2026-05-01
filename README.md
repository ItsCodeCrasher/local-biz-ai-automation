# Local Business AI Automation System

## Overview
An AI-driven multi-agent automation system designed for small local businesses (salons, restaurants, gyms). Eliminates manual customer communication overhead by routing and responding to inquiries autonomously.

## Problem
Small businesses lose customers due to slow response times and repetitive manual tasks — appointment confirmations, FAQs, follow-ups. Staff time is wasted on communication instead of core work.

## Solution
- **Classifier Agent** — reads incoming messages, detects intent, routes accordingly
- **Booking Agent** — handles appointment scheduling and confirmations
- **FAQ Agent** — answers common questions automatically
- **Escalation Agent** — flags complex issues for human review

## Tech Stack
- Orchestration: Make.com
- LLM: MiMo 2.5 (1M context window)
- Integrations: WhatsApp / Instagram DMs / Email

## Why MiMo 2.5
The 1M token context window allows maintaining complete conversation history across sessions — customers never need to repeat themselves.

## Status
In active development — agent logic and Make.com scenarios in progress.
