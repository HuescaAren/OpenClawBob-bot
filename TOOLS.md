# TOOLS.md - Local Notes

Skills define _how_ tools work. This file is for _your_ specifics — the stuff that's unique to your setup.

## What Goes Here

Things like:

- Camera names and locations
- SSH hosts and aliases
- Preferred voices for TTS
- Speaker/room names
- Device nicknames
- Local services (ports, URLs, credentials storage locations)
- Anything environment-specific

## Examples

```markdown
### Cameras

- living-room → Main area, 180° wide angle
- front-door → Entrance, motion-triggered

### SSH

- home-server → 192.168.1.100, user: admin
- dev-vm → 192.168.1.50, user: robert, Ubuntu in Hyper-V

### Local services

- openclaw-gateway → http://127.0.0.1:18789
- ollama → http://127.0.0.1:11434
- lm-studio → http://127.0.0.1:1234

### Security / secrets

- API keys are stored in env vars (no files): `OPENAI_API_KEY`, `OPENROUTER_API_KEY`
- Never write secrets to disk; if needed, use placeholders and ask me where to paste them

### TTS

- Preferred voice: "Nova" (warm, slightly British)
- Default speaker: Desktop speakers on DESKTOP-VPU12UK
```

## Why Separate?

Skills are shared. Your setup is yours. Keeping them apart means you can update skills without losing your notes, and share skills without leaking your infrastructure.[web:55][web:46]

---

Add whatever helps you do your job. This is your cheat sheet.
