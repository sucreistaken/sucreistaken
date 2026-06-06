# Kadir Ay

Computer Engineering senior at Izmir University of Economics. I build full-stack web applications.

- LinkedIn: [linkedin.com/in/aykadir](https://linkedin.com/in/aykadir)
- Email: kadir@kadiray.com

## What I'm working on

**Quedl** ([quedl.com](https://quedl.com)) — A dating app for Turkish university students with `.edu.tr` email verification. Web app (PWA) built with Next.js, Express, and MongoDB. Soft launch coming. The repository is private; I can show you a demo or walk through the code if you reach out.

**forum.ieu.app** — University community forum for Izmir University of Economics. Around 8,000 active users. Sponsored by Red Bull and Youthall. Built on NodeBB with several custom plugins (most of them in the list below).

**prompt-clash** — A live AI image prompt battle game I built for university events. Players join with QR codes from their phones, write prompts, and an AI judges the winner on the big screen.

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [AIcelerate](https://github.com/sucreistaken/AIcelerate)

Online study rooms with shared quizzes, flashcards, mind maps, and an AI tutor. Audio lectures are transcribed with Whisper. Group Pomodoro timer keeps everyone in the room on the same focus block.

`React 19` `TypeScript` `Node` `Socket.io` `Whisper` `Gemini`

</td>
<td width="50%" valign="top">

### [forum-moderation-api](https://github.com/sucreistaken/forum-moderation-api)

Content moderation service used by forum.ieu.app. Flags spam, profanity, and harassment using Gemini. Handles single and bulk requests; returns reasons, not just a yes/no.

`Java 21` `Spring Boot 4` `Gemini` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [switchview](https://github.com/sucreistaken/switchview)

Web dashboard that shows which devices are connected to which switch ports on our campus network. Polls switches over SNMPv3 every few minutes. Running in production on a ~40-switch Huawei and Cisco fleet.

`Python` `Flask` `SNMPv3` `pysnmp`

</td>
<td width="50%" valign="top">

### [free-cv-maker](https://github.com/sucreistaken/free-cv-maker)

CV and cover letter builder that runs entirely in the browser. No account, no server. 7 templates, drag-and-drop sections, PDF export. Data stays on the user's device.

`React 19` `TypeScript` `Tailwind 4` `Zustand` `jsPDF`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [prompt-clash](https://github.com/sucreistaken/prompt-clash)

1v1 AI image-prompt game for events. Players join with a QR code from their phone, write a prompt for the same theme, AI generates both images, Gemini scores which prompt won. Big screen for the audience.

`Next.js 15` `TypeScript` `Gemini` `Tailwind`

</td>
<td width="50%" valign="top">

### [ask](https://github.com/sucreistaken/ask)

Tiny Bash CLI that talks to any OpenAI-compatible chat API. Works with Gemini, Groq, OpenAI, OpenRouter, and anything else that follows the standard `/chat/completions` format. Configurable via three environment variables.

`Bash` `curl` `jq`

</td>
</tr>
</table>

## Tech stack

**Frontend** Next.js, React, Tailwind, TypeScript, Zustand
**Backend** Node + Express, Spring Boot, Python (Flask, FastAPI)
**Databases** MongoDB, PostgreSQL
**AI** Gemini, Whisper, OpenAI-compatible APIs
**Infrastructure** Docker, Google Cloud, nginx, GitHub Actions

I also maintain a set of [NodeBB plugins](https://github.com/sucreistaken?tab=repositories&q=nodebb-plugin) used on forum.ieu.app: event calendar, polls, PDF preview, bulk announcement mailer, loyalty wallet, and a few others.

## Contact

kadir@kadiray.com · [linkedin.com/in/aykadir](https://linkedin.com/in/aykadir)
