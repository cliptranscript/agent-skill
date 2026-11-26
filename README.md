# Video transcripts by Clipscript

**Video transcript generator: transcribe video to text from a link.**

This agent skill tells an agent how to use the Clipscript MCP server: transcribe YouTube videos and Shorts, TikTok, Instagram Reels, Facebook and X videos to text, transcribe up to 10 links at once, list a channel's latest videos, and export saved transcripts as TXT or as SRT, VTT and JSON subtitles and captions.

[Website](https://cliptranscript.app) · [Agent guide](https://cliptranscript.app/skill.md) · [MCP repository](https://github.com/cliptranscript/mcp-server)

## When to use it

> Get the transcript of https://www.youtube.com/watch?v=… with timestamps and list the main points.

> List the latest 10 videos on this TikTok profile and transcribe the three most recent.

## Install

```sh
npx skills add cliptranscript/agent-skill
```

Skill installation and MCP connection are separate: connect `https://cliptranscript.app/mcp` in a remote MCP client, or use `npx -y clipscript-mcp` for a stdio client with Node.js 22+. Sign in through the browser, or use a Clipscript API key on Pro and Scale.
