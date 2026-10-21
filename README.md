# Confessional

A Mac menu-bar app that records your calls, transcribes them on your Mac, tells the speakers
apart, takes screenshots of what was shared, and writes a summary. No bot joins the call, and
nothing leaves your Mac unless you choose a cloud AI for summaries.

**[Download Confessional](https://github.com/mgrody1/confessional-releases/releases/latest/download/Confessional.dmg)**

Needs a Mac with Apple Silicon (M1 or later) and macOS 14 Sonoma or later.

## Installing

1. Open the downloaded `Confessional.dmg` and drag **Confessional** into **Applications**.
2. Open Confessional from Applications. macOS will say it can't check it for malicious
   software (it isn't notarized by Apple yet). Click **Done**, then open
   **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to
   Confessional. Confirm, and enter your password. You only do this once.

   (Or, before opening the DMG: in Terminal, run
   `xattr -d com.apple.quarantine ~/Downloads/Confessional.dmg` and it opens normally.)
3. The setup window walks you through the permissions it needs (microphone, screen and
   system audio recording, and optionally your calendar).
4. The first time you transcribe, it downloads the speech model (about 1–3 GB), so do your
   first test on good Wi-Fi rather than right before an important call.

## Updates

Confessional checks for updates once a day and offers to install them with one click
(menu bar icon → ⬇, or Settings → Updates). It never restarts in the middle of a recording
or while a meeting is being transcribed.

## Please note

Recording laws vary: in many places everyone on a call has to agree to be recorded. Let
people know you're recording.
