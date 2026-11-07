# Blackbaud MCP

Ask Claude about your homework and tests. Blackbaud MCP is a small Mac app that connects your school's Blackbaud Learning Platform to AI apps like Claude, so you can ask things like "What tests do I have this week?" or "What is due tomorrow?"

This project is unofficial. It is not made, approved or supported by Blackbaud or your school. Releases only, the source is not published.

## Download

Get the latest `.dmg` from the [Releases](../../releases/latest) page.

## Install

1. Open the DMG and drag Blackbaud MCP into Applications.
2. Open it. macOS will say it cannot verify the app. Click Done, open System Settings, go to Privacy & Security, scroll down, click Open Anyway, then Open. (The app is not notarized.)
3. Sign in to your school's Blackbaud in the window that appears.
4. Click Add to Claude. Claude closes and reopens with the tools added.
5. Ask Claude: "What tests do I have coming up?"

You need a Mac with macOS 13 or newer (Apple Silicon or Intel) and the Claude desktop app.

## What it can do

- List your homework for any date range
- List upcoming tests, quizzes and exams
- Show overdue and missing work
- Show an assignment's instructions
- List your classes and teachers

Everything is read only. It cannot change anything in Blackbaud.

## How it works

The app keeps a Blackbaud sign-in in its own window and runs a small local server on your Mac. Claude talks to that server. Your sign-in is saved in your Mac's Keychain, and nothing is sent to me. The school data goes only to the AI app you connect.

- Quit (Cmd+Q) or close the window: the app hides and keeps running so Claude can still use it.
- Terminate process: stops everything. The same button then says Resume process.

## ChatGPT

ChatGPT's regular chat can only reach servers on the public internet, so the app can make a temporary public link. It is off until you click Connect ChatGPT chat, and it turns itself off after 1 hour. The link passes through Cloudflare, and anyone who has it can read your school info while it is on. Keep it private. The app also offers an import for ChatGPT's Codex mode.

## Limits

- Mac only.
- The school address is built in for one school, so it will not work for other schools yet.
- It uses the same pages the Blackbaud website uses, not an official API, so it can break when Blackbaud changes things.
- Check your school's rules before you use it, including rules about AI tools.

All rights reserved.
