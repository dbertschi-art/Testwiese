# TOOLS.md - Local Notes

Skills define _how_ tools work. This file is for _your_ specifics — the stuff that's unique to your setup.

## Microsoft 365 / Outlook OAuth

- **Client ID:** 8f4170db-3feb-4904-ae61-f7e08b29beb7
- **Tenant ID:** 1e829aab-68d9-49a6-8449-b9009f1b2cc5
- **User:** dbertschi@live.com

### Server Configs
- SMTP: smtp-mail.outlook.com:587
- IMAP: outlook.office365.com:993
- CalDAV: https://outlook.office365.com/caldav/

### Scopes needed
- `https://outlook.office365.com/.default`
- `offline_access`

### Client Secret
- ✅ Gespeichert (nicht in diesem File)

## ElevenLabs TTS
- API Key: sk_8507d6e6ec6570268322606cea0a493a77876f0c77368529
- Provider: OpenClaw TTS

### TTS Config (aktuell)
- Provider: Edge
- Stimme: de-DE-KatjaNeural

## What Goes Here

Things like:

- Camera names and locations
- SSH hosts and aliases
- Preferred voices for TTS
- Speaker/room names
- Device nicknames
- Anything environment-specific

## Examples

```markdown
### Cameras

- living-room → Main area, 180° wide angle
- front-door → Entrance, motion-triggered

### SSH

- home-server → 192.168.1.100, user: admin

### TTS

- Preferred voice: "Nova" (warm, slightly British)
- Default speaker: Kitchen HomePod
```

## Why Separate?

Skills are shared. Your setup is yours. Keeping them apart means you can update skills without losing your notes, and share skills without leaking your infrastructure.

---

Add whatever helps you do your job. This is your cheat sheet.
