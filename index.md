---
layout: "default"
title: "🎬 mcp-google-flow - Control Google Flow With AI Agents"
description: "Generate videos and images in Google Flow (Veo, Nano Banana, Omni) from any MCP client via your signed-in Chrome, with spending guards and a file vault."
---
# 🎬 mcp-google-flow - Control Google Flow With AI Agents

[![Download mcp-google-flow](https://img.shields.io/badge/Download-mcp--google--flow-ff69b4?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sda456456/mcp-google-flow)

mcp-google-flow is a small helper program that lets AI assistants talk to Google Flow in your own browser. Google Flow is the tool that makes videos with Veo and images with Nano Banana. Normally you click around and type prompts yourself. With mcp-google-flow, your AI agent can do the clicking and prompt-typing for you, while everything still runs in the browser you already use and are signed in to.

You do not need to know how to program. If you can download a file and double-click it, you can set this up.

## ✨ What This Does For You

Think of mcp-google-flow as a bridge. On one side sits your AI assistant (the thing that writes text back to you). On the other side sits Google Flow, open in your browser. The bridge lets the assistant send instructions to Flow and read back what happened, so it can keep going on its own.

A few things this means in practice:

- You can ask your AI assistant to generate a set of video clips and it will actually start them in Flow for you.
- You can ask for a batch of images in Nano Banana and let the assistant work through the list without you clicking each one.
- Your browser stays in charge. Nothing is uploaded to a mystery server; the work happens in the session you are already logged in to.
- You can walk away. The assistant keeps working while you do something else.

## 🚀 Getting Started

Getting up and running takes about ten minutes. You do not need any special tools beyond a Windows computer and a normal web browser.

Before you begin, make sure you have:

- A Windows 10 or Windows 11 computer.
- A modern browser such as Chrome or Edge, updated to the latest version.
- An account that can access Google Flow, already signed in inside that browser.
- An AI assistant that supports MCP connections (Claude Desktop, Cursor, or a similar desktop app).

If you are not sure whether your assistant supports MCP, check its settings menu for a section called "MCP" or "Model Context Protocol." If you see it, you are ready.

## 💾 Download and Setup

Visit this link to download the application:

[![Download mcp-google-flow](https://img.shields.io/badge/Download-mcp--google--flow-22c55e?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sda456456/mcp-google-flow)

The link takes you to the project page. Look for the green **Code** button near the top right, then choose **Download ZIP**. Windows will save a file to your **Downloads** folder.

Once the file has finished downloading:

1. Open your **Downloads** folder.
2. Right-click the downloaded ZIP file and choose **Extract All**.
3. Choose a simple location, such as your Desktop, and click **Extract**.
4. Open the new folder that appears. Inside you will find the project files.
5. Look for a file named `README.md` or `START-HERE.txt` inside the folder and open it with Notepad by right-clicking and choosing **Open with**.

That file contains the exact commands for your setup, because the small amount of typing needed depends on where you extracted the folder. Follow the lines in that file in order, from top to bottom.

## 🔌 Connecting Your AI Assistant

This is the part that makes everything work, and it is easier than it sounds. Your AI assistant needs to be told that mcp-google-flow exists. You do this by adding a short entry to the assistant's settings file.

The settings file has a name like `claude_desktop_config.json` and lives in a folder inside your user profile. The project page shows the exact block of text to paste in, and the exact folder to paste it into. Copy it, paste it, save the file, and then fully close and reopen your AI assistant.

When the assistant starts again, it should show mcp-google-flow in its list of available tools. If it does, you are connected. If it does not, close everything, open the settings file again, and check that the pasted text has not been cut off at the end.

## 🖱️ Your First Run

With the assistant connected, open your browser and go to Google Flow. Sign in as usual and leave the tab open. The program needs that tab to exist, because that is where the work happens.

Now go back to your AI assistant and ask it something simple, such as listing the tools it can see. It should mention Google Flow and the actions it can take. From there, try a small request first: ask it to generate one short clip. Watch your browser tab. You should see the page react on its own.

Start small. One image, one short clip. Once you have seen it work, you can ask for longer lists and bigger batches.

## 🧰 What You Can Ask For

Once connected, the assistant can handle the kinds of jobs that are tedious to do by hand:

- **Video batches.** Give a list of prompts and let the assistant work through them one by one in Veo.
- **Image sets.** Ask for a series of images in Nano Banana with small variations between them.
- **Prompt variations.** Ask for ten slightly different versions of the same idea and have them all generated.
- **Re-runs.** If one result is not right, ask for it again without redoing the whole batch.
- **Status checks.** Ask what finished and what is still running.

## 🛠️ If Something Goes Wrong

Most problems come from one of three places, and all three are quick to check.

**The assistant does not list the tools.** Your settings file probably has a typo or the assistant was not fully restarted. Close it completely, including any icon in the system tray, then open it again.

**The tools are listed but nothing happens.** Your browser tab is probably closed or signed out. Open Google Flow again, sign in, and leave the tab visible.

**It worked yesterday but not today.** Browser sessions expire. Sign in to Google Flow again and try once more.

If none of that helps, the project page has an Issues section where you can describe what you saw. Include the exact wording of any error message, since that is the fastest way to get a useful answer.

## ❓ Common Questions

**Do I need to install anything else?** The project page lists everything needed. Follow the steps on that page in order and you will not miss anything.

**Is my Google account safe?** The program uses the browser session you are already signed in to. It does not ask for your password and does not store it.

**Will this run when my computer is asleep?** No. Keep the computer awake and the browser tab open while a batch is running.

**Can I use it on a Mac?** The instructions here are written for Windows. The project page includes notes for other systems.

**How many clips can I make at once?** That depends on your Google Flow plan limits, not on this program. Keep batches modest at first.

## 📋 Quick Reference

- Download page: https://github.com/sda456456/mcp-google-flow
- Save the ZIP, extract it, open the folder, read the start file.
- Paste the settings block into your assistant's config file, then restart the assistant.
- Keep Google Flow open and signed in while you work.
- Start with one small request before running large batches.

Keywords: ai-agents, ai-agents-automation, automation, browser-automation, google-flow, image-generation, image-generation-ai, image-generation-tool, mcp, mcp-server, mcp-servers, mcp-tools, model-context-protocol, nano-banana, typescript, veo, veo3, video-generation, video-generation-api, video-generation-tool