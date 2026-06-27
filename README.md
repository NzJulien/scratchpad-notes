# Scratchpad

> A Markdown notes app with tags, search, live preview, and word count — powered by a custom zero-dependency Markdown parser. No AI, no backend.

## Live Demo
https://nzjulien.github.io/scratchpad-notes

## Features
- Write notes in Markdown with a live split-view preview
- Custom Markdown parser (headers, bold, italic, code, code blocks, quotes,
  lists, links) — no external library
- Tag notes and filter by tag from the sidebar
- Full-text search across titles and content
- Word count + estimated read time per note
- Export any note as a `.md` file
- Three view modes: Write / Split / Preview
- Autosave to localStorage as you type

## Stack
- Vanilla HTML / CSS / JavaScript
- Hand-written Markdown-to-HTML parser (~40 lines)
- localStorage for persistence
- Zero dependencies, zero build step

## Why a custom parser?

Rather than pulling in marked.js or showdown for a notes app, Scratchpad
ships its own small parser covering the Markdown subset people actually use
day to day: headers, emphasis, inline code, fenced code blocks, blockquotes,
lists, and links. It's intentionally compact and easy to extend.

Made by NzJulien
