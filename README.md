# Agentic Marketing Copilot

An interactive multi agent decision support prototype that turns a marketing campaign brief into a structured campaign recommendation.

## Live Demo

(https://kandacelin1998.github.io/agentic-marketing-copilot/)

## The Problem

Marketing teams often need to combine audience insight, commercial strategy, creative thinking, and performance optimisation before making a campaign decision.

That process can require multiple teams, disconnected analysis, and repeated manual synthesis.

The Agentic Marketing Copilot explores how specialised AI agents could coordinate this work.

## How It Works

A user provides:

1. Campaign or product
2. Business objective
3. Target audience
4. Budget
5. Commercial context

The system coordinates four specialist agents.

### Strategy Agent

Defines the campaign objective, positioning, and overall approach.

### Audience Agent

Identifies audience segments, motivations, behaviours, and potential barriers.

### Creative Agent

Develops messaging directions and channel recommendations.

### Optimisation Agent

Defines experiments, KPIs, and optimisation logic.

### Orchestrator

Synthesises the specialist outputs into one actionable campaign recommendation.

## Agent Workflow

Campaign Brief → Specialist Agents → Parallel Analysis → Orchestrator → Action Plan

## Product Thinking

This prototype demonstrates several concepts relevant to AI Product Operations:

• translating a business problem into an AI workflow

• decomposing work into specialised agent responsibilities

• orchestrating multiple agent outputs

• designing structured human readable recommendations

• connecting AI outputs to measurable business KPIs

• designing a workflow where humans remain responsible for final decisions

## Success Metrics

Potential production metrics include:

• conversion rate

• click through rate

• return on ad spend

• campaign revenue

• cost per acquisition

• recommendation adoption rate

• time saved per campaign

## Production Evolution

A production version could add:

• LLM powered agent reasoning

• campaign performance APIs

• CRM and audience data

• experimentation history

• memory across campaign cycles

• confidence scoring

• human approval gates

• audit logs

• automated performance monitoring

## Tech Stack

HTML

CSS

JavaScript

GitHub Pages

## Current Version

This repository contains a front end product prototype.

The current agent outputs are simulated using deterministic JavaScript logic so the product workflow can be tested without external APIs or credentials.

The next iteration would connect each specialist agent to an LLM and relevant marketing data sources.

## Why I Built This

I wanted to explore how agentic AI could support commercial decision making rather than simply generate content.

The project focuses on orchestration: breaking a marketing decision into specialist tasks, coordinating those tasks, and translating their outputs into an actionable recommendation.
