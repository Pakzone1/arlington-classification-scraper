# Arlington Job Classification Scraper

**Collect government job classifications and turn long descriptions into structured records.**

## The problem

The site had 812 classifications and showed ten per page. Each detail page contained the useful information.

Opening them one by one was technically an option. Writing a script seemed like a better use of the afternoon.

## The solution

A Python collection and extraction workflow for Arlington job-classification pages, followed by a dedicated pass that separates the long description into useful fields.

## What it does

- Paginated classification collection.
- Detail-page fetching and structured JSON output.
- Title and major-duty extraction.
- Specific tasks and minimum qualifications.
- Separate education and experience fields.
- Browser-assisted and request-based collection variants.

## Engineering highlights

Separates collection from structuring: one stage gathers classification detail pages, and a second extracts the requested fields from saved description text. The collected dataset can be reorganized and reused without repeating the collection stage.

## Technology

Python, HTTP requests, browser-assisted collection, HTML/text parsing, JSON.

## Source code

This repository documents the project, its capabilities, and the engineering behind it. The application source code is maintained privately.
