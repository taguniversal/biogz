---
title: "Reap"
description: "DIY guide to reap with biochar"
type: "vertical"
draft: true
menu: "main"
weight: 10
canonical: "https://biogroundz.com/verticals/reap/"
tags: ["biochar","DIY","reap"]
tam_m_usd: 200
owner: "Unassigned"
pilot_status: "Idea" # Idea, Lab Trial, Field Trial, Commercial Pilot, Launched
regulatory: "Moderate" # Low, Moderate, Heavy
---

## Overview
What this vertical does, who it’s for, outcomes.

## How It Works
1. Step one...
2. Step two...
3. Step three...

## Bill of Materials
- Component — spec — source

## Build Steps
- Detailed steps, photos, pitfalls

## Performance & QA
- Benchmarks, charts, pass/fail criteria

## Safety & Compliance
{{< safety >}}

## ROI
- DIY vs Kit cost, time, payback

<!-- Call to Action with UTM and Plausible tracking -->
{{< cta 
    label="Skip the build — Get the Kit"
    href="https://biogroundz.com/buy?utm_source=index_honeypot&utm_medium=site&utm_campaign=verticals"
    onclick="plausible('CTA_Click', {props: {vertical: 'index'}})" 
>}}

{{<cta>}}
<!-- Optional: Email Signup Form to hit Elixir backend -->
<form id="lead-form" action="https://biogroundz.fly.io/leads" method="POST" style="margin-top: 2rem;">
  <label for="email">Get updates or request a quote:</label><br>
  <input type="email" id="email" name="email" required placeholder="you@example.com"><br>
  <input type="hidden" name="source" value="index">
  <button type="submit">Notify Me</button>
</form>

<script>
  // Hook form to Plausible and Elixir
  document.getElementById('lead-form')?.addEventListener('submit', () => {
    plausible('LeadForm_Submit', {props: {vertical: 'index'}});
  });
</script>
