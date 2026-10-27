# idv.rayawa.top

English | [简体中文](README_zh.md)

A browser-based rank-progress planner for Identity V.

Archived project retained for reference.

## Overview

The single-page interface calculates progress toward a seasonal rank target and presents remaining days, required daily points and progress history. Calculations run in the browser.

## Technology and Dependencies

HTML, JavaScript and Tailwind CSS loaded from a CDN, with externally hosted visual resources. A browser is required; a static server is optional. Network access is needed for CDN assets.

## Repository Structure

- `index.html` — interface, styling and calculation logic
- `CNAME` — custom domain configuration
- `favicon.ico` — site icon

## Quick Start

Serve the repository root so absolute asset paths resolve correctly:

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000/`. Edit the HTML and assets directly; no frontend build is required.

Enter the current progress and target values, then inspect the calculated daily plan.
