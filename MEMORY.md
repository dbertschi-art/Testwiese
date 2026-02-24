# MEMORY.md - Long-Term Memory

## Was ich heute gelernt habe (2026-02-24)

### Setup
- Damian nutzt VirtualBox mit Ubuntu 24.04
- GPU: NVIDIA GTX 1060 3GB durchgereicht (PCI Passthrough)
- Ollama mit MiniMax M2.5 läuft lokal mit GPU-Beschleunigung

### TTS
- ElevenLabs hat keine gute deutsche Stimme
- **Edge TTS mit de-DE-KatjaNeural** klingt gut und ist gratis!
- OpenClaw TTS Config: provider=edge, voice=de-DE-KatjaNeural

### E-Mail
- Microsoft OAuth braucht User-Login (Device Flow), Client Credential reicht nicht
- Device Flow ist schwierig ohne interaktive Session
- Python msal Library funktioniert für OAuth

### GitHub
- gh CLI installiert und eingeloggt
- Workspace nach GitHub gepusht: dbertschi-art/Testwiese
- OpenClaw Source geklont nach /home/damian/openclaw-src/

## Offene Tasks
- E-Mail Integration fertigstellen (OAuth Device Flow oder SMTP mit App Password)
- Kalender via Outlook/Graph API
- Heartbeat für E-Mails und Kalender einrichten

## Persönliches
- Damian mag es pragmatisch und direkt
- Mag Geschichten auf Deutsch (Zauberwald)
- TTS auf Deutsch ist ihm wichtig
